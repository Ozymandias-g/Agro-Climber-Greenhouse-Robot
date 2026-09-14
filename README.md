# Agro-Climber-Greenhouse-Robot
CAD design, FEA static analysis, and mechanical assembly of the Agro-Climber robot for automated plant monitoring in greenhouse environments, modeled in SolidWorks.

# Agro-Climber: Autonomous Greenhouse Monitoring Robot

## 📌 Project Overview
The **Agro-Climber** is a specialized climbing robot designed to enhance operational efficiency and make plant monitoring autonomous, precise, and cost-effective in modern greenhouse environments. It travels along greenhouse suspension cables and pipes to collect environmental and crop health data without compacting soil.

* **Course:** Computer-Aided Design (CAD)
* **Team Members:** Hamza Yiğit Yazıcı, Derviş Kekeç, Eren Burak İşler
* **Date:** January 2026

---

## ⚙️ Key Technical Features

* **Adaptive Clamping & Suspension:** 
  Modeled with custom high-precision springs using SolidWorks Helix/Spiral features. The spring-loaded suspension system absorbs ground and cable vibrations, protecting sensitive sensor payloads and ensuring smooth movement across varying cable diameters.
* **Transmission Unit:** 
  Utilizes spiral bevel gears designed for high torque delivery during vertical climbing and horizontal cable transitions.
* **Traction Wheels:** 
  Custom tread-pattern wheel profiles modeled to prevent slipping in humid, muddy greenhouse conditions.
* **Material Selection:**
  * **POM (Polyoxymethylene / Acetal):** High dimensional stability, low friction, and excellent resistance to greenhouse humidity.
  * **AISI 304 Stainless Steel:** High corrosion resistance for structural fasteners, shafts, and mounting brackets.
  * **Tires:** Matte rubber for maximum grip.
* **Total Assembly Mass:** ~9.42 kg (9,418.52 g)

---

## 🔬 FEA & Static Stress Analysis

A linear static analysis was conducted on the main body in SolidWorks Simulation to evaluate stress distribution under maximum expected operational loads:
* **Material Model:** Linear Elastic Isotropic (POM Acetal Copolymer)
* **Tensile Strength:** $7.15 \times 10^7\text{ N/m}^2$
* **Elastic Modulus:** $2.60 \times 10^9\text{ N/m}^2$
* **Applied Load:** $1000\text{ N}$ normal force on critical mounting flanges.
* **Result:** von Mises stresses remained within allowable material thresholds, confirming the structural integrity of the frame.

---

## 🛠️ Assembly Breakdown
The robot assembly consists of:
* Main Structural Body & Holders
* Drive Engine & Spiral Bevel Gear Mechanism
* Tensioning Cylinder & Holder
* Grooved Cable Climbing Wheels
* Shock-Absorbing Spring Assemblies
* Guidance Pipe Clamps

---

## 🚀 Future Recommendations
* **AI Vision Integration:** Mounting high-resolution camera modules with onboard edge computing for real-time plant disease detection.
* **Power Optimization:** Refining gear reduction ratios to maximize battery endurance during continuous vertical ascents.
