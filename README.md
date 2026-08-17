# Springless Car Suspension System Using Bevel Gears

## 📌 TA-212 Project

This project presents the **design, manufacturing, and implementation of a springless vehicle suspension system using bevel gears**. The system is designed to absorb shocks and maintain continuous wheel contact with the ground, preventing wheel lift during uneven-terrain operation.

The project was developed as a **Group 15 Mechanical Engineering project** under the guidance of **Prof. Virkeshwar Kumar** and **Mr. Rahul**.

---

## 🎯 Objectives

* Design a **springless suspension mechanism** using bevel gears.
* Maintain continuous contact between all wheels and the ground.
* Improve vehicle stability over uneven terrain.
* Design and manufacture the mechanical components required for the suspension system.
* Integrate the mechanical system with **DC motors, motor drivers, Arduino UNO, and battery supply**.
* Validate the design through mechanical calculations, manufacturing, and assembly.

---

## ⚙️ Working Principle

The proposed suspension system replaces conventional springs with a **bevel-gear-based mechanical mechanism**.

When one wheel encounters an uneven surface, the bevel gears transmit the corresponding motion through the shafts and suspension structure. This allows the wheel assembly to accommodate terrain variations while helping maintain contact between the wheels and the ground.

The system therefore aims to improve **stability, load distribution, and terrain adaptability** without relying on conventional coil or leaf springs.

---

## 🔩 Major Components

| Component     | Quantity | Material / Type             | Manufacturing |
| ------------- | -------: | --------------------------- | ------------- |
| Bevel Gear    |        3 | Mild Steel                  | Manufactured  |
| L-Support     |        6 | Mild Steel                  | Manufactured  |
| Base Plate    |        1 | Mild Steel                  | Manufactured  |
| Legs          |        4 | Mild Steel                  | Manufactured  |
| Shafts        |        3 | Mild Steel                  | Manufactured  |
| Rubber Wheels |        4 | Rubber                      | Bought        |
| DC Motors     |        4 | Metal & Plastic             | Given         |
| Motor Driver  |        1 | Electronic Components       | Bought        |
| Arduino UNO   |        1 | Electronic Components       | Given         |
| Battery       |        1 | Chemical & Metal Components | Given         |
| Screws        |       11 | Steel                       | Given         |

The manufactured components involved operations such as **cutting, drilling, filing, turning, threading, milling, taper turning, and facing**.

---

## ⚡ Motor & Motor Driver Selection

### DC Motor

A **High-Torque 30 RPM, 12 V DC motor** was selected because the vehicle requires high torque to handle its overall load and uneven terrain. Torque was prioritized over motor speed.

### L298N Motor Driver

The motor system was evaluated based on current requirements:

* No-load current per motor pair: **~0.7 A**
* Loaded current per motor pair: **~1.4–1.6 A**
* Selected driver: **L298N**
* Current rating: **2 A**
* Number of drivers selected: **2**

The L298N provides sufficient current capacity for the measured loaded current while maintaining the project within budget.

---

## ⚙️ Bevel Gear Design Calculations

The primary bevel-gear design parameters are:

| Parameter                 |     Value |
| ------------------------- | --------: |
| Shaft Angle, Σ            |       90° |
| Module, m                 |       1.5 |
| Number of Teeth, z₁ / z₂  |   20 / 20 |
| Pitch Diameter            |     30 mm |
| Pitch Cone Angle, δ₁ / δ₂ | 45° / 45° |
| Cone Distance, Re         |  21.21 mm |
| Maximum Face Width        |   7.07 mm |
| Addendum, ha              |    1.5 mm |
| Dedendum, hf              |  1.875 mm |
| Dedendum Angle, θf        |     5.05° |
| Addendum Angle, θa        |     4.04° |
| Outside Cone Angle        |    49.04° |
| Root Cone Angle           |    39.95° |
| Outside Diameter          |   32.1 mm |
| Pitch Apex to Crown       |     14 mm |

## These parameters were calculated for the 90° shaft-angle bevel gear arrangement used in the project.

