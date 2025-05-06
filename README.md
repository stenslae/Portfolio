# Emma Stensland's Portfolio

Welcome to my GitHub portfolio! Here, you’ll find a variety of projects organized by type, showcasing my skills in Embedded Systems, Data Collection, Data Structure and Algorithm Projects, and Other Projects.

---

## Table of Contents

- [About Me](#about-me)
- [Project Categories](#project-categories)
  - [Embedded Systems](#embedded-systems-projects)
  - [FPGAs](#fpgas-projects)
  - [Data Collection](#data-collection-projects)
  - [Circuit Designs](#circuit-designs)
  - [Data Structures and Algorithms](#data-structures-and-algorithms-projects)
  - [Other](#other-projects)
- [Contact](#contact)

---

## About Me

I’m Emma Stensland, an Electrical Engineering student with a passion for making an impact. I love working on diverse projects and exploring different areas of technology.

---

## Project Categories

Below is an overview of my projects, organized by category. Feel free to explore the different sections based on your interest!

---

### Embedded Systems Projects

These projects highlight my skills in embedded systems design.

#### Project 1: Drill Press Control
- **Description**: Interface a stepper motor with a microcontroller.
- **Technologies**: C, CSS, MSP-EXP430FR2355, Stepper Motor, Analog Discovery 2
- **Key Features**:
  - Actuates a motor using GPIO/Timers
  - Monitors an ADC pressure sensor simulation and compares to a threshold
  - Reads an RTC (I2C)
  - Reports to the user interface (UART)
- **Link**: [GitHub Repository](https://github.com/stenslae/DrillPressControl)

---


### FPGAs Projects

These projects highlight my skills in logic design.

#### Project 1: 8-Bit Microcomputer
- **Description**: Simulate and implement an 8-bit microcomputer onto an FPGA.
- **Technologies**: DE10-Lite FPGA Board with the MAX 10 10M50DAF484C7G Device, VHDL, ModelSim, Quartus
- **Key Features**:
    - Custom ALU supporting basic arithmetic and logic operations
    - 8-bit instruction set with control unit and program counter
    - RAM and ROM modules and memory-mapped I/O
    - Asynchronous reset and clock management logic
- **Link**: [GitHub Repository](https://github.com/stenslae/8_Bit_Microcomputer)

---

### Data Collection Projects

In this section, you’ll find my projects that focus on automation and data collection/processing.

#### Project 1: Battery Pack Testing
- **Description**: This program processes continuous data readings from a battery pack to calculate its total watt-hours. It reads data from a sensor and stores it in a .csv file for further analysis. The program performs essential calculations, preparing the data for post-processing in tools like Google Sheets.
- **Technologies**: C++, LabJack T7, CMake, LJM
- **Key Features**:
  - Reads continuous data and calculates total watt-hours.
  - Outputs data to a .csv file for easy integration with external tools.
  - Prepares data for post-processing in Google Sheets.
- **Link**: [GitHub Repository](https://github.com/stenslae/BatteryPackTesting)

#### Project 2: Shipping Status Checker
- **Description**: A Python script that checks the shipping status of Amazon orders in the last 6 months by scraping the shipping information from an Amazon profile. The program processes a .csv file containing order details, updates it with the current status, and makes it easy to track multiple orders at once.
- **Technologies**: Python, Pandas, Numpy, Selenium
- **Key Features**:
  - Scrapes Amazon order status and updates a .csv file.
  - Automates status tracking for efficiency.
- **Link**: [GitHub Repository](https://github.com/stenslae/Python_ShippingStatusChecker)

#### Project 3: Noise Filtering Demo
- **Description**: This is a program that demonstrates the filtering capabilities of a LabJack T7-Pro by comparing raw data, data with an increased resolution index, averaged data, and thresholded and averaged data.
- **Technologies**: LabVIEW V7.1, Lua, LabJack T7-Pro, Maxbotix Ultrasonic MB7569 Ultrasonic Sensor
- **Key Features**:
  - Read intervals
  - Noise filtering programs and comparisons
- **Link**: [GitHub Repository](https://github.com/stenslae/NoiseFilteringDemo)
- **Full Writeup**: [LabJack Website](https://support.labjack.com/docs/mb7569-maxbotix-ultrasonic-sensor-app-note)

---

### Circuit Designs

These projects highlight my skills in circuit design when given a desired circuit performance.

#### Project 1: Regulator Design
- **Description**: Designed and analyzed a voltage regulator circuit to maintain a constant DC output across varying loads and input voltages, applying small-signal analysis and SPICE simulations.
- **Technologies**: LTspice, Manual Circuit Analysis, Oscilloscope, Digital Multimeter
- **Key Features**: 
  - Simulated performance in LTspice 
  - Built circuit and measured component values to meet target performance
- **Link**: [Full Writeup](https://github.com/stenslae/Portfolio/blob/main/Project_Files/317_regulator_design_problem_stensland.pdf)

#### Project 2: BJT Design
- **Description**: Designed and analyzed a single-stage amplifier using a Bipolar Junction Transistor (BJTs)
- **Technologies**: LTspice, Manual Circuit Analysis, Oscilloscope
- **Key Features**:
  - Frequency response analysis including cutoff frequencies 
  - Verified design through simulation and in-lab measurements
- **Link**: [Full Writeup](https://github.com/stenslae/Portfolio/blob/main/Project_Files/design2_report_stensland%20(2).pdf)

---

### Data Structures and Algorithms Projects

These projects showcase my experience in data structures.

#### Project 1: Maze Solver
- **Description**: Uses recursion to solve mazes.
- **Technologies**: Java
- **Link**: [GitHub Repository](https://github.com/stenslae/MazeSolver)

---

### Other Projects

Here are some additional projects that showcase various other skills, including scripting, automation, and smaller coding challenges.

---

## Contact

Feel free to reach out to me for opportunities or questions about my projects.

- **Email**: [emma@stensland.com](mailto:emma@stensland.com)
