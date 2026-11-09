# A11 – Snap Fit Design for SLA Printing

## Snap Fit Research

A snap fit design is when one part is temporarily deformed and fits into the cavity of another, more rigid part. The two mating parts are then joined together and require some force to seperate. There are four main types of snap fit designs: cantilever, annular, torsional, and hybrid. For this assignment, I decided to create a case for my Aquaphor stick using a cantilever snap fit. I always end up losing my Aquaphor stick somewhere in my room so having a designated place to store it will hopefully avoid some very dry lips in the future.    

After reading through the document "Snap-Fit Joints for Plastics - A Design Guide" provided on Canvas, I had a much better understanding on how to design my cantilever snap fit. To reduce the internal stress on the cantilever beam, I planned on reducing its thickness linearly along its length until it reaches half its original thickness at its hook. I drew a rough sketch of what I wanted my artifact to look like and included some important equations from the document. 

<img width="376" height="259" alt="IMG_0019" src="https://github.com/user-attachments/assets/5b149b6d-7f47-4f51-b450-3111c1926e7b" />

I then researched the specifics about SLA printing. According to the document "How to Design Parts for SLA Printing" linked on Canvas, supported walls should be at least 0.4 mm thick and unsupported walls should be at least 0.6 mm thick. I decided to be safe and set my wall thickness to 2 mm. 

## CAD Design

### Female Part

Using a ruler, I measured the diameter of my stick of Aquaphor to be a little under 2 cm and the height to be around 7 cm. I began by sketching a 32 mm by 32 mm square. This accounts for the 2 cm diameter plus the 2 mm thick walls on both sides of the Aquaphor stick. I decided to add an extra centimeter for some wiggle room. 

<img width="491" height="356" alt="Screenshot 2026-11-08 201540" src="https://github.com/user-attachments/assets/038b3abd-1391-426c-90fa-6b41868fe7cb" />

I then added fillets to the four corners of my sketch. This will reduce deformations when printing, lower print time, and ease internal stresses of the part. It also looks more aesthetically pleasing. 

<img width="452" height="370" alt="Screenshot 2026-11-08 203239" src="https://github.com/user-attachments/assets/21f4be01-eadf-4dc2-84cc-dfeb03d8c001" />

Next, I extruded the sketch by 82 mm. This takes into account the 7 cm of height of the Aquaphor stick plus the 2 mm of wall thickness on the bottom plus an extra 1 cm just to be safe. 

<img width="487" height="360" alt="Screenshot 2026-11-08 202342" src="https://github.com/user-attachments/assets/6d30f36d-2113-48b1-a7da-d19fef9f9e92" />

Now, I needed to design the cavity in which the Aquaphor would be placed in. I sketched a rectangle in the center of the part, leaving 2 cm of wall thickness on all sides. I also added fillets to the four corners for the same reasons I mentioned above. 

<img width="471" height="375" alt="Screenshot 2026-11-08 203525" src="https://github.com/user-attachments/assets/40726ef9-02e1-4fe4-9c61-ac931ccabe53" />

I then extruded into the block by 80 mm, leaving a floor thickness of 2 mm on the bottom. 

<img width="407" height="442" alt="Screenshot 2026-11-08 203703" src="https://github.com/user-attachments/assets/7323a76d-96fb-4003-a3b0-1036f36303c0" />



## Preprocessing


## Postprocessing


## Lessons Learned

## References 

[How to Design Parts for SLA Printing](https://www.hubs.com/knowledge-base/how-design-parts-sla-3d-printing/#how-do-you-design-for-sla-printing)
