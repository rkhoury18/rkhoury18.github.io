---
layout: page
title: Gymbro
description: Coursework for 3rd Year module ELEC60013 - Embedded Systems
img: assets/img/gymbro.jpg
importance: 1
category: Machine Learning/Software
---

In a team of four we successfully developed Gymbro, a workout companion device. Gymbro is designed to assist you during your exercise sessions by providing various features such as rep counting, rest time tracking, and real-time data synchronization with a dedicated web application through HTTP.

Utilizing an acceleration sensor, Gymbro accurately detects your movements, enabling precise rep counting and rest time monitoring. Whenever you achieve your target number of reps or your rest period comes to an end, Gymbro immediately alerts you through buzzing notifications, ensuring you stay on track with your workout goals. The code for the sensor was written in Python and implemented peak detection.

One of the key features of Gymbro is its seamless integration with the accompanying web application. The device wirelessly sends live data to the web app, allowing you to monitor your workout progress in real-time. As you perform exercises, Gymbro transmits the collected data, including rep counts and rest times, directly to the web app, ensuring that your workout history is continuously updated.

The web application that we coded using CSS, HTML and JavaScript, serves as a centralized hub where users can create customized workouts, save their progress, and review their comprehensive workout history. By accessing the web app, you can track your performance over time, analyze trends, and make informed decisions about your fitness journey. The live data synchronization ensures that you have access to up-to-date information, empowering you to stay motivated and focused during your workouts. The full code can be found <a href="https://github.com/rkhoury18/Gymbro">here</a>. The advertising website done for the device can be found <a href="https://pr1120.wixsite.com/gymbro-1?classId=5472a3f9-8019-4764-a3a2-2804674e716c&assignmentId=95c87d7e-e230-4e23-862b-9817d51049b5&submissionId=acb7ac6d-81e7-d5fd-2719-5137d31f400b">here</a>.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gymbro.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Image of the Homepage of our webapp.
</div>