# 🏎️ F1 Telemetry & Advanced Race Analytics 

A full-stack sports analytics project using **Python** and the **FastF1 API** to extract, analyze, and visualize Formula 1 telemetry data.

This project moves beyond basic statistics to perform **Diagnostic** and **Predictive Analytics**, using real-world engineering techniques to deconstruct driver performance, tyre strategy, and car physics.

## 🚀 Features & Modules

### 📊 Level 1: Telemetry & Performance
* **Gap Analysis:** Calculated the precise time delta between two drivers (e.g., VER vs. LEC) over every meter of the lap to pinpoint exactly where time was gained or lost.
* **Speed Trace Comparison:** Overlaid velocity profiles to identify cornering speeds and braking points.

### 🗺️ Level 2: Track Dominance
* **Dominance Map:** Generated a GPS track map color-coded by driver speed, visualizing exactly which track segments belong to which car (Red vs. Blue).
* **Gear Shift Map:** Visualized gear selection around the circuit to analyze engine torque usage and driving styles (short-shifting vs. high-RPM rotation).

### 🧠 Level 3: Strategy & Race Pace
* **Tyre Degradation Analysis:** Plotted lap times across the entire race to visualize the "crossover point" of tyre wear vs. fuel burn.
* **Race Trace (Gap to Leader):** Visualized the narrative of the entire Grand Prix, showing pit windows, battles for position, and relative pace to the race leader.

### 🏎️ Level 4: Physics & Engineering
* **Driver Inputs (Telemetry Traces):** Analyzed Throttle and Brake traces for specific corners to reveal distinct driving styles (e.g., "V-Style" late braking vs. "U-Style" momentum driving).
* **Friction Circle (G-G Diagram):** Calculated Longitudinal vs. Lateral G-Forces to visualize the traction circle and car performance envelope.
* **Corner Analysis Table:** Automated script to extract and compare minimum Apex Speeds for every corner on the track.

### 🤖 Level 5: Advanced / Experimental
* **The "Frankenstein" Lap:** Calculated the theoretical "Perfect Lap" by stitching together the best individual sectors from the entire grid to benchmark actual Pole Position performance.
* **ML Corner Clustering:** Used **K-Means Clustering (Unsupervised Learning)** to automatically categorize track corners into "Low Speed," "Medium Speed," and "High Speed" clusters based on telemetry data.
* **Ghost Car Animation:** Rendered a frame-by-frame race animation of two drivers competing in real-time.

---

## 🛠️ Tech Stack
* **Core Library:** `FastF1` (Official F1 Live Timing API wrapper)
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Machine Learning:** `Scikit-learn` (K-Means Clustering)
* **Environment:** Jupyter Notebook / Google Colab

---
