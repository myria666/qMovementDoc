
# Quake Player Movement Document

This page is for a PDF document I have written that details the workings of (most of) quake's `pmove.c` file.
Included is a breakdown of the following functions:
- PM_AirMove
- PM_GroundMove
- PM_FlyMove
- PM_Friction
- PM_Accelerate
- PM_AirAccelerate
- PM_CatagorizePosition
- PM_ClipVelocity
- NudgePosition
- MovePlayer

As well, I included a bit of a ramble that briefly introduces collision algorithms such as GJK and EPA, and some other structures like BVH and BSP.
Feel free to use this paper for whatever you need, just cite/credit where applicable please. 
If you have any questions or comments, sadly I am not usually very reachable. Might be best to check u/myria666 on reddit and leave a comment under my post for this document.
