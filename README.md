<h1 align="center">🤖 XArm7 ROS 2 Description Package</h1>

<p align="center">
  <b>A Complete URDF file Package Xarm 7 for ROS 2 Jazzy</b>
  <br><br>
  <img src="https://img.shields.io/badge/ROS_2-Jazzy-blue?logo=ros&logoColor=white" alt="ROS 2 Jazzy" />
  <img src="https://img.shields.io/badge/Build-Colcon-orange" alt="Build Status" />
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License" />
  <br><br>
  XArm7 ROS 2 Full provides description files for the XArm7 manipulator.
</p>

---

## 📦 Package Overview

| Package | Description |
| :--- | :--- |
| **`xarm7_description`** | Contains URDFs, meshes, and basic launch files. |
---

## 🚀 How to Run the Simulation

### 1. Installation & Build

Clone the packages into your workspace `src` folder.

```bash
# Clone repositories
git clone <YOUR_REPO_LINK> src/

# Build and Source
colcon build
source install/setup.bash
```
### 2. Execution (3 Terminals)

**Terminal 1: Launch Simulation**

```bash
ros2 launch xarm7 display.launch.xml

```
## 🛠 Debugging

```bash
# List all active topics
ros2 topic list

# Get info on a specific topic
ros2 topic info /<topic_name>

```

```
Have fun playing with Xarm7!
