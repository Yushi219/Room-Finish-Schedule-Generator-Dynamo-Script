# Room-Finish-Schedule-Generator-Dynamo-Script
The Dynamo script automatically adds the area, material, and orientation of room's floor, ceiling, wall to the Room Schedule through the "Room.Finish" node

Software environment: Dynamo 2.6 (Revit 2021)

Revit Model Samples file: "Room Finish Example.rvt" is example with completely set Room Schedule.

Script Package Pre-download: Clockwork 

Revit Schedule Set: 
Step 1: Create Room Schedule in Revit

Step 2: Add "Name" to schedule fields, and create 28 new Project Parameters in "Text" type with name of 
"Floor Finish Area","Floor Finish Material",
"Ceiling Finish Area","Ceiling Finish Material",
"Wall 1 Area","Wall 1 Material","Wall 1 Orientation",
"Wall 2 Area","Wall 2 Material","Wall 2 Orientation"...
(create 8 sets of numbered wall parameters)
![image](https://user-images.githubusercontent.com/55901325/165413069-ec19eda1-b55f-4361-9da4-1e3959b2e2e5.png)
![image](https://user-images.githubusercontent.com/55901325/165413135-fe1dace9-e30e-440f-a23b-90f3a40e3682.png)

Step 3: Run the script
