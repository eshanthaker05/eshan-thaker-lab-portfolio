# A9 – Laser Cutter

**Group:** Eshan Thaker and Andy Chwalik

## Objective

- Evaluate laser cutting as a viable manufacturing process. You will select and record machine settings, and explain the process's strengths and limits compared with FDM printing.

- Measure laser kerf and actual material thickness, and apply both as engineered allowances so your joints fit reliably across the whole sheet.

- Translate a parametric 3D model into 2D cut files, then back into a working 3D assembly.

## Analyze

### Step 1: Measure the Material  

We started by measuring the thickness of the board at three different places using a caliper and taking the average. 

<img width="286" height="214" alt="IMG_3218" src="https://github.com/user-attachments/assets/7d51ab89-5882-4a6b-ae3d-a12c90e7d7b4" />

<img width="403" height="302" alt="IMG_3219" src="https://github.com/user-attachments/assets/964a6b9c-203d-4aa9-b517-360e9d2d2ff0" />

<img width="286" height="218" alt="IMG_3221" src="https://github.com/user-attachments/assets/25556cf5-ae09-4d21-b7d3-3be59691366a" />

**Thickness 1:** 0.114 in

**Thickness 2:** 0.117 in

**Thickness 3:** 0.111 in

**Average Thickness:** 0.114 in

### Step 2: Measure the Kerf

The kerf is the amount of material the laser burns away and must be experimentally measured. We measured the kerf by lasering a square with a nominal width and length of 0.591 in. This is equal to 15.114 mm which represents our chosen length plus the average thickness. Using calipers, we measured the actual length in the x and y directions of the square and got 0.584 in and 0.582 in respectively. Subtracting this from our nominal values, we got the kerfs listed below: 

**X Direction Kerf:** 0.007 in

**Y Direction Kerf:** 0.009 in

For the rest of this assignment, we used the average of these two values for a kerf value of 0.008 in. The images below show the dimensions of the square in SolidWorks and then what it looked like when we moved it onto the Inkscape and Epilogue softwares. 

<img width="477" height="452" alt="Screenshot 2026-11-13 224342" src="https://github.com/user-attachments/assets/f503e72a-3998-4136-9e50-bf43a4141c7c" />

<img width="468" height="382" alt="Screenshot 2026-11-13 224349" src="https://github.com/user-attachments/assets/196abf2b-4747-46f9-b8bb-365ea61cd96c" />

<img width="465" height="387" alt="Screenshot 2026-11-13 224355" src="https://github.com/user-attachments/assets/8aa6d120-1126-43ed-9a37-16956ef07191" />

### Step 3: Run a Fit Test

Next, we ran a fit test by lasering a square with slots of varying width. The goal of this is to find a slot width capable of press fitting the thickness of the wood plate. We created five slots in our lasered coupon. The middle slot is the nominal width and the two slots in either direction have widths increasing or decreasing by the measured kerf. After testing all the slots, we found the slot with a width two times our kerf to be a good fit. The images below show the coupon in SolidWorks, Inkscape, and Epilogue softwares. The last image is the lasered coupon and the wood chip in the slot we decided to use for our clearance. 

<img width="236" height="186" alt="Screenshot 2026-11-13 224759" src="https://github.com/user-attachments/assets/57e857f7-067c-4263-b9ba-1086f1b778dd" />

<img width="235" height="180" alt="Screenshot 2026-11-13 224804" src="https://github.com/user-attachments/assets/02af8f36-a913-4d00-9adc-bbb34a3c7214" />

<img width="241" height="201" alt="Screenshot 2026-11-13 224811" src="https://github.com/user-attachments/assets/309c0505-1f34-4acb-9cfc-30d7c65bc30d" />

<img width="302" height="403" alt="IMG_3222" src="https://github.com/user-attachments/assets/64cf26f7-79f0-4376-9149-f4b5385f347c" />

## Decide

### Step 4: Choose your Clearance

As mentioned in the previous step, we chose a clearance of two times our measured kerf. This is because, unlike the other slots, this clearance firmly held our wood piece in place. The only other slot that came close was the clearance of one times our kerf, but after a few uses it wore down the slot so that it wasn't a good fit anymore. 

After deciding on the clearance, we spent some time brainstorming an artifact to create with three unique parts. After searching the internet for inspiration, we ended up going with a simple rocket ship similar to the one shown below. We counted the two frames as one unique part, and each ring as its own unique part since they have to be modeled with different sizes. We also wanted all the rings to clip onto the outside of the frame, except the lowest one, to make the assembly easier. 

<img width="426" height="421" alt="Screenshot 2026-11-13 210739" src="https://github.com/user-attachments/assets/403f72d0-24c8-48a8-a694-436377fe2bc7" />

## Design

### Parameter Table 

<img width="432" height="206" alt="Screenshot 2026-11-13 230038" src="https://github.com/user-attachments/assets/48f2ba7b-7343-42a4-bd35-2f7ec8bd02ab" />

### Outer Rings

My task in the design process was to design the rings that would attach onto the frame. We wanted five rings in total with two small rings, two medium rings, and one large ring. The rings would have to be designed in halves since the frame was going to cut through them. Unlike the other rings, the small ring at the bottom of the rocket was going to be attached from the inside of the frame to account for the shape of the frame and to maintain the overall aesthetics of the rocket. I began by inputting the clearance, kerf, and thickness into the parameters section. Using these values, I created equations to automatically set the inner and outer radius of each ring.  

<img width="343" height="183" alt="Screenshot 2026-10-26 214013" src="https://github.com/user-attachments/assets/7a46d7b5-02aa-43af-8da8-9290c01a5951" />

