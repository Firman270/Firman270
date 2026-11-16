<div align="center">

# Hi, I'm Firman Nur Hidayat 👋

**Informatics Engineering Student | IoT | Embedded Systems | Hardware & Firmware Integration**

<p>
  <a href="https://linkedin.com/in/fir-man-33a820370">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:firmn030@gmail.com">
    <img src="https://img.shields.io/badge/Email-firmn030%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/Firman270?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" />
  </a>
</p>

</div>

I'm a final-year Informatics Engineering student interested in building practical solutions using embedded systems, microcontrollers, and Internet of Things (IoT) technologies.

I have hands-on experience developing and integrating projects using **ESP32, ESP8266, and STM32**, including sensor integration, actuator control, firmware modification, MQTT communication, and hardware troubleshooting. I enjoy understanding how systems work, solving technical problems, and turning hardware prototypes into functional applications.

<div align="center">
  <img src="./github-metrics.svg" alt="Firman270 GitHub Metrics" width="100%" />
</div>

---

## 🔧 Technical Skills

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Microcontrollers & Embedded Platforms</strong><br/>
      • ESP32 &bull; ESP8266 &bull; STM32<br/><br/>
      <strong>Programming & Firmware</strong><br/>
      • <strong>C/C++</strong> — Code understanding, modification, integration, and debugging<br/>
      • <strong>Python</strong> — Used in supporting IoT data-processing workflows<br/><br/>
      <strong>Communication & Protocols</strong><br/>
      • MQTT &bull; HTTP &bull; I2C &bull; SPI
    </td>
    <td width="50%" valign="top">
      <strong>Hardware & Development Tools</strong><br/>
      • Sensor and actuator integration<br/>
      • Digital multimeter<br/>
      • Arduino IDE &bull; ESP-IDF &bull; ST-Link<br/>
      • Git & GitHub<br/><br/>
      <strong>IoT Platforms</strong><br/>
      • ThingsBoard<br/>
      • Mosquitto MQTT Broker
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

### 1. [PAMSIMAS Multi-Node Smart Water Meter](https://github.com/Firman270/smart-water-meter)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![AES-128-CBC](https://img.shields.io/badge/AES--128--CBC-2E7D32?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ThingsBoard](https://img.shields.io/badge/ThingsBoard-305680?style=flat-square)

An IoT-based smart water metering system designed to monitor water consumption and improve telemetry reliability.

<details>
  <summary><strong>View Technical Contributions & Experimental Results</strong></summary>
  <br/>
  <strong>My contributions:</strong>
  <ul>
    <li><strong>Node & Sensor Integration:</strong> Developed and integrated ESP32-based water meter nodes using YF-B1 flow sensors.</li>
    <li><strong>Telemetry Processing:</strong> Implemented water flow measurement and telemetry processing.</li>
    <li><strong>Adaptive Sending Interval:</strong> Worked on adaptive telemetry intervals to reduce unnecessary data transmission.</li>
    <li><strong>Data Resilience:</strong> Implemented backlog recovery to resend stored data after connectivity interruptions.</li>
    <li><strong>End-to-End Security:</strong> Integrated AES-128-CBC encrypted telemetry with a Python decryption bridge.</li>
    <li><strong>Cloud Visualization:</strong> Integrated device telemetry with ThingsBoard.</li>
  </ul>
  <blockquote>
    <strong>Experimental Results:</strong> Successfully tested communication involving <strong>two ESP32 nodes</strong>, recorded <strong>21,270 unique telemetry records</strong>, and recovered <strong>128 backlog records</strong> during connectivity interruption testing.
  </blockquote>
</details>

---

### 2. [Smart Parking System](https://github.com/Firman270/smart-parking-system)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-00878F?style=flat-square&logo=espressif&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![ThingsBoard](https://img.shields.io/badge/ThingsBoard-305680?style=flat-square)
![Telegram Bot](https://img.shields.io/badge/Telegram_Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white)

An IoT-based parking management system that monitors parking slot availability and assists vehicle allocation.

<details>
  <summary><strong>View Technical Contributions</strong></summary>
  <br/>
  <strong>My contributions:</strong>
  <ul>
    <li><strong>Multi-Node Firmware:</strong> Developed firmware for ESP32 central control and ESP8266 sensor nodes.</li>
    <li><strong>Sensor & Messaging:</strong> Integrated parking sensors and MQTT communication.</li>
    <li><strong>Allocation Logic:</strong> Implemented parking block recommendation logic.</li>
    <li><strong>Actuators & UI:</strong> Integrated servo-based barrier control and display interfaces.</li>
    <li><strong>Platform Integration:</strong> Connected the system to ThingsBoard and Telegram Bot.</li>
    <li><strong>Hardware Validation:</strong> Handled hardware assembly, system integration, troubleshooting, and testing.</li>
  </ul>
</details>

---

### 3. [Digital Scoliometer](https://github.com/Firman270/scoliometer-digital)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![MPU6050](https://img.shields.io/badge/MPU6050-455A64?style=flat-square)
![LCD 16x4](https://img.shields.io/badge/LCD_16x4-0277BD?style=flat-square)
![Kalman Filter](https://img.shields.io/badge/Kalman_Filter-6A1B9A?style=flat-square)
![Laravel API](https://img.shields.io/badge/Laravel_API-FF2D20?style=flat-square&logo=laravel&logoColor=white)

A digital measurement device prototype designed to measure the Angle of Trunk Rotation (ATR).

<details>
  <summary><strong>View Technical Contributions</strong></summary>
  <br/>
  <strong>My contributions:</strong>
  <ul>
    <li><strong>Embedded Hardware:</strong> Integrated ESP32 with MPU6050 sensor and LCD 16x4.</li>
    <li><strong>Signal Filtering:</strong> Worked on sensor data processing using a Kalman filter.</li>
    <li><strong>User Interface:</strong> Implemented physical button controls for measurement operations.</li>
    <li><strong>Backend Sync:</strong> Integrated device communication with a Laravel-based API.</li>
    <li><strong>PCB & Power:</strong> Worked on hardware wiring, PCB design, and battery monitoring.</li>
  </ul>
</details>

---

## 📚 Currently Learning & Connecting

<table>
  <tr>
    <td width="55%" valign="top">
      <strong>Currently Focusing On</strong><br/>
      • Embedded firmware development with C/C++<br/>
      • STM32 development and peripheral integration<br/>
      • Embedded systems debugging and testing<br/>
      • IoT communication and device security<br/>
      • Hardware-software integration
    </td>
    <td width="45%" valign="top">
      <strong>Connect With Me</strong><br/>
      • <strong>GitHub:</strong> <a href="https://github.com/Firman270">github.com/Firman270</a><br/>
      • <strong>LinkedIn:</strong> <a href="https://linkedin.com/in/fir-man-33a820370">linkedin.com/in/fir-man-33a820370</a><br/>
      • <strong>Email:</strong> <a href="mailto:firmn030@gmail.com">firmn030@gmail.com</a><br/><br/>
      <em>Interested in embedded systems, IoT development, and engineering projects that connect hardware and software.</em>
    </td>
  </tr>
</table>
