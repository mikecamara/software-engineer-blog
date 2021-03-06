---
layout: blog
title: Docker
description: "🙋‍♂️ What is Docker?"
date: 2021-10-09T18:28:09.472Z
---
# What is Docker

> \[Spoiler Alert]- Long story short is Docker is a software that you download, but think of it as an empty box, or a brand-new computer, that you can use to install an operating system (OS), libraries, programs, dependencies, system variables, and then you can run the box and work directly on it, or share it with anybody, that can then run the box in any operating system that they might be using or deploy it directly on the cloud without having to install all dependencies or software again. It is almost like a virtual machine, but it's more than that.  

![doker logo with blue whale loading containers on top as if it was a big ship.](./docker_facebook_share.png "Docker logo")

I've been working as a software programmer for many years now, and until recently I didn't know about Docker, but recently we started using it in our company, and it's awesome!

A lot of people ([Wikipedia](https://en.wikipedia.org/wiki/Docker_(software))) will tell you that Docker is a software development platform or virtualization technology, container this, orchestration that, bla bla bla. \
\
The reality is that in the tech industry, the term container will surely pop up in conversations at some point.\
\
So, let's get to the bottom of it, what is Docker?\
\
Docker is a company. 

The estimated annual Revenue in 2020 was 100 million US dollars, and it has 318 employees registered on [LinkedIn](https://www.linkedin.com/company/docker/about/). 

It was founded in 2013 by [Solomon Hykes](https://twitter.com/solomonstre) and his four friends Eric Bardin, Sam Alba, Jerome Petazzoni, Julien Barbier.

![Docker founder image](./frencheweb_docker-550x311.jpeg "Docker founders image")

[Image Source](https://www.frenchweb.fr/cloud-open-source-docker-fonde-par-le-francais-solomon-hykes-leve-15-millions-de-dollars/138977)

What the company Docker invented was a product that they called Docker Engine, which is available for download on Linux, macOS and Windows. \
\
Docker Engine is also an open-source project, more precisely, an open-source containerization technology for building and containerizing your applications. It is written in the Go programming language. \
\
It consists of three essential parts, a server to run the containers, some APIs to talk to the containers and a command-line interface (CLI) client (also a Desktop version if you prefer).

Now the best part, we can use it for free. The paid options have extra features but are not essential for typical use. 

# What is Docker used for?

Every piece of software depends on some sort of infrastructure to be built, for instance, besides a computer, a programmer needs an operating system, some programming language libraries, let's say Python or React, and then you will need some libraries installed as well. 

However, you might want to have more people working on the same app, so now every developer would have to make sure that they download the same version of all the libraries that the app depends on. Or even if you want to deploy the app on the cloud, you will still need to install all the libraries and dependencies in a cloud infrastructure such as AWS or Microsoft Azure.

Docker simplifies this process by allowing developers to install all the necessary software development infrastructure inside a container that can be shared or deployed with any operating system. 

# How can I start using Docker?

It's simple, free, anyone can do it, and only takes a few minutes to get up and running with Docker. 

So, do these following steps:

* Download [Docker](https://docs.docker.com/engine/install)
* Run the app
* Follow the onboarding tutorial to create a docker file, create an image, run containers simultaneously and deploy a React app. 

Docker is an essential tool to Software Engineers and it came here to stay. It will become ubiquitous, similar to git, it is a must for all software engineers.