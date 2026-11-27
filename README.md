# Hi, I'm Kaushik 👋

High school senior in Katy, Texas, heading into engineering, with a focus on **general engineering** and **materials science**. I like seeing a whole system come together, from circuits and code to the mechanism that moves it, and asking what every part should be made of and why.

## 🔬 Focus

- 🧪 **Materials science:** choosing plastics, metals and battery chemistry for heat, sun, water and corrosion; designing around how 3D-printed parts fail; how printed plastics age outdoors.
- 🛠️ **General engineering:** taking a system from requirements to drawings, parts lists and simulation, then reviewing the design for failures before anything is built.

My projects also draw on ⚡ electrical, ⚙️ mechanical and ✈️ aerospace engineering: safety controllers and power systems, mechanisms and parametric CAD, and the physics of things in flight.

---

## 🔧 What I'm building

### 💧 Lawn Watering Turret
A camera-guided turret that finds the dry patches of a lawn with a thermal camera and waters only those, one aimed jet at a time. In simulation it uses about 80% less water than watering every patch the same.
- **Status:** designed, simulated and through a full design review; 3D-printing parts for the first prototype
- 🧪 ASA and PETG chosen against 60 °C Texas sun (glass transition, UV), no PLA; parts oriented around weak layer bonds; bosses so heat-set inserts can't break through; corrosion between galvanised steel and stainless. [Materials notes →](https://github.com/Kaushik-Yanamandra/lawn-watering-turret/blob/main/docs/materials-selection.md)
- 🛠️ Whole-system design: requirements, 23 parametric 3D-printed parts, parts list, simulation, and a design review that found and fixed 19 problems
- ⚡⚙️✈️ ESP32 safety controller that shuts the water off on its own; a pan/tilt head with no jet torque on the motors; jet trajectories with drag and wind
- **Repo:** [lawn-watering-turret →](https://github.com/Kaushik-Yanamandra/lawn-watering-turret)

### ☀️ Solar Outage Backup System
A solar-charged 24 V battery system that keeps internet, two laptops and a fan running through 2–3 day hurricane outages.
- **Status:** designed and sized; not yet built
- 🧪 Lithium iron phosphate (LiFePO4) battery, chosen after researching battery chemistries
- 🛠️ Load budget, solar and battery sizing, an all-DC design with no inverter losses, fuse and wire sizing, energy data logging
- ⚙️ Ground-mounted array that can come down before a storm
- **Repo:** [solar-outage-backup →](https://github.com/Kaushik-Yanamandra/solar-outage-backup)

---

## 🧰 Tools I use
- **Languages:** Python (NumPy, SciPy, OpenCV) · C/C++ · Verilog
- **Hardware:** Arduino · Raspberry Pi · FPGA dev boards
- **Design & simulation:** parametric CAD for 3D printing · circuit simulation · numerical simulation in Python

## 📚 Currently learning
- How printed plastics age outdoors, and how battery chemistries compare
- How power gets converted and stored in off-grid systems
- Numerical methods for motion with drag, and estimating unknowns from measurements
- Digital logic design on FPGAs

---

## 📫 Get in touch
Open an issue on any of my repos. I'm happy to talk about projects.
