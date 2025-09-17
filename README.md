# GPTTest-5.3
 Houdini-UE-GPT
From GPT, Houdini to Unreal: One-click AI-based Terrain Generation

This project implements an AI-assisted procedural asset pipeline that generates complete terrains and environment setups in Unreal Engine with a single operation. By combining GPT-driven natural language parameter extraction, Houdini procedural generation, and Unreal Engine integration, the system enables creators to produce rich 3D environments in minutes instead of hours.

📖 This work was developed as part of my MSc Dissertation in Computer Science (Augmented & Virtual Reality) at Trinity College Dublin.

🚀 Features

Natural Language Input → Describe your scene (e.g., “a grassy valley with pine trees and a small river”).

AI Parameter Extraction → GPT converts text into structured JSON parameters (terrain size, slope limits, vegetation density, etc.).

Procedural Generation in Houdini → Houdini Digital Assets (HDAs) generate terrains, erosion layers, vegetation scattering, and material assignments.

Automated Unreal Integration → Scenes are imported into Unreal Engine 5.3 with correct materials, instanced foliage, and collisions.

Rapid Iteration → Small edits regenerate in seconds, full terrains in 1–2 minutes (vs ~1–3 hours manually).

🛠️ Tech Stack

AI: ChatGPT-3.5 (parameter generation)

Procedural Tools: Houdini 20.5

Game Engine: Unreal Engine 5.3

Automation: Python + Unreal Blueprints + Houdini Engine API

⚙️ How It Works

Input: Enter natural language description in the Unreal Editor UI.

AI Processing: GPT extracts numeric values and outputs JSON.

Procedural Generation: Houdini HDA uses parameters to:

Initialize terrain

Apply erosion & layers (grass, soil, rock)

Scatter vegetation & rocks

Bind Unreal asset paths for auto-instancing

Integration: Python + Blueprint scripts sync assets into UE5.3.

Result: Fully playable map in minutes.

📊 Evaluation

Performance (RTX 3060 Ti, i5-12400F, 32GB RAM):

Small (150×150m): ~28s generation, 120+ FPS

Medium (400×400m): ~1 min, 50+ FPS

Large (1000×1000m): ~6 min, ~40 FPS

Productivity Gains: Reduced workflow time from hours → minutes.

User Feedback:

Beginners: Could create playable maps without learning Houdini/UE terrain tools.

Experts: Used pipeline for rapid prototyping and biome variations.

📈 Future Work

Extend support to animated assets, weather, and gameplay logic.

Add real-time editing inside Unreal without full regeneration.

Adapt pipeline for Unity, Godot, or custom engines.

Fine-tune LLM on game design datasets for more precise parameter extraction.
