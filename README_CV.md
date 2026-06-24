# Sumin Seo — Academic CV

**Chemical Engineering, Sungkyunkwan University**
📧 pandamin52@naver.com | 📱 +82-10-4793-5649 | 📍 Suwon, South Korea

---

## Objective

Chemical engineering student with hands-on experience in semiconductor device fabrication and PLC data analysis. Focused on bridging industrial control systems with machine learning to build anomaly detection, fault diagnosis, and predictive maintenance solutions for smart factory environments.

---

## Education

**Sungkyunkwan University** — B.S. in Chemical Engineering
Mar 2022 – Feb 2027 (Expected) | GPA: 4.33 / 4.5

- Relevant Coursework: Reaction Engineering, Chemical Engineering Thermodynamics, Semiconductor Chemical Engineering, Process Control and Design, Smart Factory Capstone Design

---

## Experience

**Seoul National University** — Research Intern
Dec 2025 – Feb 2026

- Fabricated MoS₂ FET devices via hypotaxy-based processes (wafer cleaning, metal deposition, graphene transfer, plasma treatment)
- Performed contact engineering through graphene transfer to improve device integration
- Characterized device performance via transfer and output I-V measurements
- Verified single-crystal structure using TEM analysis; observed measurable improvements in channel performance

---

## Capstone Design Project

**RT-FAD: Response Time-Based Fault Diagnosis Framework for PLC-Controlled Pneumatic Systems**
Mar 2026 – Jun 2026 | Smart Factory Capstone Design, Sungkyunkwan University | Team 7

### Summary

In smart factory environments, unplanned downtime caused by pneumatic actuator failures is a critical challenge. Existing PLC-based fault detection methods are limited by fixed thresholds, single-axis analysis, and inability to classify fault types without additional sensors.

This project proposes **RT-FAD**, a real-time fault diagnosis framework that uses only PLC-internal response time data (Δt = T_sent − T_start) from 15 pneumatic cylinder axes (D2000–D2014) collected at 100ms intervals. The system combines Z-score-based spike detection and LSTM Autoencoder-based drift detection in a dual-detection structure, followed by a rule-based classifier that identifies fault type and severity. A parallel workpiece anomaly detection module cross-validates load registers (D100–D400) against presence sensors (X207–X20A) to detect six types of material flow anomalies.

**Key results:**
- Real data collected: 165 normal samples, 295 compressor-off samples from Mitsubishi Q02HCPU PLC
- 3,000 synthetic samples generated for air hose aging and disconnection scenarios
- 22 unit tests: PASS 22 / FAIL 0
- No additional hardware required — software-only predictive maintenance on existing PLC infrastructure

**My role:** Anomaly detection SW development for pneumatic systems

**Team:** 문준상 (PLC/HMI), 안광현 (공압 이상탐지 SW), 민경원 (재하 이상탐지 SW), 서현교 (재하 이상탐지 SW), 서수민 (공압 이상탐지 SW)

---

## Research Outcomes

### Software Registration (SW Copyright)

| Item | Details |
|------|---------|
| Title | PLC 제어 공압 설비의 응답 시간 기반 고장 진단 프레임워크 RT-FAD |
| Registration No. | 2026-037020 |
| Registration Date | 2026-06-16 |
| Registrant | 성균관대학교 산학협력단 (Representative: 서수민) |
| Issuer | 한국저작권위원회 |

### Invention Disclosure (Patent Pending)

| Item | Details |
|------|---------|
| Title | PLC 응답 시간 및 재하 데이터 기반 공압 실린더 고장 진단 및 노후화 탐지 시스템 (RT-FAD) |
| Status | Invention report submitted (patent application in progress) |
| Key Claims | Sensor-free fault diagnosis using PLC internal Δt and load data; dual detection (Spike + Gradual); 3-level alert classification |
| Inventors | 문준상, 안광현, 민경원, 서현교, 서수민 |

