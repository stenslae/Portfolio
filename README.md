# Emma Stensland's Portfolio

Welcome to my GitHub portfolio! Here, you’ll find a variety of projects organized by type, showcasing my skills in Embedded Systems, Data Collection, Data Structure and Algorithm Projects, and Other Projects.

---

## Table of Contents

- [About Me](#about-me)
- [Project Categories](#project-categories)
  - [Embedded Systems](#embedded-systems-projects)
  - [Data Collection](#data-collection-projects)
  - [Data Structures and Algorithms](#data-structures-and-algorithms-projects)
  - [Other](#other-projects)
- [Skills](#skills)
- [Education](#education)
- [Contact](#contact)

---

## About Me

I’m Emma Stensland, an enthusiastic Electrical Engineering student with a passion for making an impact. I love working on diverse projects and exploring different areas of technology.

- 🌱 Currently learning: Linux, Markdown, SQL, Cybersecurity Basics
- 💼 Seeking opportunities in: Embedded Systems, Cybersecurity

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
  - Monitors and ADC pressure sensor simulation and compares to a threshold
  - Reads an RTC (I2C)
  - Reports to the user interface (UART)
- **Link**: [GitHub Repository](https://github.com/stenslae/DrillPressControl)

---

### Data Collection Projects

In this section, you’ll find my projects that focus on project involing automation and data collection/processing.

- #### Project 1: Battery Pack Testing
- **Description**: This program processes continuous data readings from a battery pack to calculate its total watt-hours. It reads data from a sensor and stores it in a .csv file for further analysis. The program performs essential calculations, preparing the data for post-processing in tools like Google Sheets.
- **Technologies**: C++, LabJack T7, CMake, LJM
- **Key Features**:
  - Reads continuous data and calculates total watt-hours.
  - Outputs data to a .csv file for easy integration with external tools.
  - Prepares data for post-processing in Google Sheets.
- **Link**: [GitHub Repository](https://github.com/stenslae/Lua_NoiseReduction)
- **Demo**: [Link to Jupyter Notebook or other demo, if available]

#### Project 2: Analog Input Noise Reduction
- **Description**: A Lua script that performs noise reduction on analog input readings from a LabJack T7 by applying a rolling average and threshold method. The script filters out extreme readings, removing 25% of the highest and lowest values to clean the data using user RAM, read intervals, and arrays.
- **Technologies**: Lua, LabJack T7
- **Key Features**:
  - Interval reads
  - Reading user RAM
  - Noise filtering
- **Link**: [GitHub Repository](https://github.com/stenslae/Lua_NoiseReduction)
- **Full Writeup**: [LabJack Website](https://support.labjack.com/docs/mb7569-maxbotix-ultrasonic-sensor-app-note)

#### Project 3: Shipping Status Checker
- **Description**: A Python script that checks the shipping status of Amazon orders in the last 6 months by scraping the shipping information from an Amazon profile. The program processes a .csv file containing order details, updates it with the current status, and makes it easy to track multiple orders at once.
- **Technologies**: Python, Pandas, Numpy, Selenium
- **Key Features**:
  - Scrapes Amazon order status and updates a .csv file.
  - Automates status tracking for efficiency.
- **Link**: [GitHub Repository](https://github.com/stenslae/Python_ShippingStatusChecker)

---

### Data Structures and Algorithms Projects

These projects showcase my experience in data structures.

#### Project 1: Uno
- **Description**: Uses the stack data structure to emulate a game of uno.
- **Technologies**: Java
- **Link**: [GitHub Repository](https://github.com/stenslae/UnoGame)

#### Project 2: Maze Solver
- **Description**: Uses recursion to solve mazes.
- **Technologies**: Java
- **Link**: [GitHub Repository](https://github.com/yourusername/project-name)

---

### Other Projects

Here are some additional projects that showcase various other skills, including scripting, automation, and smaller coding challenges.

#### Project 1: Noise Filtering Demo
- **Description**: This is a program that demonstrates the filtering capabilities of a LabJack T7-Pro by comparing raw data, data with an increased resolution index, averaged data, and thresholded and averaged data.
- **Technologies**: LabVIEW V7.1, Lua, LabJack T7-Pro, Maxbotix Ultrasonic MB7569 Ultrasonic Sensor
- **Key Features**:
  - Read intervals
  - Noise filtering programs and comparisons
- **Link**: [GitHub Repository](https://github.com/stenslae/NoiseFilteringDemo)
- **Full Writeup**: [LabJack Website](https://support.labjack.com/docs/mb7569-maxbotix-ultrasonic-sensor-app-note)

---

## Education

- **Bachelor of Science in Electrical Engineering**  
  Montana State Univerity, Bozeman
  Expected December 2026 
  Relevant coursework: Data Structures and Algorithms, Logic Design, Microprocesses HW and SW.

---

## Contact

Feel free to reach out to me for collaboration, opportunities, or questions about my projects.

- **Email**: [emma@stensland.com](mailto:emma@stensland.com)
