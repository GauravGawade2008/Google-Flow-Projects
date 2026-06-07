# Retro Spacecraft Scene

## Overview

Retro Spacecraft Scene is a cinematic science-fiction video project inspired by classic 1970s–1980s space-opera films.

The project explores a frame-to-frame AI filmmaking workflow to create a consistent spacecraft flyby sequence above Earth. Rather than generating an entire video in a single prompt, the scene was constructed using sequential keyframes and AI-assisted video generation techniques.

The goal was to maintain visual consistency while creating the illusion of a continuous cinematic camera movement through space.

---

## Project Workflow

### Keyframe Generation

The project began with the generation of seven keyframes.

The first frame established the spacecraft design, environment, lighting, and overall visual style. Each subsequent frame was generated using the previous frame as a visual reference.

This approach helped maintain consistency across the sequence while gradually changing the camera position.

Camera progression:

1. Establishing Shot
2. Approach Shot
3. Close Tracking Shot
4. Side Profile Reveal
5. Hero Flyby Shot
6. Rear Three-Quarter View
7. Departure Shot

---

### Consistency Technique

Maintaining consistency is one of the biggest challenges in AI-generated visual storytelling.

To reduce visual drift, each newly generated frame referenced the previous frame:

Frame 1 → Frame 2

Frame 2 → Frame 3

Frame 3 → Frame 4

Frame 4 → Frame 5

Frame 5 → Frame 6

Frame 6 → Frame 7

This workflow helped preserve:

* Spacecraft design
* Surface details
* Lighting direction
* Color palette
* Camera continuity
* Overall cinematic style

---

## Production Pipeline

### Image Generation

All keyframes were generated using ChatGPT's image generation capabilities.

Prompts were refined between frames while preserving the same spacecraft, environment, and lighting conditions. Only the camera position and composition were adjusted to create a smooth visual progression.

### Video Generation

The generated keyframes were imported into Google Flow.

Frame-to-frame video generation was used to create motion between the images and transform the static keyframes into cinematic video clips.

### Model Used

Video generation and scene interpolation were performed using the Gemini Omni Flash model available within Google Flow.

### Final Assembly

Multiple video clips were generated and reviewed.

The final sequence was assembled by selecting and combining the most visually consistent clips to create a complete spacecraft flyby scene.

---

## Visual Style

The project was designed to emulate:

* Classic 1970s–1980s science-fiction cinema
* Practical miniature spacecraft models
* Space-opera aesthetics
* Cinematic orbital photography
* Realistic Earth orbit visuals

Key visual elements include:

* Film grain
* Anamorphic lens flare
* Detailed spacecraft hulls
* Atmospheric glow
* Dramatic sunlight
* Large-scale cinematic composition

---

## Repository Structure

```text
01-retro-spacecraft-scene
│
├── frames
├── scenes
├── prompts
├── final_video.mp4
└── README.md
```

---

## Learning Outcomes

This project provided practical experience in:

* Prompt engineering
* AI image generation
* Frame-to-frame consistency techniques
* AI-assisted filmmaking
* Cinematic scene planning
* Visual storytelling
* Video generation workflows
* Git and GitHub project management

---

## Purpose

This project serves as an experiment in combining AI image generation and AI video generation to create a longer, visually consistent cinematic sequence.

It demonstrates how iterative prompting, reference-based generation, and frame-to-frame workflows can be used to build complex scenes while maintaining creative control over the final output.
