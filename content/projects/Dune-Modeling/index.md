---
title: "Discrete Modeling of Dune-Obstacle Interactions and Dynamics" 
date: 2023-02-12
tags: ["Discrete Dynamics","Modeling"]
author: ["Horacio Moreno Montanes", "Jess Yang", "ZhengXu Tang"]
description: "In this project, we expand upon a discrete desert dune field model by Bishop et. al (2002) and incorporate dune-obstacle interactions." 
summary: "In this project, we expand upon a discrete desert dune field model by Bishop et. al (2002) and incorporate dune-obstacle interactions."
cover:
    image: "originaldune.png"
    alt: "Dune Field"
    relative: false

---

---

##### Download:

- [Paper](Dune_Modeling.pdf)

---

##### About:

This was a midterm project for the Introduction to Mathematical Modeling course (MATH 462) at the University of Michigan. 

---

##### Figure 7: Dune-obstacle interaction 

 $t=25$                     |                $t=50$            
:-------------------------:|:-------------------------------:
![](3Dmesh-before.png)    |   ![](3Dmesh-during.png)   


 $t=90$                     |                $t=125$            
:-------------------------:|:-------------------------------:
![](3Dmesh-after.png)    |   ![](3Dmesh-afterafter.png)        

---

##### Animations

<figure style="width: 100%; max-width: 100%; margin: 0 auto;">
  <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" controls>
      <source src="DuneDifferentHeights.mp4" type="video/mp4">
    </video>
  </div>
  <figcaption>Behavior of discrete desert dune field model by Bishop et. al (2002) for different initial amounts of sand $H_0$.</figcaption>
</figure>

<figure style="width: 100%; max-width: 100%; margin: 0 auto;">
  <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" controls>
      <source src="DuneObstacleHeatmap.mp4" type="video/mp4">
    </video>
  </div>
  <figcaption>Top view of interaction of dunes and rectangular obstacles of height $h_{obs}$.</figcaption>
</figure>
