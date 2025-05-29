# 📘 Calculating Days' Supply & Billing Quantity

<!-- 
## Reference

Pharmacy Calculations, 6e; Morton Publishing | Chapter 12 & 13
-->

🔗 [Quick Reference Table](../ref/days_supply_table.md)

## 🔑 Key Concepts

The **Days Supply** refers to how long a prescription will last based on the quantity dispensed and the prescribed dosing instructions. It is a technical quantity based entirely on math; not a guess, and not just the number of pills dispensed.

### Billing Quantity

**Billing Quantity** is the amount of drug product reported to insurance for payment and inventory tracking. It is not always the same as the number of doses, units taken, or total uses. Instead, it reflects the **form in which the drug is dispensed** (e.g., tablets, milliliters, grams, vials, puffs).

- The **billing unit** must match the **product’s NDC (National Drug Code)** unit of measure.
- Quantities must reflect the **dispensed amount**, not just what is consumed.
  - 🚨 **Billing quantity must match what is physically dispensed, regardless of expected usage.** For example, if a patient is prescribed a cream to apply once daily for 30 days and receives a **60g tube**, the **billing quantity is 60 grams**, even though the patient may only use 30 grams.
- Insurance claims **require accurate billing quantities** to calculate reimbursement and determine refill eligibility.
  - 🚨 Incorrect entries may cause claim rejection, reimbursement errors, or audit flags.

🧾 **Common Billing Units by Dosage Form**

| Dosage Form | Billing Unit | Example |
|-------------|--------------|---------|
| Tablets / Capsules | Each | 30 tablets = 30 billing units |
| Patches | Each | Box of 15 patches = 15 units |
| Liquids (oral) | mL | 120 mL bottle = 120 units |
| Topical creams/ointments | Grams | 45g tube = 45 units |
| Inhalers (MDIs) | Grams | Labeled on canister (e.g., 8g) |
| Nebulizer vials | mL | Box of 30; 1mL vials = 30 units|
| Eye/Ear drops | mL | 5 mL bottle = 5 units |
| Injector pens | mL | 3 mL per pen = 15 mL for box of 5 |
| Injections (vials) | mL | 1 mL vial = 1 billing unit |

### 🏷️ Inscription & Signa: Reading and Translating Prescriptions

Understanding how to read prescriptions requires familiarity with the **Inscription** and **Signa** sections—two core components of written or electronic prescription orders.

#### 📃 Prescription Structure

| Section | Purpose |
|---------|---------|
| **Inscription** | Lists the **drug name**, **strength**, and **dosage form** |
| **Signa (Sig)** | Provides **directions for the patient** |

> 🛡️ "Signa" is Latin for "let it be labeled." It tells the patient how to take the medication.

#### 🔄 Translating Signa Abbreviations

Sig codes are often written in abbreviated Latin phrases. Pharmacy technicians must be able to **translate these into patient-friendly instructions**.

🔗 See [Translating the Signa](../ref/sig_translation.md)

### Days Supply Calculations

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

### ⏱️ Dosing Frequency

`Why Days Supply Calculations can Vary Across Patients`

${\boxed{\text{Dosing Frequency} \implies \text{Doses per Diem}}}$

Dosing frequency refers to how often a medication is taken each day. It directly determines how fast the dispensed quantity will be used and therefore controls the days supply.

The same quantity of medication can result in different days supplies depending on the prescribed frequency. For example, a 30-count bottle will last:

- 30 days if taken once daily  
- 15 days if taken twice daily

The math must always reflect the **maximum daily use** allowed by the prescription. If the directions say "take 1–2 tablets every 4–6 hours as needed," the calculation should be based on 2 tablets every 4 hours (i.e., the highest permissible daily dose).

📘 **Example**: Around-the-Clock

**Sig**: `Take 1 tablet by mouth every 8 hours`

${\boxed{\text{Hours per Dose} = 8 \, \text{hours}}}$

