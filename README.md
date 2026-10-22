<div align="center">

<!-- OPTION 1 : BANNIÈRE DYNAMIQUE (Fonctionne immédiatement sans uploader d'image) -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:09090b,75:18181b,100:ff7b00&height=220&section=header&text=ZUBULMUK92&fontSize=65&fontColor=ffffff&fontAlignY=42&desc=%5B%20AUTONOMOUS%20ROBOTICS%20%2F%2F%20ROS%202%20%2F%2F%20EMBEDDED%20SYSTEMS%20%5D&descSize=16&descAlignY=68&stroke=ff7b00&strokeWidth=1" width="100%" alt="Header Banner" />

<!-- OPTION 2 : Si tu télécharges l'image 3D générée, mets-la dans /assets/banner-tactical.png et décommente la ligne ci-dessous en supprimant l'Option 1 : -->
<!-- <img src="https://raw.githubusercontent.com/zubulmuk92/zubulmuk92/HEAD/assets/banner-tactical.png" width="100%" alt="zubulmuk92"> -->

<!-- TELEMETRY TYPING HUD -->
<a href="https://github.com/zubulmuk92">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=14&duration=3000&pause=1000&color=FF7B00&center=true&vCenter=true&width=800&height=30&lines=SYS.STATUS+%3A+ONLINE+%2F%2F+LOC+%3A+FRANCE+%5B43.6047%C2%B0+N%2C+1.4442%C2%B0+E%5D;CORE+STACK+%3A+ROS+2+%7C+AUTONOMOUS+NAVIGATION+%7C+EMBEDDED+C%2FC%2B%2B+%26+RUST;DIRECTIVE++%3A+ROBOTS+BY+DAY%2C+SOFTWARE+BY+NIGHT+%E2%80%94+SHIP+IT%2C+DON'T+JUST+DEMO+IT." alt="System Telemetry" />
</a>

<p align="center">
  <b>Mechatronics & Autonomous Robotics Engineer 🇫🇷</b><br>
  <i>Bridging custom hardware, real-time embedded firmware, and high-level ROS 2 autonomy.</i>
</p>

<!-- TACTICAL BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/MIDDLEWARE-ROS_2_%2F_DDS-ff7b00?style=for-the-badge&logo=ros&logoColor=white&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/DOMAIN-UAV_%26_UGV_AUTONOMY-1f242d?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/FIRMWARE-C_%2F_C%2B%2B_%2F_RUST-1f242d?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/STATUS-FIELD_READY-ff7b00?style=for-the-badge&labelColor=0d1117" />
</p>

</div>

---

### `01 // OPERATIONAL_CAPABILITIES`

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><code>[AUTONOMY & ROS 2 ARCHITECTURE]</code></h4>
      <ul>
        <li><b>Navigation & Mapping:</b> ROS 2, Nav2, SLAM, path planning & obstacle avoidance for mobile platforms (UGV/UAV).</li>
        <li><b>Perception & Sensor Fusion:</b> 2D/3D LiDAR, stereo depth cameras, IMU integration & real-time target detection.</li>
        <li><b>Multi-Agent Systems:</b> Distributed swarm communication, DDS middleware tuning & onboard Edge AI / SLM integration.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4><code>[EMBEDDED SYSTEMS & HARDWARE]</code></h4>
      <ul>
        <li><b>Low-Level Firmware:</b> Bare-metal & RTOS development in <code>C</code>, <code>C++</code>, and <code>Rust</code> (STM32, ESP32, Raspberry Pi).</li>
        <li><b>Industrial Protocols:</b> Custom hardware drivers over CAN, RS485, Modbus, UART, SPI, and I2C.</li>
        <li><b>Mechatronics Integration:</b> Custom PCB design (KiCAD), power monitoring, CAD modeling (SolidWorks / Fusion 360) & rapid prototyping.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><code>[SIMULATION & CONTROL LOOPS]</code></h4>
      <ul>
        <li><b>Digital Twins:</b> Robotics simulation, kinematics modeling & synthetic testing in <b>Unity</b> (C#) and <b>Gazebo</b>.</li>
        <li><b>Control Theory:</b> PID regulation, motor control, odometry calibration & MATLAB/Simulink validation.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4><code>[GROUND CONTROL & INFRASTRUCTURE]</code></h4>
      <ul>
        <li><b>Containerized Robotics:</b> Reproducible ROS 2 deployments via Docker & Linux embedded environments.</li>
        <li><b>Telemetry & Command UI:</b> Low-latency WebSockets, MQTT, WebRTC gateways & custom React/TypeScript dashboards.</li>
      </ul>
    </td>
  </tr>
</table>

---

### `02 // SYSTEM_PIPELINE`

> **Full-Stack Robotics Architecture** — *From custom silicon & actuator control to high-level autonomous decision-making.*

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#161b22', 'primaryTextColor': '#e6edf3', 'primaryBorderColor': '#ff7b00', 'lineColor': '#ff7b00', 'secondaryColor': '#0d1117', 'tertiaryColor': '#161b22'}}}%%
flowchart LR
    subgraph HW ["01 // HARDWARE & SENSORS"]
        direction TB
        S1["LiDAR / Depth / IMU"]
        S2["Custom PCB & Actuators"]
    end

    subgraph EMB ["02 // LOW-LEVEL FIRMWARE"]
        direction TB
        F1["STM32 / ESP32 (C/C++/Rust)"]
        F2["CAN / RS485 / Modbus"]
    end

    subgraph ROS ["03 // ROS 2 AUTONOMY CORE"]
        direction TB
        R1["DDS Middleware & Drivers"]
        R2["SLAM / Nav2 / Control Loops"]
        R3["Swarm & Edge AI Logic"]
    end

    subgraph GCS ["04 // SIM & MISSION CONTROL"]
        direction TB
        G1["Unity / Gazebo Digital Twin"]
        G2["Docker / Telemetry UI"]
    end

    HW ==> EMB ==> ROS ==> GCS
    GCS -. "Mission Commands" .-> ROS
