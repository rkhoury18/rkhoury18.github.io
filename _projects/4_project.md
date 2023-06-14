---
layout: page
title: Artificial Neural Networks
description: Coursework for 3rd Year module COMP70050 - Introduction to Machine Learning
img: assets/img/ML.jpg
importance: 3
category: Machine Learning/Software
---

In a team of 3, we created a neural network in Python to predict the price of houses in California using metrics that were included in the1990 census. The model is a multi layer neural network containing one input layer, one hidden layer and an output layer. The layers are all linear, with ReLu used for the activation functions. Pytorch and Sklearn libraries were used to implement different functions and methods such as scaling/normalisation, forwarding and step optimisation


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ML.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Graph depicting the RMSE by epoch, demonstrates the implementation of early stopping, which helps prevent overfitting.
</div>