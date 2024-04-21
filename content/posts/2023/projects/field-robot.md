---
title: "Field Robot"
date: 2023-10-15
author: "Simon Sure"
draft: false
---

With a team of varying size (2 to 5), we have worked on the Field Robot Development Project. I've been part of the project from 2019 to 2023.

The goal was to build a small, mobile agricultural robot for row crops such as corn. The robot ought to be fully autonomous (meaning no GPS, no cellular or other connectivity etc.). Our robot drive system based on a recycled hoverboard, whose motors we reused. For the majority of the time we also worked on creating a two-weheled self-balancing system for increased mobility and flexibility.  The 'brain' of the robot fully relied on cameras. We trained a custom convolutional neural net to detect drivable areas and used reverse image-projection to get a 3D map of the drivable environment. This custom software was implemented in ROS2. We could then use the ROS2 framework to enable odometry, mapping, navigation, and more.

The idea for the projet came from the Field Robot Compeition. I was also awarded 5th place in the national German Youth Reearch Compeition (Jugend forscht) as well as the Konrad-Zuse Youth Award for Computer Science from the Eduard-Rhein Foundation.

A collection of code of various parts of the project [can be found on GitHub](https://github.com/orgs/fieldrobot/repositories).