---

## Publications

### Team Paper (In Preparation — To Be Submitted)

**RT-FAD: A Real-Time Fault Diagnosis Framework for PLC-Controlled Pneumatic Systems Using Response Time Features**

Junsang Moon, Gwanghyeon An, Gyeongwon Min, Hyungyo Seo, **Sumin Seo**

*Manuscript in preparation, 2026*

**Abstract (planned):** In smart factory environments, PLC-controlled pneumatic systems are prone to unplanned downtime, yet existing approaches cannot diagnose multiple fault types simultaneously without additional sensors. This paper proposes RT-FAD, which extracts pneumatic cylinder response time (Δt) as a single feature from PLC ladder logic and combines Z-score-based spike detection with LSTM Autoencoder-based drift detection in a dual-detection structure. A rule-based classifier then identifies six fault classes in real time. Experiments on a Mitsubishi Q02HCPU-based 4-station rotary index table target F1-score ≥ 0.90 across all fault classes and Compressor Recall of 100%, with Recall +12%p and Precision +8%p improvement over single-detector baselines via Ablation Study. The framework requires no additional hardware and is immediately deployable on existing PLC infrastructure.

---

## Team Assignment — Literature Review & Code Implementation

**Reviewed Paper:** Wojtulewicz, A.; Chaber, P. "Industrial Robot Control System with a Predictive Maintenance Module Using IIoT Technology." *Sensors*, 25(4), 1154, 2025.
[https://doi.org/10.3390/s25041154](https://doi.org/10.3390/s25041154)

- Reviewed a PLC-based predictive maintenance system using IIoT/MQTT architecture for industrial robots
- Reproduced the predictive maintenance logic (grease/belt/gear/bearing consumption functions) in Python as a team implementation exercise

---

## Individual Assignment — Literature Review, Implementation & Presentation

**Reviewed Paper:** Zubieta, J. et al. "Step-time measurement: A scalable sub-cycle time defining methodology for anomaly detection and predictive maintenance in sequential production lines." *Journal of Manufacturing Systems*, 83, 2025.
[https://doi.org/10.1016/j.jmsy.2025.08.011](https://doi.org/10.1016/j.jmsy.2025.08.011)

- Reviewed the Step-time methodology for scalable sub-cycle time measurement in PLC-based sequential production lines
- Independently reimplemented the anomaly detection pipeline in Python based on the paper
- Prepared and delivered a presentation summarizing the methodology, implementation, and key findings

---

## Skills

**Programming:** Python, MATLAB

**Data Analysis & ML:** Time-series analysis, Anomaly detection (Z-score, LSTM Autoencoder), Regression (CSTR dynamic modeling)

**Industrial / PLC:** Mitsubishi GX Works2, MX Component Ver.4, PLC data analysis

**Semiconductor Processing:** Lithography, Deposition, Device characterization (I-V, TEM)

**Tools:** Excel, Git

---

## Honors & Awards

| Award | Institution | Date |
|-------|------------|------|
| Academic Excellence Scholarship (Highest Distinction) | Sungkyunkwan University | Sep 2022 |
| Academic Excellence Scholarship | Sungkyunkwan University | Sep 2025 |

---

## Certifications

| Certification | Date |
|--------------|------|
| Computer Specialist in Spreadsheet & Database (Level 2) | Jul 2024 |
| OPIc IH (Intermediate High) | Sep 2025 |

---

## Leadership

**Music Director** — Gukak Club, Sungkyunkwan University | Mar – Jun 2024
- Led weekly rehearsals and musical coordination; managed end-to-end performance preparation

**Event Organizer & MC** — Student Council MT, Sungkyunkwan University | 2024
- Planned and executed the full event program; hosted recreation sessions as MC

---

## Additional Information

**Languages:** Korean (Native), English (OPIc IH)

**Interests:** Semiconductor Process Engineering, Data Analysis, Badminton
