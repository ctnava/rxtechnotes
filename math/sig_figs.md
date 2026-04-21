# 🔢 Significant Figures (Sig Figs)

<!-- 
## Reference

The Pharmacy Technician, 7e; APhA | Chapter 6
-->

`When working with measured amounts, significant figures provide us with information about the sensitivity of equipment used.`

## 🔑 Key Concepts

Significant figures (**'sig figs'**) are the essential digits in a number that contribute to its **accuracy** & **precision**. The idea behind this is the fact that the precision of your *final answer*, during **multiplication & division**, is bound by the precision of the **limiting factor** (i.e. *least precise data point*).

These rules determine which digits in a number contribute to its measured precision.

| Rule # | Description | Example | Sig Figs Count |
| -------- | ------------- | --------- | ---------------- |
| 1️⃣ | **Nonzero digits are always significant.** | `123` | 3 |
| 2️⃣ | **Zeros between nonzero digits are always significant.** | `101`, `1.008` | 3, 4 |
| 3️⃣ | **Trailing zeros *after* the decimal are always significant.** | `2.300`, `0.450` | 4, 3 |
| 4️⃣ | **Trailing zeros *before* the decimal in numbers ≥ 10 are significant.** | `150.` | 3 |
| 5️⃣ | **Leading zeros (placeholders) are *never* significant.** | `0.0045`, `0.00001` | 2, 1 |

📌 **Atlantic–Pacific Rule**

- If the **decimal point is present** (Pacific), start counting from the **Pacific (left)** side.
- If the **decimal point is absent** (Atlantic), start from the **Atlantic (right)** side.

## ⚙️ Workflow: How to Apply Sig Figs in Calculations

Given: `0X.XX00 ÷ 0Y.0Y0`

### Step 1: Identify significant figures from all numbers

- `0X.XX00` → 5 sig figs  
- `0Y.0Y0` → 4 sig figs
- → Limiting factor = 4 sig figs

### Step 2: Perform the full calculation

`X0.XX0 ÷ 0Y.0Y0 = Z.ZZZZZZZZZ`

### Step 3: Round to match least precise sig fig count

==> `Z.ZZZZZZZZZ ≅ Z.ZZZ` (Rounded, 4 Sig Figs)

## 🧪 Example Calculations Involving Significant Figures

### 📏 Multiplication

Given: `2.34 x 1.2`  

- `2.34` → 3 sig figs  
- `1.2` → 2 sig sigs
- → Limiting factor = 2 sig figs

`2.34 x 1.2 = 2.808`

==> `2.808 ≅ 2.8` (Rounded, 2 Sig Figs)

### ➗ Division

Given: `5.67 / 0.82`

- `5.67` → 3 sig figs  
- `0.82` → 2 sig sigs
- → Limiting factor = 2 sig figs

`5.67 / 0.82 = 6.9146341`

==> `6.9146341 ≅ 6.9` (Rounded, 2 Sig Figs)

### 🧩 Mixed Example

Given: `(602000000000000000000000. x 18.01528) / 16.00`

- `602000000000000000000000.` → 24 sig figs  
- `18.01528` → 7 sig figs  
- `16.00` → 4 sig figs  
- → Limiting factor = 3 sig figs

`6.02 x 18.01528 = 108.4519896`

`108.4519896 x 16.00 = 6.77824935`

==> `6.77824935 ≅ 6.78` (Rounded, 3 Sig Figs)

---

🔗 Back to [**Mathematics Concepts Directory**](./readme.md)
