# A5 – [Design for a Snap Fit]

## Objective

The objective of this lab is to parametrically design and 3D print a two-part snap-fit flexure artifact consisting of two parts that can clip and unclip without breaking. 

## Modeling

### Required Parameters

Material: PLA

Young's Modulus (E): 3600 MPa

Yield Strength (Sy) = 60.0 MPa

Safety Factor = 3.5

### Calculations

<img width="243" height="349" alt="Screenshot 2026-09-22 023638" src="https://github.com/user-attachments/assets/a1335015-73f6-440d-ac12-212a986fd084" />

<img width="249" height="132" alt="Screenshot 2026-09-22 024321" src="https://github.com/user-attachments/assets/aa247c92-bbd8-48d3-8558-59713c15be71" />


All the variables listed below were found as shown above. I began with choosing the thickness and height of the beam to be 5 mm. Using these dimensions, I calculated the moment of inertia. Next, I rewrote the equation for the maximum stress, then used that to find the length of the beam, which came out to be 40.123 mm. Using the values I've found, I calculated the maximum deflection to be 1.022 mm. Lastly, I checked the numbers to make sure the axial stress and average shear were under the max stress limit. 

Thickness (b) = 5 mm

Height (h) = 5 mm

Transverse Load (P): 2 lbf = 8.90 N (chosen)

Axial Load (Q): 6 lbf = 26.69 N (chosen) 

Allowable Stress (σ) = Sy / 3.5 = 17.14 MPa 

Moment of Inertia (I) = 52.98 mm^4

Length = 40.123 mm

Max Deflection (δ) = 1.022 mm

### Free Body Diagram

<img width="248" height="179" alt="Screenshot 2026-09-22 024450" src="https://github.com/user-attachments/assets/f54e5e07-333f-477e-a2f8-040750e0013d" />

Before drawing the free body diagram, I drew a rough sketch of what this artifact is supposed to look like. 

<img width="250" height="127" alt="Screenshot 2026-09-22 023703" src="https://github.com/user-attachments/assets/0338c77c-4502-4632-8ee2-60b03b11dec2" />

With the sketch in mind, I drew a free body diagram for both parts of this artifact. 

## Parametric Design

<img width="374" height="235" alt="Screenshot 2026-09-22 032009" src="https://github.com/user-attachments/assets/2def1bb7-9478-4272-aa4d-b8a80d222ddf" />

<img width="349" height="231" alt="Screenshot 2026-09-22 040719" src="https://github.com/user-attachments/assets/3f3eb203-1cff-4581-a085-bf8aecb45b38" />

Before starting the design process, I immediately changed the default to metric units. Next, I inputted all the known variables into the parameters section, which I will later use to constrain certain dimensions.  

<img width="312" height="246" alt="Screenshot 2026-09-22 101648" src="https://github.com/user-attachments/assets/d62665ea-0f67-4709-a0eb-34bb8a61f233" />

Next, I sketched the first part using some of the parameters I set up, like the length and the width of each side. 

<img width="301" height="233" alt="Screenshot 2026-09-22 191554" src="https://github.com/user-attachments/assets/c970700d-0b51-4fbc-9071-48320ac317a5" />

Then, I extruded the part by 5 mm by setting the thickness equal to the thickness variable I previously defined. 

<img width="297" height="85" alt="Screenshot 2026-09-22 102203" src="https://github.com/user-attachments/assets/06e6c74b-9823-4258-9f89-cdff9ce3220f" />

Next, I created the second part into which the first part will snap. I began by extruding a box slightly wider than part 1. 

<img width="284" height="143" alt="Screenshot 2026-09-22 102749" src="https://github.com/user-attachments/assets/c5a5487c-bef2-42b3-ba29-81dbb0e05756" />

Next, I extruded a small portion into the box. To find the dimensions, I took the thickness and length of the prongs from part 1 and 0.2 mm. I chose this number because I learned from the last lab that this is the tolerance of dimensions on the Prusa Slicer Core One printer. 

## 3D Printing and Test

<img width="478" height="246" alt="Screenshot 2026-09-22 123701" src="https://github.com/user-attachments/assets/eda0dd4e-d83a-42ce-b6af-cda4f0500965" />

After finishing the modeling process, I moved part 1 and part 2 onto Prusa Slicer as shown above. The feature type information and sliced info can be found in the top left and bottom right, respectively. I used the default, grid, infill pattern for its speed during the printing process. 

<img width="878" height="57" alt="Screenshot 2026-09-22 121706" src="https://github.com/user-attachments/assets/29bf40cc-4890-4552-919c-f02530f284f1" />

I saved the files as a G-code and uploaded it onto the USB drive, as shown above. 

<img width="571" height="428" alt="IMG_3044" src="https://github.com/user-attachments/assets/ddeeaea6-5573-4d3a-a6df-556b24988a8d" />

It took about 12 minutes in total to print. I forgot to take a picture of the screen on the printer, but I've included a video of the printer in action below. 

<iframe width="560" height="315" src="[https://www.youtube.com/embed/VIDEO_ID](https://youtu.be/2ifBkFhLHsg)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

https://youtu.be/2ifBkFhLHsg