${\boxed{\Rightarrow \text{Doses Per Diem} = \frac{24 \, \text{hours}}{8 \, \text{hours/dose}} = 3 \, \text{doses/day}}}$

${\boxed{\text{Tablets per Dose} = 1 \, \text{tab}}}$

${\boxed{\Rightarrow \text{Tablets Per Diem} = 1 \, \text{tab/dose} \times 3 \, \text{doses/day} = 3 \, \text{tabs/day}}}$

If the prescription is written for `#90 tablets`:

${\boxed{\Rightarrow \text{Days Supply} = \frac{90 \, \text{tabs}}{3 \, \text{tabs/day}} = 30 \, \text{days}}}$

> 📍 Divide 24 hours by the interval to determine frequency.

📘 **Example**: As Needed

**Sig**: `Take 1–2 tablets every 4–6 hours as needed for pain`

${\boxed{\text{Minimum Hours per Dose}} = \min(4, 6) = 4 \, \text{hours}}$

${\boxed{\Rightarrow \text{Doses Per Diem}} = \text{24 hours/day} \div \text{4 hours/dose} = \text{6 doses/day}}$

${\boxed{\text{Tablets per Dose}} = \text{2 tabs/dose}}$

${\boxed{\Rightarrow \text{Tablets Per Diem}} = \text{2 tabs/dose} \times \text{6 doses/day} = \text{12 tabs/day}}$

If the prescription is written for `#60 tablets`:

${\boxed{\Rightarrow \text{Days Supply} = \frac{60 \, \text{tabs}}{12 \, \text{tabs/day}} = 5 \, \text{days}}}$

> 🚨 Always calculate based on the **maximum** allowed usage, even for PRN directions.

This principle applies to **all dosage forms**; not just tablets. Whether dosing is measured in mL, grams, puffs, or vials, the frequency determines the per diem amount used and therefore the days supply.

### 🚨 Tips & Best Practices

- 🛡️ Always read the sig carefully; BID can mean two tablets, two times a day, or one tablet twice a day.
- 🚨 For eye/ear drops, check if **both eyes/ears** are being treated.
- 🛡️ Topical use is often estimated; confirm application area with pharmacist if unclear.
- 🛡️ Document how you arrived at your days’ supply if not obvious.

> 📌 Many pharmacy systems calculate days’ supply automatically, but knowing how to do it manually helps catch input errors and supports DUR decisions.

<!-- todo: seperate based on route & dosage form -->
<!-- todo: insert billing quantity math -->

## 💊 Tablets & Capsules

**Billable Units**: Whole Tablets or Capsules

*also includes patches & suppositories

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

---

## 🥤 Oral Liquid Solutions, Suspensions, Syrups

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

---

## 📘 Topical Creams, Ointments, Gels, & Lotions

**Billable Units**: Mass (g); for Lotions - Volume (mL)

🔠 **Abbreviations**:

- creams = `cm`/ `crm`
- ointments = `ung`/ `oint`
- gels = `gel`
- lotions = `lot.` (uncommon)

🔢 **Formula**:

${\boxed{\text{Grams Per Diem} = {\text{Grams per Application} \times \text{Applications Per Diem}}}}$

${\boxed{\text{Days Supply} = \frac{\text{Grams Dispensed}}{{\text{Grams per Application} \times \text{Applications Per Diem}}}}}$

>- 📍 Estimate **1 gram/ 1mL per application**, unless prescriber or labeling indicates otherwise  
>- 📍 1 gram typically covers a **10 cm × 10 cm** area of skin  

🧴 **Example**:

**Sig**: `AAA QAM & QPM #XXX`

==> `Apply to affected area every night & morning #30g tube`

${\boxed{\text{Grams Dispensed} = 30 \, \text{g}}}$

${\boxed{\text{Grams per Application} = 1 \, \text{g}}}$

${\boxed{\text{Applications per Diem} = 2 \, \text{times/day}}}$

