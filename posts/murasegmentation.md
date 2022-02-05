---
title: Mura Segmentation Project
description: MyLink is an app and website that serves as a database of all charitable organizations in Lincoln, NE.
date: 2021-01-05
tags:
  - project
layout: layouts/post.njk
cover: /img/mura_example.png
---
This project is an implementation of the Unet Image Segmentation CNN for use on the Stanford Mura X-Ray Dataset. The model is trained to segment between the body and not body parts of an X-Ray image. The project uses Keras and Tensorflow for ML and uses PyQt for a training feedback GUI.

![Some training examples](/img/mura_example.png)

All the programming and data annotation for this project was done by yours truly. I worked on this project independently for Eric Psota as an undergraduate researcher at UNL. Dr. Psota provided general direction and advice on a weekly basis and also helped me on the rare occasion I was stuck or confused by Tensorflow's Documentation. We originally planned to use the segmented dataset as part of a larger project relating to Radiology. However, for reasons unrelated to this project, Dr. Psota accepted another job and left academia in January 2021. There's a good chance I'll continue the project on my own, but as of this writing I'm not sure. Either way, it was a great project and a wonderful introduction to the world of machine learning and computer vision.

[Github Link](https://github.com/lukeboi/mura-segmentation)