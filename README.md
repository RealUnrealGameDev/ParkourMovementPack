# ParkourMovementPack (UE5)

This pack is an Unreal Engine 5 gameplay template built for fast, skill-based traversal centered around **momentum**.

Unreal Engine 5’s default Character Movement Component is a general-purpose locomotion system. While flexible, it introduces velocity damping, float-heavy jumps, and conservative acceleration that limit high-speed traversal design.

This template edits the player movement around a **fast paced model** inspired by Titanfall-style mobility systems.

---

## Overview

- Momentum-preserving movement model  
- Physics-aware sliding system  
- Responsive, non-floaty jump arcs  
- Wall interaction mechanics with controlled force separation  
- Optional camera and velocity feedback systems  
- Cleanly exposed variables for rapid tuning and iteration  

---

## Core Systems

### Sliding

- Physics-based, slope-reactive slide system  
- Preserves player velocity instead of dampening it  
- Naturally chains into jumps and wall actions  
- Encourages skill-based speed maintenance  

---

### Wall Jumping

- Horizontal and vertical forces calculated independently  
- Prevents infinite vertical climbing exploits  
- Maintains forward flow and readable momentum  
- Supports advanced movement routing  

---

### Jump Design

- Tuned gravity scaling for fast traversal  
- Eliminates float-heavy hang time  
- Creates sharp, readable movement arcs  
- Optimized for competitive responsiveness  

---

### Camera & Speed Feedback

- Optional velocity-based camera tilt  
- Speed-based visual feedback systems  
- Reinforces sense of motion and control  
- Maintains clarity at high traversal speeds  

---

### Customization

- All major movement variables exposed  
- Adjustable acceleration, gravity scale, slide friction, wall force values  
- Designed for rapid Blueprint or C++ iteration  
- Clean architecture for expansion  

---

## Technical Details

### Features

- Velocity-preserving character controller  
- Slope-aware physics sliding  
- Force-separated wall jump logic  
- Adjustable gravity and air control systems  
- Modular camera feedback options  

### Number of Blueprints

- Core movement Blueprint(s)  
- Optional camera feedback Blueprint  

### Number of Maps

- 1 example traversal map  

### Input

- Standard FPS-style movement bindings  
- Jump  
- Slide  
- Context-driven wall jump  

### Network Replicated

- No  
  (Designed for single-player or prototype use. Can be extended.)

### Supported Development Platforms

- Windows: Yes  
- Mac: Yes  
- Console: Configurable  
- VR: Not configured by default  

### Documentation

- Inline comments within movement systems  
- Movement tuning variables clearly labeled  

---

## Intended Use Cases

- High-mobility FPS games  
- Parkour action titles  
- Movement-focused indie games  
- Traversal-driven prototypes  
- Skill-based speedrunning experiences  

---

## What This Template Is Not

- Not a full FPS framework  
- Not a combat system  
- Not a cinematic locomotion solution  
- Not a realism-focused movement model  

This template provides a fast, controllable, momentum-driven baseline for Unreal Engine 5 projects where traversal is a primary gameplay pillar.

---

## Getting Started

1. Clone or download this repository  
2. Open the `.uproject` file in Unreal Engine 5  
3. Open the example map  
4. Adjust movement variables in player BP
5. Enjoy!
