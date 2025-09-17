# 🌍 AI-Assisted Terrain Generation  

An end-to-end pipeline for **one-click terrain generation** using **GPT, Houdini, and Unreal Engine**.  
Users can describe environments in natural language, and the system automatically creates fully playable terrains with erosion, material layers, and scattered vegetation.  

---

## 🎮 Overview  

**AI-Assisted Terrain Generation** is a procedural content pipeline that connects **natural language input** with **game-ready environments**.  

- **GPT** interprets user descriptions into structured parameters  
- **Houdini** generates terrains, erosion layers, and vegetation scattering  
- **Unreal Engine 5.3** imports the results automatically, producing a ready-to-play scene in minutes  

> “From a single sentence to a complete world — one click transforms your ideas into interactive 3D landscapes.”  

## 📺 Demo Videos  

- ▶️ [Final Terrain Showcase](https://youtu.be/HMsPl0aJFrs) 
- ▶️ [How to Use the Pipeline](https://youtu.be/dxFyJdg12x4) 

---

## 🧩 Core Features  

- **Natural Language to Parameters**  
  - Enter a plain description (*“grassy valley with a river and pine forest”*) → structured JSON parameters  

- **Procedural Generation in Houdini**  
  - Terrain heightfield with erosion simulation  
  - Automatic material layering (grass, soil, rock)  
  - Vegetation and rock scattering with randomized transforms  

- **Seamless Unreal Integration**  
  - Landscape layers imported and auto-bound  
  - Instanced foliage & props placed correctly  
  - Fully playable maps in **seconds to minutes**  

- **Performance Gains**  
  - Small terrain: ~30s  
  - Large terrain (1km × 1km): ~6 min (vs ~3h manually)  


## ⌨️ Usage  

1. Open Unreal Engine and launch the **Editor Utility Widget**  
2. Enter a natural language description of the scene  
3. GPT generates structured parameters (JSON)  
4. Houdini creates terrain and scattering automatically  
5. Assets are imported back into Unreal → **ready to play**  


## 🛠️ Tech Stack  

- **ChatGPT-3.5** → Natural language to procedural parameters  
- **Houdini 20.5** → Procedural asset generation  
- **Unreal Engine 5.3** → Real-time environment visualization  
- **Python & Blueprints** → Data transfer + automation  


## 🚀 Future Work  

- Add support for animated assets, weather, and gameplay logic  
- Enable real-time parameter editing inside Unreal  
- Extend pipeline to Unity, Godot, and other engines  

---

## 👤 Author  

**Yuning Sun**  
🎓 MSc Computer Science (AR/VR), Trinity College Dublin  
🌐 Graphics Engineer / Technical Artist  
📩 [https://www.linkedin.com/in/yuning-sun-830636327/]  
