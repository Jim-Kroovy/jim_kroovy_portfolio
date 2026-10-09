---
layout: default
title: Dynamic Gun Rigging
description: A procedural Control Rig system for aiming, firing, and recoil without baked animation.
---

# Dynamic Gun Rigging

> Technical Animation • Unreal Engine • Control Rig

<div class="video-wrapper">
  <iframe
    src="https://www.youtube-nocookie.com/embed/vOFz9Wi4OtU"
    title="Dynamic Gun Rigging"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>

## Overview

I designed and built a fully procedural Control Rig system for aiming, firing, and recoil. The rig could be quickly adjusted to support a wide range of firearms and additively override the character's upper-body pose at runtime, delivering responsive weapon movement without relying on baked animation.

I authored the underlying pose-driving systems in C++ for performance and stability. Artists could capture poses directly inside the Control Rig editor and configure the system entirely within Unreal Engine, making it straightforward to support new weapons without creating or importing animation assets.

## Skills Demonstrated

- Unreal Engine Control Rig
- Procedural Weapon Animation
- Runtime Character Rigging
- Additive Animation Systems
- Reusable Rig Architecture
- C++ Animation Systems
- Artist-Facing Tools and Pipelines

## Software

- Unreal Engine
