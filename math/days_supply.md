# 📘 Calculating Days' Supply

## 🔑 Key Concepts

The Days Supply refers to how long a prescription will last based on the quantity dispensed and the prescribed dosing instructions. It is a technical quantity based entirely on math; not a guess, and not just the number of pills dispensed.

**Why It Varies**:

Two patients may receive the **same quantity** of medication but have **different dosing instructions**. For example:

- **Patient A**: Take 1 tablet daily → 30 tablets = 30 days
- **Patient B**: Take 2 tablets daily → 30 tablets = 15 days

**General Calculation**:

${\boxed{\text{Per Diem}} = \text{Amount per Dose} \times \text{Doses per Diem}}$

${\boxed{\text{Days Supply}} = \text{Amount Dispensed} \div \text{Amount Per Diem}}$

${\boxed{\Rightarrow \text{Days Supply} = \frac{\text{Amount Dispensed}}{\text{Amount per Dose} \times \text{Doses per Diem}}}}$

- Round **down** to the nearest whole day
- Days supply should be calculated based on **maximum daily usage**
- Consider split dosing and package-size limitations (e.g., inhalers, patches)

**It affects**:

- **Insurance billing**: Insurers require accurate days' supply to determine when a refill is allowed.
- **Controlled substances**: Days' supply impacts legal refill limits and audit compliance.
- **Pharmacist review**: DUR (Drug Utilization Review) relies on accurate days’ supply to detect overuse, underuse, or interactions.
- **Medication synchronization**: To align refill dates across multiple prescriptions. Technicians may need to:
  - Adjust fills to **short-term supplies** (e.g., 21 or 28 days)
  - Calculate partial fills to align dates
  - **Document synchronization quantity** in pharmacy software

### 🚨 Tips & Best Practices

- 🛡️ Always read the sig carefully — BID can mean two tablets, two times a day, or one tablet twice a day.
- 🚨 For eye/ear drops, check if **both eyes/ears** are being treated.
- 🛡️ Topical use is often estimated — confirm application area with pharmacist if unclear.
- 🛡️ Document how you arrived at your days’ supply if not obvious.

> 📌 Many pharmacy systems calculate days’ supply automatically, but knowing how to do it manually helps catch input errors and supports DUR decisions.

## 💊 Tablets & Capsules

**Billable Units**: Whole Tablets or Capsules

🔠 **Abbreviations**:

- Capsules = `cap`/ `c`
- Tablets = `tab`/ `t`

🔢 **Formula**:

For the sake of simplicity, I will be referring to them as `pills`.

${\boxed{\text{Pills Per Diem}} = \text{Pills per Dose} \times \text{Doses Per Diem}}$

${\boxed{\text{Days Supply} }= \text{Pills Dispensed} \div \text{Pills Per Diem}}$

${\boxed{\Rightarrow \text{Days Supply} = \frac{\text{Pills Dispensed}}{\text{Pills per Dose} \times \text{Doses per Diem}}}}$

💊 **Example**:

**Sig**: `iii tabs po QID #XLV`

==> `Take 3 tablets by mouth, 4 times a day #45`

${\boxed{\text{Pills Dispensed}} = \text{45 tab}}$

${\boxed{\text{Pills per Dose}} = \text{3 tab/dose}}$

${\boxed{\text{Doses per Diem}} = \text{4 dose/day}}$

${\boxed{\Rightarrow \text{Pills Per Diem}} = \frac{\text{3 tab}}{\text{1 dose}} \times \frac{\text{4 dose}}{\text{1 day}} = \frac{\text{12 tab}}{\text{1 day}} = \text{12 tab/day}}$

${\boxed{\Rightarrow \text{Days Supply}} = \text{45 tab} \div \text{12 tab/day} = \frac{\text{45 tab}}{\text{1}} \times \frac{\text{1 day}}{\text{12 tab}}}$

${\boxed{\Rightarrow \text{Days Supply}} = \text{3.75 Days} = \text{3 Days (Rounded Down)}}$

## 🥤 Liquid Solutions, Suspensions, Syrups

**Billable Units**: Volume (mL)

🔠 **Abbreviations**:

- Solutions = `sol`
- Suspensions = `susp`
- Syrups = `syr`

🔢 **Formula**:

