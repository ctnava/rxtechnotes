# 📘 Calculating Days' Supply

## Key Concepts

The Days Supply refers to how long a prescription will last based on the quantity dispensed and the prescribed dosing instructions. It is a technical quantity based entirely on math; not a guess, and not just the number of pills dispensed.

**Why It Varies**:

Two patients may receive the **same quantity** of medication but have **different dosing instructions**. For example:

- **Patient A**: Take 1 tablet daily → 30 tablets = 30 days
- **Patient B**: Take 2 tablets daily → 30 tablets = 15 days

**General Calculation**:

`Days Supply = Quantity Dispensed / Amount Taken Per Day`

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
