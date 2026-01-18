# Emma Stensland's Portfolio

Welcome! This portfolio organizes my favorite projects by their most relevant application: embedded, software, or hardware. Each repository for the project includes source code and relevant documentation.

---

## 📚 Table of Contents

- [🛡️ Embedded Systems](#-embedded-systems-projects)
  - [TRNG on FPGA](#-trng-on-fpga)
  - [Instrument Simulator for REAL Flatsat](#-instrument-simulator-for-real-flatsat)
  - [Secure Boot and OTA Updates Video](#-secure-boot-and-ota-updates-video)
- [🖥️ Software Systems](#-low-level-software-systems)
  - [Encrypted Patterns](#-encrypted-patterns)
- [⚡ Hardware Systems](#-hardware-systems-projects)
  - [Pulsar Side Channel Analysis](#-pulsar-side-channel-analysis)
  - [Silicon Strip Detector Characterization Board](#-ssd-characterization-board)
  - [Silicon Strip Detector Data Acquisition System](#-ssd-data-aquisition-system)
- [⚙️ Other Projects](#-other-projects)
  - [Industrial Control Systems Security Report](#-ics-security-report)
- [📬 Contact](#-contact)

---

## 🛡️ Embedded Systems Projects

### 🔀 [TRNG on FPGA](https://github.com/stenslae/FPGA-TRNG)
Custom True Random Number Generator implemented on an SoC FPGA.
- **Technologies:** VHDL, MURO ring oscillators, Von Neumann correction, LFSR whitening, Linux userspace & kernel drivers, NIST STS validation
- **Skills:** hardware entropy extraction, cryptographically secure design, statistical validation
- **Results:** Produced a fully validated TRNG IP core with provable statistical randomness
- **[Full Report](https://github.com/stenslae/FPGA_TRNG/blob/main/docs/trng.md)**

![TRNG System Diagram](assets/TRNG_DIAGRAM.png)

### 🛠️ [Instrument Simulator for REAL Flatsat](https://github.com/stenslae/InstrumentSim)  
Teensy 4.1 simulator for MSU's REAL CubeSat instrument telemetry.  
- **Technologies**: C/C++, Teensy, UART  
- **Skills**: command packet processing (CCSDS), CRC-CCITT-16, telemetry output, robust OBC testing
- **Results:** Enables hardware-in-the-loop testing

### 🎥 [Secure Boot and OTA Updates Video](https://youtu.be/J5bsz8OYWcQ)
This video essay dives into firmware/embedded security topics.
- **Skills:** hardware root of trust, multi-stage boot verification, local & remote attestation, OTA vulnerabilities & security practices

---

## 🖥️ Low-Level Software Systems

### 📱 [Encrypted Patterns](https://github.com/stenslae/EncryptedPattern)
TCP based polling server demo that uses symmetric and asymmetric encryption and vulnerability exploration in networked applications.
- **Technologies:** C, OpenSSL, TCP sockets, AES, EC keys, getopt
- **Skills:** Encryption (AES, EC), TCP client-server communication, vulnerability analysis, denial-of-service (DoS) attacks
- **Results:** Explored and demonstrated multiple vulnerabilities caused by poor client-server design, with mitigation suggestions.

---

## 🔌 Hardware Systems Projects

### 🌌 [Pulsar Side-Channel Analysis](https://github.com/stenslae/PulsarSideChannel)
Simulated EM side-channel attacks on pulsar-like signals, including scrambling, leakage analysis, & seed recovery.
- **Technologies:** MATLAB/Octave, Fourier & Hilbert transforms, PRNG-based scrambling, signal processing
- **Skills:** side-channel analysis, spectral fingerprinting, envelope detection, brute-force seed recovery, SNR/noise handling
- **Results:** Demonstrated effective seed recovery under varied noise conditions and analyzed leakage metrics
- **[Full Report](https://github.com/stenslae/PulsarSideChannel/blob/main/pulsar_report.md)**

### ☢️ [SSD Characterization Board](https://github.com/stenslae/SSD-CharacterizationBoard)
Analog PCB for silicon strip detector readout and characterization.
- **Technologies:** Altium, LTSpice, Analog Circuit Design, Soldering
- **Skills:** analog filtering, shielding
- **Results:** Successfully routed 3-channel analog front-end and made a usage guide for live radiation testing
- **[Full Report](https://github.com/stenslae/3InputTestBoard/blob/main/Docs/quackems_test_board_operation.pdf)**

![Test Altium Layout](assets/QUACK_TEST.png)

### ⚡ SSD Data Acquisition System
Work in progress multi-board system for data acquisition and processing to do advanced silicon strip detector characterization and prototype a CubeSat instrument.
- **Technologies:** FPGA, 8-channel 16-bit ADCs, custom differential ZCD & peak follower
- **Skills:** high-speed analog design, synchronized data acquisition
- **Results:** ~200kHz bandwidth, 20mV–5V dynamic range

![Top Level](assets/QUACK_DAQ.png)

![Analog Signal Processing](assets/QUACK_DAQ_B.png)

---

## ⚙️ Other Projects 

### 💥 [ICS Security Report](https://github.com/stenslae/SecurityWriteups/blob/main/Notes_And_Reports/ICS/pera.md)
This report explains how the Purdue Enterprise Reference Architecture (PERA) model works, then maps key vulnerabilities and mitigations at each layer. Additional models, real-life exploits, and network access control are discussed.
- **Skills:** threat modeling, risk analysis, enterprise attack examples, CIA triad, systems & controls, IT/OT convergence

---

## 📬 Contact

Feel free to reach out:  

- 📧 **Email**: [emma@stensland.com](mailto:emma@stensland.com)
