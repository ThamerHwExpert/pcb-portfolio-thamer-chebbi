# PCB & Hardware Design Portfolio – Thamer Chebbi

This portfolio reflects how I approach hardware design: clear architecture, disciplined routing, and practical solutions shaped by real constraints. The examples shown here are redacted and conceptual, but the engineering decisions, methods, and process are authentic.

---

## 🔧 About Me

I am a Senior Hardware & PCB Design Engineer with experience in high-speed digital, mixed-signal, and power-electronics systems across industrial, automotive, and aerospace-related projects.  
My focus areas include:

- High-speed interfaces (LVDS, MIPI, PCIe, DDR, Ethernet RMII)  
- Industrial communication (RS485, RS232, CAN, UART, SPI, I²C)  
- Power electronics (DC/DC converters, LDO rails, CubeSat EPS subsystems)  
- EMI/EMC-aware design, filtering, grounding, and protection  
- Multilayer PCB routing (4–8 layers, HDI, BGA fanout, impedance control)  

This repository showcases **how I think**, not confidential files.  
Everything shown is safe, redacted, and recreated for portfolio purposes.

---

## 📂 Repository Structure

pcb-portfolio-thamer-chebbi/
├── README.md                # You are here
├── case-studies/            # Redacted engineering case studies
│   ├── proj01-multi-protocol-uart/
│   ├── proj02-stm32h757-hmi/
│   ├── proj03-cubesat-eps/
│   └── proj04-agilex3-pcie/
├── diagrams/                # Generic diagrams (block diagrams, stackups, examples)
│   ├── generic-block-diagrams/
│   └── generic-stackups/
└── assets/
    ├── images-redacted/     # Cropped or blurred images (non-identifiable)
    └── templates/           # Markdown templates for future projects



---

## 📘 Case Studies

These case studies are rewritten and redrawn specifically for public presentation.  
They highlight the **engineering reasoning**, not protected design files.

### **1️⃣ Multi-Protocol UART → RS485 / RS232 / LVDS Converter (4-layer)**
A mixed-signal communication module designed for robust industrial environments.  
Focus: differential routing, ESD strategy, failsafe biasing, charge-pump layout.

👉 `case-studies/proj01-multi-protocol-uart/README.md`

### **2️⃣ STM32H757 HMI / Display Controller Board (6-layer)**
High-speed controller with LTDC/DSI interface, external SDRAM, and 24 V industrial front-end.  
Focus: impedance-controlled routing, via-fences, power sequencing.

👉 `case-studies/proj02-stm32h757-hmi/README.md`

### **3️⃣ CubeSat EPS Subsystem (MPPT + Battery Management)**
Redacted version of my academic/industrial space-electronics work.  
Focus: solar array modeling, MPPT strategy, thermal & reliability considerations.

👉 `case-studies/proj03-cubesat-eps/README.md`

### **4️⃣ Agilex 3 PCIe x2 Add-In Card (HDI, high-speed)**
High-speed digital design with differential PCIe lanes, HDI microvias, and power integrity focus.  
Focus: BGA fanout, length-matching, stackup engineering.

👉 `case-studies/proj04-agilex3-pcie/README.md`

---

## 🧠 Engineering Focus Areas

### **🔹 High-Speed PCB Design**
- Differential pairs, impedance control, length matching  
- Return-path planning & stitching via fences  
- Routing PCIe, LVDS, DSI, RMII, SDRAM

### **🔹 Power Electronics**
- Buck converters, LDO rails, USB-PD considerations  
- Thermal management, copper spreading, via arrays  
- MPPT and battery protection in space systems

### **🔹 Signal Integrity & EMC**
- Crosstalk reduction, filtering networks, ESD/TVS placement  
- Common-mode chokes, controlled current return paths  
- Separation of noisy/quiet domains

### **🔹 Industrial Communication**
- RS485 failsafe biasing, termination strategies  
- RS232 charge pumps, noise isolation  
- LVDS signal integrity and cable-driven constraints

---

## 🧱 My Hardware Development Workflow

1. Requirements & architecture  
2. Block diagrams & interface definitions  
3. Schematic capture  
4. PCB stackup planning  
5. Design rules (SI/PI, EMC, mechanical)  
6. Placement strategy  
7. Routing (priority layers, diff pairs, power)  
8. Review (ERC/DRC, SI checks, thermal checks)  
9. Documentation & fabrication outputs  
10. Bring-up, testing, and iteration  

---

## 📄 Portfolio PDF (Optional)

A polished PDF version of this portfolio—including formatted layouts, project summaries, and redacted technical visuals—can be shared upon request.

---

## 📫 Contact

**Thamer Chebbi**  
Senior Hardware / PCB Design Engineer  
📍 Tunisia — open to relocation & remote roles  
🔗 LinkedIn: *https://www.linkedin.com/in/thameur-chebbi-b9157b167/*
📧 Email: *chebbythamer@gmail.com*

---

## ⚠️ Disclaimer

All project files in this repository are **redacted, recreated, or simplified** to avoid sharing proprietary or NDA-protected designs.  
The focus is on illustrating engineering decisions, methods, and layout strategy.

---
