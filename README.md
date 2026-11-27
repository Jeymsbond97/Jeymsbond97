<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F4B,100:2348FF&height=140&section=header&text=Tokhirbek%20Aminjonov&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Robotics%20Software%20Engineer%20%C2%B7%20Physical%20AI&descAlignY=60&descSize=18"/>
</p>

<p align="center">
  <a href="https://jeymsbond97.github.io"><img src="https://img.shields.io/badge/Portfolio-jeymsbond97.github.io-2348FF?style=for-the-badge&logo=astro&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/aminjonov-tokhirbek"><img src="https://img.shields.io/badge/LinkedIn-aminjonov--tokhirbek-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:aminjonovtoxirbek@gmail.com"><img src="https://img.shields.io/badge/Email-aminjonovtoxirbek%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <b>Seoul, South Korea</b> · E-7 visa · English (IELTS 7.0) · Korean (TOPIK 4) · Uzbek
</p>

---

## About

I'm a **robotics software engineer** in Seoul. I write the software that makes robots work in the real world: **vision, manipulation, voice AI, PLC integration and on-device AI on NVIDIA Jetson**.

Right now I build application software for service robots and cobot factory lines at **Cutshion (쿳션)**, from ROS 2 nodes and vision all the way to field installation. Before robotics I spent 4 years as a full-stack and mobile developer, so I can also build the system around a robot: backend, dashboard and operator app. My current focus is **Physical AI**: reinforcement learning and imitation learning for robot control, applied to humanoid locomotion in **MuJoCo** and **Isaac Lab**.

---

## Achievements

- 🏭 **Factory line delivered:** injection-molding automation with 2 JAKA cobots, 3 conveyors, 3 cameras and an LS PLC (Modbus TCP). **Passed customer acceptance in Aug 2026.**
- 🤖 **On-device robot assistant:** JAKA Lumi voice + vision + pick-and-place, all on Jetson Thor. **~2 s** voice reply, **4–13 ms** YOLO + TensorRT detection, **3.3 mm** hand-eye calibration.
- 🍎 **Simulation benchmark:** vision-guided mobile manipulation in MuJoCo. **97 % clean pick-ups and 0 collisions** over 90 random episodes.

---

## Experience

<p align="center"><sub>⬆ career path: read from the bottom up ⬆</sub></p>

<table>
<tr>
<td width="140" align="center">🟢<br/><b>2026.05 – now</b><br/><sub>Seoul</sub></td>
<td>

**Robotics Engineer · Cutshion (쿳션)**<br/>
<sub>Robotics startup: service robots and cobot factory automation</sub>

- 🏭 Built the backend and vision for an injection-molding line with **2 JAKA cobots, 3 conveyors, 3 cameras and an LS PLC** (Modbus TCP, e-stop and door interlocks). **It passed customer acceptance in Aug 2026.**
- 🤖 Built the application software for the **JAKA Lumi** mobile manipulator: Korean/English voice AI with a local LLM (~2 s reply), YOLO + TensorRT vision (4–13 ms) and pick-and-place with **3.3 mm** hand-eye calibration, all on **Jetson Thor**.
- 🎨 AI drawing robot: Gemini line art → OpenCV vectorizing → robot paths, with a Flutter kiosk app.
- 🧩 LLM engine that writes JAKA block programs from natural language, with safety checks. STM32 ultrasonic sensor node (Modbus RTU / RS485).

</td>
</tr>
<tr>
<td align="center">🔵<br/><b>2025.10 – 2026.05</b><br/><sub>Seoul</sub></td>
<td>

**Software Developer · KEICO**<br/>
<sub>Energy-efficiency company: IoT and AI energy platform</sub>

- 📱 Rebuilt the **FECO** energy-management app in Flutter: monitoring, schedules and alarms, plus remote control of IoT devices over REST, MQTT and a Zigbee edge gateway.
- 🌡️ Prototyped reinforcement-learning temperature control on live sensor data.
- 🌐 Company websites with NestJS + GraphQL and Next.js, deployed with Docker on AWS.

</td>
</tr>
<tr>
<td align="center">⚪<br/><b>2023.08 – 2025.07</b><br/><sub>Remote</sub></td>
<td>

**Backend Developer · Exadot LLC**<br/>
<sub>Remote, while studying at Jeonbuk National University</sub>

- ⚙️ REST and GraphQL APIs with NestJS, Spring Boot and Python on PostgreSQL, MySQL and MongoDB.
- 🔐 JWT / Spring Security auth, real-time features with WebSocket and Socket.IO, Docker deploys on AWS EC2 + Nginx.

</td>
</tr>
<tr>
<td align="center">⚪<br/><b>2021.11 – 2023.02</b><br/><sub>Remote</sub></td>
<td>

**Frontend Developer · Colibrisoft**<br/>
<sub>Remote, while studying at Jeonbuk National University</sub>

