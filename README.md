# Emma Stensland's Portfolio

Welcome! This portfolio summarizes my public repositories.

---

## 📚 Table of Contents

- [TRNG on FPGA](#trng-on-fpga)
- [Pulsar Side Channel Analysis](#pulsar-side-channel-analysis)
- [Silicon Strip Detector Data Acquisition System](#ssd-data-acquisition-system)
- [📬 Contact](#-contact)

---

### [TRNG on FPGA](https://github.com/stenslae/FPGA-TRNG)
Custom True Random Number Generator implemented on an SoC FPGA.
- **Technologies:** VHDL, MURO ring oscillators, Von Neumann correction, LFSR whitening, Linux userspace & kernel drivers, NIST STS validation
- **Skills:** hardware entropy extraction, cryptographically secure design, statistical validation
- **Results:** Produced a fully validated TRNG IP core with provable statistical randomness
- **[Full Report](https://github.com/stenslae/FPGA_TRNG/blob/main/docs/trng.md)**

![TRNG System Diagram](assets/TRNG_DIAGRAM.png)

### [Pulsar Side-Channel Analysis](https://github.com/stenslae/PulsarSideChannel)
Simulated EM side-channel attacks on pulsar-like signals, including scrambling, leakage analysis, & seed recovery.
- **Technologies:** MATLAB/Octave, Fourier & Hilbert transforms, PRNG-based scrambling, signal processing
- **Skills:** side-channel analysis, spectral fingerprinting, envelope detection, brute-force seed recovery, SNR/noise handling
- **Results:** Demonstrated effective seed recovery under varied noise conditions and analyzed leakage metrics
- **[Full Report](https://github.com/stenslae/PulsarSideChannel/blob/main/pulsar_report.md)**

### SSD Data Acquisition System
Work in progress multi-board system for data acquisition and processing to do advanced silicon strip detector characterization and prototype a CubeSat instrument.
- **Technologies:** FPGA, 8-channel 16-bit ADCs, custom differential ZCD & peak follower
- **Skills:** high-speed analog design, synchronized data acquisition
- **Results:** ~200kHz bandwidth, 20mV–5V dynamic range

![Top Level](assets/QUACK_DAQ.png)

![Analog Signal Processing](assets/QUACK_DAQ_B.png)

---

## 📬 Contact

Feel free to reach out:  

- 📧 **Email**: [emma@stensland.com](mailto:emma@stensland.com)
