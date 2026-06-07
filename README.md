# 🚂 AcoustiRail-AI
> **Continuous Autonomous Acoustic Wave Propagation and Predictive Structural Integrity Monitoring for Modern Rail Networks**

---

## 📌 Project Overview
AcoustiRail-AI is an automated, closed-loop hardware-software hybrid network engineered to revolutionize railway safety infrastructure. By combining trackside edge computing nodes with localized AI inference, the system detects sub-surface micro-cracks, fractures, and progressive rail foot wear in under 2 seconds—completely eliminating cloud dependency and operational latency.

## 🛠️ The Technical Pipeline
1. **Raw Audio Ingestion:** High-sensitivity acoustic emission sensors capture live vibrational signals.
2. **Adaptive IIR Noise Filtration:** Removes heavy environmental and ambient locomotive movement background clutter.
3. **FFT Feature Extraction:** Translates physical characteristics into structured spectral energy density distributions.
4. **Edge AI Inference:** A lightweight machine learning classifier processes patterns locally into three definitive profiles:
   * **Class 0:** Normal Baseline (Safe operations)
   * **Class 1:** Surface Wear (Superficial pitting requiring standard maintenance)
   * **Class 2:** Critical Fracture (Immediate risk; fires automated speed restrictions)

## 📁 Repository Structure
* `main.py` - Core Python processing kernel managing the DSP pipeline, noise thresholds, and local classification states.
* `README.md` - Comprehensive documentation and technical architectural summary.

## 👥 Team INS VIKRANT — Core Leadership
* **HIMANSHU RAJ** - Chief Executive Architect & Lead AI Engineer
* **AMMAR** - Director of Git Operations & Version Control
* **ASJAD** - Lead Systems Analyst & Implementation Specialist