- 💻 Responsive web apps with React, TypeScript, Redux and Tailwind. i18n and Three.js 3D features.

</td>
</tr>
</table>

---

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**JAKA Lumi assistant**](https://github.com/Jeymsbond97/Jaka-Lumi) | Turns a JAKA Lumi mobile manipulator into an office assistant. It talks in Korean and English, navigates, tracks people and does pick-and-place. Everything runs on the robot's Jetson Thor. | Python · whisper.cpp · Ollama (local LLM) · YOLOv8 + TensorRT · RGB-D · IK · FastAPI |
| [**Lumi App**](https://github.com/Jeymsbond97/lumi-app) | Mobile and tablet app for the same robot: live 3D robot state, cameras, map, driving and one-tap behaviours. | React Native (Expo) · TypeScript · REST |
| [**PiCar Apple Picker**](https://github.com/Jeymsbond97/picar-mujoco-apple-picker) | Vision-guided mobile manipulation in MuJoCo. A car-like robot finds an apple, drives around obstacles and picks it up with a 4-DOF arm. **97 % clean pick-ups, 0 collisions over 90 random episodes.** | MuJoCo · MJCF · OpenCV · potential fields · analytic IK |
| [**Booster K1 locomotion**](https://github.com/Jeymsbond97/Booster) *(in progress)* | Teaching a 22-DOF humanoid to stand, balance and walk with RL, following the Booster Gym pipeline: PPO training in simulation, then sim-to-sim validation in MuJoCo, then the real robot. | MuJoCo · Isaac Lab · PPO · PyTorch |

<p align="center">
  <img src="https://raw.githubusercontent.com/Jeymsbond97/picar-mujoco-apple-picker/main/media/demo_obstacles.gif" width="49%" alt="PiCar apple picker in MuJoCo"/>
  <img src="https://raw.githubusercontent.com/Jeymsbond97/Jaka-Lumi/main/real/thor/sim/sorting/media/sorting_demo.gif" width="49%" alt="Lumi sorting in simulation"/>
</p>

---

## Skills

**Robotics**
<p>
  <img src="https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white"/>
  <img src="https://img.shields.io/badge/MuJoCo-1F2937?style=flat-square"/>
  <img src="https://img.shields.io/badge/NVIDIA%20Isaac%20Lab-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/Manipulation%20%26%20IK-374151?style=flat-square"/>
  <img src="https://img.shields.io/badge/Hand--Eye%20Calibration-374151?style=flat-square"/>
  <img src="https://img.shields.io/badge/Mobile%20Manipulation-374151?style=flat-square"/>
  <img src="https://img.shields.io/badge/Cobots%20(JAKA)-374151?style=flat-square"/>
</p>

**Physical AI & machine learning**
<p>
  <img src="https://img.shields.io/badge/Reinforcement%20Learning-6D28D9?style=flat-square"/>
  <img src="https://img.shields.io/badge/Imitation%20Learning-6D28D9?style=flat-square"/>
  <img src="https://img.shields.io/badge/Sim--to--Real-6D28D9?style=flat-square"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/LLM%20(local)-111827?style=flat-square"/>
  <img src="https://img.shields.io/badge/Speech%20(STT%2FTTS)-111827?style=flat-square"/>
</p>

**Vision & edge AI**
<p>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square"/>
  <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/RGB--D%20Cameras-374151?style=flat-square"/>
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white"/>
</p>

**Industrial & embedded**
<p>
  <img src="https://img.shields.io/badge/PLC%20(LS%20XGB)-B45309?style=flat-square"/>
  <img src="https://img.shields.io/badge/Modbus%20TCP%2FRTU-B45309?style=flat-square"/>
  <img src="https://img.shields.io/badge/RS485-B45309?style=flat-square"/>
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/Safety%20Interlocks-B45309?style=flat-square"/>
</p>

**Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"/>
</p>

**Backend, apps & DevOps**
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square"/>
</p>

---

## Education

| | |
|---|---|
| 🎓 **B.S. Computer Science & Engineering** · Jeonbuk National University (전북대학교), Korea | 2019.09 – 2025.02 |
| 🎓 **Mechanical Engineering** · Ferghana Polytechnic Institute, Uzbekistan | 2016.09 – 2019.09 |

---

## Awards & certifications

| | |
|---|---|
| 🏆 **Excellent Student Award**: top 10 in the Dept. of Computer Science & Engineering, Jeonbuk National University | 2023.02 |
| 📜 **Google Project Management Professional Certificate** (Coursera) | 2026.09 |
| 🇰🇷 **TOPIK Level 4** (Korean) | 2026.10 |
| 🇬🇧 **IELTS 7.0** (English) | |

---

## GitHub activity

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Jeymsbond97&theme=tokyonight&hide_border=true" alt="streak"/>
</p>

<p align="center"><i>Open to robotics software, robot application and Physical AI roles in Korea. Feel free to reach out.</i></p>
