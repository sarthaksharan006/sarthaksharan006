<!--
  GitHub Profile README — Sarthak Sharan
  Render preview: https://readme.so or push to github.com/sarthaksharan006/sarthaksharan006
-->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=120&section=header&text=Sarthak%20Sharan&fontColor=c9d1d9&fontSize=36&fontAlignY=65&animation=fadeIn&fontFamily=Georgia" />
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:eef2ff,100:e0e7ff&height=120&section=header&text=Sarthak%20Sharan&fontColor=1e293b&fontSize=36&fontAlignY=65&animation=fadeIn&fontFamily=Georgia" />
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:eef2ff,100:e0e7ff&height=120&section=header&text=Sarthak%20Sharan&fontColor=1e293b&fontSize=36&fontAlignY=65&animation=fadeIn&fontFamily=Georgia" width="100%" alt="header" />
</picture>

<img src="https://readme-typing-svg.demolab.com?font=Georgia&size=16&duration=4000&pause=2000&color=64748B&center=true&vCenter=true&width=600&lines=B.Tech+CSE+(Data+Science)+%C2%B7+Heritage+Institute+of+Technology;Autonomous+Systems+%C2%B7+Embedded+Sensing+%C2%B7+Computational+Modelling;Seeking+undergraduate+research+opportunities" alt="subtitle" />

<br/>

