# IK_2PoleVectors
Creates a 2 Pole Vector IK system for a double articulated limb, usually for creatures (Back Limb).
Select joints from bottom to top of the limb (4 joints, from end of limb without hands all the way to shoulder)
Creates necessary IK systems, constraints, controls and attributes in for Shoulder Sytem Ratio and Knee Bend Ratio.
Ends up with "foot_Ctrl_Old" (important in use with the SDK_FootRig Script and LinkIK_1PoleVector Script) 
If SDK_FootRig was used, then use LinkIK_1PoleVector next to tie the FootSystem and IK together.
(Wouldn't it be nice for it to all be one button? But that way it works with the IK_1PoleVectorscript without so much brain energy.)
