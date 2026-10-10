# A7 – [Linkage Mechanisms]

## Objective

The objective of this assignment is to design, 3D print, and document a working linkage or mechanism that performs a defined motion or task. 

## Research

### Patent 1: Gimbal Assembly 

<img width="406" height="295" alt="Screenshot 2026-10-05 160351" src="https://github.com/user-attachments/assets/d2334cb0-e930-4d9e-883e-cf412fef585f" />

Patented in 2025, this device was designed by Mark E. Rosheim to optimize the rotational movement of a gimbal assembly. It uses two specific types of joints, called yokes, to minimize the jolt experienced by the device when stabalizing in the X, Y, and Z axes. This device has applications in the aerospace industry to stabalize optical cameras or antenna, especially during high-speed flight. This device also has applications in the robotics industry by allowing a robotic arm to execute highly fluid, complex movements without seizing up. 

**Resource**: https://ppubs.uspto.gov/api/pdf/downloadPdf/US-12385597-B2?source=USPAT&requestToken=eyJzdWIiOiI4YzRkOTVkMC1kMjliLTQ4MWEtYTBmOS1lZjFhODExOThjZTQiLCJ2ZXIiOiIyMjExNzdiZC1mY2ZlLTQ4NTktOTk3My1mN2JmMTRmM2NiMDIiLCJleHAiOjB9

### Patent 2: Suspension Assembly for a Cycle having a Fork Arm with Dual Opposing Tapers

<img width="406" height="295" alt="Screenshot 2026-10-05 162944" src="https://github.com/user-attachments/assets/4671fd4b-4869-436e-be94-2f054c2309d3" />

Patented in 2022, this device was designed by David Weagle to reduce the stress on mountain bikes by optimizing the geometry of the existing linkage design. It also utilizes hollow structural fork arms to maximize the allowable bending stress. This device primarily has applications in suspension systems to ease the stress in the vehicle. This can be applied to the biking industry as well as the automotive industry. 

**Resource**: https://ppubs.uspto.gov/api/pdf/downloadPdf/US-11345432-B2?source=USPAT&requestToken=eyJzdWIiOiI4YzRkOTVkMC1kMjliLTQ4MWEtYTBmOS1lZjFhODExOThjZTQiLCJ2ZXIiOiIyMjExNzdiZC1mY2ZlLTQ4NTktOTk3My1mN2JmMTRmM2NiMDIiLCJleHAiOjB9

## Design

It took me a while to figure out what kind of linkage I wanted to design for this assignment. As I was sitting in the library going over my options, I noticed that one of the elevators was out of order, and in front of it was a linkage sign similar to a scissor lift. Unlike a scissor lift, it extended in the horizontal direction to block people from using the elevator. I used this as inspiration for my artifact. 

<img width="325" height="218" alt="Screenshot 2026-10-05 184114" src="https://github.com/user-attachments/assets/8e0a7d69-dd85-4ffc-83f4-f1b3947eafaa" />

<img width="360" height="274" alt="Screenshot 2026-10-05 184522" src="https://github.com/user-attachments/assets/05f19a68-2085-44d6-badc-3a20cea3c779" />

I started by designing the pin since it was the simplest part of this linkage. I sketched a circle with a diameter of 5 mm and extruded by 50 mm. Learning from my mistakes last week, I wanted to keep this artifact relatively small to keep the print time as low as possible. 

<img width="484" height="220" alt="Screenshot 2026-10-05 185413" src="https://github.com/user-attachments/assets/ba9ef175-1aa4-41cd-89e0-370cbbdccff0" />

Next, I designed the links for the pins to snap into. I began by sketching a rectangle. I arbitrarilly chose 60 mm as the length of the link. I set the width to 10 mm to give the holes for the pins a clearance of 2.5 mm on each side. 

<img width="456" height="198" alt="Screenshot 2026-10-05 185551" src="https://github.com/user-attachments/assets/0768e019-7e7f-410a-b94f-b5e7696653a0" />

I then added a 5 mm arc on each side of the rectangle, bringing its total length of to 70 mm. 

<img width="326" height="186" alt="Screenshot 2026-10-05 185627" src="https://github.com/user-attachments/assets/785b35f4-c848-4ca0-b883-2ba739415a68" />

Then, I extruded the link by 5 mm. 

<img width="493" height="181" alt="Screenshot 2026-10-05 192157" src="https://github.com/user-attachments/assets/786bb9bf-900e-433f-9e49-85bb84df4000" />

Finally, I added three equally spaced holes for the pins to fit into. According to the linkages module for this week's lab, to have a pin comfortablly fit into a hole, the hole should have a clearance of 0.2 mm to 0.3 mm per side. Applying this to the holes, I can chose between a range of 5.4 mm and 5.6 mm for the diameter. I decided to go with a diameter of 5.5 mm to safely stay within that range.  

<img width="290" height="285" alt="Screenshot 2026-10-05 193806" src="https://github.com/user-attachments/assets/bc0ae9ff-22df-40b5-9cda-c348479e07c5" />

Lastly, I created the two supports on either side of my artifact. I sketched an I-beam with a 30 mm base and a total height of 50 mm. 

