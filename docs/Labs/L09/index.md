# A9 – Laser Cutter

**Group:** Eshan Thaker and Andy Chwalik

## Objective

- Evaluate laser cutting as a viable manufacturing process. You will select and record machine settings, and explain the process's strengths and limits compared with FDM printing.

- Measure laser kerf and actual material thickness, and apply both as engineered allowances so your joints fit reliably across the whole sheet.

- Translate a parametric 3D model into 2D cut files, then back into a working 3D assembly.

## Analyze

### Step 1: Measure the Material  

We started by measuring the thickness of the board at three different places using a caliper and taking the average. 

<img width="571" height="428" alt="IMG_3218" src="https://github.com/user-attachments/assets/7d51ab89-5882-4a6b-ae3d-a12c90e7d7b4" />

<img width="403" height="302" alt="IMG_3219" src="https://github.com/user-attachments/assets/964a6b9c-203d-4aa9-b517-360e9d2d2ff0" />

<img width="571" height="428" alt="IMG_3221" src="https://github.com/user-attachments/assets/25556cf5-ae09-4d21-b7d3-3be59691366a" />

**Thickness 1:** 0.114 in

**Thickness 2:** 0.117 in

**Thickness 3:** 0.111 in

**Average Thickness:** 0.114 in

### Step 2: Measure the Kerf

The kerf is the amount of material the laser burns away and must be experimentally measured. We measured the kerf by lasering a square with a nominal width and length of 0.591 in. This is equal to 15.114 mm which represents our chosen length plus the average thickness. Using calipers, we measured the actual length in the x and y directions of the square and got 0.584 in and 0.582 in respectively. Subtracting this from our nominal values, we got the kerfs listed below: 

**X Direction Kerf:** 0.007 in

**Y Direction Kerf:** 0.009 in

For the rest of this assignment, we used the average of these two values for a kerf value of 0.008 in. 

### Step 3: Run a Fit Test

Next, we ran a fit test by lasering a square with slots of varying width. The goal of this is to find a slot width capable of press fitting the thickness of the wood plate. We created five slots in our lasered coupon. The middle slot is the nominal width and the two slots in either direction have widths increasing or decreasing by the measured kerf. After testing all the slots, we found the slot with a width two times our kerf to be a good fit. 

<img width="302" height="403" alt="IMG_3222" src="https://github.com/user-attachments/assets/64cf26f7-79f0-4376-9149-f4b5385f347c" />

## Decide

### Step 4: Choose your Clearance

As mentioned in the previous step, we chose a clearance of two times our measured kerf. This is because, unlike the other slots, this clearance firmly held our wood piece in place. The only other slot that came close was the clearance of one times our kerf, but after a few uses it wore down the slot so that it wasn't a good fit anymore. 

### Step 5: Cut and Assemble your Final Kit

<img width="428" height="571" alt="IMG_3225 (1)" src="https://github.com/user-attachments/assets/ce83805e-83c5-47a9-9d35-4bc51adb1477" />

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

