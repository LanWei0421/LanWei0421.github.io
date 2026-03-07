---
title: "Qìfield: VR Tai Chi Multimodal Haptics (Click for more)"<br/><img src='/images/teaser.png'>
collection: portfolio
permalink: /portfolio/qi-field/
excerpt: "Palm-centered airflow and vibrotactile feedback modulated by EMG for embodied Tai Chi practice in XR."
---

## Overview

Qìfield is a VR Tai Chi system that externalizes subtle bodily coordination through palm-centered airflow and vibrotactile feedback modulated by forearm EMG and gesture phase.

## Demo Video

[![Watch the Qìfield demo](https://img.youtube.com/vi/tXkOp1gFsg0/hqdefault.jpg)](https://youtu.be/tXkOp1gFsg0)>

## Research Question

How can multimodal haptics help users perceive and extend internal bodily intention in Tai Chi practice?

## System Design
The system integrates:
- XR hand tracking (Quest 3)
- gesture recognition
- EMG sensing
- Unity interaction engine
- serial JSON communication
- ESP32-based actuator control

![Qìfield hardware](/images/lanwei_lbw.jpg)

![Qìfield ui](/images/tutorial_ui1.png)
## Interaction Technique

Gestures used in the system include:

- Fajin (Tui shou)
- Huajin (Yun shou)
- 
Each gesture triggers directional airflow and vibration patterns to simulate “Qi flow”.

![Qìfield flowchat](/images/flowchart.png)
<div style="display: flex; gap: 10px;">
  <img src="/images/fajin.gif" width="50%">
  <img src="/images/huajin.gif" width="50%">
</div>



## Technical Stack

Unity  
XR Hands  
C#  
ESP32 C3/S3  
EMG sensing  
Serial JSON protocol  
Airflow + vibration actuators

## Publication

Lan, W. et al.  
*Qìfield: Externalizing Qi as a Palmar Haptic Field for Volitional Extension in Tai Chi Practices.* CHI EA 2026. [Paper](/files/chiea26-517.pdf)
