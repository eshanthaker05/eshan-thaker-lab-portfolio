# A10 – RC2 Sliding Fit Design

## Research

An RC 2 sliding fit is a type of engineering tolerance class for cylindrical mating parts where the two parts can easily slide/rotate under a light force. A table of RC 2 clearances from the Machinery's Handbook is shown below and lists dimension specifics, depending on the nominal size of the parts. 

<img width="404" height="247" alt="Screenshot 2026-11-09 232821" src="https://github.com/user-attachments/assets/09948a93-fc4c-444d-93de-56e6c9028333" />

I decided I wanted to design and print a spinner with four possible outcomes for the hand to land on. From the table above, I chose to set my nominal hole diameter to 5 mm, or 0.197 in. This means that the hole will have a tolerance of 0.0000 in to +0.0003 in and the shaft will have a tolerance of -0.00032 in to -0.00015 in. Even though these are the values listed in the handbook, I decided to go with a diametrical clearance of 0.30 mm because after talking to my classmates, it turns out the listed tolerances don't work as intended for the resin printers. In the end, I set the hole diameter to 5.11 mm and the shaft diameter to 4.80 mm. 

## CAD Design

### Part A

I started by sketching the base as a circle with a diameter of 40 mm. 

<img width="339" height="241" alt="Screenshot 2026-11-09 201535" src="https://github.com/user-attachments/assets/a28bb615-4d75-4a10-9ea7-ec6bb580448e" />

I then extruded the sketch by 5 mm.

<img width="325" height="190" alt="Screenshot 2026-11-09 200326" src="https://github.com/user-attachments/assets/c95d4508-06d6-429d-bad2-02e0f1815635" />

Next, I needed to design the hole in the center in which the spinner would slide into. I set the hole diameter to 5.11 mm. 

<img width="294" height="241" alt="Screenshot 2026-11-09 235813" src="https://github.com/user-attachments/assets/0007e928-342f-4ea0-9f42-86623b9d732c" />

I then extruded the sketch downwards by 3 mm. 

<img width="299" height="195" alt="Screenshot 2026-11-09 202133" src="https://github.com/user-attachments/assets/7ecadb3c-33e8-46e6-9340-534b125d6d42" />

Next, I sketched a thin ring along the edge for a border. 

<img width="297" height="249" alt="Screenshot 2026-11-10 003250" src="https://github.com/user-attachments/assets/443ec27a-7357-4581-b9b2-9322331e6754" />

I then extruded this ring by 1 mm. 

<img width="481" height="341" alt="Screenshot 2026-11-10 003320" src="https://github.com/user-attachments/assets/ebcd56ef-1bcb-4aff-886d-2db8f9c37393" />

Lastly, I added four equally sized triangles on each side of the disc. This will help differentiate which quandrant the spinner lands on. 

<img width="316" height="246" alt="Screenshot 2026-11-10 004844" src="https://github.com/user-attachments/assets/08f803b6-2df8-4490-b4c2-d2971e656d8d" />

### Part B 

For the spinner, I began by sketching a circle with a diameter of 4.80 mm.

<img width="258" height="173" alt="Screenshot 2026-11-10 002304" src="https://github.com/user-attachments/assets/a96c2a79-7faf-4e77-9f7a-5ce74f48e775" />

I extruded the sketch by 6 mm. 

<img width="388" height="267" alt="Screenshot 2026-11-09 234608" src="https://github.com/user-attachments/assets/4601df9c-2795-4910-9e29-1df2a3587b85" />

Next, I extruded a section to later turn into the arm for the spinner. 

<img width="284" height="184" alt="Screenshot 2026-11-10 002800" src="https://github.com/user-attachments/assets/bfb51bd6-8654-4d25-a7c9-7aadc5f50c33" />

I then created a pointed edge by chamfering the two corners of the arm. 

<img width="295" height="225" alt="Screenshot 2026-11-10 003011" src="https://github.com/user-attachments/assets/9a481afc-5040-4aa7-9d77-bf31a2792242" />


## Preprocessing

**Machine Name:** Humorous Petrel

<img width="512" height="302" alt="Screenshot 2026-11-21 203349" src="https://github.com/user-attachments/assets/5a14d786-285c-45b6-9a90-2242b04b199a" />

I decided to orient the parts as shown above because it was the lowest print time I could achieve. For the supports, I just had the software autogenerate them for me and I went with the default layer thickness of 0.050 mm. I left all the other parameters at their default settings as well and went to print. 

## Post-Processing

<iframe
  width="560"
  height="315"
  src="https://www.youtube.com/embed/4nqJnwd_510"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen>
</iframe>

Shown above is a video of the resin printer beginning to print the artifact. 

<img width="428" height="571" alt="IMG_3344" src="https://github.com/user-attachments/assets/6ec12422-6fd1-46c5-88db-9ca0895f70f6" />

<img width="571" height="428" alt="IMG_3345" src="https://github.com/user-attachments/assets/51940d01-4455-433e-87c6-85c713042641" />

After printing, I moved it over to the alcohol bath to sit in for around 10 minutes. Once it was done, I opened the tray and scrapped the supports off my artifacts. It came out a lot stickier than I was expecting and was kind of annoying to touch. 

## Fit Test

<img width="302" height="403" alt="IMG_3373" src="https://github.com/user-attachments/assets/62b6ae24-30e5-44b0-b6a1-e648782b7d05" />

I measured the dimensinons of my artifact using a caliper after printing, and the values were on the lower end of my expected tolerances. This made sense because of the shrinking that occurs during the printing and curing process. The spinner and the base ended up fitting a little tightly, but still worked. 

## Lessons Learned

The main challenge with this assignment was operating the resin printer and making sure my calculations accounted for the shrinkage. After the printing process, the surface of my artifact was sticky, making it hard for the two parts to fit together. I fixed this by washing it with the alcohol liquid provided in the Fab Lab a bunch of times and drying it off with a paper towel. To improve my accuracy next time, I can design the parts to have larger tolerances to account for that stickiness post-print. 

**Total Time Spent:** 6 hours


