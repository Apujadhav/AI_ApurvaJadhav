# AI_ApurvaJadhav
# AI-Powered Knowledge Graph to Manim Animation Automation

## Overview
This project creates educational videos automatically using AI and Manim animations.  

- Students ask about a concept from a knowledge graph made from books.  
- The AI makes slides and a script explaining the concept.  
- The slides are turned into an animated video using Manim.  
- The slides and video are saved so students can view them later.  

This system can be used for topics like GIS, Space Technology, or Data Structures & Algorithms.

---

## How It Works (Pipeline Steps)
1. **Knowledge Graph** – Stores and organizes book content so concepts can be found easily.  
2. **AI Module** – Makes slides and a detailed script for the concept.  
3. **Slide & Script Formatter** – Arranges the slides and script in a clear format.  
4. **Manim Automation** – Converts slides into an animated video.  
5. **Storage** – Saves slides and videos for students to access anytime.

---

## Folder Structure
AI_ApurvaJadhav/
├── docs/
│ ├── workflow_description.md
│ └── high_level_diagram.png
├── pseudo_code/
│ └── pipeline_pseudocode.md
├── src/
│ ├── knowledge_graph/
│ ├── ai_module/
│ ├── slide_formatter/
│ └── manim_automation/
├── outputs/
│ ├── slides/
│ └── videos/
├── README.md
├── LICENSE
└── .gitignore

---

## Thought Process
- Made the system **automatic** to save time creating videos.  
- Designed in **modules**: AI, Formatter, and Manim work separately but together.  
- Considered **trade-offs**: accuracy of AI vs. time to make video.  
- Designed to be **scalable** for different subjects and topics.
