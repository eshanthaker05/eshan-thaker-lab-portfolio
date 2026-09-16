# A4 – [Benchmark a Parameter]

## Objective

The goal of this lab is to test the limits of the Prusa Core One printer and gain a better understanding of the manufacturing process behind engineering projects. 


## Parameter

I've chosen to conduct a tolerance gauge test for this project. 

After deciding on what to design (discussed below), I predicted that the key would reach the final hole, with a diameter of 4.76 mm. 

## Document Design

It took me a long time to decide how I wanted to approach this project. I knew I wanted to design an artifact with multiple holes and test the diameters of each, but I thought that alone would be too basic. In order to give this project some more flair, I decided to design a "lock" with five, equally spaced holes of incrementally decreasing diameters. I wuld also print a "key" to go with this lock. The idea was that as the diameters of the holes get smaller and smaller, and eventually, the key would stop fitting into them, telling me exactly where the limit of the Prusa Core One printer lies. 

<img width="1186" height="331" alt="Screenshot 2026-09-15 144211" src="https://github.com/user-attachments/assets/1f9495e5-76d4-4f05-b507-e66c4b4b3957" />

This idea was partly inspired by the reference model (shown above) provided for a tolerance gauge test. Instead of the extruding prongs out of the body and measurign their diameters, I decided to put holes into the body and measure them using a key. 

<img width="561" height="351" alt="Screenshot 2026-09-15 153917" src="https://github.com/user-attachments/assets/0aae7870-88d5-4493-8518-1f5cd3f76ffe" />

Before even beginning the design process, I set the units to mm in Creo Parametric (shown above) to make it easier to follow the design rules chart.

<img width="424" height="201" alt="Screenshot 2026-09-15 100930" src="https://github.com/user-attachments/assets/05810777-32b8-4f8c-8f53-6fddc945265a" />

<img width="441.2" height="246.8" alt="Screenshot 2026-09-15 100959" src="https://github.com/user-attachments/assets/3e2df05b-91f4-458d-920b-2d7db0b2a318" />

I began my design by sketching a 60mm x 15mm rectangle, then extruding it by 5mm (shown above). 

<img width="455" height="186" alt="Screenshot 2026-09-15 105100" src="https://github.com/user-attachments/assets/20397dc1-b199-4633-ad41-2811f5924a26" />

Next, I individually added five holes (shown above). The first one is 10mm from the left edge with a diameter of 5mm. The next hole is 20mm from the left edge with a diameter of 4.94mm. This pattern keeps going for all five holes until the last one, which is 50mm from the left edge with a diameter of 4.76mm. I decided to start with 5mm because I wanted to keep the print time to a minimum as best I could. According to the design rules chart, the tolerance is +/- 0.3% with a lower limit of 0.3mm. After running some calculations, I realized 0.3% of 5mm is less than 0.3mm, so I decided to decrease the diameters by 0.3mm since that's the lowest the printer can handle. I set the diameters so that they would decrease until the last one reaches the lower limit (I later realize I messed up). 
Underneath each hole, I extruded some text into the body labelling the diameter of each hole. 

<img width="497" height="284" alt="Screenshot 2026-09-15 105944" src="https://github.com/user-attachments/assets/ab3bfc6f-e111-492f-87ef-d97c23585b33" />

Next, I added the loop on the top of the body to make it look more like a lock. Honestly, I should have done this step a lot earlier, when I was first sketching the body, but I guess that thought didn't occur to me. 

 <img width="454" height="280" alt="Screenshot 2026-09-15 111150" src="https://github.com/user-attachments/assets/bb43761a-8bba-4965-82c1-315f63cb6220" />

Next, I designed the key for the lock (shown above). I gave it a base with a diameter of 6mm to ensure the key didn't get stuck in the holes. The long part of the key has a diameter of 5mm and the whole thing has a length of 7mm. Just for fun, I added some text at the tip of the key to label it as "key."


## Preprocessor

<img width="478" height="247" alt="Screenshot 2026-09-15 111347" src="https://github.com/user-attachments/assets/11179351-1eb5-4812-8ecf-a88debe57f5c" />

