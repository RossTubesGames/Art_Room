# Pirate Room – Art Fundamentals Project

## Overview

This project was created as part of the CMGT Art Fundamentals course.  
The objective was to design and build a stylized pirate-themed interior environment using Autodesk Maya and present it inside Unity (URP).

The primary focus areas of this project were:

- Clean topology
- Manual UV unwrapping
- Consistent texel density
- Organized scene structure
- Production-ready asset preparation

---

## Software Used

- **Autodesk Maya 2025** – Modeling and UV unwrapping
- - **Substamce painter 3D** – Texturing  
- **Unity (Universal Render Pipeline)** – Scene setup, materials, lighting  
- PBR texture workflow  

---

## Modeling Approach

### Clean Topology First

During development, several meshes (including the chair components) were rebuilt instead of force-fixing broken geometry.  
This decision improved:

- Mesh integrity  
- UV stability  
- Shading consistency  
- Export reliability  

Prioritizing clean geometry over quick fixes ensured the assets remained predictable and engine-ready.

---

## UV Workflow

All UVs were manually:

- Cut  
- Unfolded  
- Stacked (where applicable)  
- Oriented and aligned  
- Packed inside the 0–1 UV space  

Texel density was kept consistent across modular elements to maintain visual cohesion and prevent stretching.

---

## Production Cleanup

Before export and final submission, all assets were prepared using standard production practices:

- History deleted  
- Transforms frozen  
- Pivots centered  
- Scene hierarchy organized  

This ensures the assets are clean, lightweight, and suitable for engine integration.

---

## Unity Implementation

The environment was imported into Unity and configured using:

- Universal Render Pipeline (URP)  
- Custom materials  
- Controlled lighting setup  
- Scene composition for final renders  

The included Unity project can be opened directly using the `Assets`, `Packages`, and `ProjectSettings` folders.

---

## Included Files

- Final Maya scene (`.ma`)  
- Exported FBX file  
- Unity project files  
- Final presentation renders  
- Concept sheet  

---

## Reflection

A key takeaway from this project was understanding that rebuilding clean geometry is often faster and more professional than attempting to patch broken topology.

This workflow reinforced:

- Structured modeling practices  
- Manual UV management  
- Clean export preparation  
- Organized project presentation  
- Version control discipline using Git  

---

## Author

**Jordan Ross**  
Creative Media & Game Technologies (CMGT)
