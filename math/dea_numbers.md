# 🔐 Verifying DEA Numbers

- 🔙🔗 [DEA Policy](../law/csa_cmea.md#-prescriber--pharmacy-responsibilities)

---

A **DEA number** is a unique identifier issued by the Drug Enforcement Administration (DEA) to entities authorized to **prescribe, dispense, or administer controlled substances** (Schedules II–V). It is assigned when an individual practitioner, pharmacy, hospital/ clinic, or teaching institution files **Form 224** with the DEA.

Pharmacy technicians may assist in DEA number verification as part of controlled substance prescription screening.

## 🔑 DEA Number Structure

A valid DEA number contains **two letters followed by seven digits**:

```plaintext
AB1234563
```

| Position | Meaning |
|----------|---------|
| **1st letter** | Registrant type (see below) |
| **2nd letter** | Usually the **first letter of the prescriber’s last name** |
| **7th digit** | **Check digit**, used for mathematical validation |

### 📁 First Letter: Registrant Type

| Letter  | Registrant Type |
|---------|-----------------|
| A, B, F | Physicians, hospitals, clinics, pharmacies |
| G       | Department of Defense Contractors |
| M       | Mid-level practitioners (NPs, PAs, optometrists) |
| X       | Buprenorphine prescribers (DATA-waived providers for opioid use disorder) |

> 📍 X may precede or replace the first letter depending on transition status under the SUPPORT Act.

### 🔢 DEA Number Validation Formula

To verify the DEA number’s **check digit**, apply this 4-step calculation.

==> Given the number `AB1234563`

🔢 Steps:

| Step | Operation | Example |
|------|-----------|---------|
| 1    | Add the 1st, 3rd, and 5th digits | 1 + 3 + 5 = **9** |
| 2    | Add the 2nd, 4th, and 6th digits, then multiply by 2 | (2 + 4 + 6) × 2 = 12 × 2 = **24** |
| 3    | Add the results from step 1 and 2 | 9 + 24 = **33** |
| 4    | **Last digit** of the total must match the **7th digit** | 33 === **3** = 7th digit ✅ |

> 🚨 If the final digit doesn't match, **flag for pharmacist review**.

## 🛡️ Controlled Substance Dispensing Rules

- DEA numbers are **required for all controlled substance prescriptions**
- Prescriber must be **registered and authorized** to issue the medication ordered.
- Invalid DEA numbers are **red flags for fraud** and require **immediate escalation**, flag for pharmacist review.

## 🌐 Online DEA Number Verification

DEA number verification can also be conducted using **online resources**, though **only authorized parties** such as pharmacies, law enforcement, and healthcare institutions may access official DEA registrant databases.

| Source | Use |
|--------|-----|
| ✅ [DEA Diversion Control Division](https://www.deadiversion.usdoj.gov) | Official DEA registrant data |
| ✅ NABP PMP InterConnect | Indirect verification via multi-state monitoring |
| ✅ State Medical Boards | Often include DEA registration status |
| ✅ Pharmacy Software (PioneerRx, QS/1, etc.) | DEA pattern-matching, auto-validation |
| ⚠️ Third-party tools | Use **only** if verified and approved by your facility |

> 🛡️ DEA verification **must not be done using Google searches or untrusted sites**.

### 🦅x🐻 Legal & Practice Considerations (California)

- Pharmacy technicians **can assist** in DEA number validation.
- Direct access to DEA databases is often restricted to **pharmacists** or **credentialed users**.
- Facility policies may limit how DEA numbers are stored, checked, or printed.

## Best Practices for Technicians

- 🔐 Use only **verified systems** or **pharmacist-approved methods**
- 📍 Cross-check the **last name initial** and **check digit math**
- 🛡️ Document any **manual verification** done outside normal software
- 🚨 Report **suspicious** or **unverifiable DEA numbers** immediately
- 🩺 When in doubt, **consult the pharmacist**
- 💡 If you're unsure or can't validate, **don’t process the prescription without pharmacist review**.

---

🔗 Back to [**Mathematics Concepts Directory**](./readme.md)
