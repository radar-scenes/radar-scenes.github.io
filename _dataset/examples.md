---
title: "Examples"
permalink: /dataset/examples/
excerpt: "Some RadarScenes!"
last_modified_at: 2021-03-25
toc: false
classes: wide
header:
  overlay_filter:  rgba(10, 160, 150, 0.85)
  overlay_image: /assets/whole_scene.png

gallery1:
  - url: /assets/examples/sequence_1_scene_3962.png
    image_path: /assets/examples/sequence_1_scene_3962.png
    alt: "radar point cloud"
    title: "Radar point cloud with three cars."
  - url: /assets/examples/sequence_1_scene_3962.jpg
    image_path: /assets/examples/sequence_1_scene_3962.jpg
    alt: "camera image"
    title: "Camera image of the scene."

gallery2:
  - url: /assets/examples/sequence_20_scene_2881.png
    image_path: /assets/examples/sequence_20_scene_2881.png
    alt: "radar point cloud"
    title: "Three groups of pedestrians."
  - url: /assets/examples/sequence_20_scene_2881.jpg
    image_path: /assets/examples/sequence_20_scene_2881.jpg
    alt: "camera image"
    title: "Camera image of the scene."


gallery3:
  - url: /assets/examples/sequence_77_scene_882.png
    image_path: /assets/examples/sequence_77_scene_882.png
    alt: "radar point cloud"
    title: "Approaching and receding cars."
  - url: /assets/examples/sequence_77_scene_882.jpg
    image_path: /assets/examples/sequence_77_scene_882.jpg
    alt: "camera image"
    title: "Camera image of the scene."

gallery4:
  - url: /assets/examples/city_4.png
    image_path: /assets/examples/city_4.png
    alt: "radar point cloud"
    title: "Inner city scene."
  - url: /assets/examples/city_4.jpg
    image_path: /assets/examples/city_4.jpg
    alt: "camera image"
    title: "Camera image of the scene."


gallery5:
  - url: /assets/examples/intersection.png
    image_path: /assets/examples/intersection.png
    alt: "radar point cloud"
    title: "Intersection with multiple road users."
  - url: /assets/examples/intersection.jpg
    image_path: /assets/examples/intersection.jpg
    alt: "camera image"
    title: "Camera image of the scene."

---

The following galleries contain some example scenes from the data set.


{% include gallery id="gallery5" caption="Intersection with multiple road users." layout="half" %}

{% include gallery id="gallery4" caption="Inner city scene with pedestrians, cars and a bicycle." layout="half" %}

{% include gallery id="gallery1" caption="Radar transvision effect: the vehicles in front of the ego-vehicle can be seen even though the direct line of sight is blocked." layout="half" %}

{% include gallery id="gallery2" caption="Annotation of a pedestrian group: Detections cannot be associated to individual pedestrians and hence the class label `Pedestrian Group` was chosen." layout="half" %}

{% include gallery id="gallery3" caption="T-junction with multiple cars." layout="half" %}



