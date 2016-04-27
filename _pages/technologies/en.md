---
layout: single-column-cover
lang: en
permalink: /en/technologies/
role: technologies
title: Technologies
description: ""
cover_image: "/assets/img/covers/poppy_humanoid_ergo_playground.jpg"
cover_title: "Open source technologies for building amazing robots"
published: true
in_nav: true
---

The Poppy platform develops open-source tools for rapid prototyping and flexible experimentation of robotic creatures. It addresses mechanics, electronics, and software.

It targets the needs of a multidisciplinary community where researchers, teachers, artists, and robotic enthusiasts can share their work and ideas.
Poppy tools are designed to be modular, easy to use, and easy to integrate – providing a set of building blocks that can be easily assembled and reconfigured.

## Robots

<div class="row columns" data-equalizer data-equalize-on="large">

  <div class="large-4 columns creature" data-equalizer-watch>
    <a href="#" >
      <figure>
        <img width="188" height="188" src="{{ site.baseurl }}/assets/img/creatures/small/humanoid.jpg" data-interchange="[{{ site.baseurl }}/assets/img/creatures/large/humanoid.jpg, retina]" alt="A sitting Poppy Humanoid robot">
      </figure>
      <h3>Poppy Humanoid</h3>
      </a>
      <p>
        Poppy Humanoid is our leading creature. It is aesthetic, modular,
        and parametric. From a single arm to the complete humanoid, this
        platform is actively used in labs, engineering schools, FabLabs, and
        artistic projects.
      </p>
  </div>


  <div class="large-4 columns creature" data-equalizer-watch>
    <a href="#" >
      <figure>
        <img width="188" height="188" src="{{ site.baseurl }}/assets/img/creatures/small/torso.jpg" data-interchange="[{{ site.baseurl }}/assets/img/creatures/large/torso.jpg, retina]" alt="Facing Poppy Torso">
      </figure>
      <h3>Poppy Torso</h3>
    </a>
      <p>
        Poppy Torso is an humanoid robot torso meant to be used in contexts
        such as education, FabLabs or research projects.
      </p>
  </div>

  <div class="large-4 columns creature" data-equalizer-watch>
    <a href="#">
      <figure>
        <img width="188" height="188" src="{{ site.baseurl }}/assets/img/creatures/small/ergo.jpg" data-interchange="[{{ site.baseurl }}/assets/img/creatures/large/ergo.jpg, retina]" alt="Ergo close-up">
      </figure>
      <h3>Poppy Ergo Jr</h3>
      </a>
      <p>
        Poppy Ergo Jr was first developed for an exhibition mixing art and
        science. With only 6 motors it is the perfect project to start.
      </p>
  </div>

</div>

## Modular technologies

## Hardware overview

Our major challenge is to make the robotic hardware cheap and modular so anyone can change the morphology of his/her robot to be adapted for the experience targeted.

Of course, all this work is open source and distributed under Creative Commons BY-SA licenses.

### 3D Printed body

We use 3D printing to design Poppy creatures – it is a reproducible and cheap production technique that allows anyone to produce locally its own and customized parts. In addition, it removes usual manufacturing constraints from classical production techniques.

### Modular actuation

Poppy creatures are based on modular smart-actuators called Robotis Dynamixel. They embed in a small form factor several features such as high-level control and a communication bus. They are commonly used in robotics and are available with multiple actuation power. Yet the project is open to new contribution for robot actuation.

### Arduino electronics

We develop custom electronic board optimized for robotics needs. We want  you to be able to add motors and sensors where you want. As a first step, we developed an Arduino compatible board; it features plenty of I/O and benefits from the Arduino community, but also includes new features, such as a USB HUB and the elements needed to control Dynamixel servos.

## Software overview

The software developed in the Poppy project target to offer easy-to-use, cross-platform and modular tools so anyone can easily program and use both real and simulated robots.

The software is open source and distributed under GPLv3 licenses.

### Pypot library

A python library to control Poppy creatures:

* Low-level access to motors and sensors (meant to be easily extendable to new types of devices).

* Creation of complex behaviors by combination of independent primitives.

### Robot simulator

Poppy creatures are being integrated in the v-rep simulator with a transparent switch from simulated to physical robots through pypot.

### Creature specific repositories

Each creature has a specific software repository with basic configuration files and high-level behaviors.

### Web control interface

A web control interface to remotely launch behaviours on Poppy creatures without needing to install anything on your computer.