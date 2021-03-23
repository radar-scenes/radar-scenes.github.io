---
title: "Statistics"
permalink: /dataset/statistics/
excerpt: "Give me the facts!"
last_modified_at: 2021-03-25
toc: false
header:
  overlay_filter:  rgba(10, 160, 150, 0.85)
  overlay_image: /assets/whole_scene.png
---

# The Numbers

* Four radar sensors
* One documentary camera
* &gt; 100 km driving
* &gt; 4 hours recording time 
* 158 different sequences
* &gt; 7500 unique road users
* 11 different object classes
* About 4 million annotated detections

# The Figures

Feel free to reproduce these figures right from the data set itself!

Number of detections for the five mapped classes (see [labeling](/dataset/labeling#the-5-simplified-classes)) in each scan versus radial distance.
![](../../assets/ndet_vs_range.png)


Number of detections measured by one of the sensors. Two cases are discerned: A moving ego-vehicle and a stationary ego-vehicle.
![](../../assets/ndet_movingcar.png)

Comparison of the RCS values of the classes `car` and `pedestrian` for different radial distances. The shaded areas are the standard deviation aroud the mean value (solid line).
![](../../assets/rcs_car_ped.png)
