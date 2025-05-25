# Roman Numeral System

Roman numerals are a non-positional numeral system originating from ancient Rome. They are still used today in certain contexts, such as on clocks, outlines, monarch names, and some medical or pharmaceutical labels (e.g. cranial nerves, Schedule classes).

## 🔑 Basic Roman Numerals

| Symbol | Value |
|--------|-------|
| I      | 1     |
| V      | 5     |
| X      | 10    |
| L      | 50    |
| C      | 100   |
| D      | 500   |
| M      | 1000  |

## 🧮 Combining Symbols

Roman numerals are typically formed by combining symbols **left to right**, adding or subtracting values based on position:

- **Add** values when a symbol is followed by one of **equal or lesser** value.
  - Example: `VI` = 5 + 1 = **6**
- **Subtract** when a smaller value **precedes** a larger one.
  - Example: `IV` = 5 - 1 = **4**

> - 🚨 Only powers of ten (I, X, C) and V can be used to subtract.
> - 🚨 No symbol can be repeated more than **three times** in a row.

## 🔁 Converting Roman to Arabic (Integer)

To convert a Roman numeral into Arabic (standard number form):

1. Read the Roman numeral **left to right**.
2. Compare each symbol to the one **to its right**:
   - If the current symbol is **smaller**, subtract it.
   - If the current symbol is **equal or larger**, add it.

### Example: `MCMXCIV`

Breakdown:

- M (1000) → next is C (100), smaller → **add 1000**
- C (100) → next is M (1000), smaller → **subtract 100**
- M (1000) → next is X (10), smaller → **add 1000**
- X (10) → next is C (100), smaller → **subtract 10**
- C (100) → next is I (1), larger → **add 100**
- I (1) → next is V (5), smaller → **subtract 1**
- V (5) → end → **add 5**

Total: 1000 - 100 + 1000 - 10 + 100 - 1 + 5 = **1994**

## 🔁 Converting Arabic (Integer) to Roman

To convert an Arabic number into a Roman numeral:

1. Start with the **largest possible Roman value** and work down.
2. Subtract as you go and append the symbol(s).

### Conversion Table (for constructing Roman numerals)

| Value | Symbol |
|--------|--------|
| 1000  | M      |
| 900   | CM     |
| 500   | D      |
| 400   | CD     |
| 100   | C      |
| 90    | XC     |
| 50    | L      |
| 40    | XL     |
| 10    | X      |
| 9     | IX     |
| 5     | V      |
| 4     | IV     |
| 1     | I      |

### Example: `944`

Start from highest value that fits:

- 900 → CM (944 - 900 = 44)
- 40 → XL (44 - 40 = 4)
- 4 → IV

Final Roman numeral: **CMXLIV**

## ✅ Tips and Reminders

- Repeat only **I, X, C, M**, and only up to **3 times**.
- Never subtract more than one order of magnitude (e.g., `IC` for 99 is invalid; use `XCIX`).
- Roman numerals are case-insensitive but typically written **in uppercase**.

<!-- 
## Reference

Pharmacy Calculations, 6e; Morton Publishing | Chapter 1
-->
