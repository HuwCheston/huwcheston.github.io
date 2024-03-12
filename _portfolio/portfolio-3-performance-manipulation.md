---
title: "Music Performance Manipulation Software"
excerpt: "A new software platform for introducing <b>controlled manipulations</b> into multiple <b>synchronised audio-video feeds</b> during an experiment <br><br/><img src='/images/jitter-coordination_img.png'>"
collection: portfolio
---

<img src='/images/jitter-coordination_img.png'>

[![Code](http://img.shields.io/badge/Code-available_on_GitHub-purple)](https://github.com/HuwCheston/AV-Manip)

One of the difficulties associated with studying music performances in experiments is the difficulty in ensuring **consistency and repeatablity between several performances**. In this project, we developed a software platform that allows the researcher to **manipulate audio and video feedback** given to performers in **a real time and controllable** manner during an experiment. 

The software looks similar to a **conference call** made on a telecommunication platform such as Zoom or Skype, albeit one where all the participants are **together in the same room**. Two or more musicians are seated opposite to each other, with direct visual contact between them prevented through the use of a physical barrier. Instead, they communicate through a closed-circuit audiovisual system, consisting of a **webcam, monitor, headphones, and musical instrument**, each connected to an external computer running our software. Participants in our experiments hear each other’s performance using headphones, with visual feeds from their partner’s webcam displayed on a monitor in front of them.

<img src="/images/performance-manipulation-diagram_img.png">

At any point during a performance, the researcher may use our software to **introduce a manipulation into these feeds**. Manipulations currently implemented in the software include the addition of **delay** (or latency, including latency with variable and random times), **echo**, **pitches** (e.g., artificial ‘wrong notes’), and automatic face and body **occlusion**; however, the platform is designed to be extendable and can interface with any existing audio or MIDI effect in the standard `VST` format. 

The software also provides a straightforward way to capture **synchronised audio and video feeds** (both manipulated and non-manipulated) from **multiple sources** by integrating with the open source [OpenCV (for video)](https://opencv.org/) and [REAPER (for audio)](https://www.reaper.fm/), eliminating the need to manually align audio and video post-experiment. The user can also **save and recall preset configurations** for particular experiments and conditions using a simple GUI.

<img src="/images/performance-manipulation-software_img.png">

The development of this software was supported by a *Project Incubation award* from [**Cambridge Digital Humanities**](https://www.cdh.cam.ac.uk/). You can read the [project page here](https://www.cdh.cam.ac.uk/research/projects/newmusicsoftwareplatform/).

[Read a recent paper created using the software!]({{ site.baseurl }}/publications/2024-02-16-jitter-coordination-paper/)

<img src="https://user-images.githubusercontent.com/97224401/231712093-133cafa0-dffe-4a23-945d-5249c4385bab.gif">