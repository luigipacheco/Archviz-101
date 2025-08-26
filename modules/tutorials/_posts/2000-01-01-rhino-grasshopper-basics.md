---
layout: course_page
title: Rhino & Grasshopper Basics
published: true
---

# Rhino & Grasshopper Basics

## Overview

This tutorial introduces the fundamental concepts of Rhino 3D modeling and Grasshopper visual programming. These tools are essential for computational design workflows in architecture.

## Prerequisites

- Rhino 7 installed on your system
- Grasshopper plugin enabled
- Basic understanding of 3D modeling concepts

## Getting Started with Rhino

### Interface Overview
- **Command Line**: Type commands or access tools
- **Toolbars**: Quick access to common operations
- **Viewports**: Multiple perspectives of your model
- **Properties Panel**: Object attributes and settings

### Basic Operations
1. **Creating Geometry**: Use primitives (box, sphere, cylinder)
2. **Transforming Objects**: Move, rotate, scale, copy
3. **Boolean Operations**: Union, difference, intersection
4. **Surface Operations**: Loft, sweep, revolve

## Introduction to Grasshopper

### What is Grasshopper?
Grasshopper is a visual programming interface that extends Rhino's capabilities through node-based programming. It allows you to create parametric models and automate complex operations.

### Key Concepts
- **Components**: Pre-built functions and operations
- **Parameters**: Input values and data
- **Data Trees**: Hierarchical data structures
- **Connections**: Data flow between components

### Basic Workflow
1. **Add Parameters**: Define input values
2. **Connect Components**: Build your algorithm
3. **Preview Results**: See changes in real-time
4. **Bake to Rhino**: Convert to editable geometry

## Common Components

### Input Components
- **Number Slider**: Adjustable numeric values
- **Point**: 3D coordinate locations
- **Curve**: Line, circle, or custom shape
- **Surface**: Planar or curved surfaces

### Operation Components
- **Move**: Translate geometry in 3D space
- **Rotate**: Rotate around specified axis
- **Scale**: Resize objects uniformly or non-uniformly
- **Array**: Create multiple copies in patterns

### Output Components
- **Preview**: Visualize geometry in viewport
- **Bake**: Convert to Rhino objects
- **Export**: Save data to external formats

## Practice Exercise

### Simple Parametric Tower
1. Create a base rectangle
2. Extrude to create a box
3. Use number sliders for dimensions
4. Add rotation and scaling parameters
5. Create multiple floors with arrays

## Tips & Best Practices

- **Organize your canvas**: Group related components
- **Use descriptive names**: Label important parameters
- **Test incrementally**: Build your algorithm step by step
- **Document your work**: Add notes and comments
- **Optimize performance**: Avoid unnecessary calculations

## Next Steps

- Explore advanced data tree operations
- Learn about custom Python scripting
- Practice with real architectural examples
- Join the Grasshopper community forum

## Troubleshooting

**Common Issues:**
- **Red components**: Missing or invalid inputs
- **No preview**: Check viewport settings
- **Slow performance**: Simplify complex operations
- **Crashes**: Save frequently and use stable components

**Getting Help:**
- Check component help files
- Search online documentation
- Post questions in forums
- Review example files