<img width="363" height="293" alt="Screenshot 2026-10-05 193952" src="https://github.com/user-attachments/assets/55f8d4e1-bd55-4f75-9e45-b83745d3d3f8" />

I then extruded my I-beam by 10 mm. 

<img width="251" height="347" alt="Screenshot 2026-10-05 201340" src="https://github.com/user-attachments/assets/f3974105-81c5-4d29-9176-14978a7bddac" />

Finally, I added two holes on the side of my I-beam. I kept made their diameters equal to the diameters of the holes on the links I designed for consistency. 

<img width="302" height="203" alt="Screenshot 2026-10-05 203805" src="https://github.com/user-attachments/assets/83540b21-5301-438b-8388-ce558ff18358" />

I realized that the lengths of the pins were unneccessarily long, so I reduced them to 30 mm and rounded the sides to make it easier to fit them into the links. 

## Preprocessor

<img width="471" height="30" alt="Screenshot 2026-10-05 222645" src="https://github.com/user-attachments/assets/e7328951-1901-4b1b-a690-bdc656ceb3ad" />

<img width="515" height="26" alt="Screenshot 2026-10-05 222826" src="https://github.com/user-attachments/assets/d94621a3-4f8c-4e81-a216-13fd79bdfa23" />

Before loading my CAD models onto Prusa Slicer, I changed the elephant's foot compensation from 0.2 mm to 0.1 mm. When I was researching, I found that PLA does not expand as much as other filaments when heated during the printing process, so I felt confident reducing the compensation by 0.1 mm. For the seam position, I changed it to Random because it will scatter the weak points of my prints randomly rather than having them concentrated in a single location. This will boost the overall strength of each part.  

<img width="639" height="329" alt="Screenshot 2026-10-05 221514" src="https://github.com/user-attachments/assets/209f5238-b4a0-4287-8521-d057589ff396" />

<img width="896" height="71" alt="Screenshot 2026-10-05 221522" src="https://github.com/user-attachments/assets/f03ab7e9-6442-444d-8feb-ebf2db46425d" />

Next, I counted out the correct number of each part I'll need and put them onto Prusa Slicer. I decided to use two printers to print my linkage mechanism to reduce the amount of time I spend on the printing process. Luckily, the Rapid Lab was empty when I went to print. I loaded the pins and links together in a single print, and exported the G-code. 

<img width="639" height="329" alt="Screenshot 2026-10-05 221630" src="https://github.com/user-attachments/assets/70613ca1-e951-47dc-b20b-1a0e8183d7c8" />

<img width="927" height="86" alt="Screenshot 2026-10-05 221640" src="https://github.com/user-attachments/assets/ee3a1810-1af2-4587-b545-14c0ac831a39" />

I then moved the two supports onto Prusa Slicer and exported the G-code. 

## Printing Process

During the printing process, I realized that the I shape of my supports blocks my links from fully extending, so I shaved off the edges in Prusa Slicer and printed. I used printer #3 for this assingment. 

<img width="403" height="302" alt="IMG_3134" src="https://github.com/user-attachments/assets/77157c27-e2bc-4623-8f9d-d9f04f67d383" />

<img width="405" height="304" alt="IMG_3130" src="https://github.com/user-attachments/assets/bb87e5d1-eda8-4013-a46e-727e7a10ac2a" />

The images above shows the printing screen during the printing process of the pins and linkages. The other image shows the actual printer at work. 

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/3EaoiHEB8Qw"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen>
</iframe>

The image below is the final printed artifact.

<img width="428" height="5712" alt="IMG_314" src="https://github.com/user-attachments/assets/af0625f5-8069-4366-9957-82d9a23920ff" />

**Purpose**: The original purpose of this artifact was to mimic a sliding sign I saw in the library. After printing it, I realized it acted more like a toy, so now that's its purpose as it sits on my desk. 

**Components**: All components were printed for this assignment. The three individual parts needed for this artifiact are: pins (8), linkages (8), and supports (2). 

**Tolerances**: For the hole diameters, I chose to make them 0.25 mm smaller than the pin diameter so that they would snap together, as stated on Canvas. 

**Design Decisions**: When deciding the overall size of the artifact, I purposely chose to make it small so that the print time wouldn't be to high. Once again, I realize I could've made it smaller. I guess I underestimate the size of milimeters. Another decision I made was to change the shape of the supports. This was because in the originial design, they blocked the linkages from fully extending, make it impossible for them to connect. Lastly, I decided to only connect the links at the ends, ignoring the hole at its center. This was because I misjudged their proportions when designing and didn't realize that the links would be too close to each other for the linkages to move. 

## Lessons Learned

**Time Spent**: 30 minutes researching, 2 hours CAD modeling, 20 minutes for slicing, 2 hours for printing, 30 minutes for post-processing and assembly. Total time was approximately 4.5 hours. This was less time than I had expected, but that might be because the previous labs have always taken me a lot longer. 

**Biggest Mistake**: Underestimating the scale of milimeters caused me to pivot and rebrand my artifact into a toy. 
