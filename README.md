<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Sujith Kumar — Robotics Software · Embedded Systems · Control"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sujith-kumar26"><img src="https://img.shields.io/badge/LinkedIn-sujith--kumar26-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:SUJITHKU002@e.ntu.edu.sg"><img src="https://img.shields.io/badge/Email-NTU-22D3EE?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/B.Eng-Computer%20Engineering%20%40%20NTU-34D399?style=for-the-badge"/>
  <img src="https://komarev.com/ghpvc/?username=suujithhhh&style=for-the-badge&color=0d1a24&label=VISITORS"/>
</p>

---

### 🤖 `$ cat about.txt`

```cpp
struct Engineer {
    std::string name_     = "Sujith Kumar";
    std::string base_     = "Singapore 🇸🇬";
    std::string study_    = "B.Eng Computer Engineering @ NTU (2024 – 2028)";
    std::vector<std::string> loves_ = {
        "firmware that talks to real hardware",
        "control loops that actually settle",
        "test rigs that find the fault before the robot does",
    };
    std::string now_      = "taking an autonomy stack from STM32 → CAN → ROS 2";
};
```

<p align="center">
  <img src="assets/telemetry.svg" width="100%" alt="Telemetry: PID step response, UART/CAN frame log, CAN waveform"/>
</p>

### 🛠️ `$ ls ~/projects`

<table>
<tr>
<td width="50%" valign="top">

#### 🏆 [Autonomous Robot — NTU MDP](https://github.com/suujithhhh/SC2079-MDP-Group7)
**1st of 32 teams** · Team Lead · STM32 firmware lead

- STM32F407 + FreeRTOS firmware: command queue → motion state machine
- Cascaded wheel PID + IMU heading hold, **within ~1°** on turns
- UART protocol with ACK/ERR + priority STOP
- Python state-lattice planner that powered the #1 run

`C` `FreeRTOS` `I2C` `UART` `PWM` `Python`

</td>
<td width="50%" valign="top">

#### ⚙️ [MDP Robot Autonomy Stack](https://github.com/suujithhhh/mdp-robot-autonomy-stack)
**C++17 · simulated CAN · ROS 2** (in progress)

- Hardware-free STM32 simulator speaking the real protocol
- CAN 2.0A from scratch: bit stuffing, CRC-15, arbitration, bus-off
- **100/100** missions completed with ~5% frames corrupted
- Planner ported to C++: **33× faster**, 213 GoogleTest cases

`C++17` `CMake` `GTest` `ASan/UBSan` `ROS 2`

</td>
</tr>
</table>

<p align="center">
  <img src="assets/factory.svg" width="100%" alt="Robot arm inspecting parts on a conveyor"/>
</p>