Moving onto the preprocessor stage, I downloaded my CAD files and uploaded them onto Prusa Slicer (shown above). The design specifications and slice information can be found in the top left and bottom right corners, respectively. I kept the fill pattern on the default setting of Grid because it doesn't take long to print. Also, I didn't really think the fill pattern would play a big role for this artifact. For the filament, I used PLA because, again, it was the default filament and I didn't think it would make a big difference whether I used PLA or PETG. As for the orientation, I made sure the larger diameter for the key was on the base to avoid having to use supports. I didn't need to scale the artifact because I had already set the units to mm in Creo Parametric. The only thing I had to do was uncheck the Inches box in Prusa Slicer and the units automatically set to mm, matching my CAD files. 

<img width="917" height="67" alt="Screenshot 2026-09-15 154439" src="https://github.com/user-attachments/assets/310666e6-1990-431d-8cf2-c185b9648a32" />

Next, I exported the G-code (shown above), moved the file onto the USB, and plugged it into a printer with PLA filament. 

## Print Artifact

<img width="303" height="403" alt="IMG_3028" src="https://github.com/user-attachments/assets/4dd6c7f9-6e89-4882-9e92-85b4f76e451a" />

Moving onto the printing process, I loaded up the file on the printer and hit Print. Everything was running smoothly until halfway through, I noticed the nozzle was no longer putting filament onto the artifact and was just moving around, occasionally spraying filament. I stopped the printer and took out the artifact (shown above). The bottom half was printed normally and you can see the fill pattern. I didn't know what went wrong. Luckily, Dr. Raquet walked in a few moments later and I asked him. He said the problem was most likely some moisture build up in the nozzle, jamming the filament. 

<img width="336" height="252" alt="IMG_3026" src="https://github.com/user-attachments/assets/de550a9b-7c4a-4cd9-b3c5-17996b42f0af" />
<img width="381" height="286" alt="IMG_3029" src="https://github.com/user-attachments/assets/a29e504d-b3dc-497b-8299-cb298926e3ef" />

I moved to another PLA printer and restarted the printing process. Luckily, everything went smoothly this time. The pictures above show the printer display during the printing process and the nozzle laying down filament. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/voe-jwNCcng" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The printer I chose used black filament and was working correctly (shown above). 

## Lessons Learned 

Throughout this project, I made a ton of mistakes, which I didn't realize until far too late. Starting off, I messed up the diameters of the holes on the lock. They were supposed to go all the way down to 4.7mm, but I forgot to account for the 5mm hole counting as one, making it six incremental steps in total, not five. Second, my goal was to use the key as a measuring tool, but I didn't realize that this key was subject to the same tolerances as the holes and that I should be using a caliper to measure instead. Third, all of the text on the artifact, especially the "key" text, was wayyyy too small. The printer's quality at such a small scale is greatly reduced, making it very hard to read the text. They also should have been extruded deeper into the artifact to make them easier to read. If I could change things, I would make the whole artifact much bigger. Lastly, looking back at my work, I realized I was not as thorough as I could have been with my documentation. There are several times where I describe what I'm doing as if its intuitive without providing any images. As for the outcome, the key was able to fit into the first two holes, but wouldn't fit into any holes after that, proving my prediction wrong.

My greatest takeaways from this project are: 

1. Don't be afraid to make the artifact bigger as long as its within the constraints.

2. Document more thoroughly as you go.

3. Be more precise with tolerance calculations in the future.

4. Assume everything will go wrong during the printing process (this is the 2nd time a printer has malfunctioned on me).

In total, this assignment took me about four hours to complete. 

## Resources

Google Gemini

[Design Rules For 3D Printing](https://instructure.charlotte.edu/courses/272053/files/33203768?wrap=1)

[Lock CAD File](https://drive.google.com/file/d/199JwmW0opaw8fZf2ie3VKVm2qFlVOWdc/view?usp=drive_link)

[Key CAD File](https://drive.google.com/file/d/1aDicdPzyb096VI820ECDRrw_ua46wxDS/view?usp=drive_link))


