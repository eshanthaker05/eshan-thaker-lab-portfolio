# A6 – [Design Fits for an Artifact]

## Objective

The objective of this lab is to parametrically design an artifact that snap-fits onto a known object. My object is an Arduino Leonardo R3 microcontroller board. 

## Dimensions

In class, I used a caliper to take the basic dimensions of my Arduino board. Documentation of my use of the caliper is shown below. 

<img width="381" height="285" alt="IMG_3045" src="https://github.com/user-attachments/assets/4f20fdd4-81af-4544-a580-552fc2d44bb8" />

<img width="381" height="285" alt="IMG_3047" src="https://github.com/user-attachments/assets/3c25f886-ee33-4621-8dd6-ab98f234078c" />

<img width="381" height="285" alt="IMG_3045" src="https://github.com/user-attachments/assets/9e45fddc-fd9b-46c9-9954-9da498a16549" />

Width: 2.102 inches

Length: 2.701 inches

Height: 0.070 inches

Pin Distance from Edge = 0.053 inches

I decided on a simple design that would latch onto the sides of the Arduino board and hold it securely. Unfortunately, I made a very annoying mistake here which I realized too late: I forgot to use the caliper to measure how far the pins are from the edge of the board. To replace the caliper, I ended up using my Bic 0.9mm mechanical pencil lead. I chose to take measurments using this because it was the object with the smallest known dimension that I had on me at the time. 

First, I measured the height of the Arduino since I already knew that dimension from using the caliper earlier, and compared it to the value I got with the pencil lead. I measured it to be approximately 2 pencil leads, which is 1.8 mm. Converting this to inches, I got 0.071 inches, which is surprisingly close to the value measured from the caliper. Next, I measured the pins distance from the edge using the pencil leads. It looked to be around 1.5 pencil leads, which converts to 0.053 inches. 

## Parametrically Design

<img width="366" height="234" alt="Screenshot 2026-09-28 184017" src="https://github.com/user-attachments/assets/4c895ba0-bdf2-4c1e-9c80-654950c86170" />

I started by inputting the main dimensions of the Arduino board into the parameters tab.

<img width="410" height="286" alt="Screenshot 2026-09-28 184035" src="https://github.com/user-attachments/assets/3f44fef1-7edd-4eae-8a9d-12dc82df3fce" />

Next, I added the extra length to give the artifact some strength. I arbitrarily chose 1.0 inches to add onto each dimension. 

<img width="428" height="293" alt="Screenshot 2026-09-28 184317" src="https://github.com/user-attachments/assets/eb466b01-e835-40f1-8e80-797cd8e07879" />

The extruded box is shown above. 

<img width="402" height="281" alt="Screenshot 2026-09-28 191626" src="https://github.com/user-attachments/assets/e06c2053-f385-4a07-adfa-31be8613d372" />

Next, I extruded space for the Arduino board to fill. I added the parameters of the Arduino board and added a 0.04 inch buffer on either side so the board will fit. 

<img width="405" height="251" alt="Screenshot 2026-09-28 192034" src="https://github.com/user-attachments/assets/333e2f9d-bdfc-4ca3-ade9-8acadeebd60b" />

I then extruded it downwards into the box. The depth of the extrusion is a little over two times the height of the board. 

<img width="379" height="251" alt="Screenshot 2026-09-28 194439" src="https://github.com/user-attachments/assets/aff0f247-0dcd-4c67-9ed7-f25fcc00da42" />

I need to account for the connector pins that hang a little bit off the side. Since I don't have a caliper, I have to eyeball/estimate everything using the 0.9mm pencil lead. I measured the connector to be around 3 pencil leads from the side, which converts to approximately 0.12 inches. 

<img width="389" height="245" alt="Screenshot 2026-09-28 201824" src="https://github.com/user-attachments/assets/e75f842a-0ab6-40c7-b907-96b722109998" />

Lastly, I extruded a bar with a height of 2 pencil leads (about 0.07 inches) to keep the Arduino board in place. 

<img width="389" height="245" alt="Screenshot 2026-09-28 201824" src="https://github.com/user-attachments/assets/b7264ef4-00df-40d6-8032-a80fd9ce2fe9" />

Lastly, I made a little space for the Arduino board to securely "snap" into. After finishing up the modeling process, I went to the Rapid Lab. 

## Preprocessor 

<img width="405" height="303" alt="Screenshot 2026-10-01 144908" src="https://github.com/user-attachments/assets/949316eb-fe58-4dad-847c-a6410aad745e" />

<img width="405" height="304" alt="Screenshot 2026-10-01 144914" src="https://github.com/user-attachments/assets/1e9223dd-a0ca-4c8e-850b-8dac3779e700" />

Once I got to the lab, I was able to find a caliper and adjust my dimensions so that they were more accurate. Looking back, the dimensions I took with my pencil leads were not too far off from the ones I measured using the caliper. I wanted to make sure that the Arduino would definitely snap into place, so I measured the lengths of the pins from the edge.

<img width="1201" height="792" alt="Screenshot 2026-09-28 203311" src="https://github.com/user-attachments/assets/c6393daf-a52b-42ff-b418-c4ceb82ae9aa" />

I saved my part as an STL file and loaded it up Prusa Slicer. Before printing, I checked how long it would take the printer to finish my part since I already knew this was a pretty big artifact. It would take the printer about an hour and a half to fully finish printing my artifact, so I tried finding ways to trim down on this print time. 

<img width="479" height="229" alt="Screenshot 2026-09-28 204129" src="https://github.com/user-attachments/assets/2958edf3-214f-4997-8516-862b74ad88d5" />

I noticed that the height of the artifact was a lot bigger proportionally than I had expected, so I cut it in half using in Prusa Slicer (shown above), bringing my print time down to about 40 minutes. Although this is still a longer time than I had hoped, it was an acceptable print time for me. Additionally, I changed the infill pattern to rectilinear since it is simple, slightly reducing the print time. 

<img width="927" height="197" alt="Screenshot 2026-09-28 204144" src="https://github.com/user-attachments/assets/adb352f7-ef7a-423b-a9d2-6780dc7ef594" />

I saved the file as a G-code and sent it to printer #3. 

## Printing Process

<img width="404" height="281" alt="Screenshot 2026-10-01 145706" src="https://github.com/user-attachments/assets/bf683a68-f6b9-4481-9979-0013aca83773" />

<iframe width="560" height="315" src="https://www.youtube.com/embed/XpBa8LuegNM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<img width="402" height="301" alt="Screenshot 2026-10-01 145713" src="https://github.com/user-attachments/assets/459241d2-ee3c-48ae-a4a2-09b76e9133e5" />

Shown above are screen of the printer halfway through the printing process, a short clip demonstrating the printer at work, and the finished product lying on the printing tray. 

## Lessons Learned

A lesson I learned pretty quickly is that I should have taken more measurements with the caliper when I had it. This was partly because I didn't realize I would need more specific measurements, and partly because I didn't have a design in mind when I was taking the measurements in class. Either way, I should have measured things like how far the pin connections are from the edge, diameters of all the holes, locations of the holes with respect to the edges, etc. 

