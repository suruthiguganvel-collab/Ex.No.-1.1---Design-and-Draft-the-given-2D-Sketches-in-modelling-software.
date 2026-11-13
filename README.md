# Ex.No.-1.1-Design and Draft the given 2D Sketches in modelling software.

## AIM

To create a 3D model from given orthographic projection."
Detailed Explanation: The primary objective of this lab exercise is to convert 2D orthographic engineering drawings—such as the Front View, Top View, and Side View—into a complete, accurate 3D solid model using computer-aided design software.
Through this process, designers learn how to sketch 2D profiles based on structural blueprint and transform them into functional 3D parts using tools like extrusion.

## REQUIREMENTS

1.Autodesk Fusion 360: The core cloud-based Computer-Aided Design (CAD) software utilized for sketching, 3D modeling, and engineering design.
2.Windows 10: The minimum required operating system environment needed to run the Fusion 360 application smoothly and reliably.
3.16 GB of RAM: High-performance memory capacity required to handle complex 3D graphics and rendering operations (integrated graphics with 1 GB VRAM or more is strongly recommended).
4.Internet Connection: A stable broadband connection with a download speed of 2.5 Mbps or faster, and an upload speed of 500 Kbps or faster to support cloud saving and workspace syncing.

## PROCEDURE
Step 1: Launch and Setup the Workspace
1. Software Initialization:
Initialize and launch Autodesk Fusion 360 from your desktop shortcut or application menu and wait for the main application interface and cloud synchronization to load completely.
2. Creating and Managing a New Design File:
Navigate to the top application menu, click on File, and select New Design to open a fresh, blank modeling canvas where your 3D component will be constructed from scratch.

<img width="1600" height="819" alt="WhatsApp Image 2026-11-12 at 7 19 13 PM" src="https://github.com/user-attachments/assets/0f31dfc0-7074-4ffb-9e25-211fe89b1722" />

<img width="1916" height="1013" alt="Screenshot 2026-11-12 191450" src="https://github.com/user-attachments/assets/dcbcebfa-0148-4d37-b0a7-478a94d7717a" />

3. Configuring Document Settings and Units:
Expand the Document Settings folder located at the top of the browser tree on the left side of the screen.
Check the current active unit measurement system and verify or change the units to Millimeters (mm) (which is the standard unit used for precision mechanical components and engineering design drawings) by clicking on the Change Active Units icon.

<img width="1914" height="1021" alt="Screenshot 2026-11-12 191601" src="https://github.com/user-attachments/assets/9720b6d2-3498-4a1a-bd5d-e9d2fc68ce7d" />

4. Saving the Design Project:
Click on the Save icon (disk symbol) on the quick access toolbar or go to File > Save to open the save dialog box.
Enter an appropriate, descriptive file name for your project (e.g., Exercise_1.1 or Mechanical_Component_Ex1) and save it securely inside your designated cloud project folder or local data panel for version control and easy retrieval.

<img width="1920" height="964" alt="Screenshot 2026-11-12 192334" src="https://github.com/user-attachments/assets/2ec99ee4-2f51-4b9d-983a-8ed797b0d1aa" />

Step 2: Creating the Base Sketch
1. Activating the Sketch Environment and Selecting the Datum Plane:
Navigate to the Solid tab on the top toolbar, locate the Create panel, and click on the Create Sketch icon to enter the 2D sketching environment.
Identify the three primary reference origin planes (XY, YZ, and XZ planes) displayed at the center of the workspace.
Select the appropriate standard working plane (such as the XY Plane for the Top view or the XZ Plane for the Front view, depending on the orientation shown in the engineering drawing) to establish your 2D sketching surface.

<img width="1600" height="900" alt="WhatsApp Image 2026-11-12 at 9 09 09 PM" src="https://github.com/user-attachments/assets/bd967547-bbcf-4cd5-96e7-f8482cdba376" />

