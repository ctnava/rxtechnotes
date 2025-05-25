# 📘 Calculating Days Supply

The Days Supply refers to how long a prescription will last based on the quantity dispensed and the prescribed dosing instructions. This is used by insurers to determine refill eligibility during adjudication.

**Formula**:  
`Days Supply = Quantity Dispensed / Daily Allowance of Medication`

**Rules:**

- Round **down** to the nearest whole day
- Days supply should be calculated based on **maximum daily usage**
- Consider split dosing and package-size limitations (e.g., inhalers, patches)

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
