---
title: "RadarScenes"
layout: splash
permalink: /
header:
  overlay_filter:  rgba(10, 160, 150, 0.85)
  overlay_image: /assets/whole_scene.png
  actions:
    - label: "Download"
      url: "https://zenodo.org/record/4559821"
excerpt: "A real-world radar point cloud data set for automotive applications. Four radar sensors. Over 4 hours of driving. More than 7500 unique objects."
intro: 
  - excerpt: "The data set is licensed under [Creative Commons Attribution Non Commercial Share Alike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode). Find out more about [how to cite](/citation) the data set."
feature_row:
  - image_path: /assets/statistics.png
    alt: "statistics"
    title: "Statistics"
    excerpt: "Learn more about the data set, the number of objects within it and other useful statistics."
    url: "/statistics"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/labeling_splash.png
    alt: "labeling"
    title: "Labeling"
    excerpt: "The data set contains point-wise class labels as well as *track-ids* for the individual objects."
    url: "/labeling"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/publications_splash.jpg
    title: "Publications"
    excerpt: "There already exist a number of publications using this data set."
    url: "/publications"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

