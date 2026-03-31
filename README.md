# Solidworks- Fan Blade Model
This repository contains a parametric 3D fan blade model designed in SolidWorks.  

The project focuses on understanding the feature-based modeling workflows that are commonly used in turbomachinery, cooling systems, and ventilation applications , the fundamentals of fan blade geometry, constraint-driven design.

This model is intended primarily for learning, experimentation, and documentation of the design process.  

---

## 🎯 Objectives

The primary learning goals were to:
- Generate blade geometry using profiles, guide curves, and reference planes for precise shape control of this model 
- Develop a fully-defined base sketch instead of relying on trial and error
- Using revolve operations construct a smooth hub profile
- Maintain surface continuity and curvature quality avoiding sharp or irregular geometry
- Create geometry that can be easily edited and reused in future design
- Export the design in formats compatible with multiple CAD tools like CATIA , Fusion 360 , AutoCAD etc.

---

## 📐 Modeling Overview

![Modek Fan blade](https://github.com/user-attachments/assets/9c23d5e0-81b9-40b1-ad1b-81029681b879)

![Modek Fan blade Right view](https://github.com/user-attachments/assets/f6cbaa36-0baf-4476-ad83-ecfbf92d2aab)


### 1️⃣ Revolved Base (Hub)

The hub acts as the foundation for positioning the blade.

A 2D sketch was created to define the hub profile and then revolved 360°.  
Key considerations included:

- Appropriate proportions of length and diameter
- Perfect symmetry about the axis
- Smooth rounded nose profile
- Avoids under defined geometry

---

### 2️⃣ Blade Definition and Shaping

A blade is the curved part of the design that moves through air (or fluid) to create force or motion, just like the blades of a fan or propeller.

In this model, the blade is carefully shaped to be smooth and efficient, so it can move easily through air and perform its function properly.

The blade was constructed by sketching profiles on reference planes positioned along the hub.

Important design aspects:

- Uniform blade thickness
- Gradual twist and curvature along its length
- Transitions between sections that avoid sudden edges or breaks
- Fully constrained reference geometry

---

### 3️⃣ Refinement and Cleanup

Fillets and edge transitions were applied to:

- Improve overall visual realism
- Reduce stress concentrations conceptually avoiding sudden changes in geometry
- Ensures the modle mimics the manufacturable geometry

---

## 📁 Repository Structure

| Path | Description |
|------|-------------|
|Model Fan blade.SLDPRT" | Native SolidWorks part file |
|Model Fan blade.mp4"| dynnamic preview or motion study  |
No assembly is included — this repository contains a single part file | -
---

## ⚙️ Software Compatibility

This project has been created in SolidWorks 2023.

---

## 🚀 Possible Extensions

There's plenty of room to build on this model , some ways are:

- Attach the blade to a hub or shaft to make it part of complete working assembly
- Create motion animation showing rotational behavior of the model
- Run CFD simulations to study airflow qualitatively
- Structural analysis to understand loading and deformation
- Redesigning the blade and experimenting with different shapes would allow for performance comparisons

These improvements can transform the model into a more practaical and engineering focused useful project.

---

## 📜 License and Usage

This repository is shared for educational and learning purposes.  
The model may be downloaded, modified and reused with appropriate credit.

Commercial use is not permitted.

---

## 🙌 Author

Created by **Shreya** as part of CAD learning and self practice using SolidWorks.

Feedback and suggestions are  most welcome.