## 🏭 Manufacturing Process

The major manufacturing operations used in the project include:

* **Cutting**
* **Drilling**
* **Filing**
* **Turning**
* **Threading**
* **Facing**
* **Milling**
* **Taper Turning**

The bevel gears were manufactured using **lathe and milling operations**, including taper turning, facing, and drilling. Shafts involved cutting, turning, and threading, while the L-supports and legs involved cutting, filing, and drilling.

---

## 💰 Cost Analysis

### Material Cost

The calculated material cost was:

**₹2,911.89**

Major material expenses included:

* Base plate: ₹188.40
* L-supports: ₹104
* Legs: ₹94
* Shafts: ₹19.75 + ₹81.80
* Bevel gears: ₹333 + ₹666 + ₹277.94
* Wheels: ₹330
* DC motors: ₹800
* Battery: ₹350

### Machinery Cost

| Machine   |      Time |       Cost |
| --------- | --------: | ---------: |
| Drilling  |   6 hours |       ₹430 |
| Turning   | 3.5 hours |       ₹525 |
| Milling   |   8 hours |     ₹2,000 |
| **Total** |           | **₹2,955** |

### Total Project Cost

**Total Project Cost = ₹5,866.89**

This includes:

* Material Cost = **₹2,911.89**
* Machinery Cost = **₹2,955**

**Total = ₹5,866.89**

---

## 🧩 Project Highlights

* Springless suspension mechanism
* Bevel-gear-based shock absorption
* 90° bevel-gear arrangement
* High-torque 12 V DC motors
* Arduino UNO-based control
* L298N motor-driver interface
* Mild-steel mechanical structure
* In-house manufacturing of major mechanical components
* Designed for improved wheel-ground contact
* Complete mechanical and cost analysis

---

## 🔮 Future Improvements

The project report identifies the following possible improvements:

* Introduce **remote-control functionality**.
* Add **battery-powered wireless control using Bluetooth**.
* Improve the **durability and material selection of the gears**.
* Increase the overall service life of the suspension mechanism.

---

## 👥 Team

**Group 15**

* Akul Agarwal — 230108
* Karan Kumar — 230533
* Soham Girish Panchal — 231014
* Meher Narula — 230648
* Shravan — 230983
* Ananya Kartick Iyer — 230133
* Keshav Meena — 230555
* Vedant Neekhra — 231131
* Ronit Kumar — 230875

---

## 🛠️ Skills & Technologies

**Mechanical Design**

* Bevel Gear Design
* Suspension Mechanism Design
* Shaft Design
* Mechanical Assembly
* Engineering Calculations

**Manufacturing**

* Lathe Machining
* Milling
* Drilling
* Taper Turning
* Facing
* Threading
* Fabrication

**Electronics & Control**

* Arduino UNO
* DC Motors
* L298N Motor Driver
* 12 V Power Supply

---

## 📄 Project Report

The complete project documentation, including **design calculations, component drawings, manufacturing details, material cost analysis, machinery cost, and final project cost**, is available in the project report.

**Report:** `TA212_Group15_FinalReport.pdf`

---

## 📊 Project Summary

| Category               | Details                          |
| ---------------------- | -------------------------------- |
| Project                | Springless Car Suspension System |
| Mechanism              | Bevel Gear Based                 |
| Shaft Angle            | 90°                              |
| Motor                  | 12 V, 30 RPM High Torque DC      |
| Controller             | Arduino UNO                      |
| Motor Driver           | L298N                            |
| Main Material          | Mild Steel                       |
| Manufactured Parts     | 17                               |
| Material Cost          | ₹2,911.89                        |
| Machinery Cost         | ₹2,955                           |
| **Total Project Cost** | **₹5,866.89**                    |

---

## ⭐ Key Takeaway

The project demonstrates the **design, analytical calculation, manufacturing, and integration of a springless suspension mechanism using bevel gears**. It combines mechanical design and manufacturing with basic embedded control to develop a practical suspension system capable of maintaining wheel-ground contact over uneven terrain.
