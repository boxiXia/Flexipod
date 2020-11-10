<!-- ---
title:A Legged Soft Robot Platform for Dynamic Locomotion
--- -->
![flexipod at columbia](./assets/images/flexipod_at_columbia.jpg "flexipod at columbia")	

Abstract—We present an open-source untethered quadrupedal soft robot platform for dynamic locomotion (e.g., high-speed running and backflipping). The robot is mostly soft (80 vol.%) while driven by four geared servo motors. The robot’s soft body and soft legs were 3D printed with gyroid infill using a flexible material, enabling it to conform to the environment and passively stabilize during locomotion on multi-terrain environments. In addition, we simulated the robot in a real-time soft body simulation. With tuned gaits in simulation, the real robot can locomote at a speed of 0.9 m/s (2.5 body length/second), substantially faster than most untethered legged soft robots published to date. We hope this platform, along with its verified simulator, can catalyze the development of soft robotics.


### Github
[Hardware](https://github.com/boxiXia/FlexipodHardware){:target="_blank"}
&nbsp;&nbsp;|&nbsp;&nbsp;
[Software](https://github.com/boxiXia/FlexipodFast){:target="_blank"}


### Paper video
<div>{%- include youtubePlayer.html id='3h0RwY_tpGc' -%}</div>

### Material
The flexible material used for printing the soft body and legs is a flexible TPU.Although the filament has a shore hardness of 95A, it is possible to achieve a lower hardness by varying the infill density and the flow rate (the percentage of the material extruded). 
![material](./assets/images/material_flow_infill_hardness.jpg "material")
(a) Shore hardness vs. flow rate and infill density; (b-c) 3d printed cross-section of (b) gyroid 20% infill density and 90% flow rate, and (c) with 16% infill density and 80% flow rate.

### Soft leg
![soft leg](./assets/images/leg.jpg "soft leg")
Flexipod soft leg and demonstration: (a) Soft Leg, leg coupler and bearing; (b) 3D model of the leg assembly showing its internal structure; (c) chronophotograph of the Flexipod dropped from 2.0 m.

### Simulation
<div>{%- include youtubePlayer.html id='D83X0FhM4kI' -%}</div>

### locomotion patterns
![flexipod locomotion](./assets/images/gait.jpg "flexipod locomotion")	
(a) bounding gait, (b) pace gait, (c) turning, (d) backflip

### locomotion in the wild
<div>{%- include youtubePlayer.html id='dFAsGUMLO9U' -%}</div>

### People
[Boxi Xia](https://github.com/boxiXia), [Hongbo Zhu](https://github.com/DonovanZhu), [Zhicheng Song](https://github.com/ZhichengSong6), Yibo Jiang,Jiaming Fu, [Hod Lipson](https://www.hodlipson.com/)