${\boxed{\Rightarrow \text{Grams Per Diem} = \frac{1 \, \text{g}}{1 \, \text{application}} \times \frac{2 \, \text{applications}}{1 \, \text{day}} = \frac{2 \, \text{g}}{1 \, \text{day}} = 2 \, \text{g/day}}}$

${\boxed{\Rightarrow \text{Days Supply} = \frac{30 \, \text{g}}{2 \, \text{g/day}} = \frac{30}{1} \times \frac{1 \, \text{day}}{2} = 15 \, \text{days}}}$

## 👁️ Eyedrops & Eardrops

**Billable Quantity**: Volume (mL)
**Clinical Quantity**: Total **drops** (gtt)

🔠 **Abbreviations**:

- **Drops**: `gtt`
- **Eye**: `OS` (left); `OD` (right); `OU` (both)
- **Ear**: `AS` (left); `AD` (right); `AU` (both)

🔢 **Formula**:

${\boxed{\text{Total Drops Available} = \text{Volume Dispensed (mL)} \times \frac{20 \, \text{gtt}}{1 \, \text{mL}}}}$

${\boxed{\text{Drops per Diem} = \text{Drops per Dose} \times \text{Doses per Diem}}}$

${\boxed{\text{Days Supply} = \frac{\text{Total Drops Available}}{\text{Drops per Diem}}}}$

> 📍 Estimate **20 drops per mL** unless otherwise specified by package insert  
> 🛡️ Always check if treatment is **unilateral or bilateral**

📘 **Example**

**Sig**: `ii gtt ou qpm # V`

==> `instill 2 drops in both eyes at night #5mL`

${\boxed{\text{Volume Dispensed} = 5 \, \text{mL}}}$

${\boxed{\Rightarrow \text{Drops Dispensed} = 5 \, \text{mL} \times \frac{20 \, \text{gtt}}{1 \, \text{mL}} = 100 \, \text{gtt}}}$

${\boxed{\text{Drops per Eye per Dose} = 2 \, \text{gtt}}}$

${\boxed{\text{Number of Eyes Treated} = 2 \, \text{eyes (OU)}}}$

${\boxed{\text{Drops per Dose} = 2 \, \text{gtt/eye} \times 2 \, \text{eyes} = 4 \, \text{gtt}}}$

${\boxed{\text{Doses per Diem} = 1 \, \text{dose/day}}}$

${\boxed{\Rightarrow \text{Drops per Diem} = \frac{4 \, \text{gtt}}{1 \, \text{dose}} \times \frac{1 \, \text{dose}}{1 \, \text{day}} = \frac{4 \, \text{gtt}}{1 \, \text{day}} = 4 \, \text{gtt/day}}}$

${\boxed{\Rightarrow \text{Days Supply} = \frac{100 \, \text{gtt}}{4 \, \text{gtt/day}} = \frac{100}{1} \times \frac{1 \, \text{day}}{4} = 25 \, \text{days}}}$

---

## 🌬️ Aerosols

### 💨 Nebulized Solutions

**Billable Quantity**: Volume (mL)  
**Clinical Quantity**: Based on **container**; **whole vials**

🔠 **Abbreviations**:

- **By Nebulizer**: `per neb`
- **Handheld Nebulizer**: `HHN`

🔢 **Formula**:

${\boxed{\text{Vials per Diem} = \text{Vials per Dose} \times \text{Doses per Diem}}}$

${\boxed{\text{Days Supply} = \frac{\text{Vials Dispensed}}{\text{Vials Per Diem}}}}$

>- 📍 Each nebulizer vial is unit-dose (e.g., 2.5 mL each)  
>- 📍 Do **not** assume volume-use fractions; vials are **not** split

📘 **Example**:

**Sig**: `i vial via HHN QHS # XXV vials (2.5mL each)`

==> `Inhale 1 vial via handheld nebulizer every night`

${\boxed{\text{Vials Dispensed} = 25 \, \text{vials}}}$  

${\boxed{\text{Vials Per Diem} = 1 \, \text{vial/day}}}$  

