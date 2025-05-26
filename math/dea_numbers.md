# 📘 Verification of DEA Numbers

A DEA number is a unique identifier assigned by the Drug Enforcement Administration (DEA) to healthcare providers who are authorized to prescribe, dispense, or administer controlled substances. It is assigned when an individual practitioner, pharmacy, hospital/ clinic, or teaching institution files Form 224 with the DEA.

Pharmacy technicians may be required to help verify DEA numbers as part of prescription validation, especially for controlled substances (Schedules II–V).

## 🔢 **DEA Number Format**

A valid DEA number has two letters followed by seven digits:

```nginx
AB1234563
```

**First Letter**: Identifies the registrant type

| Letter  | Registrant Type |
|---------|-----------------|
| A, B, F | Physicians, hospitals, clinics, pharmacies |
| G       | Department of Defense |
| M       | Mid-level practitioners (NPs, PAs, optometrists) |
| X       | Buprenorphine prescribers (DATA-waived providers for opioid use disorder) |

**Second Letter**: Usually the first letter of the prescriber’s last name (e.g., “Smith” → “S”)

## ✅ **Verifying the Check Digit (Mathematical Validation)**

To confirm the validity of the DEA number, use this simple formula based on the last digit:

🔢 Steps:

1. Add the 1st, 3rd, and 5th digits
→ A = 1st + 3rd + 5th
1. Add the 2nd, 4th, and 6th digits, then multiply by 2
→ B = (2nd + 4th + 6th) × 2
1. Add A + B
→ Total = A + B
1. The last digit of the total must match the 7th digit (the check digit) of the DEA number.

## ⚠️ **Important Reminders**

- DEA numbers are required for all prescriptions involving controlled substances.
- Pharmacies must keep DEA numbers on file and ensure the prescriber’s authority.
- Invalid or altered DEA numbers are a red flag for fraudulent prescriptions and must be reported to the pharmacist immediately.

## 🌐 Online DEA Number Verification

DEA number verification can also be conducted using **online resources**, though **only authorized parties** such as pharmacies, law enforcement, and healthcare institutions may access official DEA registrant databases.

### 🦅x🐻 Legal Note

Pharmacy technicians in California are permitted to **assist with DEA number validation**, but **access to official DEA registrant databases** may be restricted to pharmacists or other credentialed staff depending on facility policy.

### 🔗 Verification Resources

| Resource | Description |
|----------|-------------|
| ✅ **DEA Diversion Control Division** | [https://www.deadiversion.usdoj.gov](https://www.deadiversion.usdoj.gov) — Official site for DEA registration, forms, and updates |
| ✅ **NABP PMP InterConnect** | A multi-state prescription monitoring system that may cross-check DEA registration indirectly |
| ✅ **State Licensing Boards** | Many prescriber license lookups include DEA status |
| ✅ **Pharmacy Management Systems** | Commercial systems (e.g., PioneerRx, QS/1, McKesson) often include DEA auto-validation |
| ⚠️ **Third-party Lookup Tools** | Use caution. Only rely on services with verified access to DEA data |

## 🚨 Best Practices

- 🛡️ Use **official sources or trusted pharmacy software** for verification
- 📍 If unsure about a prescriber’s authority, **consult the pharmacist**
- 🛡️ Keep a **record of any manual or external verification** performed, especially if it affects dispensing decisions
- 🚨 **Never fill a controlled substance** prescription with a questionable or unverifiable DEA number without pharmacist review

> 💡 **Tip**: If you're working in a setting without direct DEA lookup access, **ask the pharmacist** to verify or use their credentials on registered platforms.

🔗 Back to [**Mathematics Concepts Directory**](./readme.md)
