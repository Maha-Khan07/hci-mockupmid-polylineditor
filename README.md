Polyline Editor - Design Phase

Project Overview

This repository contains the design documentation and behavioral modeling for an interactive Polyline Editor. The system allows users to create, move, and delete vertices to form complex shapes using mouse and keyboard interrupts.

Challenges & Difficulties Faced:

1. Behavioral Modeling (The STN Struggle)
->Mapping Complexity: My biggest challenge was creating a functional State Transition Network (STN). I initially struggled with the "arrows"—ensuring every user action (like pressing 'b' or 'm') led to the correct system state.
->Workflow Friction: I experienced significant difficulty jumping back and forth between the Polyline Editor logic and Excalidraw. It was hard to visualize the feedback loops in real-time while trying to document them statically

2.Applying HCI Principles
->Theory vs. Practice: Even after reviewing the course chapters and midterm worksheets, I found it difficult to apply abstract rules to my specific layout.
->Learning Curve: I had a hard time grasping some of the "rules" of interaction design initially. However, by repeatedly reviewing the material and applying it to this editor, I was able to implement Fitts's Law for button sizing and Error Prevention for the 'Refresh' command.

3. Design Evolution
->Hierarchical Modes: I considered creating separate STNs for each mode (Move, Delete, Begin) to manage the complexity of the "Selection" states.
->Feedback Loop Definition: Identifying the right "Expressive Feedback" for each keypress was an iterative process that required multiple design changes to feel natural.

Key HCI Principles Used
1.Visibility of System Status: Using the top status bar to tell the user what to do next.
2.Control and Freedom: Including a confirmation alert for the 'Refresh' ('r') key to prevent accidental clearing of the canvas.
3.Direct Manipulation: Allowing the user to "drag" points in Move mode, providing a sense of physical agency.
