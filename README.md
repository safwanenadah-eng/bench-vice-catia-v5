This project presents the mechanical design, assembly, and kinematic analysis of a bench vice in **CATIA V5**, as part of my mechatronics studies.

---

## 📷 Project Preview

![Bench vice preview](Images/apercu.png)

---

## ⚙️ Kinematic Analysis (Kinematics)

The mechanism was modeled using CATIA's **DMU Kinematics** module to simulate the vice's real behavior:

- **Screw Joint:** Converts the rotation of the clamping screw (`Jaw Screw`) into linear translation of the movable jaw (`Vice Jaw`).
- **Revolute Joint:** Rotation of the handle bar (`Screw Bar`) through the screw head.
- **Prismatic Joint:** Translational guiding of the movable jaw along the fixed base.
- **Degrees of Freedom (DOF):** Full mechanism simulation validated with 1 main degree of freedom (driven by the screw pitch).

---

## 🛠️ Technical Specifications

- **Software used:** CATIA V5 (Part Design, Assembly Design, DMU Kinematics)
- **Project type:** 3D modeling, Assembly & Kinematic simulation
- **Integrated components:**
  - Base (`Base.1`)
  - Movable jaw (`Vice Jaw.1`)
  - Clamping screw (`Jaw Screw.1`)
  - Support pads & mounting plates (`Base Plate`, `Clamping Plate`)
  - Handle bar and end caps (`Screw Bar`, `Bar Globes`)
  - Assembly screws (`Set Screws`)

---

## 📂 Repository Organization

- **`/CAD_Native/`**: Native CATIA V5 source files (`.CATProduct`, `.CATPart`).
- **`/CAD_STEP/`**: Universal 3D model (`.STEP`) readable by any CAD software.
- **`/Images/`**: Screenshots and visual renders of the project.
