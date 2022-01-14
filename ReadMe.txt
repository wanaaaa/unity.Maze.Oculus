-> Development Process
First, the ProGrid window was activated to show the grid. Then I set up the environment such as floor and wall. Then the props(desk, chair, flower base, tree) were placed. All the environments and  props came from SNAPS Prototype Pack. The layer of wal is XR ray interaction. Unless, a user can go through the wall to other place by teleporting. 
The key was made from Probuilder. The key was extended from dounut shape. The key has righdbody and Collider. It has XR Grab interactable to be grabbed. The door in hallway has empty box which has collider as a trigger. When the key is in the box, the door open.
The empty object was created for XR rig which has Camera Offset. We can teleport and do interaction with the XR rig which is room scale. The left and right hand control were in the Camera Offset. A cube was attached to each hand controller as a start point. The both hand controller has XR controller. The left hand controller has Line Renderer for indicating teleportation place. 
The WinZone has created in empty object to show “win message”. The user entered the trigger zone and message appears.

-> Assets used in this App
- Snaps Protopyings
- Probuilder
- TestMesh Pro
- Progrid
