# Hi there, I'm fireowl 👋

<p align="center">
  <a href="https://github.com/fireowl-sw">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=520&lines=Hi+there%2C+I'm+fireowl+%F0%9F%91%8B;MS+%40+PolyU+%7C+Embodied+AI+%26+Simulation;Isaac+Lab+%7C+3D%2F4DGS+%7C+Sim2Real" alt="Typing SVG" />
  </a>
</p>

---

### 💫 About Me (关于我)

- 🎓 **Education**: 
  - **The Hong Kong Polytechnic University (PolyU)** - M.Sc. in Electric Vehicles (香港理工大学硕士在读, 2025.09 - 2027.03)
  - **Hunan University of Technology (HUT)** - B.Eng. in Automation (湖南工业大学自动化专业本科, 2019.09 - 2023.06)
- 💼 **Experience**:
  - **UBTECH Robotics (优必选科技)** - Embodied Simulation Algorithm Intern (具身仿真算法实习生, 2026.07 - Present)
- 🔍 **Research & Interests**:
  - **Embodied AI & Robot Learning**: Isaac Sim / Isaac Lab, MuJoCo, Sim2Sim / Sim2Real, Whole-body Locomotion & Dexterous Manipulation
  - **Spatial Intelligence & Neural Rendering**: 3DGS / 4DGS, `gsplat`, Multi-view Dynamic Data Synthesis, High-fidelity Asset Reconstruction
  - **VLA & Policy Closed-Loop**: VLA (LeRobot / OpenPI), StreamVLN, POSIX Zero-copy IPC, Real-time Robotics Control
- ✉️ **Contact**: fireowlsw@outlook.com
- 🤗 **Hugging Face**: [fireowl-sw](https://huggingface.co/fireowl-sw)

---

### 🛠️ Tech Stack (技术栈)

<p align="left">
  <!-- Languages & Compute -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <br />
  <!-- Robotics & Simulation -->
  <img src="https://img.shields.io/badge/Isaac%20Sim%20/%20Lab-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Isaac Lab" />
  <img src="https://img.shields.io/badge/MuJoCo-412991?style=flat-square&logo=simulation&logoColor=white" alt="MuJoCo" />
  <img src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS2" />
  <img src="https://img.shields.io/badge/CARLA-000000?style=flat-square&logo=carla&logoColor=white" alt="CARLA" />
  <img src="https://img.shields.io/badge/Gazebo-F56600?style=flat-square&logo=gazebo&logoColor=white" alt="Gazebo" />
  <br />
  <!-- Spatial Intelligence & Embodied -->
  <img src="https://img.shields.io/badge/3D/4D_Gaussian_Splatting-FF6F00?style=flat-square&logo=webassembly&logoColor=white" alt="3DGS" />
  <img src="https://img.shields.io/badge/OpenUSD-00599C?style=flat-square&logoColor=white" alt="OpenUSD" />
  <img src="https://img.shields.io/badge/VLA_%26_LeRobot-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="LeRobot" />
  <img src="https://img.shields.io/badge/Reinforcement_Learning-PPO/APPO-008080?style=flat-square" alt="RL" />
  <img src="https://img.shields.io/badge/POSIX_IPC-0-Copy-gray?style=flat-square" alt="IPC" />
</p>

---

### 🚀 Featured Projects (精选项目)

#### 🤖 人形双足与全身运动控制 (Humanoid Locomotion & Whole-Body Control)
- **🐕 [rl_sar](https://github.com/fireowl-sw/rl_sar)** - 基于 Isaac Lab 的智元 D1 机器人步态控制策略训练与 Sim2Sim 跨引擎（MuJoCo/Gazebo）零样本迁移验证系统，提供 [Bilibili 演示视频](https://www.bilibili.com/video/BV1Kn7g6HEx9/)。
- **⚡ [supermimic_vibed](https://github.com/fireowl-sw/supermimic_vibed)** - 人形机器人全身运动模仿强化学习训练框架，基于 LAFAN 动捕标准对齐，具备高速 GPU 并行推步与稳健动作复现能力。

#### ✋ 灵巧手与操作学习 (Dexterous Manipulation & In-Hand Control)
- **✋ [MiniLab-Hand](https://github.com/fireowl-sw/MiniLab-Hand)** - 基于 MuJoCo 仿真器的仿人五指灵巧手强化学习（APPO 异步并行 + 共享内存 IPC）操作与控制系统，支持手内操纵与动作轨迹评估，提供 [Bilibili 演示视频](https://www.bilibili.com/video/BV1UDj16XEHM/)。
- **🔬 [MiniLab](https://github.com/fireowl-sw/MiniLab)** - 轻量级机器人灵巧手仿真与强化学习测试环境平台（Gymnasium + MuJoCo 架构）。

#### 🌐 空间智能与神经辐射场 (Spatial Intelligence & 3D/4DGS)
- **🤗 [sugar-code](https://huggingface.co/fireowl-sw/sugar-code)** - 基于 3DGS 的表面对齐场景几何与网格重建，支持利用泊松重建导出高精度 Mesh 网格并导入 Isaac Sim/Isaac Lab 进行物理交互仿真，提供 [Bilibili 演示视频](https://www.bilibili.com/video/BV1bELR6CEET/)。

#### 🚗 自动驾驶感知与多模态模型 (Perception & Autonomous Systems)
- **🚗 [fireowl_sim_drive](https://github.com/fireowl-sw/fireowl_sim_drive)** - 基于 CARLA 仿真器与 ROS2 框架实现的自动驾驶实时点云建图与感知系统。
- **🧠 [minimind-v-model](https://huggingface.co/fireowl-sw/minimind-v-model/tree/main)** - 极简 VLM（视觉语言模型）复现项目，支持端到端多模态数据训练、微调与推理验证。

---

### 📊 GitHub Activity & Stats (活跃度与统计)

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=fireowl-sw&show_icons=true&theme=radical&hide_border=true&title_color=38bdf8&icon_color=38bdf8&text_color=94a3b8&bg_color=0f172a" alt="fireowl-sw GitHub Stats" height="160px" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fireowl-sw&layout=compact&theme=radical&hide_border=true&title_color=38bdf8&text_color=94a3b8&bg_color=0f172a" alt="Top Langs" height="160px" />
</p>
