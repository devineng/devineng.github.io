---
layout: project
type: project
image: images/interfacePed_square.jpg
title: Nimitz Corridor V2X System
permalink: 
# projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2021-08-16
labels:
  - C#
  - GitHub
  - SourceTree
summary: Information exchanges between vehicles to effectively balance traffic demand distribution among traffic networks and facilitate flow progression.
---

<img class="ui image" src="../images/interfaceCar.jpg">

Traffic congestion on Nimitz Hwy and Ala Moana Blvd during traffic hours results in drivers sitting in their cars longer than they want to. The Nimitz Corridor V2X System will help prevent car, pedestrian, and cyclist collisions, speed guidance for optimum fuel efficiency based on the status of signals and car density at intersections ahead of the vehicle, and a real-time map reflecting signal status and the positions of all participating vehicles. Each participant will have a supported phone, app, and on board unit (OBU) device. This project is led by Dr. Guohui Zhang.

There are two major components to this project, the OBU client and OBU Server. The OBU client is the internal name for a process that runs in background and uses the services of the Signal Status (SS) server to constantly get up to date signal status information, and used to update the UHV2X map. OBU clients also constantly report vehicle position information to the SS server. The SS server runs on a Windows 10 server, physically located in the UH test lab, and directly connected to the NC high speed wired network.  The SS server maintains a database representing the current state of the NC, including the status of signals at all intersections and the location and movement of participating vehicles and non-participating V2X vehicles within it.

Currently, I am working on the development of the OBU Client, which is what drivers would see. There are numerous features to this. The following are features I have helped create.

OBU Client
- Stoplight visual to display the current signal status of the upcoming intersection
- Progress bar showing percentage and color indication (red, yellow, green) for fuel efficiency
- Vehicle interface shows the host vehicle and nearby remote vehicles, pedestrians, and crosswalks. The lane markers move based on the host vehicle's speed to give the illusion of movement

OBU Server
- Lane arrows for each intersection phase that change colors based on the real-time signal status at 34 intersections in GMAPS API

My current task now is to create a time space diagram (TSD). A TSD is a graph that illustrates the relationship between the location of a vehicle(s) in traffic and time as the vehicles move along the road. It shows upcoming signals and their durations for a number of intersections and the trajectory of a vehicle along the intersections. The information displayed on a TSD can also indicate how well intersections are synchronized with each other and the speeds to drive at to pass through the most number of intersections without stopping.

<img class="ui massive image" src="https://th.bing.com/th/id/R.3a2a0d5d9729ff043a34b4b60aac1d0b?rik=PhFE3w7%2bdYA69Q&riu=http%3a%2f%2fwww.clipartbest.com%2fcliparts%2fLcK%2f7dj%2fLcK7djB7i.png&ehk=aT3sHYTXr7HENoh5tXQ1iyRNVChN0%2b6OWFgVAB0toMU%3d&risl=&pid=ImgRaw&r=0">

Team: Dr. Guohui Zhang, Robert Lemon, Igor Lashkov, Hanyi Yang, Yiwei Wang
