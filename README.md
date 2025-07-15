# exowomb
Artificial womb simulation UI for fetal development in space microgravity — built with Python, Plotly Dash, and scientific visualization tools.
# 🌌 ExoWomb
<br>
**ExoWomb** is a space-compatible artificial womb simulation dashboard — built using **Python**, **Plotly Dash**, and scientific visualization tools.  
It is designed to explore **fetal development in microgravity**, with real-time UI controls and potential deformity correction via pressure simulation.
<br>
---
<br>
## 🌱 Origin of the Idea
<br>
While watching a Discovery Science program on **NASA + SpaceX's Dragon capsule**, I had a strange but powerful thought:  
> "What if humans gave birth in space?"  
Would the baby develop normal physiology in zero gravity?  
Would the absence of corrective pressure inside the womb lead to structural deformities?
<br>
This idea led to **ExoWomb** — a simulator for fetal growth in space-like conditions, allowing parameter control and real-time data visualization.
<br>
---
<br>
## 🧠 What This Project Does
<br>
- 🧪 Simulates fetal development under microgravity conditions  
- ⚙️ Provides control sliders for external pressure, fluid dynamics, and nutrient levels  
- 📈 Visualizes parameters like heart rate, bone growth, fluid pressure using **matplotlib**  
- 🧬 Conceptual model for **space medicine**, **astrobiology**, and **medical UI design**  
- ☁️ To be hosted via **Google Cloud ($300 free credits)**
<br>
---
<br>
## 🎯 Project Goals
<br>
- Build a **Plotly Dash** based interactive UI
- Model an artificial womb with user-controlled fetal environment
- Integrate visualization and logic modules using **Python** and **BioPython**
- Create a responsive, clean, Figma-inspired dashboard
- Open-source the project for beginner-friendly contributions
- Submit this idea as part of **Google Summer of Code 2025** under relevant open science orgs
<br>
---
<br>
## 📐 UI Preview
<br>
> *(Coming soon — Figma mockup + hosted link)*  
> `https://exowomb.uc.r.appspot.com` (Google Cloud demo URL)
<br>
---
<br>
## 🧪 Tech Stack
<br>
| Layer       | Tools |
<br>
|-------------|-------|
<br>
| Frontend    | Plotly Dash |
<br>
| Backend     | Python (Flask, BioPython) |
<br>
| Visuals     | Matplotlib, Seaborn |
<br>
| Hosting     | Google Cloud Run / App Engine |
<br>
| UI Design   | Figma |
<br>
| Repo        | GitHub (MIT License) |
<br>
---
<br>
## 📁 Folder Structure
<br>
📁 exowomb/
├── 📁 dash_ui/               ← Main Plotly Dash UI
│   └── app.py
├── 📁 simulation_modules/    ← Logic for fetal growth, gravity effects
│   ├── fluid_dynamics.py
│   └── fetal_growth_model.py
├── 📁 assets/                ← Static files (images, CSS)
│   └── styles.css
├── 📄 requirements.txt       ← Python libraries
├── 📄 README.md              ← Full project overview
└── 📄 LICENSE (MIT)
