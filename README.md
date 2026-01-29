Gesture-Controlled Voxel Architecture System

Overview:

An experimental gesture-driven 3D construction system that allows users to build, manipulate, and deconstruct voxel-based structures in real time using hand gestures. The project explores embodied human–computer interaction, spatial reasoning, and intent-based input without traditional controllers.

Built using MediaPipe Hands for gesture recognition and Three.js for real-time 3D rendering.


Core Idea:

Traditional 3D modeling tools rely on indirect inputs (mouse, keyboard, UI panels).
This system investigates whether human gestures can act as a first-class interface for spatial construction — closer to how humans think about form and structure.


Key Features:

Real-time hand tracking using MediaPipe

Gesture-to-intent mapping (build, erase, grab, rotate, reset)

Voxel-based construction with grid snapping

Sketch → commit workflow for controlled building

Physics-inspired gravity and restoration modes

Global structure manipulation (translation + rotation)

Visual feedback via HUD overlays and state indicators


Gesture Controls:

Pinch → Build voxels

Point + pinch → Erase voxels

Closed fist (hold) → Grab entire structure

Two palms (hold) → Rotate structure

Two fists (hold) → Hard reset

Thumb down (hold) → Gravity burst

Thumb up (hold) → Restore structure


Tech Stack:

JavaScript

Three.js — 3D rendering

MediaPipe Hands — hand tracking

HTML Canvas — HUD & biometric overlays

WebGL


Why This Matters:

Demonstrates intent-based interaction design

Combines computer vision with real-time graphics

Explores alternatives to GUI-heavy modeling tools


Applicable to:

Architectural prototyping

Spatial computing

XR / HCI research

Educational visualization


Status:

Actively developed / experimental.
Future extensions may include multi-layer voxel depth, persistent saves, and collaborative interaction.
