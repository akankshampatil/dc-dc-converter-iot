# High-Efficiency DC-DC Converter for IoT Devices

> This project focuses on the design and simulation of a high-efficiency buck converter tailored for power-constrained IoT environments. Developed in 180nm CMOS using LTSpice and Cadence Virtuoso, the circuit optimizes transient performance and steady-state efficiency.

---

### 📌 **Project Overview**
- **Objective:** Develop a compact, low-dropout buck converter that operates efficiently under typical IoT load conditions and responds quickly to load transients.
- **Methodology:** Designed a synchronous buck topology in Cadence Virtuoso and LTSpice with appropriate PMOS/NMOS switching transistors, control logic, and compensation networks. Simulated voltage ripple, switching loss, and transient performance.

---

### 💡 **Key Features**
- Peak efficiency of 92% at IoT-class current levels  
- Low ripple (<50mV) and fast settling time  
- Tuned feedback loop for stability and compensation  
- Synchronous design reduces diode losses  

---

### 🧰 **Skills Used**
Power Electronics, Analog Simulation, Transient Response Optimization, Feedback Control

---

### 🧪 **Technologies & Tools**
LTSpice, Cadence Virtuoso, 180nm CMOS PDK

---

### 🔍 **Key Findings**
- Verified converter performance across multiple load profiles.  
- Adjusted switching frequency and inductor values for optimal regulation.  
- Ripple voltage controlled through high-frequency compensation network.

---

### 🎓 **What I Learned**
- How parasitic inductance and ESR affect ripple  
- Trade-offs between efficiency and transient response  
- Designing a compact power converter in deep-submicron technology

---

### 🚀 **Future Work**
- Build PCB prototype and test with real-world IoT sensors  
- Implement auto-mode switching (PWM/PFM) for further savings  
- Integrate this buck converter with a PMIC for a wearable device

---

### 📂 **Files Attached**
dcdc_converter.sch, ltspice_sim.asc, efficiency_plot.png, cadence_netlist.sp
