# Runga-Kutta
# 💧 Droplet Evaporation Simulation

A numerical simulation of evaporating water droplets using coupled heat transfer, mass transfer, and particle dynamics.

---

## 📖 Overview

This project simulates the evaporation and motion of a single water droplet in air by solving a system of coupled ordinary differential equations (ODEs).

The model considers:

- 💧 Droplet evaporation
- 🌡️ Heat transfer
- 💨 Mass transfer
- 🚀 Particle motion
- 🌍 Gravity
- 🌬️ Aerodynamic drag

The governing equations are solved using the **LSODA** numerical solver from **SciPy**.

---

## ⚙️ Physical Models

✔️ Temperature-dependent air properties

✔️ Reynolds Number

✔️ Nusselt Number

✔️ Sherwood Number

✔️ Stefan Flow Correction

✔️ Spalding Mass Transfer Number

✔️ Convective Heat Transfer

✔️ Convective Mass Transfer

✔️ Drag Force

✔️ Gravity

---

## 📊 Outputs

The simulation generates:

- 📈 Droplet diameter vs. time
- 🌡️ Droplet temperature vs. time
- 📍 Droplet position
- 🚀 Droplet velocity
- ✅ Validation with experimental data

---

## 🛠️ Technologies

- 🐍 Python
- 🔢 NumPy
- 📉 SciPy
- 📊 Matplotlib

---

## 🚀 Installation

```bash
pip install numpy scipy matplotlib
```

---

## ▶️ Run

```bash
python droplet_simulation.py
```

---

## 📂 Project Structure

```
📦 Droplet-Evaporation
 ┣ 📜 droplet_simulation.py
 ┣ 📜 README.md
 ┗ 📊 Simulation Results
```

---

## 👩‍💻 Author

### **Elaheh Shokrollahi**

🎓 M.Sc. Student in Applied Mathematics
(Specialization: Financial Mathematics)

### 🔬 Research Interests

- Numerical Analysis
- Runge–Kutta Methods
- Ordinary Differential Equations (ODEs)
- Scientific Computing
- Mathematical Modeling
- Computational Mathematics

---

## ⭐ If you find this project useful, don't forget to star the repository!