Using the parameters, I first designed the small bottom ring. This means that the opening had to be drawn on the inside of the semi-circle so that it could be attached on the inside of the frame, as shown in the image. 

<img width="405" height="234" alt="Screenshot 2026-10-26 224856" src="https://github.com/user-attachments/assets/064fb831-7ecd-4260-9ceb-d7c1c720e01b" />

Next, I designed the medium ring. Using the equations I set earlier, I just changed the radius values and updated my model. For the medium and large rings, the opening had to be drawn on the outside of the semi-circle since they were being attached on the outside of the frame. 

<img width="276" height="153" alt="Screenshot 2026-10-26 224913" src="https://github.com/user-attachments/assets/156a1055-cb10-4b38-ab65-02689632afb6" />

I repeated this step until I had a semi-circle for the large ring as well. 

### Frame 

The documentation below is by Andy since he designed the frame. 

For the first step, I wanted to make the shape of the body for a rocket. Originally I wanted to use a spline tool to do this, but I heard from another group that Inkspace reacts weirdly to the spline tool. To get around this, I just created an elipse that was 4.5in in length and 1in in width. I then offset the elipse I created 0.25in to create the body without the connections. Using an elipse like this will make our rocket ship look more round, but we thought that was fine.

<img width="271" height="644" alt="elipse" src="https://github.com/user-attachments/assets/1d5f94f2-0316-441a-87b2-8dd42f32684d" />

The next step I took was creating the first connection point. We are going to have five connection points up the side of the body to connect the donuts to. I decided to start with the middle one first. To do this, I created a centerline through the middle of my elipse and then offset that line by our clearance: 0.098in. Next, we decided how long we wanted our connection point to be. We decided on 0.15in, so I made sure the connection point was 0.15in in from the outside of the body. I then trimmed the body to make it all of the geometry work together

<img width="464" height="170" alt="connection_center" src="https://github.com/user-attachments/assets/ae32f877-7b69-4785-8a3b-7a12303fd6f4" />

Now that the center connection point is done, I had to find the location for the other four location points. To do this, I took the height of the inner elipse (4in) and then divided it by five for the five connections we have. This gave me 0.8in which will be the gap between each of our connection points. Using this value, I created the two connection points of the center one. The top connection point is on the inside of the body because I am going to mirror it, and I didn't want the connection point to mess with the fins.

<img width="237" height="341" alt="connection_top3" src="https://github.com/user-attachments/assets/b45f7d63-735e-4cb1-a804-02600cc04d55" />

Now that I have all of my connection points, I can mirror my connection points over the centerline I created earlier for the center connection. This will give me all five of my connection points on one side of the body.

<img width="236" height="661" alt="connection_right5" src="https://github.com/user-attachments/assets/05b78b48-58d5-4759-9659-cb79e2157f72" />

Once I had all of the connection points, it was time to move onto the fins. To do this, I used the line tool and made my first click between the bottom connection and the one above it. There is no real measurement with it, I just clicked between them. I then created a triangle shape that connected to the bottom of the rocket. We wanted the rocket to be about 5.5in tall, so I made the bottom of the triangle 1in from the bottom of the body. To make it look more like a fin, I rounded the sharp edge by 0.1.

<img width="461" height="485" alt="rocket_fin" src="https://github.com/user-attachments/assets/25f1b630-b4b9-4321-a858-4cbd8337571b" />

Now that I had one side completed, I made a centerline going from the top of the ellipse all the way to the bottom. I then mirrored the entire shape over that centerline to complete the main shape of the silhouette.

<img width="355" height="464" alt="rocket_mirror" src="https://github.com/user-attachments/assets/277fc404-466a-4d4c-b367-eaaee19b979d" />

The last thing I had to worry about was creating a connection between the two different silhouettes. To do this I decided to make a cutout at the very bottom of the rocket and then a small cutout at the top of the rocket. The idea is that the bottom of this silhouette will slide over the top of the other, and they will connect with the two indents at the top.

<img width="537" height="434" alt="silhouette_connection_top1" src="https://github.com/user-attachments/assets/d78fb5ed-4bd1-4cb0-a1ee-fc470ff45d89" />

<img width="649" height="346" alt="silhouette_connection_bottom1" src="https://github.com/user-attachments/assets/49760783-a627-4a80-9f61-b8052837cbdf" />

To make the second silhouette, I saved the previous file as is and then undid the previous step. To finish the connection points, I did the exact same thing as the previous step by opposite. For the top connection, I made the connection point on the top. For the bottom connection. it is just solid material for the other silhouette to slide over

<img width="449" height="301" alt="silhouette_connection_top2" src="https://github.com/user-attachments/assets/d5e38d01-b540-4cf6-8940-547b515fdbf7" />

Once I had both silhouettes finished, I extruded them by 0.114in (the thickness of our board) and then put them in an assembly. This will give a better understanding of what our vision for this rocket ship is like.

<img width="307" height="469" alt="rocket_full" src="https://github.com/user-attachments/assets/c14c2a4d-3fbb-4313-8fa1-513a1859c06e" />

That completes the CAD model for the silhouette. If you notice in the full picture of the sketch, there are dimensions show the diameter of the connection points. This was so Eshan knew what diameter the donuts had to be in order for all of our parts to fit correctly.

## Manufacturing




<img width="214" height="286" alt="IMG_3225 (1)" src="https://github.com/user-attachments/assets/ce83805e-83c5-47a9-9d35-4bc51adb1477" />

<iframe
  width="315"
  height="560"
  src="https://www.youtube.com/embed/J-SVBTnp-wQ"
  title="YouTube Short"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen>
</iframe>



## Communicate

