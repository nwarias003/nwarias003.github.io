---
layout: project
type: project
image: img/weekend/mascot.png
title: "Golden Eagle VR Data Visualization Experience"
date: 2026
published: True
labels:
  - Unity
  - Blender
  - C#
  - 3D Animation
  - VR Development
  - GitHub
  - Cesium
summary: "A virtual reality data visualization project I worked on for my ICS 496 Capstone Project that brings GPS-tracked Golden Eagle flight data to life."
---

<!-- <link rel="stylesheet" href="style.css"> -->

<div style="display: flex; justify-content: center; align-items: center; height: 100%; padding: 20px;">
  <img src="https://nwarias003.github.io/img/golden/Screenshot 2026-10-28 102818.png" style="width: 400px; height: auto; box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.5); border-radius: 8px;" alt="Application Logo">
</div>

## Table of contents

- [Overview](#overview)
- [Project Goals](#project-goals)
- [Technologies Used](#technologies-used)
- [Documentation](#documentation)
- [Project Contributions](#project-contributions)
- [3D Model and Weight Painting](#3d-model-and-weight-painting)
- [Flight Animation and Animation Tree](#flight-animation-and-animation-tree)
- [Lessons Learned](#lessons-learned)
- [Project Gallery](#project-gallery)
- [Project Resources](#project-resources)


## Overview
A virtual reality (VR) experience representing the flight of migrating juvenile Golden Eagles. Using Unity and GPS tracking data collected by University of Wyoming (UWO) ecologists, we have integrated it into a VR data visualization experience for those same researchers. Bridging the gap between raw data and the real world, researchers are able to re-live and experience flying alongside the eagle, thus enabling insights not possible before with simpler data visualization techniques.

## Project Goals

- Visualize real-world Golden Eagle migration data in an immersive 3D environment.
- Represent recorded flight paths using geographic data.
- Develop a 3D Golden Eagle model capable of realistic flight animation.
- Connect the eagle's animations to its recorded flight behavior.
- Provide researchers with an alternative way to explore and understand eagle migration data.

## Technologies Used
- Unity: VR environment, animation integration and real-time visualization.
- Blender: 3D model preparation, weight painting and flight animation.
- C#: Scripting and integration within the Unity project.
- Cesium: Geographic visualization of real-world coordinates.
- GitHub: Version control and team collaboration.
- GPS Tracking Data: Recorded eagle flight data used in the visualization.


## Documentation 
Click <a href="https://drive.google.com/drive/folders/1DBwkojOSYPcGsmRUpERf2d5wzzO058-t?usp=sharing">here</a> to view the Golden Eagle documentation/milestone slideshows.

## Project Contributions

My primary contributions to the Golden Eagle VR Data Visualization Experience focused on 3D model preparation, weight painting, flight animation, and animation integration in Unity. I collaborated with my girlfriend, Ranae Hunter, on the weight painting and animation work, helping prepare the Golden Eagle model and bring its flight behaviors to life.

### 1. 3D Model Weight Painting

I worked on weight painting the Golden Eagle model in Blender to improve how its mesh deformed when controlled by the rig. This involved refining vertex weights across the beak, tongue, body, head, neck, wings, and feet.

Weight painting was an important step in preparing the model for animation, helping its body parts deform more naturally during different flight movements.

### 2. Flight Animation Development

I then worked on creating and refining the Golden Eagle's flight animations in Blender. These animations represented several flight behaviors needed for the VR experience:

- **Flapping:** Wing movements representing active flight.
- **Gliding:** A flight state with the wings extended.
- **Burst Flapping:** A sequence combining flapping and gliding.
- **Ascending and Descending:** Animations representing increases and decreases in altitude.
- **Turning:** Animation for directional changes during flight.

These animations provided the eagle with different flight behaviors that could be integrated into the larger VR experience.

### 3. Unity Model Integration

I successfully ported the updated Golden Eagle model and its animations into Unity. This involved bringing the prepared model into the project and integrating its animation assets into the existing environment.

### 4. Animation Tree and State Transitions

I configured the Unity animation tree and established transitions between the different animation states. This organized the completed animations into a system that could transition between flapping, gliding, burst flapping, altitude changes, and turning.

The animation tree helped connect the individual animations into a unified system for the eagle's flight behaviors.

### 5. Team Collaboration

I collaborated with my capstone teammates to integrate the animated eagle into the larger VR data visualization experience.


Through these contributions, I helped integrate the Golden Eagle's 3D model and flight animations into the larger VR data visualization experience.

## 3D Model and Weight Painting

A major part of my work involved preparing the Golden Eagle model for animation.

Weight painting determines how strongly individual bones influence different parts of a model's mesh. Incorrect weights can cause vertices to stretch, twist, or deform unnaturally when a model moves.

I assigned and refined vertex weights across the eagle's body and appendages to improve how the model responded to its rig during flight animations.

The process involved inspecting the mesh, painting vertex weights, testing deformations, and refining problem areas.

### Weight Painting Process

<!-- TODO: Replace this image with a Blender weight-painting screenshot. -->

<img src="https://nwarias003.github.io/img/golden/Untitledvideo-MadewithClipchamp54-ezgif.com-video-to-gif-converter.gif" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Weight 1">

<img src="https://nwarias003.github.io/img/golden/Untitledvideo-MadewithClipchamp55-ezgif.com-video-to-gif-converter.gif" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">

<img src="https://nwarias003.github.io/img/golden/Untitledvideo-MadewithClipchamp56-ezgif.com-video-to-gif-converter.gif" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">

<img src="https://nwarias003.github.io/img/golden/ezgif.com-video-to-gif-converter(3).gif" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">

*Blender weight-painting workflow for the Golden Eagle model.*

## Flight Animation and Animation Tree

After preparing the model, I worked on creating its flight animations in Blender and integrating them into Unity.

The animation set included flapping, continuous flapping, turning while flapping, gliding, and turning while gliding. These animations represented different flight behaviors that could be used within the VR experience.

In Unity, I organized the animations through an animation tree to manage transitions between flight states.

The project also used recorded flight data to help represent the eagle's movement. The animation system was part of the broader effort to connect the visual behavior of the eagle with its recorded flight.

### Flight Animation and Unity Animation Tree Showcase

<!-- TODO: Replace this image with a screenshot of the animation timeline or animation preview. -->

<img src="https://nwarias003.github.io/img/weekend/updated_home_1.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">


*Animation tree and flight animation development in Unity.*


## Lessons Learned

This project strengthened my understanding of the relationship between 3D modeling, rigging, animation, and real-time application development.

Through my work on the Golden Eagle model, I gained practical experience in:

- **Weight Painting:** Refining vertex weights to improve mesh deformation during animation.
- **3D Animation:** Creating multiple flight behaviors for a rigged character model.
- **Unity Animation Systems:** Organizing animation states and transitions within Unity.
- **3D Asset Integration:** Preparing and importing animated assets into a real-time environment.
- **Team Collaboration:** Coordinating individual contributions with the requirements of a larger capstone project.
- **Technical Problem-Solving:** Testing and refining model deformation and animation behavior throughout development.

The project also demonstrated how 3D animation can contribute to scientific visualization by making complex real-world data easier to explore through an immersive environment.

## Project Gallery:

<img src="https://nwarias003.github.io/img/golden/Screenshot 2026-10-28 082358.png" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">

<img src="https://nwarias003.github.io/img/golden/IMG_4185.jpg" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">

<img src="https://nwarias003.github.io/img/golden/IMG_0862.jpg" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">

<img src="https://nwarias003.github.io/img/golden/IMG_0861.jpg" style="width: 768px; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" alt="Landing Page Screenshot">





