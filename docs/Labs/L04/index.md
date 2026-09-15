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

<img width="424" height="201" alt="Screenshot 2026-09-15 100930" src="https://github.com/user-attachments/assets/05810777-32b8-4f8c-8f53-6fddc945265a" />

<img width="441.2" height="246.8" alt="Screenshot 2026-09-15 100959" src="https://github.com/user-attachments/assets/3e2df05b-91f4-458d-920b-2d7db0b2a318" />

I started my design by sketching a 60mm x 15mm rectangle, then extruding it by 5mm (shown above). 

<img width="455" height="186" alt="Screenshot 2026-09-15 105100" src="https://github.com/user-attachments/assets/20397dc1-b199-4633-ad41-2811f5924a26" />

Next, I individually added five holes (shown above). The first one is 10mm from the left edge with a diameter of 5mm. The next hole is 20mm from the left edge with a diameter of 4.94mm. This pattern keeps going for all five holes until the last one, which is 50mm from the left edge with a diameter of 4.76mm. I decided to start with 5mm because I wanted to keep the print time to a minimum as best I could. According to the design rules chart, the tolerance is +/- 0.3% with a lower limit of 0.3mm. After running some calculations, I realized 0.3% of 5mm is less than 0.3mm, so I decided to decrease the diameters by 0.3mm since that's the lowest the printer can handle. I set the diameters so that they would decrease until the last one reaches the lower limit (I later realize I messed up). 
Underneath each hole, I extruded some text into the body labelling the diameter of each hole. 

<img width="497" height="284" alt="Screenshot 2026-09-15 105944" src="https://github.com/user-attachments/assets/ab3bfc6f-e111-492f-87ef-d97c23585b33" />

Next, I added the loop on the top of the body to make it look more like a lock. Honestly, I should have done this step a lot earlier, when I was first sketching the body, but I guess that thought didn't occur to me. 



## Preprocessor


## Print Artifact


## Lessons Learned 


## Resources

