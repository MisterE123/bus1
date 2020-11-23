Bus model and texture CC0 by MisterE

included .blend file needs blender 2.8 to open

included .obj export

included .b3d and .blend (hopefully) has the following animations:

+++++++++++++++++++++++++++++
| Keyframe | Name |Desc     |
+++++++++++++++++++++++++++++
 1           rest_start       Rest- bus does nothing (can be used for standing still or moving straight forward)
 20	     rest_end

 40          door_open_start    the bus kneels and the door slides open
 70          door_open_end

 70          door_open_wait_start   the bus does nothing in the kneeling position with the door open
 80	     door_open_wait_end

 100	     door_close_start		the door closes and the bus returns from the kneeling position
 130	     door_close_end		

 140         turn_from_straight_to_left_start   the bus's wheels turn to the left and the bus leans
 145	     turn_from_straight_to_left_end

 150         turn_from_left_to_straight_start
 155         turn_from_left_to_straight_end

 160	     turn from straight to right start
 165         turn from straight to right end

 170         turn from right to straight start
 175         turn from right to straight end