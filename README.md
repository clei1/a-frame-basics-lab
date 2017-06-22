# AFrame Basics Lab

![Aframe Basics](https://s3.amazonaws.com/upperline/curriculum-assets/aframe/aframe-basic.jpg)

Welcome to the world of virtual reality on the web (also known as WebVR)! This is a cutting edge field where many of the tools you work with are still being beta tested and are under development! Virtual reality is one of the fastest growing tech fields and is poised to completely change the way that we interact with computers.

AFrame is a Javascript library that allows you to write basic HTML-like tags that get rendered in a virtual reality environment. With a few basic lines of code you can have  VR world build that can be experience on your computer, Google Cardboard, Samsung Gear VR, and Oculus Rift.

The best place to get started, and the spot you should always come back to is the [A-Frame Documentation Page](https://aframe.io/docs/0.5.0/introduction/). For an interactive slide tutorial, check out [A-Frame School](https://aframe.io/aframe-school/#/). We've also put together some [basic introduction videos here](https://www.youtube.com/watch?v=DDePTwGOWKY&list=PLetu2kRAyoeBhF9gBlUkUpjwO3mBVlTO1)!

In this lab, you'll be using the most basic building blocks to create a scene in a-frame. We've set up some boilerplate code in index.html for you to start with (by forking and cloning this repo), or you can create your own html page and link to the A-Frame library in a `<script>` tag in the head - your choice.

The goal of this lab is for you to get comfortable and start exploring A-Frame. It's up to you to decide how to use it - Have fun!

## Your Goals

### Easy

+ Add the following primitives to your scene `<a-box>`,`<a-cone>`, `<a-sphere>`, `<a-cylinder>`,`<a-plane>`. Make sure they are spaced out and of different sizes

+ Add a sky and a floor to the scene.

+ Use the asset library to import images and apply them as textures on your shapes. (eg, make the floor textured with soil)

+ Add an image texture to the sky with a [360 degree image](https://www.flickr.com/groups/equirectangular/).

### Medium

+ Change the type and angle of the lighting.

+ Update the placement of your camera.

+ Add in basic animation for your shapes (movement, changing colors, changing sizes).

+ Add in basic text

### Harder

+ Animate your light source so that shadows change as the scene moves on.

+ Add in a cursor - when you click on an object, have it animate.

+ Add in gravity using the [a-frame-physics-system](https://github.com/donmccurdy/aframe-physics-system)


+ Add in and use `.obj` files (pre-made 3D objects).

+ Create a photo gallery. When you click on an image, have it expand.
