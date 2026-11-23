# EX No.4.2. CUT SECTION OF SOLIDS
## DATE:17-11-2026

## AIM: 
To create the solid model from given drawing and section the solid model

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
STEP 1 : Set Up the Sketch : 

•Open Fusion 360 and set the document units to millimetres (mm)
•Click Create Sketch and select the XY (Front) Plane
•The vertical Y-axis is the axis of revolution. Draw the profile on the left side of it (negative X), as shown in the sketch. 

<img width="279" height="556" alt="Screenshot 2026-11-23 131820" src="https://github.com/user-attachments/assets/8f02a5eb-3abe-45a1-8457-07528d0376c6" />

STEP 2 : Sketch the Base and Stem : 

•Draw a horizontal line from the origin to the left, 1.366 mm long. This is the bottom of the base. 
•From the left end of this line, draw a sloping line up to the stem. The base is 0.148 mm thick at the stem and tapers to a sharp edge at the outer end. 
•Draw the stem outer line vertically, 0.123 mm to the left of the Y-axis. 
•Draw a vertical line on the Y-axis from the origin up to 1.501 mm. The 0.123 mm gap between this line and the stem outer line is the stem radius. 

STEP 3 : Sketch the Bowl Walls : 
•Use Create > Arc > Center Point Arc. Place the common centre point 0.721 mm to the right of the Y-axis and 1.986 mm above the 1.501 mm level. 
•Draw the inner arc of R 2.113 mm starting from the top of the Y-axis line (1.501 mm level) and curving up and to the left.
•Draw the outer arc of R 2.261 mm from the same centre, starting at the top of the stem outer line. 
•End both arcs at the rim height of 3.520 mm above the bottom line.
•Close the rim with a short horizontal line of 0.148 mm (wall thickness) between the two arc ends. 
•Join the small gap at the stem top with a short line so that the profile is one closed loop. Trim the extra segments.

<img width="217" height="371" alt="Screenshot 2026-11-23 131934" src="https://github.com/user-attachments/assets/d0b1944b-d0c4-4758-95b7-310fb04e09e6" />

•Add the dimensions with the Sketch Dimension (D) tool until the sketch is fully constrained (black lines). 

STEP 4 : Revolve the Profile : 
•Click Finish Sketch and select Create > Revolve. 
•Select the closed profile and choose the Y-axis line as the Axis. • Set Angle to 360° and Operation to New Body, then click OK. The wine glass solid is formed.

<img width="311" height="376" alt="Screenshot 2026-11-23 132200" src="https://github.com/user-attachments/assets/fcf1eeca-d898-4128-a633-962531a1847b" />

STEP 5 : Section the Model : 
•Go to Inspect > Section Analysis, select the XY plane and keep the offset as 0. 
•The cut through the centre shows the hollow bowl, the solid stem and the tapered base, matching the sketch. 
•Optionally apply a glass appearance (Modify > Appearance) and capture the final model and section view.


## INPUT:

![image](https://user-images.githubusercontent.com/113594316/199409656-c021c100-857a-4ae4-9752-9ae59465c9c2.png)

## OUTPUT:

<img width="816" height="614" alt="Screenshot 2026-11-23 131248" src="https://github.com/user-attachments/assets/c3b9fb7d-b03d-4600-89b4-ad291c61fd32" />

<img width="1116" height="789" alt="Screenshot 2026-11-23 131405" src="https://github.com/user-attachments/assets/39603180-1688-416c-9ea7-24d026ff9cf7" />


## RESULT:
Thus, the cut section for solid model is created.


