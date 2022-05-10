# Building Damage Assessment 

<img src='images/maxar.jpg'>

[Source: Maxar images](!maxar.com/open-data)


## Problem Statement
As a Data Scientist working for the United Nations, we've been tasked with creating a predictive model for assessing building damage from satellite images of natural disasters.

Assessing building damage after a disaster has struck is very important for disaster response and management in order to prevent significant losses to life as well as property. However, these natural disasters often impact large areas and access to these areas may not be possible.

`Using pre and post disaster satellite images of different buildings and locations can we predict the level of damage of a building?`

The dataset used for this project is the Xview2 challenge dataset which can be obtained from https://xview2.org/dataset. It contains pre and post disaster images of natural disasters as well as metadata which is a json file containing damage levels and coordinates of buildings. The different natural disasters present can be seen in the graph below:

<img src='images/disasters.png'>

There are two main goals for this project:
1. Detecting buildings in the images
2. Classifiying the level of damage.

The models used in the project are Res-Net and U-Net. These models are used for classification and image segmentation problems. 

<img src='images/u-net.png'>

<img src='images/resnet.jpeg'>

[Source](!https://aditi-mittal.medium.com/introduction-to-u-net-and-res-net-for-image-segmentation-9afcb432ee2f)


The images were first masked 
