# Emma Stensland's Portfolio

Welcome to my GitHub! I'm Emma, an Electrical Engineering student with a love for problem-solving. Here, you'll find a variety of my favorite projects that I have done.

---

## 📚 Table of Contents

- [📁 Project Categories](#-project-categories)
  - [🧠 Microcontrollers](#-microcontroller-projects)
  - [💖 FPGAs](#-fpgas-projects)
  - [📊 Data Collection](#-data-collection-projects)
  - [🔌 Circuit Designs](#-circuit-designs)
  - [🧰 Other Projects](#-other-projects)
- [📬 Contact](#-contact)

---

## 📁 Project Categories
Take a look at the types of projects I’ve worked on so far:

---

### 🧠 Microcontroller Projects

#### 🛠️ [Drill Press Control](https://github.com/stenslae/DrillPressControl)
- Interfaces a stepper motor with a microcontroller for pressure-aware drilling.
- **Technologies**: C, MSP430, ADC, UART, I2C, Real-Time Clock
- **Key Features**:
  - Motor actuation
  - Pressure monitoring with threshold detection
  - Real-time logging via UART
  - Rolling average filtering and safety alarms

#### 🛠️ [Instrument Simulator for REAL Flatsat](https://github.com/stenslae/InstrumentSim)
- Simulates the REAL cubesat instrument on a Teensy 4.1 for development and testing.
- **Technologies**: C/C++, Teensy 4.1, UART Serial Communication, CRC-CCITT16
- **Key Features**:
  - Processes incoming command packets from the On-Board Computer (OBC).
  - Verifies data integrity with 16-bit CCITT CRC checksum.
  - Outputs telemetry packets via serial communication.
  - Enables robust validation of OBC functionality without an actual instrument.

---

### 💖 FPGAs Projects

#### 🧮 [8-Bit Microcomputer](https://github.com/stenslae/8_Bit_Microcomputer)
- Simulated and implemented a simple 8-bit computer.
- **Technologies**: VHDL, ModelSim, Quartus, DE10-Lite FPGA
- **Key Features**:
  - Custom ALU and instruction set
  - RAM/ROM and I/O control
  - Clock/reset logic

---

### 📊 Data Collection Projects

#### 🔋 [Battery Pack Testing](https://github.com/stenslae/BatteryPackTesting)
- Monitors voltage drop across a load to compute battery capacity.
- **Technologies**: C++, LabJack T7, CSV output, LJM
- **Key Features**:
  - CSV export of voltage data
  - Automated energy calculation (Wh, mAh)

#### 📉 [Noise Filtering Demo](https://github.com/stenslae/NoiseFilteringDemo)
- Demonstrates filtering techniques using a LabJack T7-Pro.
- **Technologies**: LabVIEW, Lua, MB7569 Ultrasonic Sensor
- **Key Features**:
  - Compare raw vs filtered vs thresholded data
  - Real-time read intervals  
- 📝 [Full Writeup](https://support.labjack.com/docs/mb7569-maxbotix-ultrasonic-sensor-app-note)

---

### 🔌 Circuit Designs

#### ☢️ [3 Input Test Board](https://github.com/stenslae/3InputTestBoard)
- Designed and assembled a PCB to process signals from a W1 Silicon Strip Detector. Used to characterize the detector.
- **Technologies**: Altium, LTSpice Analog Circuit Design, Soldering, LaTeX
- **Key Features**:
  - Analog filtering and electrical shielding
  - 3 Input Channels with preamplifiers and gaussian shapers

#### 🔧 [Voltage Regulator Design](https://github.com/stenslae/Portfolio/blob/main/Project_Files/317_regulator_design_problem_stensland.pdf)
- Built and analyzed a DC voltage regulator.
- **Technologies**: LTspice, Oscilloscope, DMM
- **Key Features**:
  - Simulations and real-world measurements
  - Response to varying loads

#### 📡 [BJT Amplifier Design](https://github.com/stenslae/Portfolio/blob/main/Project_Files/design2_report_stensland%20(2).pdf)
- Designed a single-stage amplifier using BJT transistors.
- **Technologies**: LTspice, Circuit Analysis, Oscilloscope
- **Key Features**:
  - Frequency response
  - Simulation-to-lab verification

---

### 🧰 Other Projects
This is where I store any other interesting projects I've done!

---

## 📬 Contact
Feel free to reach out to me for opportunities or questions about my projects:

- 📧 **Email**: [emma@stensland.com](mailto:emma@stensland.com)
