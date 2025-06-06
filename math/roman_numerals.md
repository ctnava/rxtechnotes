# Roman Numeral System

<!-- 
## Reference

Pharmacy Calculations, 6e; Morton Publishing | Chapter 1
-->

`The amount of a drug in its manufactured or prescribed form is always stated numerically; that is with numbers.`

In pharmacy calculations, two primary numeral systems may appear: **Arabic numerals** and **Roman numerals**. Understanding both is essential for interpreting medication labels, documentation, schedules, and historical references in medical texts.

- **Numeral**: A written symbol that represents a number.
- **Arabic numerals**: The standard, **base-10 positional** number system used in most of the world today.
- **Roman numerals**: A **non-positional** numeral system developed in ancient Rome, still used in specialized contexts.

## 1️⃣ Arabic Numerals

Arabic numerals are what we use every day in pharmacy and general arithmetic:

`0, 1, 2, 3, 4, 5, 6, 7, 8, 9`

### 🔑 Key Characteristics

- **Positional**: The value of a digit depends on its position (e.g., 3 in 300 = three hundreds).
- **Base-10**: Each digit represents a power of ten.
- **Widely used** in all pharmacy math, dosage calculations, and labeling.

## 2️⃣ Roman Numerals

Roman numerals use letters from the Latin alphabet to represent values:

| Roman | Arabic |
|--------|--------|
| I      | 1      |
| V      | 5      |
| X      | 10     |
| L      | 50     |
| C      | 100    |
| D      | 500    |
| M      | 1000   |

Roman numerals appear in:

- Cranial nerve designations (e.g., **CN VII** = Facial Nerve)
- Controlled substance schedules (e.g., **Schedule II**)
- Medical outlines, monarch names (e.g., **Henry VIII**)
- Clocks and numbering systems in formal documents

> 🛡️ Roman numerals may still appear on **older prescription labels**, **institutional records**, and **package inserts**, especially for controlled substances.

### 🧮 Combining Symbols

Roman numerals are typically formed by combining symbols **left to right**, adding or subtracting values based on position:

- **Add** values when a symbol is followed by one of **equal or lesser** value.
  - Example: `VI` = 5 + 1 = **6**
- **Subtract** when a smaller value **precedes** a larger one.
  - Example: `IV` = 5 - 1 = **4**

> - 🚨 Only powers of ten (I, X, C) and V can be used to subtract.
> - 🚨 No symbol can be repeated more than **three times** in a row.

### ✅ Tips and Reminders

- Repeat only **I, X, C, M**, and only up to **3 times**.
- Never subtract more than one order of magnitude (e.g., `IC` for 99 is invalid; use `XCIX`).
- Roman numerals are case-insensitive but typically written **in uppercase**.

### 🔁 Converting Roman to Arabic (Integer)

To convert a Roman numeral into Arabic (standard number form):

1. Read the Roman numeral **left to right**.
2. Compare each symbol to the one **to its right**:
   - If the current symbol is **smaller**, subtract it.
   - If the current symbol is **equal or larger**, add it.

#### Example: `MCMXCIV`

Breakdown:

- M (1000) → next is C (100), smaller → **add 1000**
- C (100) → next is M (1000), smaller → **subtract 100**
- M (1000) → next is X (10), smaller → **add 1000**
- X (10) → next is C (100), smaller → **subtract 10**
- C (100) → next is I (1), larger → **add 100**
- I (1) → next is V (5), smaller → **subtract 1**
- V (5) → end → **add 5**

Total: 1000 - 100 + 1000 - 10 + 100 - 1 + 5 = **1994**

### 🔁 Converting Arabic (Integer) to Roman

To convert an Arabic number into a Roman numeral:

1. Start with the **largest possible Roman value** and work down.
2. Subtract as you go and append the symbol(s).

#### Conversion Table (for constructing Roman numerals)

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

#### Example: `944`

Start from highest value that fits:

- 900 → CM (944 - 900 = 44)
- 40 → XL (44 - 40 = 4)
- 4 → IV

Final Roman numeral: **CMXLIV**

---

🔗 Back to [**Mathematics Concepts Directory**](./readme.md)