[![LinkedIn](https://img.shields.io/badge/linkedin.com%2Fin%2Fsarthaksharan-0A66C2?style=flat&logo=linkedin&logoColor=white&labelColor=0A66C2)](https://linkedin.com/in/sarthaksharan)&nbsp;
[![Email](https://img.shields.io/badge/sarthaksharan006%40gmail.com-333?style=flat&logo=gmail&logoColor=white&labelColor=444)](mailto:sarthaksharan006@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/github.com%2Fsarthaksharan006-181717?style=flat&logo=github&logoColor=white&labelColor=181717)](https://github.com/sarthaksharan006)

</div>

---

## About

My work sits at the intersection of autonomous systems, applied sensing, and computational modelling. I am interested in problems where physical reasoning and machine learning converge — in robotics, aerospace, and embedded inference. Alongside coursework, I build and test real hardware under real constraints, with a focus on understanding the gap between a model and a physical system.

I am actively looking for undergraduate research opportunities in autonomous systems, computational physics, or related areas.

---

## Research & Engineering

<details open>
<summary><b>Autonomous Quadcopter for GNSS-Denied Navigation</b> &nbsp;·&nbsp; <i>ISRO Robotics Challenge — IRoC-U 2026, Semi-finals</i></summary>
<br/>

Developing an autonomous quadcopter capable of completing full mission cycles — search, object detection, return, precision docking, and redeployment — without GPS. The architecture separates flight control (PX4 on STM32H7) from high-level autonomy (ROS2 on Raspberry Pi 5) to isolate faults and simplify testing. Localisation relies on visual-inertial odometry, LiDAR, optical flow, and ArUco marker-assisted docking. An edge ML module (13 TOPS class) for secondary detection validation is in development alongside the deterministic autonomy stack.

`ROS2` `PX4` `SLAM` `VIO` `LiDAR` `TensorFlow Lite` `Raspberry Pi 5` `STM32H7`

</details>

---

<details open>
<summary><b>Non-Invasive Blood Biomarker Scanner</b> &nbsp;·&nbsp; <i>1st Place — Ideapolis 2026 · Hacktonix 2026</i></summary>
<br/>

Designed and prototyped a portable multi-spectral sensing system (visible + NIR) for non-invasive blood biomarker estimation. The pipeline covers sensing, signal preprocessing, on-device inference (TensorFlow Lite on ESP32-S3), and cloud-linked monitoring. Current work focuses on expanding paired training data and improving model calibration across real-world variability.

`ESP32-S3` `NIR Spectroscopy` `TensorFlow Lite` `Edge Inference` `Signal Processing`

</details>

---

<details open>
<summary><b>Aircraft Conceptual Design Tool</b></summary>
<br/>

A Python-based fixed-wing conceptual design tool using classical aerodynamic and stability models. Drag is computed from component-level contributors — skin friction, wetted area, interference effects — rather than coarse aggregate assumptions. Implements iterative numerical solving for cruise estimation with Reynolds and Mach-aware corrections; outputs include stall speed, L/D ratio, and thrust requirements.

[`→ aero-solver`](https://github.com/sarthaksharan006/aero-solver) &nbsp;&nbsp; `Python` `Classical Aerodynamics` `Numerical Methods`

</details>

---

<details>
<summary><b>Water Rocket: Design, Testing, and Flight Optimisation</b> &nbsp;·&nbsp; <i>1st Place (×2) — NSSC 2025, IIT Kharagpur</i></summary>
<br/>

Designed, built, and flight-tested a 2.25 L single-stage water rocket. Closed-form modelling is impractical given two-phase flow and transient compressible gas expansion, so the approach was empirical: systematic variation of pressure, launch angle, nozzle geometry, and fin configuration. Achieved approximately 160 m range at 75 PSI with controlled roll and minimal lateral drift. First place in both maximum-distance and precision-targeting categories.

</details>

---

<details>
<summary><b>BIS Recommendation Engine (RAG + FAISS)</b></summary>
<br/>

Retrieval-based recommendation and chatbot system for MSEs, built with Python, FAISS, and sentence-transformers against a locally hosted LLM. Designed a document chunking and embedding pipeline with vector search for context retrieval.

`Python` `FAISS` `sentence-transformers` `RAG`

</details>

---

<details>
<summary><b>Refractor Telescope & Custom Alt-Az Mount</b></summary>
<br/>

Built a functional 50 mm aperture, 700 mm focal length refractor telescope with a fully parametric, 3D-printed Alt-Az mounting system. Designed in Fusion 360, manually collimated, and used for lunar and planetary observation — including visible crater detail, Jupiter's cloud bands, and Saturn's rings.

`Fusion 360` `Parametric CAD` `FDM 3D Printing` `Optical Alignment`

</details>

---

## Recognition

| Event | Result | Year |
|---|---|---|
| ISRO Robotics Challenge — URSCi (IRoC-U) | Semi-finals qualifier | 2026 |
| Ideapolis Ideathon — ACM HITK Student Chapter | 1st place | 2026 |
| Hacktonix — Future Institute of Engineering & Management | 1st place | 2026 |
| SRIJAN — Jadavpur University (IoT BidWars) | 1st place | 2026 |
| Dakshh Techfest — Heritage Institute of Technology | 1st (×2), 2nd | 2026 |
| National Students' Space Challenge — IIT Kharagpur | 1st place (×2) | 2025 |

---

## Technical Skills

| Domain | Tools & Methods |
|---|---|
| Embedded & autonomous systems | ESP32, ROS2, PX4, SLAM, sensor fusion, VIO, edge inference |
| Mechanical design & fabrication | Autodesk Fusion 360, parametric CAD, FDM printing, DFM |
| Computational modelling | Aerodynamics, flight mechanics, numerical methods, Python |
| Machine learning | Applied computer vision, RAG, TensorFlow Lite, edge deployment |
| Tools | LaTeX, Stellarium, Siril, DeepSkyStacker, MySQL |

---

## Education

**Heritage Institute of Technology, Kolkata** — B.Tech, CSE (Data Science), 2025–2029 · CGPA 8.43  
**Jyotirmoy Public School** — Higher Secondary (CBSE), PCM + CS · Class highest in CS (Gr. 11) & Hindi (Gr. 11–12)  
**Welkin National School** — ICSE Grade 10 · 96%

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=80&section=footer&animation=fadeIn" />
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:e0e7ff,100:eef2ff&height=80&section=footer&animation=fadeIn" />
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:e0e7ff,100:eef2ff&height=80&section=footer&animation=fadeIn" width="100%" alt="footer" />
</picture>

<sub>Kolkata, India · open to research collaboration · <a href="mailto:sarthaksharan006@gmail.com">sarthaksharan006@gmail.com</a></sub>

</div>
