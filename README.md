# Robotic_Acatuator
This project was motivated to provide the mobility to my robot within my limited budget. I want to 3D print it with $50 cost including the outerrunner. Hence, I came up with this design, which is able to reduce the motor speed by N:1 with an arbitrary N. 

In this design the stator (outer.stl) contains N (48 in this case) teeths. And the rotor (Top.stl) contains N+1 (49 in this case) teeths. The stator and rotor are connected through three Gears (Gear1.stl, Gear2.stl, and Gear3.stl), which are drivrn by a drive gear (CenterGear.stl). The driven gear is mounted to a outeruner. I picks a $16 KV360 outerrunner. For preventing the vibaration of Gear1, 2, and 3, two components (CenterDisk.stl and Topdisk.stl) are added to hold them into the position. 

The advantage of is design over the harmonic drive is its low cost and small size. The design works fine with relative large tolerance of making. Compared to Cycloidal drive, the actuator run with balanced force. Hence, it conducts less vibaration.  

The specific stl components uploaded here are for showing how. Those are modified to fit the tolerance and capbilitiy of low cost 3D printer.  
