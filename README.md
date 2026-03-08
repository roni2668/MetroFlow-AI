
# 🚀 MetroFlow AI: High-Performance Traffic Reliability System

### **A Cross-Platform Edge-AI Suite (C++ | Python | JavaScript)**

**MetroFlow AI** is a 10-module engineering framework designed to quantify urban traffic "unreliability." Moving beyond simple average speeds, this system calculates the **Buffer Index (BI)** and **Planning Time Index (PTI)** to predict congestion shocks and their associated economic impact on modern infrastructure.

---

## 🛠️ Tech Stack & Requirements

* **Low-Level Systems:** C++17 (G++ Compiler), STL, Math.h
* **Intelligence Layer:** Python 3.12, TensorFlow 2.x, Scikit-Learn, Pandas, NumPy
* **Visualization:** Plotly Express, Mapbox API, Chart.js, Seaborn
* **Environment:** VS Code, Kaggle Kernels (XLA/CUDA optimized)

---

## 📂 Modular Architecture (1-10)

### **Phase 1: The Edge Computing Kernel**

* **Module 1: Physics-Based Pre-processor (C++):** Calculates $95^{th}$ percentile speeds to define the "Reliability Gap."
* **Module 7: Monte Carlo Stress Simulator (C++):** Generates 10,000 random "Shock Events" to test system resilience.

### **Phase 2: Predictive Intelligence & Feature Engineering**

* **Module 2: BI/PTI Formalization:** Transforms raw sensor data into actionable reliability indices.
* **Module 3: LSTM Neural Network:** A deep learning model trained to forecast future $BI$ values using a sliding window approach.
* **Module 8: Economic Opportunity Cost:** Translates abstract traffic variance into the "Value of Lost Time" (VOT) in USD.

### **Phase 3: Geospatial & Sensitivity Analysis**

* **Module 4: Predictive Risk Heatmap:** A high-contrast GIS map showing where the LSTM predicts the next breakdown.
* **Module 9: Gradient Sensitivity Analysis:** Calculates $\frac{d(PTI)}{d(Speed)}$ to find the mathematical "tipping point" of road failure.

### **Phase 4: The Executive Dashboard (Full-Stack)**

* **Module 5: Live Inference Terminal (JS):** A real-time terminal simulating data packets flowing from the C++ kernel.
* **Module 10: Commuter Loss Widget (JS):** An interactive calculator for users to determine personal financial loss.

### **Phase 5: Final Analytics**

* **Module 6: Regression & Portfolio Metadata:** Final correlation analysis between speed variance and road health.

---

## 🏆 Key Debugging Milestones

* **KeyError Resolution:** Implemented dynamic column mapping for dataset flexibility.
* **Zero-Division Fix:** Handled mathematical singularities in Gradient calculations via data deduplication.
* **Keras 3 Optimization:** Migrated to explicit `Input(shape)` layers for future-proof model compatibility.

---

## 🖼️ Results Obtained (Gallery)

> 

### **1. Edge-AI Kernel Execution (C++)**

Captured from the VS Code Terminal showing the high-speed processing of sensor data.

> **<img width="490" height="302" alt="image" src="https://github.com/user-attachments/assets/92f0da89-d143-4167-aea7-f3020a86e9cb" />

<img width="488" height="278" alt="image" src="https://github.com/user-attachments/assets/17689bba-079c-467c-87ab-230b14a20adc" />

**

### **2. Deep Learning Training (LSTM)**

Visualization of the model convergence and the resulting economic loss distribution.

> **<img width="521" height="295" alt="image" src="https://github.com/user-attachments/assets/877b6cf2-cfc2-4b3d-9166-2b97886ef971" />

<img width="508" height="312" alt="image" src="https://github.com/user-attachments/assets/275757f1-19ea-4a74-970a-ae612bd79cf1" />

**

### **3. Predictive Geospatial Forecast**

The interactive Mapbox view and the calculus-based sensitivity line graph.

> **<img width="521" height="263" alt="image" src="https://github.com/user-attachments/assets/14057894-0d6c-457c-b163-ac43f8ddb882" />

<img width="499" height="317" alt="image" src="https://github.com/user-attachments/assets/28a8cfe0-5f9c-4659-b635-1b4e4c598041" />

**

### **4. Real-Time Executive Dashboard**

The final user-facing interface including the trend-line forecast and the financial loss calculator.

> **<img width="407" height="191" alt="image" src="https://github.com/user-attachments/assets/3999ae57-7e82-487a-9360-cec3ea0c292e" />

<img width="351" height="179" alt="image" src="https://github.com/user-attachments/assets/fd720ab5-9007-40cd-9ae7-a160f88cabf3" />

**

---

## 🚀 How to Run in VS Code

1. **C++ Engine:**
```bash
g++ -O3 cpp_engine/traffic_engine.cpp -o engine
./engine

```


2. **Python Analytics:**
```bash
pip install tensorflow pandas plotly scikit-learn
python python_core/main_analysis.py

```


3. **JS Dashboard:**
* Right-click `web_interface/index.html` and select **"Open with Live Server"**.



---

## 📊 Project Executive Summary Table

| Phase | Modules | Tech Stack | Core Engineering Deliverable |
| --- | --- | --- | --- |
| **I. Data Ingestion** | 1, 7 | **C++** | High-speed Statistical Moment Extraction & Monte Carlo Shocks |
| **II. Feature Eng.** | 2, 8 | **Python** | Reliability Metric Formalization (BI/PTI) & Economic VOT Analysis |
| **III. Deep Learning** | 3 | **Python** | Multi-layer LSTM Time-Series Forecasting |
| **IV. Geospatial** | 4, 9 | **Python** | GIS Risk Heatmapping & Calculus-based Sensitivity Analysis |
| **V. Interactive UI** | 5, 10 | **JS/HTML** | Real-Time Inference Terminal & Commuter Loss Dashboard |
| **VI. Finalization** | 6 | **Python** | Model Metadata & Performance Regression Analysis |

---

**Developed by [Roni Mandal]** 


