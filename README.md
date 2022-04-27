# Room-Finish-Schedule-Generator-Dynamo-Script
The Dynamo script automatically adds the area, material, and orientation of room's floor, ceiling, wall to the Room Schedule through the "Room.Finish" node
![image](https://user-images.githubusercontent.com/55901325/165414270-3d389000-e3a5-4398-8ba5-2eccf0abf86d.png)

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
![image](https://user-images.githubusercontent.com/55901325/165413902-ebb0efe0-2116-4fd9-a246-210f4bd19ba5.png)
![image](https://user-images.githubusercontent.com/55901325/165414123-da2dd72f-35f3-45d0-9817-d4c5d7fc2340.png)![image](https://user-images.githubusercontent.com/55901325/165414155-40d8b4ae-5e57-45bc-af74-ec23e85ff397.png)

Step 3: Run the script
