---
layout: course_page
title: Assignment 1.1 — CSG Massing Diagram (BIG-style)
published: true
---

## Assignment 1.1 — CSG Massing Diagram (BIG-style)

### Description

In this exercise, you will learn how to use basic Constructive Solid Geometry (CSG) operations and modeling transformations to generate an architectural massing. Starting from primitive shapes (cube, cylinder, sphere, etc.), you will apply a sequence of at least five distinct operations (move, scale, rotate, boolean add/subtract, etc.) to shape a building volume.

The goal is to create a clear, step-by-step diagram (in the style of BIG diagrams) where each axonometric view shows one transformation, culminating in a final building mass.

Beyond modeling, you will also learn:

- How to represent geometry in axonometric/isometric views.
- How to export 3D geometry as 2D contours for diagramming.
- How to create sections (using tools like Bisect in Blender or Section tools in Rhino).
- How to post-process diagrams (linework, color, textures) in 2D graphic software (Illustrator, Inkscape, Photoshop, GIMP).

### Visualization Strategy
Sequential axonometric diagrams

### Computational Theme
Constructive Solid Geometry (CSG), non-destructive operations

### Learning Objectives

By completing this assignment, students will:

- Understand and apply CSG principles (union, difference, intersection).
- Learn to use basic transformations (move, scale, rotate) with primitive geometry.
- Recognize the concept of manifold geometry (necessary for 3D printing & physical prototyping).
- Produce axonometric/isometric diagrams that clearly explain a design process.
- Export 3D models into 2D vector drawings (plans, sections, outlines).
- Post-process 2D graphics for architectural communication (line weights, color, hierarchy).

### Step-by-Step Requirements

1. **Start with primitives** (cube, cylinder, etc.).

2. **Apply at least five different operations**. Each should represent a clear design decision. Examples:
   - Subtract a cylinder to allow solar rays from the east.
   - Rotate or move a volume to adjust program.
   - Union additional blocks to represent extensions.
   - Scale vertically to change proportions.
   - Carve openings with boolean difference for circulation or light.

3. **Capture the sequence in axonometric/isometric views**.
   - **Axonometric**: parallel projection where axes are skewed, often with 120° between them.
   - **Isometric**: a type of axonometric where x, y, z axes are equally spaced at 120°.
   - In Rhino/Blender, you can set cameras to orthographic/isometric modes.

4. **Export contours/sections**:
   - Use "Make2D" (Rhino) or "Bisect + Export SVG" (Blender) to generate line drawings.
   - Extract one section cut through the mass to show internal organization.

5. **Post-process the final outputs**:
   - Use Illustrator, Inkscape, Photoshop, or GIMP.
   - Adjust line weights, add hatching, textures, or color coding.
   - Ensure clarity of each step (e.g., color-coded operations).

### Task
Perform at least 5 operations on primitive solids to develop a massing strategy (programmatic, environmental, structural, or functional). Show the design logic step by step in axonometric diagrams.

### Deliverables
- **3D Model File** (Blender or Rhino)
- **22"x11" Board** including:
  - **Process Diagram (BIG-style)** — axonometric sequence showing each step post-processed in 2D software explaining design decisions
  - **Final Section Drawing** — one clean section cut through the final mass post-processed in 2D software Focus on scale
  - **Final axonometric** of completed massing

### Extra Credit
3D print final massing.

### References

- **BIG** — Bjarke Ingels Group, *Yes is More* (2009) – graphic novel illustrating sequential diagramming.
- **Francis D.K. Ching**, *Architecture: Form, Space & Order* (2014) – foundations of form and axonometric drawing.
- **Robert Woodbury**, *Elements of Parametric Design* (2010) – on constructive logics in computational design.
- **Anthony di Mari**, *Operative Design: A Catalog of Spatial Verbs* – spatial operations and design strategies.
- **Anthony di Mari**, *Conditional Design:An introduction to elemental architecture* – fundamental design principles and elemental approaches.

### Suggested Tutorials

#### Blender
- Blender Boolean Modeling Basics
- Creating Axonometric Views
- Exporting SVG from Blender

#### Rhino
- CSG Operations in Rhino
- Make2D Command
- Section Tools

### Tips for Success

- **Plan your sequence**: Sketch out your 5+ operations before modeling
- **Use meaningful operations**: Each step should represent a real design decision
- **Maintain clean geometry**: Ensure boolean operations result in manifold geometry
- **Document each step**: Save your model at each transformation stage
- **Test your workflow**: Practice the export and post-processing steps early
- **Reference BIG diagrams**: Study how they use color and annotation to show process
