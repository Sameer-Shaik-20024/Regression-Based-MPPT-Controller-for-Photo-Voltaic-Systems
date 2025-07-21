# Regression Based MPPT Controller for Photo-Voltaic Systems



This research project focused on developing and evaluating an intelligent Maximum Power Point Tracking (MPPT) controller for solar PV systems using **Multi-Linear Regression (MLR)**. The aim was to optimize the efficiency of a DC-DC boost converter under varying irradiance and temperature conditions.



---

## 🔍 Objective

The main goals of this project are:

- To develop an MPPT controller using MLR for real-time solar energy optimization.
- To integrate the trained model into an embedded system (Arduino UNO).
- To design and validate a DC-DC Boost Converter based on calculated component parameters.
- To experimentally verify the efficiency improvements under dynamic solar conditions.

---

## 🛠️ Methodology

1. **Data Collection & Processing**
   - Collected solar panel specs and environmental data.
   - Used MATLAB for model training and simulation.

2. **MLR Model Development**
   - Trained the regression model using processed datasets.
   - Evaluated model accuracy using performance metrics.

3. **Hardware Implementation**
   - Arduino UNO for embedded model deployment.
   - Boost Converter designed with selected inductance/capacitance values.
   - TLP250-based gate driver circuit amplifies PWM signals for MOSFET switching.

4. **Testing & Validation**
   - Sensors and potentiometers used to simulate irradiance/temperature variations.
   - Real-time performance measured and compared with theoretical values.

---

## 📊 Key Findings

- The MLR-based MPPT system reached the maximum power point (MPP) in **~0.02 seconds**.
- Showed **low oscillations** and **fast convergence**, even in changing solar conditions.
- The gate driver circuit reliably boosted Arduino's PWM signals for effective switching.
- Overall, the system enhanced power extraction and improved boost converter efficiency.


├── 📄 README.md          # Project overview
