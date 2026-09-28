<h1 align="center">Hi, I'm Lenin Valentine C J 👋</h1>

<p align="center">
  <b>Embedded Software Engineer · B.Tech ECE @ SRMIST</b><br/>
  Firmware for medical devices, motor controllers & IoT systems · FreeRTOS & QNX Neutrino
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/leninvalentine/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:leninvalentine97@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/LeninValentine06"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

## 🧑‍💻 About Me

I'm an ECE undergrad who spends most of my time writing firmware — close to the metal, close to the hardware. My work spans medical devices, motor controllers, wearables and industrial IoT, from spirometers and anesthesia machines to smart sports hardware.

---

## 🛠️ Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-004482?style=for-the-badge&logo=cplusplus&logoColor=white)

**Platforms & RTOS**

![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-8CC84B?style=for-the-badge&logoColor=white)
![QNX](https://img.shields.io/badge/QNX_Neutrino-000000?style=for-the-badge&logoColor=white)

**Protocols & Connectivity**

![UART](https://img.shields.io/badge/UART-555555?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-555555?style=for-the-badge)
![I2C](https://img.shields.io/badge/I2C-555555?style=for-the-badge)
![I2S](https://img.shields.io/badge/I2S-555555?style=for-the-badge)
![BLE](https://img.shields.io/badge/BLE-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![CAN](https://img.shields.io/badge/CAN_Bus-FF6B00?style=for-the-badge)

**Peripherals & Tools**

`DMA` `ADC` `PWM` `Timers` `Interrupts` `STM32CubeIDE` `STM32CubeMX` `LVGL` `Oscilloscope` `Logic Analyzer`

---

## 🚀 Projects

### 🫁 [Deterministic Anesthesia Gas Monitor](https://github.com/LeninValentine06/UROP)
A six-process QNX Neutrino application with address-space isolation, message-passing IPC, and shared-memory communication for real-time gas monitoring and alarm management. Achieved **1.50 ms worst-case alarm latency** with priority-based scheduling. LVGL UI rendered via QNX Screen API on Raspberry Pi 4B.

`QNX Neutrino` `C` `LVGL` `Raspberry Pi 4B` `IPC` `Real-time Scheduling`

---

### 🚑 Real-Time Patient Telemetry System for Ambulances
STM32F407 firmware integrating MAX30102, MLX90614, and INMP441 over DMA-driven I²C, I²S, and SPI for continuous acquisition of heart rate, SpO₂, temperature, and respiration rate. UART-to-MQTT bridging via ESP32 to a Raspberry Pi edge node — **145 ms end-to-end latency**.

`STM32F407` `C` `DMA` `MQTT` `ESP32` `Raspberry Pi`

---

### 🌍 [Phoenix — LoRa Landslide Detection System](https://github.com/LeninValentine06/Phoenix)
Distributed early-warning system using ESP32 sensor mesh nodes (MPU6050, soil moisture, DHT22) communicating over LoRa 433MHz to a master node with TFT display, audio alert, and mobile notifications. Supports up to 50 nodes per master. Custom PCB designed for both nodes.

`C++` `ESP32` `LoRa` `PCB Design` `Flutter`

---

### 🏥 [GenAI Ventilator — AWS IoT Simulation](https://github.com/LeninValentine06/GenAI-Ventilator-AWS-Simulation)
Research prototype simulating ventilator telemetry to AWS IoT Core over MQTT/TLS, processed in real-time via AWS Lambda, and visualized through a Streamlit dashboard over WebSocket API. Accompanied by an ESP32 hardware prototype.

`Python` `AWS IoT Core` `MQTT` `AWS Lambda` `Streamlit` `ESP32`

---

### 🎾 [ThynkBall — Smart Cricket Ball](https://github.com/LeninValentine06/ThynkBall)
ESP32-C6 embedded system integrating BMI088 IMU (SPI/I2C) and INMP441 microphone (I2S). Processes accelerometer and gyroscope data to compute ball speed and trajectory, streamed in real time over BLE. Includes a Python dashboard for live visualization and CSV data logging.

`C++` `ESP32-C6` `BLE` `IMU` `Python`

---

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=LeninValentine06&show_icons=true&theme=tokyonight&hide_border=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LeninValentine06&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>
