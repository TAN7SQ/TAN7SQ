<div align="center">

# Hi, I'm TAN7SQ

Robotics Software · Embedded Vision · ROS2 Perception · State Estimation

正在从 RoboMaster 机器人系统开发，深入到 **视觉导航、传感器融合、ROS2 感知系统与边缘端 AI 部署**。

[![GitHub followers](https://img.shields.io/github/followers/TAN7SQ?style=flat-square&logo=github&label=Follow)](https://github.com/TAN7SQ)
[![Profile Views](https://komarev.com/ghpvc/?username=TAN7SQ&style=flat-square&color=0e75b6)](https://github.com/TAN7SQ)
[![Email](https://img.shields.io/badge/Email-1240973173%40qq.com-blue?style=flat-square&logo=gmail)](mailto:1240973173@qq.com)

</div>

---

## About Me

我是汤俊琦，长期参与 RoboMaster 机器人系统开发，做过工程机器人、飞镖机器人、嵌入式视觉端、机器人主控板、飞控板、超级电容控制器和上位机调试工具。

我现在重点关注：

- **视觉导航与状态估计**：object detection, tracking, monocular state estimation, VIO / SLAM
- **传感器融合**：camera-IMU, camera-LiDAR, tf2, calibration, EKF / factor graph
- **ROS2 感知系统**：camera node, detector node, tracker node, fusion node, RViz visualization
- **边缘端 AI 部署**：YOLO, ONNX, RK / RDK / NVIDIA, FPS / latency / CPU / NPU profiling
- **工程化交付**：Linux, C++, Python, Git, Shell, Markdown, testable demos and technical docs

我也会使用 **Codex** 和 **OpenCode** 辅助代码阅读、工程重构、调试路径拆解、README / 技术文档整理与测试清单设计，但会以实际运行结果和代码审查来校验 AI 生成内容。

---

## Current Focus

```text
ROS2 Perception Pipeline

camera_node
  -> detector_node
  -> tracker_node
  -> state_estimator
  -> fusion_node
  -> RViz / HUD / metrics
```

近期主线是把机器人视觉能力从“能检测目标”推进到：

- stable track id
- image-plane velocity estimation
- distance / lateral offset estimation
- camera calibration and tf2 frame tree
- camera-IMU branch
- KITTI / nuScenes camera-LiDAR offline association demo
- RK / RDK edge deployment metrics

---

## Featured Project

### [TrackCam](https://github.com/TAN7SQ/TrackCam)

A ROS2-based visual object tracking and state estimation system for autonomous-driving perception prototyping.

当前已完成：

- C++ ROS2 camera node
- USB camera input and `/camera/image_raw`
- YOLO detector node
- SORT / Kalman tracker node
- image-plane state estimation
- custom ROS2 interfaces for detection / tracking / state output

Roadmap:

- HUD visualization
- latency metrics
- camera geometry and calibrated state estimation
- Camera-LiDAR Fusion with KITTI-style image and point cloud projection

---

## Tech Stack

### Robotics & Perception

![ROS2](https://img.shields.io/badge/ROS2-Humble-22314E?style=flat-square&logo=ros)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=flat-square&logo=opencv)
![YOLO](https://img.shields.io/badge/YOLO-Detection-00FFFF?style=flat-square)
![Kalman](https://img.shields.io/badge/Kalman-State%20Estimation-1f6feb?style=flat-square)
![SLAM](https://img.shields.io/badge/VIO%20%2F%20SLAM-Learning-0e75b6?style=flat-square)

### Embedded & Systems

![C++](https://img.shields.io/badge/C%2B%2B-17-00599C?style=flat-square&logo=cplusplus)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-FCC624?style=flat-square&logo=linux&logoColor=black)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-Embedded-00979D?style=flat-square)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-ESP32-E7352C?style=flat-square&logo=espressif)
![STM32](https://img.shields.io/badge/STM32-MCU-03234B?style=flat-square&logo=stmicroelectronics)

### Tools

![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=flat-square&logo=git&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-Automation-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-Build-064F8C?style=flat-square&logo=cmake)
![Markdown](https://img.shields.io/badge/Markdown-Docs-000000?style=flat-square&logo=markdown)
![Codex](https://img.shields.io/badge/Codex-AI%20Coding-111111?style=flat-square)
![OpenCode](https://img.shields.io/badge/OpenCode-AI%20Coding-111111?style=flat-square)

---

## Robotics Experience

- RoboMaster robot system development
- Embedded Linux vision pipeline
- FreeRTOS control-side development
- STM32 / ESP32-S3 / MaixCAM platform bring-up
- CAN / RS485 / UART / SPI / I2C communication
- IMU / magnetometer / barometer data acquisition
- Kalman-based state estimation
- Web / desktop upper-computer debugging tools
- PCB design and hardware-software co-debugging

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=TAN7SQ&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TAN7SQ&layout=compact&theme=transparent&hide_border=true" />

</div>

---

## Learning Roadmap

- [x] ROS2 camera input and image topic
- [x] YOLO detector node
- [x] SORT / Kalman tracker node
- [x] structured ROS2 interfaces
- [ ] camera calibration and tf2 tree
- [ ] ByteTrack / Hungarian association
- [ ] camera-IMU state estimation branch
- [ ] KITTI / nuScenes camera-LiDAR association demo
- [ ] RK / RDK edge deployment and performance table

---

## Contact

- Email: 1240973173@qq.com
- Feishu personal page: [TAN7's User Manual](https://my.feishu.cn/wiki/O8lZwoOpqietcOkYcMlcEXuynpf)
- GitHub: [TAN7SQ](https://github.com/TAN7SQ)

<div align="center">

Keep building real robots, real systems, and real demos.

</div>
