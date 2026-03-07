---
title: "EMG-Driven Pseudo-Haptic Feedback for VR Surgical Training"
collection: portfolio
permalink: /portfolio/emg-pseudohaptics/
excerpt: "Using surface EMG to drive effort-adaptive pseudo-haptic feedback for incision training in VR.<br/><img src='/images/teaser_pesudo.png'>" 
---

## Overview

This project explores how **surface electromyography (EMG)** can be used to drive adaptive pseudo-haptic feedback in virtual reality surgical training.  
Instead of relying on grounded force-feedback devices, the system estimates muscular effort in real time and modulates multimodal cues to guide users toward an appropriate force range during incision tasks.

The work investigates whether **biosignal-driven feedback** can support force awareness and motor learning in VR-based skill training.

---

## Research Question

Can physiological signals such as EMG be used to create **effort-aware pseudo-haptic feedback** that helps users regulate force during VR surgical training without mechanical force rendering?

---

## Interaction Concept

The system treats muscular effort as an interaction signal.

When the user's muscle activation deviates from the target effort range:
- visual cues highlight the incision path
- audio feedback signals excessive or insufficient force
- vibrotactile feedback reinforces corrective actions
<div style="display: flex; gap: 10px;">
  <img src="/images/teaser-4-EmgSensor.png" width="50%">
  <img src="/images/tesaer-1-EmgCalib.png" width="50%">
</div>

This creates a **closed feedback loop between muscle effort and perceived resistance**.

---

## System Pipeline

The system integrates real-time biosignal processing and XR interaction.

---

## Interaction Flow

1. The user performs a simulated incision in VR.
2. EMG sensors measure muscle activation in the forearm.
3. The system estimates the user's effort level in real time.
4. If effort exceeds or falls below the target range, the system triggers multimodal feedback.
5. The user adjusts force accordingly, improving motor control during the task.

---

## Technical Stack

XR Platform  
Meta Quest / OpenXR environment

Software  
Unity  
C#  
Real-time signal processing pipeline

Biosensing  
Surface EMG acquisition  
Effort estimation and threshold detection

Feedback  
Visual cues  
Audio alerts  

---

## Research Contribution

This project explores a lightweight alternative to traditional haptic devices for VR training.

Key contributions include:

- EMG-driven adaptive pseudo-haptic feedback
- real-time effort estimation for interaction control
- multimodal feedback for force awareness in VR

The work demonstrates how **physiological sensing can become a core interaction modality in XR training systems**.

---

## Related Publication

Lan, W. et al.  
*Towards EMG-Driven Pseudo-Haptic Feedback for VR Surgical Training.*  
IEEE Conference on Virtual Reality and 3D User Interfaces Workshops (VRW), 2026.