${\boxed{\Rightarrow \text{Days Supply} = \frac{25 \, \text{vials}}{1 \, \text{vial/day}} = 25 \, \text{days}}}$

> 🚨 Do **not** use total volume (e.g., 2.5 mL × 25 = 62.5 mL) to calculate days supply. Use **vial count** and **dosing frequency** only.

---

### 🔫 Metered-Dose Inhalers (MDIs) & Sprays

**Billable Quantity**:

- Based on **container**  
- Mass (g) for Dry Powder Cartridges
- Volume (mL) for Liquid Mist Sprays

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

## 🧪 Specialized Dosing Schedules

**Billable Quantity**: Varies
**Clinical Quantity**: Total number of **doses** administered over a **calendar schedule**

🔠 **Common Terms**:

- **Loading dose**: High starting dose, then taper
- **Fixed taper**: Dose decreases or increases over time
- **Packaged therapy**: Manufacturer-defined duration (e.g., Z-Pak, Medrol Dosepak, Monistat, OCPs)

🔢 **Formula**:

${\boxed{\text{Days Supply} = \text{Total Calendar Days Covered by Instructions}}}$

>- 🚨 **Do not** calculate based solely on quantity or max daily dose  
>- 🛡️ Use labeled **day-by-day schedule** if provided  
>- 🛡️ Document pack-based durations in notes or comments fields if system-calculated days supply differs

### 📦 **Example: Z-Pak (Azithromycin 250 mg)**

**Sig**: `Take 2 tablets on day 1, then 1 tablet daily on days 2–5 #6 tabs`  
==> **Days Supply = 5 calendar days**

### 🌸 **Example: Monistat 7 (Miconazole 100 mg Vaginal Cream)**

**Sig**: `Insert 1 applicatorful vaginally at bedtime for 7 nights #7 prefilled applicators`  
==> One dose nightly × 7 nights

${\boxed{\text{Doses per Day} = 1}}$  
${\boxed{\text{Total Doses} = 7}}$  
${\boxed{\text{Days Supply} = 7}}$

>- 📌 Applicators are single-use, prefilled  
>- 🛡️ System-calculated supply based on quantity = 7, but still requires documentation if used **PRN** or **shortened**

### 💊 **Example: Combined Oral Contraceptive (OCP)**

**Sig**: `Take 1 tablet daily #28-day pack`  
==> Common contraceptive schedule

- **21 active tablets** (hormonal)  
- **7 placebo tablets** (reminder/inert)

${\boxed{\text{Tablets Dispensed} = 28}}$  
${\boxed{\text{Tablets per Day} = 1}}$  
${\boxed{\text{Days Supply} = \frac{28 \, \text{tab}}{1 \, \text{tab/day}} = 28 \, \text{days}}}$

>- 📌 If dispensing a **3-month supply** (e.g., 84 active + 7 placebos × 3), adjust days supply accordingly  
>- 🛡️ Ensure consistent labeling between **dispensed quantity** and **cycle length**  
>- 🛡️ Clarify if patient is **skipping placebos** or using for **noncontraceptive indication**

## 💉 Insulin: Special Considerations for Days' Supply

Insulin is dosed in **Units**, but dispensed and billed by **volume (mL)**. Most insulins are **U-100** (100 Units/mL), though higher concentrations exist (e.g., U-200, U-300, U-500). The most common package sizes are:

- **Vial**: 10 mL (1,000 Units for U-100)
- **Pen**: 3 mL (300 Units for U-100)

📍 **Opened insulin products expire 28 days after first use**, even if medication remains. Days’ supply is limited by:

- **Daily usage** (Units/day)
- **Package volume** (Units total)
- **Post-opening expiration period** (usually 28 days)

🛡️ The correct Days Supply is the **shorter of**:

- How long the volume lasts based on dose
- The product’s discard period

This prevents billing beyond usable shelf-life and supports safe patient use.

🔗 See [Days Supply Calculations for Insulin](./insulin_days_supply.md)

---

- 🔙🔗 [**Mathematics Concepts Directory**](./readme.md)
