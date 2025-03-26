<div align="center">
	<img width="500" height="350" src="media/logo.svg" alt="Awesome">
	<br><br>
	<h1>Awesome NVidia Omniverse</h1>
	<p>A curated list of awesome resources, tools, and projects for <strong>NVIDIA Omniverse</strong>.</p>
	<br>
	<sub>🚀 Explore the metaverse of 3D simulation, digital twins, robotics, and AI</sub>
</div>
<br><br><br>

## Contents

- [Research Papers](#research-papers)
- [Reinforcement Learning](#reinforcement-learning)
- [Synthetic Data Generation](#synthetic-data-generation)
- [Core Components of Isaac Sim](#core-components-of-isaac-sim)
- [Integration with ROS 2 and Related Tools](#integration-with-ros-2-and-related-tools)
- [Utilities and Development Tools](#utilities-and-development-tools)
- [Tutorials and Documentation](#tutorials-and-documentation)
- [Community Projects](#community-projects)

---

## Research Papers

- [Isaac Gym for High Performance Reinforcement Learning](https://arxiv.org/abs/2108.10470)  
  Introduces Isaac Gym, NVIDIA’s high-performance physics engine for reinforcement learning.
- [OmniIsaacGymEnvs: Domain Randomization RL for Robotics](https://github.com/NVIDIA-Omniverse/OmniIsaacGymEnvs)  
  Collection of domain-randomized environments for training RL agents in Isaac Sim.
- [Sim2Real with Isaac Sim](https://developer.nvidia.com/blog/tag/sim2real/)  
  Blog series and papers related to simulation-to-reality transfer using Isaac Sim.

---

## Reinforcement Learning

- **OmniIsaacGymEnvs**  
  A set of GPU-accelerated, ready-to-use RL environments for robotic simulation.
- **Isaac Orbit**  
  A modular framework built on Isaac Sim for robot learning and control research.
- **Reinforcement Learning with PhysX**  
  Utilize the PhysX engine inside Isaac Sim to build reliable RL environments.

---

## Synthetic Data Generation

- **Omniverse Replicator**  
  A powerful tool for generating annotated synthetic data for perception models.
- **Domain Randomization**  
  Built-in tools in Isaac Sim to vary lighting, texture, and geometry for robustness.
- **Camera & Sensor Simulation**  
  Simulate RGB, depth, and LiDAR sensors with ground truth annotations.

---

## Core Components of Isaac Sim

- **USD (Universal Scene Description)**  
  The foundational data format used across Omniverse for efficient scene composition.
- **PhysX**  
  NVIDIA’s physics engine supporting rigid body dynamics, articulation, collision, etc.
- **OmniGraph**  
  Node-based visual scripting system for reactive simulation logic.
- **ActionGraph**  
  High-level task automation framework for composing agent behaviors.

---

## Integration with ROS 2 and Related Tools

- **ROS 2 Bridge**  
  Enables two-way communication between Isaac Sim and ROS 2 topics/services/actions.
- **MoveIt 2 Integration**  
  Connect Isaac Sim to MoveIt 2 for advanced motion planning and manipulation.
- **Nav2 in Isaac Sim**  
  Test autonomous navigation pipelines within simulated environments.
- **Multi-Robot Systems**  
  Launch and coordinate multiple ROS 2 robots in a shared Isaac Sim environment.

---

## Utilities and Development Tools

- **Kit SDK & Extensions**  
  Customize and extend Isaac Sim functionality via Python or C++ plugins.
- **Asset Validator**  
  Verify that your USD assets are optimized and ready for simulation.
- **OmniCLI**  
  Command-line interface for scripting and automation within Omniverse apps.

---

## Tutorials and Documentation

- [Isaac Sim Documentation](https://docs.omniverse.nvidia.com/isaacsim/latest/)
- [Omniverse YouTube Channel](https://www.youtube.com/c/NVIDIAOmniverse)
- [NVIDIA Developer Blog - Omniverse](https://developer.nvidia.com/blog/tag/omniverse/)

---

## Community Projects

- [isaac_ros_common](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_common)  
  A collection of ROS 2 tools and bridges developed specifically for Isaac ROS.
- [isaac_examples](https://github.com/NVIDIA-Omniverse/Isaac-Sim-Robotics/tree/main/source/extensions/omni.isaac.examples)  
  Ready-to-use examples demonstrating Isaac Sim’s key features.
- [awesome-isaac-sim](https://github.com/your-name/awesome-isaac-sim)  
  Your curated repository collecting and organizing these resources.
  
> Inspired by [sindresorhus/awesome](https://github.com/sindresorhus/awesome)
