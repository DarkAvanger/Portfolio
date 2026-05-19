---
layout: project
title: Arachnoid Robot Rig
role: Technical Artist & Feature Film Rigger
hero_image: arachnoid_hero.jpg
---

## The Challenge
For an upcoming feature film production, I was tasked with developing the rigging and proxy geometry workflow for a complex, six-legged arachnoid robot. Because the model contained heavily detailed hard-surface geometry, standard skinning resulted in severe viewport lag.

## The Python Solution
To handle the repetitive leg hierarchy, I wrote a custom Python script that automated the rig generation.

* Generated the control curves and joint chains with a single click.
* Automatically calculated and assigned bounding-box proxy meshes.
* Standardized naming conventions across the node graph.