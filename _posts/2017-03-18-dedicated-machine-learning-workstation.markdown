---
title: dedicated machine learning workstation
layout: post
---

after my old *5-node-raspy-2-distributed-computing-training cluster* 

found it's end in 2 other projects, i'm ready for a new project and repurpose my old workstation **AMD Phenom x6 1090T, SSD, Radeon HD6850**.
as a server for playing with Keras bundled with Theano & Tensorflow
as well as caffe and the usual machine-learning-supects.
My goal is to use the server as a dedicated testing environment since i run
out of my AWS-student credit and hopefully get the hackish OpenCL versions/forks of the frameworks up and running.

For the base system i choose Xubuntu since i don't need the great amazon shopping lens and it's a more less hassle free experience for a headless server.

The software configuration is pretty straight forward, i need

- dtrx
- Anaconda 3
- Keras
- TensorFlow
- scikit-learn, scikit-image
- pillow
- pandas
- OpenCV

change my ssh-server-config to public-key authentication and im ready to go.

>sidenote when you're like me and cant remember the right
>"extract formula" aka **tar** command to uncompress **tar.bz2/tgz** files,
>just use dtrx (Do The Right Extraction) *apt-get install dtrx*.

![cluster](http://zeroispri.me/assets/images/postimages/cluster.JPG)*my old cluster*
