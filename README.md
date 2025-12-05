# Emma Stensland's Portfolio

Welcome to my GitHub! This portfolio highlights my favorite projects, and links to documented repositories.

---

## 📚 Table of Contents

- [🛡️ Security Projects](#-security-projects)  
- [⚡ Embedded Systems](#-embedded-systems)  
- [🔌 DAQ & PCB Design](#-daq--pcb-design)
- [💥 Other](#-other)
- [📬 Contact](#-contact)  

---

## 🛡️ Security Projects

Projects relevant to cybersecurity.  

#### 🔀 [TRNG on FPGA](https://github.com/stenslae/FPGA_TRNG)
- Custom True Random Number Generator IP Core on an FPGA.  
- **Technologies**: VHDL, FPGA, NIST STS, MUROs, Von Neumman Correction, LFSR Whitening, HPS-Fabric interfacing, Linux userspace and kernel driver interfacing  
- **Key Skills**: hardware entropy extraction and statistical validation, hardware-based security, symmetric encryption
- **[Full Report](https://github.com/stenslae/FPGA_TRNG/blob/main/docs/trng.md)**

#### 🌌 [Pulsar Side-Channel Analysis](https://github.com/stenslae/PulsarSideChannel)
- Analysis of pulsar-like signals to detect leakage after time-domain scrambling and recover obfuscation seeds via brute-force.
- **Technologies:** MATLAB/Octave, signal processing, Fourier & Hilbert transforms, PRNG-based scrambling
- **Key Skills:** side-channel analysis, spectral fingerprinting, envelope detection, brute-force seed recovery, SNR/noise handling
- **[Full Report](https://github.com/stenslae/PulsarSideChannel/blob/main/pulsar_report.md)**

#### 📝 [Client-Server Encryption](https://github.com/stenslae/EncryptedPattern)
- Simulation of asymmetric signature verification and symmetric encryption in a client-server setup.  
- **Technologies**: C, Bash, OpenSSL 
- **Key Skills**: digital signatures, cryptography, TCP sockets  

---

## ⚡ Embedded Systems

Projects using microcontrollers and FPGAs.

#### 🛠️ [Instrument Simulator for REAL Flatsat](https://github.com/stenslae/InstrumentSim)  
- Teensy 4.1 simulator for cubesat instrument telemetry.  
- **Technologies**: C/C++, Teensy, UART  
- **Key Features**: command packet processing, telemetry output, robust OBC testing  

---

## 🔌 DAQ & PCB Design

Projects using analog electronics, data acquisition, and PCB design.  

#### ⚡ High-Speed Detector Data Acquisition *(Coming Soon)*  
- Multi-board backplaned data acquisition system PCBs for the W1 Silicon Strip Detector. The full implementation of the 3-Input Test Board.  
- **Technologies**: FPGA, 8-channel simultaneous 16-bit delta-sigma ADCs, custom differential ZCD & peak follower  
- **Key Features**: ~200kHz bandwidth, 20mV-5V dynamic range

#### ☢️ [3 Input Test Board](https://github.com/stenslae/3InputTestBoard)  
- PCB for W1 Silicon Strip Detector characterization.  
- **Technologies**: Altium, LTSpice, Analog Design, Soldering  
- **Key Features**: analog filtering, shielding, 3 channels with preamplifiers & Gaussian shapers
- **[Full Report](https://github.com/stenslae/3InputTestBoard/blob/main/Docs/quackems_test_board_operation.pdf)**

---

## 💥 Other

#### 🎥 [Firmware & Embedded Security Video](https://youtu.be/J5bsz8OYWcQ)  
- Video essay explaining secure boot, chain of trust, OTA updates, vulnerabilities, and countermeasures.  
- **Key Skills**: root of trust, multi-stage bootloader verification, local & remote attestation, OTA security practices  

---

## 📬 Contact

Feel free to reach out:  

- 📧 **Email**: [emma@stensland.com](mailto:emma@stensland.com)
  