2. Constructing the Outer Boundary Profile:
From the Sketch toolbar, select the suitable 2D drawing tools such as Line (Shortcut: L) or 2-Point Rectangle / Center Rectangle (Shortcut: R) to sketch the rough outer boundary of the primary base geometry.
Anchor the starting point of your geometry directly onto the Origin Point (0, 0, 0) so that the sketch remains properly aligned with the coordinate system.
Ensure that all corners and endpoints connect cleanly to form a completely closed 2D loop (indicated by a light-blue shaded interior region).

3. Applying Parametric Dimensions:
Activate the Sketch Dimension tool from the toolbar (or press the keyboard shortcut D) to assign exact numerical measurements to your geometry.
Click on the individual sketch lines, edges, or between two parallel entities, drag the dimension text outward, and enter the exact length, width, and positional values specified in the given technical diagram.

<img width="1910" height="956" alt="image" src="https://github.com/user-attachments/assets/90d97674-5acb-4037-a1cf-720bf0b7d4a7" />

4. Applying Geometric Constraints and Verifying Fully Constrained Status:
Open the Constraints panel on the sketch toolbar and apply necessary geometric relationships—such as Horizontal/Vertical, Parallel, Perpendicular, Coincident, or Equal—to lock the shape and alignment of the sketch elements.
Verify that the entire 2D sketch is fully constrained, which is visually confirmed when all blue sketch lines turn completely black and a small red padlock icon appears next to the sketch name in the browser tree.

<img width="463" height="656" alt="image" src="https://github.com/user-attachments/assets/228f9d5e-7a33-4517-a193-2cf9c362efce" />

Step 3: Sketching Internal Features (Holes, Slots, or Cutouts)
1. Activating Sketch Tools for Internal Profiles:
Remain inside the active 2D sketch environment or select the top flat planar face of your existing base profile, click Create Sketch to start a secondary sketch layer.
Navigate to the Create dropdown menu on the toolbar to access advanced drawing primitives such as Circle (Center Diameter Circle, shortcut: C) or Slot (Center-to-Center Slot, Overall Slot).

<img width="471" height="525" alt="Screenshot 2026-11-13 095606" src="https://github.com/user-attachments/assets/3a88b6db-582c-480b-bb9b-aa28d212dc78" />

2. Drawing Internal Circles and Slots:
Click on the canvas to place the center point of the internal hole, circle, or slot corresponding to the layout shown in the engineering drawing.
Drag your cursor outward to define the approximate size and click again, or directly type the exact diameter/radius value into the input box and press Enter.

3. Positioning Features Using Sketch Dimensions:
Activate the Sketch Dimension tool (shortcut: D) to precisely locate the center points of these internal features.
Select the center point of the circle/slot and then click on a reference outer edge or the central origin point, drag the dimension line away, and enter the exact coordinate or offset distance specified in the diagram.

<img width="877" height="811" alt="image" src="https://github.com/user-attachments/assets/0eed2f44-dc6f-4610-9eec-415cf0969e5e" />

5. Completing and Exiting the Sketch Environment:
Review all internal profiles, center distances, and dimensions to ensure everything matches the engineering reference drawing.
Locate and click the green Finish Sketch checkmark button on the right side of the floating sketch palette (or top toolbar) to exit the 2D sketching mode and return to the 3D modeling workspace.

<img width="486" height="380" alt="image" src="https://github.com/user-attachments/assets/36aab3df-46bd-4bc2-8fa5-8c3704ca48a0" />

Step 4: 3D Solid Modeling Using the Extrude Tool
1. Activating the Extrude Command:
Navigate to the Solid tab on the top toolbar, locate the Create panel, and click on the Extrude tool (or simply press the keyboard shortcut E) to open the Extrude dialog box on the right side of the screen.

<img width="787" height="735" alt="image" src="https://github.com/user-attachments/assets/c8353045-b30f-4f80-a417-854b95b0b737" />

