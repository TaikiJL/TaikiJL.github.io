---
layout: post
title:  "Disastercraft Simulation XL"
subtitle: "A crowd simulation prototype"
author: "Taiki Hagiwara"
img: "dsxl.jpg"
org:  "École Supérieure de Génie Informatique"
logo: "img/logo/esgi.png"
from: 2013-12-01 00:00:00
to: 2014-06-01 00:00:00
---

This is another school project we did on Unity3D: DSXL is a crowd simulator which uses a steering behaviors approach. Users can create their own agent types composed of different behaviors, then tweak each behavior’s weight during simulation. For example, a “Zombie” agent who has the ability to transmit his type to others can chase the “Normal” agents who will try to flee from it (those two types are already implemented). Hence the name of the application (at least part of it), since we wanted to simulate crowd behaviors during a disaster or other kinds of incidents.

Other included features are:

- enabling/disabling of various types of optimizations on the fly
- creation of walls (world creation tab) and obstacles (middle click)
- display of the optimizations
- saving & loading of the user-created agent types

You can try it out [here](demos/dsxl).

[Thomas Bonin](http://tombbonin.com/) led the project by programming most of the simulator’s features. I mainly handled the UI on this project.