${\boxed{\text{Volume Per Diem}} = \text{Volume per Dose} \times \text{Doses Per Diem}}$

${\boxed{\text{Days Supply} }= \text{Volume Dispensed} \div \text{Volume Per Diem}}$

${\boxed{\Rightarrow \text{Days Supply} = \frac{\text{Volume Dispensed}}{\text{Volume per Dose} \times \text{Doses per Diem}}}}$

💧 **Example**:

**Sig**: `2 tsp po q6h prn pain # VI oz`

==> `Take 2 Teaspoons by mouth every 6 hours, as needed for pain #6 oz`

${\text{1 tsp} = 5 \, \text{mL} \qquad \text{1 oz} = 30 \, \text{mL}}$

${\boxed{\text{Volume Dispensed}} = {6 \, \text{oz} \times \frac{30 \, \text{mL}}{1 \, \text{oz}} = 180 \, \text{mL}}}$

${\boxed{\text{Volume per Dose}} = {\text{2 tsp} \times  \frac{\text{5 mL}}{\text{1 tsp}} = 10 \, \text{mL}}}$

${\boxed{\Rightarrow \text{Volume per Diem}} = \frac{10 \, \text{mL}}{1 \, \text{dose}} \times \frac{4 \, \text{doses}}{1 \, \text{day}} = \frac{40 \, \text{mL}}{1 \, \text{day}} = 40 \, \text{mL/day}}$

${\boxed{\Rightarrow \text{Days Supply}} = \frac{180 \, \text{mL}}{40 \, \text{mL/day}} = \frac{180}{1} \times \frac{1 \, \text{day}}{40} = \frac{180}{40} = 4.5 \, \text{days}}$

${\boxed{\Rightarrow \text{Days Supply} = \text{4 Days (Rounded Down)}}}$

## 📘 Topical Medications (Creams, Ointments, & Gels)

**Billable Units**: Mass (g)

🔠 **Abbreviations**:

- creams = `cm`/ `crm`
- ointments = `ung`/ `oint`
- gels = `gel`

🔢 **Formula**:

${\boxed{\text{Grams Per Diem} = {\text{Grams per Application} \times \text{Applications Per Diem}}}}$

${\boxed{\text{Days Supply} = \frac{\text{Grams Dispensed}}{{\text{Grams per Application} \times \text{Applications Per Diem}}}}}$

>- 📍 Estimate **1 gram per application**, unless prescriber or labeling indicates otherwise  
>- 📍 1 gram typically covers a **10 cm × 10 cm** area of skin  

🧴 **Example**:

**Sig**: `AAA QAM & QPM #XXX`

==> `Apply to affected area every night & morning #30g tube`

${\boxed{\text{Grams Dispensed} = 30 \, \text{g}}}$

${\boxed{\text{Grams per Application} = 1 \, \text{g}}}$

${\boxed{\text{Applications per Diem} = 2 \, \text{times/day}}}$

${\boxed{\Rightarrow \text{Grams Per Diem} = \frac{1 \, \text{g}}{1 \, \text{application}} \times \frac{2 \, \text{applications}}{1 \, \text{day}} = \frac{2 \, \text{g}}{1 \, \text{day}} = 2 \, \text{g/day}}}$

${\boxed{\Rightarrow \text{Days Supply} = \frac{30 \, \text{g}}{2 \, \text{g/day}} = \frac{30}{1} \times \frac{1 \, \text{day}}{2} = 15 \, \text{days}}}$

## 🌬️ Metered-Dose Inhalers (MDIs)

**Billable Quantity**: Mass (g); based on **canister**  
**Clinical Quantity**: Total **metered doses** (puffs)

🔠 **Abbreviations**:

- **Metered-Dose Inhaler**: `mdi`
- **Puffs**: `p`

🔢 **Formula**:

${\boxed{\text{Puffs Per Diem} = {\text{Puffs per Dose} \times \text{Doses per Diem}}}}$

${\boxed{\text{Days Supply} = \frac{\text{Total Metered Doses}}{{\text{Puffs per Dose} \times \text{Doses per Diem}}}}}$

> 📍 MDI canisters are labeled with **number of actuations (puffs)**

📘 **Example**:

**Sig**: `iii puff q6h prn sob # IIX g (200 metered doses)`

