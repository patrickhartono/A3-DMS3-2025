## **VJ Performance Project Template (TouchDesigner)**  
**DMS3 (2025) — Assignment A3 — RMIT Vietnam**

## 🎬 **Video Demo:** [Watch on YouTube](https://youtu.be/geNuMlZYXB8)

## **Overview**

This project is a TouchDesigner template for VJ performance, developed as part of Assignment A3 for DMS3 (2025) at RMIT Vietnam.  
The project is currently a work in progress and is intended as a starting template that students can adapt and expand for live audiovisual performance.

The system focuses on real-time visuals, performance-oriented controls, and a clear signal flow from visual generation to final output.

## **Visual System Structure**

This template contains two visual sources, designed to demonstrate different approaches to visual generation in TouchDesigner.

### **Visual 1 — Image-Based Geometry**

Visual 1 is created by converting an image source (Bánh mì) into geometry.  
The image is processed and transformed into a geometric visual structure, allowing students to explore how static image content can be translated into dynamic visual forms.

### **Visual 2 — Procedural Geometry (POP-based)**

Visual 2 is generated entirely inside TouchDesigner using geometry and POP-based systems.  
This visual focuses on procedural and generative techniques without relying on external image sources.

## **UI & Performance Controls**

Each visual component (Visual 1 and Visual 2) includes a dedicated UI panel.

- All UI elements are recommended performance parameters  
- These controls are designed to be manipulated live during a VJ performance  
- Students are encouraged to customize, expand, or remap these parameters based on their own performance style  

The goal is to make the system performance-ready, not just visually functional.

## **Visual Mixing**

The two visuals are combined using a mixing system.

- In this template, mixing is demonstrated using keyboard inputs  
- Press Key 1 to trigger Visual 1  
- Press Key 2 to trigger Visual 2  

This setup is provided as a simple example and can be adapted to:
- MIDI controllers  
- OSC  
- Custom interfaces  

## **Post-Processing & Audio Input**

After mixing, the visuals pass through a post-processing (Post-FX) stage.

- Post-FX parameters are driven by audio analysis  
- Audio input is sourced from a Web Browser component  

## **Recommended Audio Source**

It is recommended to use Bandcamp as the audio source because:
- Audio can be streamed without advertisements  
- Artists can be directly supported by purchasing their work  
- Purchased audio files can be downloaded and used locally for performance  

This setup allows visuals to respond dynamically to sound while maintaining ethical support for artists.

## **Final Output & Performance Window**

After post-processing, the final visual output is sent to a Window COMP.

To perform correctly:
- Go to the Window COMP  
- Enable Open / Close  
- Select Open as Perform Window  

This ensures the visuals are displayed in a dedicated performance window, suitable for projection or live output.

## **Work in Progress**

This template is a work in progress and serves as a learning framework rather than a finished performance system.  
Students are encouraged to:
- Modify the visuals  
- Replace the audio source  
- Add new visual layers  
- Extend the UI and control logic  

[![Adobe Express - 2025-12-24 13-00-09](https://github.com/user-attachments/assets/b53eaac8-6974-40d0-a4e1-da911921e3d8)](https://github.com/user-attachments/assets/b53eaac8-6974-40d0-a4e1-da911921e3d8)
