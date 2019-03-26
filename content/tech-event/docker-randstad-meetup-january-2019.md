---
title: "Docker Randstad Meetup : Serverless platforms"
date: 2019-01-25
tags:
    - tech-events
    - meetup
---

In preparation for the [Serverlesdays Amsterdam] (https://serverlessdays.nl) conference, I've organized a [Docker meetup](https://www.meetup.com/Docker-Randstad/) around Functions as a Service (#FaaS) build on top of containers. How are they build, why and what can you do with them. We managed to get some core people from 2 projects/communities that build open-source serverless platforms: [fnproject] (https://fnproject.io) and [OpenFaas] (https://openfaas.com). We were hosted by Oracle Netherlands in their Utrecht HQ and I was glad to see a lot of first timers at the meetup.

![fnproject](http://jgovernor-media.redmonk.com/jgovernor/files/2017/10/fn-logo.png)

First talk was from [David Delabassee] (https://twitter.com/delabassee) who introduced the concept of function as a service and presented the architecture of fnproject. [Fnproject] (https://fnproject.io) was open sourced by Oracle and powers the soon to be released Oracle Cloud funtions. It's written in golang and runs on top of [Kubernetes] (https://kubernetes.io) which is also the only dependency. The focus is on simplicity (think DIY serverless). The demo was based on Java apps and David showed how to improve cold starts and reduce Docker image size. Slides are [here](https://www.slideshare.net/delabassee/randstad-docker-meetup-serverless)

![OpenFaaS](https://pbs.twimg.com/media/DFrkF4NXoAAJwN2.jpg)
The second talk was about [OpenFaaS](https://openfaas.com) and was done by one of the core contributors, [Edward Wilde] (https://twitter.com/ewilde) Platform architect @ Form3 . OpenFaaS is a real community driven project that is particulary connected to the Docker ecosystem (was started by [Alex Ellis](https://twitter.com/alexellisuk), a Docker captain) . While it was initially designed to run on top of [Docker Swarm] (https://docs.docker.com/engine/swarm), OpenFaas supports now also Kubernetes. Ed went trught the installation process of OpenFaaS and showcases in his demo how to use and integrate the platform with rxisting pieces of infrastructure. His slides are [here] (https://www.slideshare.net/edwardwilde/docker-and-serverless-randstad-jan-2019-openfaas-serverless-when-functions-and-gitops-collide)

