# 📏 Dosage Calculations Based on Body Surface Area (BSA)

<!-- 
## Reference

Pharmacy Calculations, 6e; Morton Publishing | Chapter 28
-->

## 🔑 What is BSA?

**Body Surface Area (BSA)** is a measurement of the total surface of a patient’s body. It is used in drug dosing because it provides a more accurate estimation of metabolic mass than weight alone.

> 📌 BSA is measured in **square meters (m²)**.

## 📏 Drugs Dosed by BSA

BSA-based dosing is most often used for drugs with a **narrow therapeutic index** or those requiring **precise systemic exposure**.

| Drug Class         | Example Medications          |
| -------------------- | ------------------------------ |
| 🧬 **Chemotherapy**     | Methotrexate, Doxorubicin     |
| 💊 **Antivirals**       | Acyclovir (severe cases)      |
| 🧠 **Immunosuppressants** | Cyclosporine, Tacrolimus      |
| 👶 **Pediatric Meds**     | Specially calculated doses    |

## 📐 BSA Calculation Methods

**Mosteller Formula** (commonly used)

![formula](./img/bsa/formula.PNG)
<!-- ${BSA (m^2) = \sqrt{ \frac{\text{Height (cm)} \times \text{Weight (kg)}}{3600} }}$ -->

Alternate version with inches and pounds:

![alternative formula](./img/bsa/formula_alt.PNG)
<!-- ${BSA (m^2) = \sqrt{ \frac{\text{Height (in)} \times \text{Weight (lb)}}{3131} }}$ -->

📘 Example: **BSA Using Mosteller Formula**

**Height** = 160 cm  
**Weight** = 60 kg

![formula example](./img/bsa/formula_example.PNG)
<!-- ${BSA = \sqrt{ \frac{160 \times 60}{3600} } = \sqrt{ \frac{9600}{3600} } = \sqrt{2.67} \approx \boxed{1.63\ m^2}}$ -->

**Using a Nomogram** (Theoretical)

A **nomogram** is a visual tool used to estimate BSA by drawing a straight line between a patient’s **height and weight** on a chart.

🛠️ **Steps**:

1. Locate **height** on left column.
2. Locate **weight** on right column.
3. Draw a line connecting both points.
4. Intersection with the **center axis** gives estimated BSA.

>- 🚨 This method is mostly theoretical or used in manual settings where digital calculators are unavailable. You don't actually need to know how to use this formula. **These are normally just provided.**

## 💊 Calculating Drug Dose Based on BSA

![calculation template](./img/bsa/template.PNG)
<!-- $\boxed{\text{Dose (mg)} = \text{BSA (m²)} \times \text{Dose per m²}}$ -->

### 📘 Example 1: Single Dose

**Order**: Doxorubicin 30 mg/m²  
**Patient BSA**: 1.8 m²

![example 1](./img/bsa/ex1.PNG)
<!-- ${\text{Dose} = 30 \times 1.8 = \boxed{54\ \text{mg}}}$ -->

### 📘 Example 2: Total Dose for 5 Days

**Order**: Cyclophosphamide 400 mg/m²/day for 5 days  
**Patient BSA**: 1.6 m²

![example 2](./img/bsa/ex2.PNG)
<!-- ${\text{Daily Dose} = 400 \times 1.6 = 640\ \text{mg}}$

${\Rightarrow \text{Total Dose} = 640 \times 5 = \boxed{3200\ \text{mg}}}$ -->

## 🚨 Tips and Best Practices

- 🛡️ **Always confirm height and weight** with the most recent values
- 📌 Use **metric units** when applying BSA formulas (cm, kg)
- 🛡️ BSA calculations are **critical for chemo**; double-check math
- 📌 Pediatric patients are especially sensitive to **BSA-based dosing**
- 🛡️ Round final doses **per pharmacy protocol** or **physician instruction**

---

🔗 Back to [**Mathematics Concepts Directory**](./readme.md)
