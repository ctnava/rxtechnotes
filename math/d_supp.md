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
