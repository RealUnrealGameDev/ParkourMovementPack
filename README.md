![Title Image lol](https://media.fab.com/image_previews/gallery_images/6aa27b57-94d6-4220-8765-48cb884987ea/60a7fd7e-0858-4645-8eba-90f565d9550d.jpg)
# ParkourMovementPack (UE5)

This pack is an Unreal Engine 5 gameplay template built for fast, skill-based traversal centered around **momentum**.

Unreal Engine 5’s default Character Movement Component is a general-purpose locomotion system. While flexible, it introduces velocity damping, float-heavy jumps, and conservative acceleration that limit high-speed traversal design.

This template edits the player movement around a **fast paced model** inspired by Titanfall-style mobility systems.

Available for purchase on Fab: https://fab.com/s/d93079e00dd0

---

## Overview

- Momentum-preserving movement
- Basic Sliding system  
- Responsive, non-floaty jump
- Wall Jump/Run mechanics with controlled force separation  
- Optional camera and velocity feedback  
- Cleanly exposed variables for customization

---

## Core Systems

### Sliding

- Basic Sliding system
- Preserves player velocity instead of dampening it  
- Naturally chains into jumps and wall actions
- Has checks to avoid player getting stuck

---

### Wall Jumping

- Horizontal and vertical forces calculated independently
- Similar to Titanfall but a more basic version

---

### Jump Design

- Faster Gravity while falling
- Eliminates float-heavy hang time
- Coyote Time Added
- Jump Buffer Added

---

### Camera & Speed Feedback

- Optional velocity-based camera tilt  
- Speed-based visual feedback systems  

---

### Customization

- All major movement variables customizable
- Adjustable acceleration, gravity scale, slide friction, wall force values  
- Designed for Blueprints
- Clean architecture for expansion  

---

## Technical Details

### Features

- Velocity-preserving character controller  
- Sliding  
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
