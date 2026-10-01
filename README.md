<h1 align="center">Hi, I'm Ioannis Lykokostas 👋</h1>

<p align="center">
  <b>Machine Learning Engineer</b><br>
  Electrical & Computer Engineering background with hands-on experience in machine learning, real-time motion systems, and model deployment.
</p>

<p align="center">
  My recent work has centered on human motion, from real-time markerless motion capture and 6-DoF tracking to motion retargeting for humanoid robots.
</p>

<p align="center">
  <a href="mailto:i.lykokostas@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-informational?logo=gmail" /></a>
  <a href="https://linkedin.com/in/ioannis-lykokostas/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin" /></a>
</p>

---

### Technical Focus
- Machine Learning & Deep Learning
- Generative AI & LLM Applications
- Humanoid Robotics, Robot Learning & Physical AI
- Model Deployment & Inference Optimization

### Current Focus
Currently developing a human-to-humanoid motion retargeting pipeline that transforms markerless MoCap data into RL-ready reference trajectories, starting with the Unitree G1 and later extending to other humanoid models. The work focuses on preserving the original human motion while respecting the robot's kinematic and physical constraints, with dedicated checks for joint limits, collisions, floor contact, foot slip, and motion similarity.

---

# 🛠 Tech Stack

### Languages
<p>
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white"/>
<img src="https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black"/>
</p>

### Machine Learning & AI
<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-412991?logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?logoColor=white"/>
</p>

### Robotics & Simulation
<p>
<img src="https://img.shields.io/badge/MuJoCo-000000?logoColor=white"/>
<img src="https://img.shields.io/badge/Pinocchio-4B8BBE?logoColor=white"/>
<img src="https://img.shields.io/badge/mink-6A5ACD?logoColor=white"/>
<img src="https://img.shields.io/badge/NVIDIA%20SOMA-76B900?logo=nvidia&logoColor=white"/>
<img src="https://img.shields.io/badge/Rerun-FF4F8B?logoColor=white"/>
</p>

### Model Serving & Backend
<p>
<img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/REST%20APIs-02569B?logoColor=white"/>
<img src="https://img.shields.io/badge/ONNX%20Runtime-005CED?logo=onnx&logoColor=white"/>
<img src="https://img.shields.io/badge/Microservices-6C757D?logoColor=white"/>
<img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white"/>
</p>

### Cloud, Data & Development Tools
<p>
<img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?logoColor=white"/>
</p>

---

# 📌 Core Projects

### Real-Time Markerless Motion Capture & VR Calibration — Moverse.ai
**Stack:** `Unity`, `OpenXR`, `Markerless MoCap`, `6-DoF Tracking`, `Kabsch`, `SPMC`

- Built a Unity plugin for real-time markerless motion capture integration in wireless OpenXR VR, streaming and mapping MoCap outputs directly to the avatar runtime.
- Designed a spatial and temporal calibration pipeline for asynchronous 6-DoF MoCap and VR tracking, combining resampling and latency estimation with Kabsch/Orthogonal Procrustes and Spherical Pattern Matching Correlation (SPMC).
- Integrated the calibration pipeline into the VR runtime and evaluated it on recorded walking takes, tracking positional error, estimator consistency, and MoCap-to-headset latency.

---

### Human Motion Retargeting for Humanoid Robots
**Stack:** `Python`, `MuJoCo`, `Pinocchio`, `mink`, `NVIDIA SOMA`, `Rerun`

- Building a pipeline that converts markerless GLB MoCap data into RL-ready reference trajectories for humanoid robots, starting with the Unitree G1 and extending to additional models.
- Implemented IK-based motion retargeting to preserve the original human motion while enforcing joint, velocity, and self-collision constraints.
- Built a validation pipeline covering joint limits, collisions, floor contact, foot slip, and motion similarity, reporting violations by joint and frame and integrating Rerun for visual debugging.

---

### Turbofan Engine RUL Prediction
**Stack:** `Python`, `PyTorch`, `Docker`, `ONNX`, `Optuna`, `CUDA`, `FastAPI`, `Scikit-learn`, `NumPy`

- Built an end-to-end predictive maintenance pipeline on NASA C-MAPSS, processing multi-sensor telemetry to predict turbofan remaining useful life.
- Benchmarked and optimized 1D-CNN and LSTM models against a Ridge baseline using Optuna and robust statistical evaluation, selecting the 1D-CNN for deployment.
- Exported the trained PyTorch model to ONNX, achieving 0.16 ms CPU inference latency while preserving accuracy.

---

# 📫 Contact Information

- **Email:** [i.lykokostas@gmail.com](mailto:i.lykokostas@gmail.com)
- **LinkedIn Profile:** [linkedin.com/in/ioannis-lykokostas](https://linkedin.com/in/ioannis-lykokostas/)
