# 🛡️ UI-Guardian SOC
**Zero-Trust Interface Monitoring & Anti-Spoofing Prototype**

## 📌 Overview
**UI-Guardian** is a defensive security prototype designed to mitigate **UI Spoofing** and **Notification-based Phishing**. In modern OS environments, users implicitly trust system-level dialogues. This tool applies a **Zero-Trust** philosophy to the desktop interface by verifying the integrity of active windows against their underlying process metadata.

## 🚀 Key Features
* **Heuristic Detection Engine:** Scans active window titles for high-urgency keywords (e.g., "Update", "Alert", "Critical").
* **Process Path Validation:** Cross-references UI elements with execution paths (e.g., flagging system alerts originating from `\Downloads`).
* **Real-Time Risk Analytics:** Visualizes system-wide risk distribution using **Plotly**-integrated charts.
* **Forensic Logging:** Provides a CSV export feature for incident documentation and SOC analysis.

## 💻 Tech Stack
* **Language:** Python 3.x
* **Interface:** Streamlit (SOC Dashboard)
* **Data Analysis:** Pandas, Plotly
* **System Hooks:** Psutil, PyGetWindow

## 🛠️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/devu-sunija/UI-Guardian-SOC.git](https://github.com/devu-sunija/UI-Guardian-SOC.git)
   
