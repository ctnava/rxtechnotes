# 🔁 SOP - Prescription Intake & Order Entry

Prescriptions and medication orders are instructions from a licensed medical practitioner that authorize the provision of a drug or device to a patient.

- **Medication Order**: A written or transcribed (verbal/telephone) order issued in an **inpatient** setting (e.g., hospital).
- **Prescription**: A medication order written on a prescription blank to be filled in an **outpatient/ambulatory** setting.

## 🗂️ Step 1: Check for Required Elements

Before processing, the pharmacy technician must review prescriptions for completeness and authenticity.

### ✅ Required Elements for Prescriptions

- **Prescriber Information**
  - Full name, title, office address, phone number
  - **Prescriber NPI**: National Provider Identifier (HIPAA-mandated; managed by NPPES)
  - **DEA Number** *(Controlled Substances Only)*: Valid and required on any controlled drug prescription
  - 🐻 **California Law**
    - **Prescriber License Type** *(Controlled Substances Only)*: (e.g., MD, DO, DDS)
- **Patient Identifiers**
  - **Required**: Full name and address
  - **Optional**: Date of birth and weight (especially for pediatrics)
- **Order Details**
  - **Date Written**: The date the prescriber issued the prescriptions
    - 🐻 **California Law**: *must be filled within 6 months*
  - **Inscription**
    - **Name**: Generic and/or brand (if specified)
    - **Strength**, **Dosage Form**, **Quantity**
  - **Signa (Sig)**: Complete instructions for use
  - **Refill Instructions**: Number of refills permitted
  - **Product Selection Code (Optional)**: Product selection code to indicate if substitution is allowed; default 0 (generic substitution allowed)
    - 🐻 **California Law**: Prescriber must write “Do Not Substitute” in their own handwriting to prohibit substitution (per BPC §4073)
- **Prescriber Signature**
  - Must be **manual (wet ink)** for paper prescriptions.
  - Must be **digitally signed and transmitted through a certified e-prescribing system** for electronic prescriptions.
    - 🐻 **California Law**: prescriptions for controlled substances must be issued on a **California Security Prescription Form** if not e-prescribed.

> ⚠️ **Controlled Substances must be transmitted electronically** unless exempt (e.g., system outages, veterinarian, terminal illness). Refer to BPC §688 and the 21st Century Cures Act.

## ⚠️ Pre-Entry Checklist

- Patient allergies
- Current medications
- Insurance changes or eligibility issues
- Clinical red flags
- Prescription legibility and security features (for written Rxs)

> ⚠️ **Technicians must not take verbal prescriptions or clarify orders.** Always refer unclear or incomplete orders to the pharmacist.

### 🏥 Inpatient Medication Orders

In hospital settings, medication orders require additional fields:

- **Patient Hospital ID** & Room/Bed number
- **Indication for Use**: Diagnosis or symptom
- 🐻 **California Law**
  - **Prescriber Signature**: For verbal orders, prescriber must sign within 48 hours (Title 22, §70747)

> ⚠️ **Schedule II Controlled Substances cannot be ordered verbally**, except in **bona fide emergencies** and **only by a prescriber**. In such cases, a **follow-up prescription** must be:
>
> - **Written**,  
> - **Dated**, and  
> - **Counter-signed by the prescriber**,  
>
> and received by the pharmacy **within 7 days** of the emergency oral authorization.
>
> If the prescriber fails to provide the written prescription within this timeframe, the pharmacist must **notify the DEA** (21 CFR §1306.11(d); CCR §1745).

### Verification Process

1. **Positive ID**: Confirm patient identity using hospital ID and wristband.
2. **Cross-Reference**: Scan the patient’s EMR for contraindications or duplication.
   - Alert pharmacist to any red flags, allergies, or discrepancies.
3. Only proceed with entry **after pharmacist review and approval**, unless using **automated medication systems** with pre-approved protocols. Verify system scope and tech privileges per facility policy.

## 🕵️‍♀️ Step 2: Detecting Forgery & Tampering

Technicians are responsible for flagging suspicious prescriptions before processing, especially for controlled substances.

### Common Signs of Forgery

- **Tampering**: Erasure, overwriting, or altered quantities/directions
- **Theft**: Use of stolen preprinted prescription pads
- **Mismatch**: Inconsistent handwriting or ink color, unusual instructions
- **Discretion**: Quantities unusually high for diagnosis
- 🐻 **California Law**
  - Lack of CA-required security features (e.g., watermark, checkboxes, thermochromatic ink)

> ⚠️ **Always validate DEA numbers for controlled substances**. Use automated tools or manual checksum methods.

🔗 ([DEA Number Verification](../math/i_dea_numbers.md))

## ✍️ Step 3: Translating the Signa (Sig)

Technicians must accurately convert prescriber shorthand into full instructions.

### ✅ Required Elements in Sig

- Action Verb (e.g. Take, Apply, Inject)
- Dose and Dosage Form
- Route of Administration
  - Site of Administration (for hospitals)
- Frequency & Duration of Use
- Timing (e.g., with meals, at bedtime)

**Example**:  
`℞ i tab po bid pc #30` →  
`Take 1 tablet by mouth twice daily after meals`

> ⚠️ **Errors in sig translation can cause incorrect dosing or days supply. Confirm unclear abbreviations with a pharmacist.**

