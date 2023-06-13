---
layout: page
title: Mars Rover
description: End of 2nd Year Project
img: assets/img/rover.jpeg
importance: 4
category: End-of-Year Projects
---
In a team of 7 people, designed a rover with the main purpose being to navigate around an arena autonomously, avoid obstacles and send data to a database used to map the arena and keep track of obstacles. My work mainly focused on the control sub-system.

The control subsystem played a vital role in integrating all the other subsystems by utilizing a microcontroller (ESP32). My responsibilities involved establishing various connections, such as HTTP, to send obstacle and location data to the website/database, UART to receive obstacle data from the vision subsystem, SPI to obtain location data from the optical sensor... These connections were implemented using C++ (Arduino). Additionally, the microcontroller incorporated autonomous code to enable the rover to navigate independently. To accomplish this, I implemented the C* pathfinding algorithm. The full code can be found <a href="https://github.com/krishagrawal112/Autonomous-Rover">here</a> .


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/team.jpeg" title="team image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rover.jpeg" title="rover image" class="img-fluid rounded z-depth-1" %}
    </div>

</div>
<div class="caption">
    On the left, five of the team's members at the end of the project. On the right, a view of our Mars rover.
</div>