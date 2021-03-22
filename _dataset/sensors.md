---
title: "Sensor Setup"
permalink: /dataset/sensors/
excerpt: "Mounting Position and Sensor Specs."
last_modified_at: 2021-03-25
toc: false
header:
  overlay_filter:  rgba(10, 160, 150, 0.85)
  overlay_image: /assets/whole_scene.png
---

The data set was recorded using four series automotive radar sensors. Addtionally, images from a documentary camera are recorded. Ego-motion information of the ego-vehicle is recorded using the car's odometry sensors as well as a DGPS system.

The two side-facing sensors are tilted 85° outwards and the other two sensors are tilted about 25° outwards:

![](../../assets/vehicle.svg)

Each sensor has a maximum range detection range of 100m and a field of view of about -60° to +60°.
The range and radial velocity resolution are given by 0.15m and 0.1km/h, respectively.
The average cycle time between two consecutive measurements is 60ms.
Just as any other radar sensor, the resolution in azimuth direction decreases with increasing azimuth angle. At the boresight direction, the resolution is about 0.5° and degrades to 2° at the outer parts of the field of view.