🔗 ([Abbreviation Reference Table](../prescriptions/iv_translation.md))

## 📱 Step 4: Calculating Days Supply

The Days Supply refers to how long a prescription will last based on the quantity dispensed and the prescribed dosing instructions. This is used by insurers to determine refill eligibility during adjudication.

**Formula**:  
`Days Supply = Quantity Dispensed / Daily Allowance of Medication`

**Rules:**

- Round **down** to the nearest whole day
- Days supply should be calculated based on **maximum daily usage**
- Consider split dosing and package-size limitations (e.g., inhalers, patches)

🔗 ([Days Supply Calculation Guide](../math/ii_days_supply.md))

## 💻 Step 5: Claim Submission & Adjudication

After prescription entry, claims must be submitted accurately to insurance.

### Patient & Insurance Information

- **Cardholder/Member ID**: Unique ID number for the patient’s insurance cardholder/member.
- **Group Number/ RXGROUP**: The group number associated with the patient's insurance plan.
- **Patient Identifiers**: Patient Name, Birth Date, Sex
- **Relationship Code**: The patient’s relationship to the cardholder (e.g., C=cardholder, S=spouse, D=dependent, O=other).

### Prescription Data

- **Date Written**: The date when the prescription was originally written by the prescriber.
- **Product Selection Code**: Dispense As Written code indicating product selection rules. ([Reference Table](../prescriptions/iii_product_selection.md))
- **Days Supply**: The number of days the medication is expected to last based on the dosage.
- **Prescriber ID Number**: Unique ID number for the physician who prescribed the medication.

### Dispensing Data

- **New or Refill**: Indicates if the prescription is new or a refill.
- **Pharmacy ID/ NPI**: Unique pharmacy identifier or National Provider Identifier (NPI) for the dispensing pharmacy.
- **Date Dispensed**: The date when the prescription was dispensed to the patient.
- **Quantity Dispensed**: The amount or quantity of the medication dispensed to the patient.
- **NDC**: National Drug Code identifying the medication dispensed.

### Pricing Information

- **Ingredient Cost**: The cost of the medication’s active ingredients.
- **Dispensing Fee**: The fee charged by the pharmacy for dispensing the medication.
- **Total Price**: Total amount charged for the prescription (ingredient cost + dispensing fee).
- **Copay/Deductible**: The portion of the cost the patient is responsible for, based on their plan.
- **Balance Due**: The remaining balance due after insurance payment and copay/deductible.

> ⚠️ **Double-check all billing fields. Incorrect DAW codes, expired refills, or wrong days supply can trigger audits or denials.**

### 🛑 Third-Party Rejections & Resolutions

A Third-Party Rejection (TPR) occurs when a prescription claim is denied by the PBM or insurer. These denials appear with a reject code and an associated message.

> ⚠️ **Important**: Never override rejection codes or make clinical decisions. Always escalate unresolved issues or unclear messages to the pharmacist.

| Reject Code | Reason | Resolution |
|-------------|--------|------------|
| 70 | NDC Not Covered | Use formulary alternative or request PA |
| 75 | Prior Authorization Required | Start PA process per plan requirements |
| 76 | Plan Limitations Exceeded | Verify day supply, quantity, duration |
| 79 | Refill Too Soon | Confirm last fill date; resubmit later |
| 25 | Invalid Birth Date | Recheck DOB with patient or insurer |
| 26 | Invalid Person Code | Confirm relationship to cardholder |
| 41 | Invalid Cardholder ID | Verify and update insurance information  |

> 📍 **Tech Tip**: Always verify **BIN/PCN/ID** against the latest insurance card. Incorrect values will route claims to the wrong PBM, resulting in instant rejections.

---

## 🐻 Special Considerations (California)

- **CURES Reporting** (CA’s PDMP): All Schedule II–IV drugs must be reported to CURES within 1 business day of dispensing. Pharmacists are required to consult CURES before issuing or filling most Schedule II–IV prescriptions.
  - 🔗 ([More Information on Controlled Substances](../prescriptions/ii_controlled_listed_substances.md))
- **Medi-Cal Claims**: May require **Treatment Authorization Requests (TARs)** and submission of **diagnosis codes**.
- **Technician Documentation**: Technicians must document actions in accordance with facility SOPs (e.g., initials on data entry logs).

### 🚫 Technician Limitations (BPC §4115)

Technician scope of practice is governed by **California Law (BPC §4115)**. These limitations are **state-level** and apply in all California practice settings. Federal law defers technician-specific practice rules to state boards.

Technicians **must not**:

- Take verbal orders
- Make clinical judgments
- Perform final prescription verification
- Override DUR alerts or contact prescribers

Technicians **may**:

- Enter data from valid prescriptions
- Assist with claim processing and troubleshooting
- Notify pharmacists of issues or red flags

> ⚠️ When in doubt, stop and escalate to the pharmacist.

## ✅ Technician Field Readiness Checklist

- [ ] Familiar with CA prescription security and eRx rules
- [ ] Can identify complete vs incomplete prescriptions
- [ ] Can translate and enter sigs accurately
- [ ] Understands technician scope of practice
- [ ] Can calculate days supply and flag inconsistencies
- [ ] Knows when to refer to pharmacist (DUR, forgery, unclear orders)