2. Selecting the Closed 2D Sketch Profile:
Move your cursor over the completed 2D sketch on the canvas and click directly inside the main closed profile boundary (highlighted in blue) to select the region you want to convert into a 3D solid.
Ensure that any internal holes or cutouts that need to remain hollow are left unselected so they automatically form through-holes during extrusion.
3. Defining Extrusion Direction, Extent, and Distance:
In the Extrude dialog box, verify that the Start is set to Profile Plane and choose the appropriate Direction (such as One Side, Two Sides, or Symmetric depending on your design requirement).
Drag the directional blue arrow on the screen or type the exact thickness/height measurement (e.g., 10 mm, 15 mm, or the specific value given in the engineering drawing) into the Distance input field.

<img width="341" height="775" alt="image" src="https://github.com/user-attachments/assets/3bfe39fc-1cbe-420e-b34f-8b028e00be5e" />

4. Confirming the Boolean Operation and Generating the 3D Body:
Under the Operation dropdown menu in the dialog box, ensure it is set to New Body so that Fusion 360 creates a brand-new independent 3D solid object.
Click OK (or press Enter) to finalize the extrusion and verify that the newly generated 3D solid appears under the Bodies folder in the Browser tree.

Step 5: Adding Secondary Features (Bosses, Pockets, Ribs, or Extra Extrusions)
1. Selecting a Planar Face for Secondary Sketching:
Inspect the reference engineering drawing for any secondary features such as raised cylindrical bosses, multi-level steps, internal pockets, or structural ribs.
Click directly on the top or side flat planar face of the existing 3D solid body to select it as your new sketching surface, then click the Create Sketch icon on the toolbar to enter the 2D sketch environment on that specific face.
2. Sketching and Constraining the Secondary Profile:
Use the Project tool (shortcut: P) if needed to reference existing edges or center points from the base 3D body onto your new sketch plane.
Draw the secondary 2D profile—such as a concentric circle for a cylindrical boss, a smaller rectangle for a stepped block, or a closed slot for a pocket—using the Circle, Rectangle, or Line tools.
Apply exact measurements using the Sketch Dimension tool (shortcut: D) and add geometric constraints until the secondary profile is completely black (fully constrained.
3. Exiting the Sketch and Activating the Extrude Command:
Click the green Finish Sketch icon on the toolbar to return to the 3D modeling workspace.
Select the Extrude tool (shortcut: E) from the Create panel and click inside the newly created closed secondary sketch profile.
4. Executing Join or Cut Boolean Operations:
To Add Material (Bosses / Steps): Drag the directional arrow outward away from the solid face, enter the specified protrusion height in the Distance box, and ensure the Operation dropdown is set to Join so the new feature merges seamlessly with the main body.
To Remove Material (Pockets / Blind Holes): Drag the directional arrow inward into the existing solid body (the preview will turn red), enter the exact cut depth or select All under Extent Type for through-holes, and verify that the Operation is set to Cut.
Click OK to finalize the secondary 3D feature and verify its appearance in the viewport.

<img width="666" height="912" alt="image" src="https://github.com/user-attachments/assets/9616ed00-6ef6-4ee6-9172-271164659c22" />

Step 6: Applying Edge Finishing Features (Fillets and Chamfers)
1. Activating the Fillet Command for Rounded Edges:
Navigate to the Solid tab on the top toolbar, expand the Modify dropdown menu, and select the Fillet tool (or simply press the keyboard shortcut F) to open the Fillet dialog box.
Identify all internal or external sharp corners and linear edges on the 3D solid model that require smooth rounding according to the technical drawing specifications.

<img width="1272" height="857" alt="image" src="https://github.com/user-attachments/assets/a805ed78-1d61-4b63-8229-68597cff5d41" />

2. Selecting Edges and Specifying the Fillet Radius:
Click individually on the target 3D model edges (holding the Ctrl or Cmd key if needed to add multiple edges to the same selection set) and verify that Tangent Chain is enabled if you want connected tangent edges selected automatically.
Drag the blue directional arrow inward or type the exact radius measurement (e.g., R2 mm, R5 mm, or the designated value from the diagram) into the Radius input field, verify the live preview, and click OK.
3. Activating the Chamfer Command for Beveled Cuts:
Open the Modify menu again and select Chamfer to apply angled, flat beveled transitions to sharp outer perimeters or hole openings (commonly used to remove burrs or assist fastener assembly).

<img width="857" height="737" alt="image" src="https://github.com/user-attachments/assets/7b7eb456-8a97-46e2-beea-e488263745f9" />
4. Configuring Chamfer Type, Distance, and Angle Parameters:

Select the specific sharp edges on the 3D body that require beveling.
In the Chamfer dialog box, choose the appropriate Chamfer Type matching the drawing callout—such as Equal Distance (for a standard 45-degree bevel), Two Distances, or Distance and Angle.
Enter the exact bevel width and angle values (e.g., 2 mm x 45°) into the input boxes, inspect the preview on the model, and click OK to finalize the finishing features.

Step 7: Model Verification, Inspection, and Final Saving
1. Visual Inspection and Multi-Angle Orientation Check:
Use the ViewCube located at the top-right corner of the viewport (or hold Shift + Middle Mouse Button to use the Orbit tool) to rotate and view the completed 3D solid model from all standard orthographic and isometric perspectives (Front, Top, Right, and Isometric views).
Carefully compare every geometric feature, hole alignment, extrusion depth, fillet radius, and chamfer against the reference engineering drawing to ensure complete visual accuracy.
2. Dimensional Measurement and Cross-Section Analysis:
Navigate to the Inspect dropdown menu on the top toolbar and select the Measure tool (shortcut: I) to verify critical distances, diameters, angles, and wall thicknesses directly on the 3D solid body.
Use the Section Analysis tool under the Inspect menu to slice through the 3D model along a reference plane, allowing you to inspect internal pockets, blind hole depths, and hidden geometric features.
3. Checking Physical and Mass Properties:
Right-click on the completed 3D solid under the Bodies folder in the Browser tree and select Properties (or assign a standard engineering material such as Steel or Aluminum via Modify > Physical Material) to review calculated volume, surface area, total mass, and center of mass if required for documentation.
4. Final Version Saving and File Export:
Review the Timeline at the bottom of the screen to confirm there are no yellow or red warning flags indicating unresolved sketch or feature errors.
Click the Save icon (shortcut: Ctrl + S / Cmd + S), enter a clear version description (e.g., "Final verified 3D model for Ex 1.1"), and click OK to store the completed project securely in your cloud workspace (or export it via File > Export into .STEP, .STL, or .F3D format for submission).

<img width="1912" height="956" alt="image" src="https://github.com/user-attachments/assets/6f0e74ba-bec8-4451-9249-71eb1b4a4024" />

## SKETCHS
![image](https://user-images.githubusercontent.com/113594316/198208087-87ed794e-5f1c-4583-82e0-f29699dfc305.png)

## OUTPUT
<img width="895" height="629" alt="Screenshot 2026-10-21 111511" src="https://github.com/user-attachments/assets/4ab2a7ec-ea61-498a-a0c9-cadb9d1e40df" />



<img width="491" height="435" alt="Screenshot 2026-10-19 153900" src="https://github.com/user-attachments/assets/84676271-6778-48e2-afef-67028422976a" />


## RESULT

Thus, the 3D solid parametric model of the given mechanical component was successfully designed, constructed, and verified using Autodesk Fusion 360 in strict accordance with the geometric constraints and dimensional specifications provided in the reference engineering drawing.
Through this exercise, the complete CAD modeling workflow—including workspace and unit configuration, creating fully constrained 2D base and secondary sketches, generating 3D solid features via Extrude (Join and Cut Boolean operations), applying edge-finishing operations such as Fillets and Chamfers, and performing dimensional verification using the Inspect tools—was thoroughly executed and validated without any geometric errors.

<img width="786" height="626" alt="Screenshot 2026-11-12 185222" src="https://github.com/user-attachments/assets/caa257d2-4587-452f-9750-67fde0504bd3" />


