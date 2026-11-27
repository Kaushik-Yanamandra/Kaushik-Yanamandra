# Hi, I'm Kaushik 👋

High school senior in Katy, Texas, heading into engineering. I like problems that cross disciplines: the **circuits and code** that control a machine, the **mechanism** that moves it, the **materials** it's made from, and the **physics of things in flight**.

| Discipline | Where it shows up in my projects |
|---|---|
| ⚡ **Electrical & computer** | Safety controllers, power systems, sensors and embedded firmware |
| ⚙️ **Mechanical** | Mechanisms, parametric CAD, 3D-printed parts, hydraulics |
| 🧪 **Materials science** | Choosing plastics, metals and battery chemistry for heat, sun, water and corrosion |
| ✈️ **Aerospace** | Trajectories with drag and wind, feedback correction, calibration and error budgets |

---

## 🔧 What I'm building

### 💧 Lawn Watering Turret
A camera-guided turret that finds the dry patches of a lawn with a thermal camera and waters only those, one aimed jet at a time. In simulation it uses about 80% less water than watering every patch the same.
- **Status:** designed, simulated and through a full design review; 3D-printing parts for the first prototype
- ⚡ ESP32 safety controller that shuts the water off on its own if anything fails; Raspberry Pi thermal vision
- ⚙️ Pan/tilt head with both axes through the nozzle, so the jet puts no torque on the motors; 23 parametric 3D-printed parts
- 🧪 ASA, PETG and metals chosen for 60 °C Texas sun and outdoor corrosion
- ✈️ Jet trajectory with quadratic drag and wind (Runge–Kutta), an aim solver, and wind estimated from where test shots land
- **Repo:** [lawn-watering-turret →](https://github.com/Kaushik-Yanamandra/lawn-watering-turret)

### ☀️ Solar Outage Backup System
A solar-charged 24 V battery system that keeps internet, two laptops and a fan running through 2–3 day hurricane outages.
- **Status:** designed and sized; not yet built
- ⚡ Load budget, solar and battery sizing, an all-DC design with no inverter losses, fuse and wire sizing, energy data logging
- 🧪 Lithium iron phosphate (LiFePO4) battery chemistry
- ⚙️ Ground-mounted array that can come down before a storm
- **Repo:** [solar-outage-backup →](https://github.com/Kaushik-Yanamandra/solar-outage-backup)

---

## 🧰 Tools I use
- **Languages:** Python (NumPy, SciPy, OpenCV) · C/C++ · Verilog
- **Hardware:** Arduino · Raspberry Pi · FPGA dev boards
- **Design & simulation:** parametric CAD for 3D printing · circuit simulation · numerical simulation in Python

## 📚 Currently learning
- Digital logic design on FPGAs
- How power gets converted and stored in off-grid systems
- Numerical methods for motion with drag, and estimating unknowns from measurements
- How printed plastics age outdoors

---

## 📫 Get in touch
Open an issue on any of my repos. I'm happy to talk about projects.
