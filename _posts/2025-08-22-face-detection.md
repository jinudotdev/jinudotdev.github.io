---
layout: post
title: "Face Detection: FaceMesh in Action"
date: 2025-08-22
---

So I got face_mesh to work, 

and i was able to clean up the code so that it's modular. 

main.py runs the program, hand_logic and face_logic are the brains behind where the virtual "dots" go
(imagine the person in front of the camera as one of those actors who have dots painted on their face for 
special effects, later to be replaced for something else, like in Avatar)
landmark_painter is the one that paints all the dots and the connecting lines together, and it works 
for both hand and face logic. 

<div style="text-align: center;">
  <img src="/assets/images/2025-08-22.png" alt="Face Track" width="400">
  <p><em>Brush Hero needs to track both the face and the hand</em></p>
</div>

