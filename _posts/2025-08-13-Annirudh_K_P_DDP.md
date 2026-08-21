---
layout: post
title: "Quantum Magnetometry"
subtitle: Annirudh K P
cover-img: assets/img/Cover_study.jpg
thumbnail-img: ""
share-img: ""
readtime: true
tags: [DDP, Blog]
---

### Basic Information

- **Project Title / Domain**: Quantum Magnetometry
- **Name**: Annirudh K P
- **Guide**: Siddharth Tallur, Kasturi Saha
- **Project Type**: implementation-driven

### Short Description of Project

The target is a portable NV–diamond magnetometer that reports the full magnetic-field vector and corrects temperature drift in real time. For the same, the project revolves around multitude of electronic system design principles - including FPGA Design, Microwave Circuitry, RF PCB Design, Analog Front-Ends and even Optics sometimes. I focused more on the FPGA Design as well Microwave Systems Design, while developing a novel excitation and readout scheme (patent pending) to make it portable from a lab setup.

### Whom did you work with?

PG students, The prof directly

### Tools / Simulation / Software / Hardware

I worked with Vivado for FPGA Design, KiCAD for PCB Design and Python/MATLAB for control framework simulations. I also worked with Cadence Virtuouso a bit while was exploring if the solution could be made into an SoC.

### Expectations from Guide

What I really wanted was to work on something that actually mattered to the professor. Otherwise, it always felt like there was a risk that the work would be treated as just another student project and not get the attention or seriousness it needed. At the same time, I wanted a professor who would listen to my ideas properly, discuss them with me, tell me what made sense and what did not, and help me improve the way I think and express. I was not expecting every idea of mine to be accepted, but I did want someone who would engage with them instead of brushing them aside just because they sounded unfamiliar or were not something they had seen before.

These expectations came from my earlier experiences of working with different professors, and also from what I had heard from seniors. Since I had consciously chosen to convert from B.Tech to Dual Degree, I wanted to take my DDP seriously and do it with full sincerity. Because of that, the kind of guidance and working relationship I had with my professor mattered a lot to me.

### Expectations for 8th Sem & Summer

I stayed over both the summer and winter in insti for my DDP project but that was after analysing the pros-cons of getting something (patent, publication) out of this project compared to starting something new (via say an internship) in a short time frame somewhere else. But the guides are chill if you want to do some summer internship - you will have to do some work in 8th semester. Just ensure you properly inform them and then set your targets for project accordingly - they will stick to that.

### Load: 8th Sem vs 9th (Placement) Sem

I was a curious case as I did my BTP in my 7th Sem with Zele sir, SRE in my 8th Sem with Tallur sir and then followed it up with DDP in my 9th Sem with Tallur sir and Kasturi ma'am. The load was hectic across both 8th and 9th sems - but it is upto what one is willing to take. Tallur sir is flexible - if you want to take it chill then you can pick up an exploratory project with less load. But I had willingly taken up a high-stakes project - so I was kept on my toes regarding the work and results. And I loved the work as well, so it worked both ways.

### Summer on Campus

My DDP work benefitted a lot with what I did over summer. It set up the base for the work I did further and allowed me to take enough time out in my 9th sem for placement preparations.

### Is DDP Guide Same as SRE/RnD Guide?

No

### Reason for Change of Guide

When I began working with Zele sir for my BTP, the original plan was to eventually convert it into an SRE and continue as my DDP, but that did not happen. At the time, I was genuinely very interested in analog chip design, and the project he offered was also a good one. Even though I did satisfactory work, I gradually realized that I did not quite fit into that lab environment - something was off. I often felt that I was contributing at a local level without being able to fully see the bigger picture, understand the system as a whole, or take ownership of larger technical decisions. Alas, I was just another clueless undergrad among the revered people there.

So I took a chance with Tallur sir the next semester, where I started out with a very vague project statement - work with a specific FPGA Board (ZCU111). But he gave me the flexibility to explore, think independently, and make decisions on my own. Some of those decisions worked out well and some did not, but the process taught me a great deal. I realized that I thrive in an environment where I have the freedom to explore and shape the direction of the work myself, while still having the necessary resources and support behind me. Over time, that vague starting point evolved into a well-defined problem statement that I genuinely enjoyed pursuing through my DDP. Also I loved the WEL/CPS lab environment and I grew quite fond of it that you would have found me in the lab almost always.

This experience also helped me understand myself better: I am more of a systems-and-applications person and someone who enjoys connecting ideas. And I love ownership. I am not someone whose strength lies in going very deep into one narrow problem and producing a highly specialized research outcome. This kind of realization would help you as well if you get it early in your journey - as you can choose professors and projects accordingly.

### How did your SRE help with your DDP?

My SRE with Tallur sir started with a very vague problem statement. The task was basically to explore the ZCU111 RFSoC FPGA and identify possible use cases for it. So the first one or two months mostly went into reading, experimenting, and understanding how such RFSoC boards actually work, especially since there was no prior documentation available for our use. Once I got a better sense of its architecture, capabilities, and limitations, I discussed with sir a few possible directions, including RF communication and sensor readout applications that other universities were also exploring. From those discussions, we found that it could fit well with the Quantum Magnetometry project, especially for enabling vector sensor readout, and that is how the project statement gradually became more concrete around the RFSoC.

But as the project went on, I started understanding the quantum magnetometer itself much better, not just at the implementation level, but also in terms of the actual physics and system-level challenges behind it. That changed the way I looked at the work and it was no longer just an FPGA project for me. I became more interested in the full electronics and readout chain of the sensor, and I started working more broadly on things like the microwave setup, RF design aspects, readout electronics, and noise analysis. Over time, the project grew far beyond what it had originally started as. In the end, we found a much better way to make the sensor portable, improve its performance, and still get vector readout, all without needing the RFSoC at all, which was where my SRE had originally begun.

### End Deliverables

The target is a portable NV-diamond quantum magnetometer sensor that reports the full magnetic-field vector and corrects temperature drift in real time while giving state-of-the-art noise performance. This includes the control frameworks designed using FPGA, RF PCBs, and novel schemas for excitation and readout.

### Advice

Before choosing a professor or project, clearly define what you want out of your DDP. Are you just doing the DDP for the grade? Is DDP secondary to you and are you interested in something else entirely? Or is DDP important and you actually want a meaningful output from it? 

Understand that there is nothing wrong with either of the above three options you choose, it is your choice. But based on your choice, it is extremely important to choose the professor and the project accordingly. The professor's vision and your vision should match. Mismatch would lead to a lot of unnecessary chaos later.
