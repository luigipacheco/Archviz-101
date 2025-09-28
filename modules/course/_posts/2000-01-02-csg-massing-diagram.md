---
layout: course_page
title: Assignment 1.1 — CSG Massing Diagram (BIG-style)
published: true
---

## Assignment 1.1 — CSG Massing Diagram (BIG-style)

### Description

In this exercise, you will explore Constructive Solid Geometry (CSG) as a non-destructive modeling workflow. Using either Rhino/Grasshopper (Boolean Brep component) or Blender (Boolean Modifiers), you will begin with primitive solids (e.g., cube, cylinder, sphere) and apply at least five distinct operations—such as union, subtraction, scaling, and rotation—to create a building mass.

Your presentation must include:

- A step-by-step axonometric process diagram (in the style of BIG diagrams).
- A final hero isometric view with ambient context—people, vegetation, sky/ground—added via 2D post-processing.

### Visualization Strategy
Sequential axonometric diagrams

### Computational Theme
Constructive Solid Geometry (CSG), non-destructive operations

### Learning Objectives

By completing this assignment, you will:

- Apply Boolean operations (union, subtract, intersect) using Rhino/Grasshopper or Blender.
- Use non-destructive workflows (Blender modifiers or parametric Grasshopper components).
- Manipulate primitives with basic transformations: move, scale, rotate.
- Understand manifold geometry, critical for potential 3D printing.
- Create axonometric/isometric diagrams that communicate design logic clearly.
- Produce a final isometric presentation with entourage for polished visualization.

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

4. **Export linework**:
   - Use "Make2D" (Rhino) or "SVG export" (Blender) to generate line drawings.

5. **Post-process the final outputs**:
   - Use Illustrator, Inkscape, Photoshop, or GIMP.
   - Adjust line weights, add hatching, textures, or color coding.
   - Ensure clarity of each step (e.g., color-coded operations).
   - Add entourage (people, trees, shading, textures) for scale & ambiance.
   - Annotate diagrams with labels, hierarchy, and differing line weights or color coding to clarify each step.

### Task
Perform at least 5 operations on primitive solids to develop a massing strategy (programmatic, environmental, structural, or functional). Show the design logic step by step in axonometric diagrams.

### Deliverables
- **3D Model File** (Blender or Rhino/Grasshopper) saved using non-destructive techniques
- **22" × 11" board** including:
  - **Process Diagram**: sequential axonometric illustrations (5+ diagrams)
  - **Final Hero Isometric View**: post-processed with entourage and ambient context

### Extra Credit
A 3D print of the final massing (report manifoldness).

### References

- **BIG** — Bjarke Ingels Group, *Yes is More* (2009) – sequential massing diagrams.
- **Francis D.K. Ching**, *Architecture: Form, Space & Order* (2014) – axonometric/isometric representation.
- **Robert Woodbury**, *Elements of Parametric Design* (2010) – constructive logics.
- **Anthony di Mari & Nora Yoo**, *Operative Design: A Catalog of Spatial Verbs* (2013) – catalogue of design operations (subtract, carve, lift, rotate, etc.).

### Suggested Tutorials

#### Blender
- Blender Boolean Modifier / Bool tool
- Creating /Isometric Views
- Exporting 2D SVG  (Grease pencil or Freestyle) from Blender

#### Rhino
- CSG Operations in Rhino
- Make2D Command
- Boolean Brep Component in Grasshopper

### Tips for Success

- **Plan your sequence**: Sketch out your 5+ operations before modeling
- **Use meaningful operations**: Each step should represent a real design decision
- **Maintain clean geometry**: Ensure boolean operations result in manifold geometry
- **Document each step**: Save your model at each transformation stage
- **Test your workflow**: Practice the export and post-processing steps early
- **Reference BIG diagrams**: Study how they use color and annotation to show process
- **Focus on presentation**: The hero isometric view should showcase your final design with professional entourage
