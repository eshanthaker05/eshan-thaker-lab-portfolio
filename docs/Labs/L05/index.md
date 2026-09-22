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

<img width="250" height="127" alt="Screenshot 2026-09-22 023703" src="https://github.com/user-attachments/assets/0338c77c-4502-4632-8ee2-60b03b11dec2" />


## Decide


## Communicate

