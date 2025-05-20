# 📘 Appendix I: Verification of DEA Numbers

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

> 💡 **Tip**: Many pharmacy systems perform DEA validation automatically, but it’s important to know how to check manually in case of system issues or suspicious prescriptions.