==> `inhale 3 puffs every 6 hours as needed for shortness of breath #8 grams (200 metered doses)`

${\boxed{\text{Total Metered Doses} = 200 \, \text{p}}}$

${\boxed{\text{Puffs per Dose} = 3 \, \text{p}}}$

${\boxed{\text{Doses per Diem} = \frac{24 \, \text{hr}}{6 \, \text{hr/dose}} = 4 \, \text{doses/day}}}$

${\boxed{\Rightarrow \text{Puffs Per Diem} = \frac{3 \, \text{p}}{1 \, \text{dose}} \times \frac{4 \, \text{doses}}{1 \, \text{day}} = \frac{12 \, \text{p}}{1 \, \text{day}} = 12 \, \text{p/day}}}$

${\boxed{\text{Days Supply} = \frac{200 \, \text{p}}{12 \, \text{p/day}} = \frac{200}{1} \times \frac{1 \, \text{day}}{12} = 16.66 \, \text{days}}}$

${\boxed{\Rightarrow \text{Days Supply} = 16 \, \text{Days (Rounded Down)}}}$

---

| **Dosage Form** | **Billable Quantity** | **Formula for Days Supply** | **Notes** |
| --- | --- | --- | --- |
| **Tablets / Capsules** | Quantity dispensed (Whole Units) | $\frac{\text{Quantity Dispensed}}{\text{Daily Allowance}}$ | N/A |
| **Solutions / Suspensions** | Volume (mL) | $\frac{\text{Volume Dispensed (mL)}}{\text{Daily Allowance (mL)}}$ | N/A |
| **Inhalation Solutions** | Volume (mL) | $\frac{\text{Volume Dispensed}}{\text{Daily Allowance (mL)}}$ | Add volume from all vials dispensed |
| **Inhalation Powders** | Mass (g) | $\frac{\text{Mass Dispensed (g)}}{\text{Daily Allowance (g)}}$ | Add volume from all vials dispensed |
| **Metered Dose Inhalers** | Mass (g) Stated on Unit Package  | $\frac{\text{Actuations per Inhaler (puffs)}}{\text{Daily Allowance (puffs)}}$ | Add actuations from all units dispensed |
| **Eye / Ear Drops** | Volume (mL) | $\frac{\text{Amount in Bottle (gtt)}}{\text{Daily Allowance (gtt)}}$ | Estimate 15-20 gtt/mL |
| **Lotions** | Volume (mL) | $\frac{\text{Volume Dispensed (mL)}}{\text{Daily Allowance (mL)}}$ | N/A |
| **Creams, Ointments** | Mass (g) | $\frac{\text{Mass Dispensed (g)}}{\text{Daily Allowance (g)}}$ | Default Mass per Day = 1g unless specified or packaged inside an applicator (check label for quantity) |
| **Injector Pens** | Volume (mL) | $\frac{\text{Volume Dispensed (mL)}}{\text{Daily Allowance (mL)}}$ | Add volume across all pens dispensed; standard volume for insulin is 3mL (outpatient) or 2.5mL (inpatient) |
| **Parenteral Injection Vials** | Volume (mL) | $\frac{\text{Volume Dispensed (mL)}}{\text{Daily Allowance (mL)}}$ | Add volume across all vials dispensed; standard volume for insulin is 10mL (outpatient) or 3mL (inpatient) |

> **NOTE**: Some prescriptions may include instructions like "Take as Directed" (UD), which are for medications dispensed as whole units (e.g., ZPAK or Monistat-7). These prescriptions may have a fixed Days Supply regardless of the calculated value, and pharmacies may dispense more than required. Prescriber instructions take precedence over technical calculations.

## Special Considerations for Insulin

Insulin must be refrigerated before use but can be kept at room temperature for approximately 28 days after opening (with a few exceptions).

For example, if an outpatient is dispensed a **standard U-100** insulin vial **(100 Units/mL)** during an emergency, and the patient requires 12 Units per day, the medication technically lasts for about 83 days. However, expiration date takes precedence over this calculation, as insulin degrades over time, especially once opened. Therefore, the Days Supply should reflect the expiration date, even if technically there is more insulin available.

> Always check expiration dates when dispensing more than 28 days supply

<!-- 
## Reference

Pharmacy Calculations, 6e; Morton Publishing | Chapter 12
-->
