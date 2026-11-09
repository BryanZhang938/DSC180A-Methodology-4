
---
layout: default
title: Methodology Assignment 4
---

# DSC 180A - Methodology Assignment 4

## About Me

**Name:** Bryan Zhang

**UCSD Email:** brzhang@ucsd.edu

**Section:** D17

**Mentor:** Tauhidur Rahman

---

## Quarter 2 Project Reflections

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic to me is the idea of adaptive control where a robot can automatically adjust itself when conditions change. For our drone project, this consists of a drone correcting itself when a drone suddenly produces less thrust and I'm interested how the drones recent movements and commands can reveal that something has change which allows the controller to compensate without being directly told which motor got degraded.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to investigate whether a learned correction that uses recent flight history can help a drone recover from partial motor degradation. Here, we could compare a classical controller, a controller with some learned residual correction, and a controller that receives recent observations and commands. 

The main question here would be whether flight history improves recovery under degradation conditions that were not encountered during training. We could vary the severity and timing of thrust loss, including sudden and gradual changes, and measure tracking error, recovery time, and failure rate.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

I would make the evaluation moreso focused on how the drone recovers itself throughout its flight since reaching the destination or returning to the correct altitude does not necessarily mean that it recovered well. I would measure this by using 3D tracking error and velocity relative to the intended trajectory, and compare controllers.

**4. What other techniques would you be interested in using in your project?**

I would be interested in using CNNs or recurrent networks into our project for processing flight history and uncertainty estimates that indicate when an adaptation is unreliable. These could help us understand both when adaptation improves control and when the available information is insufficient.
