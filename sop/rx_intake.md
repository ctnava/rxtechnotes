# 🛠️ SOP - Prescription Intake & Order Entry

## ⚠️ Step 0: Pre-Entry Checklist

Always check to see if the patient is already in the system

If not, then you will have to perform 🔗 [New Patient Intake](./pt_intake.md)

> Check to see if the patient is using a nickname or initial

Ensure the following are present and updated prior to entering prescriptions:

- Patient allergies
- Current medications
- Insurance changes or eligibility issues
- Clinical red flags
- Prescription legibility and security features (for written Rxs)

### Special Considerations

- ⚠️ **Technicians must not take verbal prescriptions or clarify orders**
- 🔐 Pharmacists should inspect **all incoming** Schedule II Prescriptions
- ⚠️ Pharmacists are required to determine which **OTC medicine** is requested on incoming prescriptions

> If the drug requires compounding or is not available, inform the patient that there will be a delay in filling this prescription

## 🗂️ Step 1: Check for Required Elements

Before processing, verify that the prescription is complete and authentic.

### ✅ Required Elements for Prescriptions

Always refer unclear or incomplete orders to the pharmacist

#### **Prescriber Information**

- Full name, title, office address, phone number
- **NPI** (HIPAA-Mandated National Provider Identifier; managed by NPPES)
- **DEA Number** *(Controlled Substances Only)*: Valid and required on any controlled drug prescription
  - 🐻 CA: Prescriber license type (e.g., MD, DO, DDS) must appear on controlled substance prescriptions.

#### **Patient Identifiers**

- **Required**: Full name and address  
- **Optional**: DOB, weight (important for pediatrics)

#### **Order Details**

- **Date Written**  
  - 🐻 CA: Must be filled within **6 months**
  - Check with the pharmacist to determine if the prescription can be filled if it is more than a few days old
- **Inscription**: Drug name, strength, dosage form, quantity
- **Signa (Sig)**: Complete directions for use
  - if compounded, an ingredients list is also included
- **Refills**: Number authorized
- **Product Selection Code** (optional)  
  - Default = 0 (generic substitution allowed)  
  - Can be a number or **DAW** (Dispense as Written) for brand name only
  - 🐻 CA: “Do Not Substitute” must be handwritten (BPC §4073)
  - 🔗 [Additional Codes](../ref/product_selection.md)

> **🚫 Do NOT Add Information**
>
> Never add or infer information based on what you *think* the prescriber meant.  
>
> If anything is unclear, incomplete, or contradictory, **pause and alert the pharmacist**.

#### **Prescriber Signature**

- **Paper**: Manual (wet ink)
- **Electronic**: Digitally signed via certified e‑prescribing system
- 🐻 CA: Prescriptions for controlled substances must be issued on a **California Security Prescription Form** if not e-prescribed.

> ⚠️ Controlled substances must be transmitted electronically unless exempt (system outage, veterinarian, terminal illness).  
> Refer to 🐻 BPC §688 and the 🦅 21st Century Cures Act.

![Visual Prescription](../ref/img/rx_requirements.PNG)

### 🏥 Additional Requirements for Prescriptions on Medication Orders

![sample medication order](../ref/img/sample_medication_order.PNG)

In hospitals, medication orders must also include:

- Patient hospital ID and room/bed number
- Indication for use (diagnosis or symptom)
- Patient Allergies (in Red Ink)

#### 🔍 Verification Process

Technicians may also screen prescriptions for any that seem inappropriate by flagging orders with potential problems.

1. **Positive ID**: Confirm patient identity (hospital ID, wristband).
2. **Cross‑Reference**: Review EMR for allergies, duplications, interactions, or contraindications.
   - Alert pharmacist to any red flags, allergies, or discrepancies.
3. **Pharmacist Review**:  
   - Required unless using automated dispensing systems under approved protocols.
   - Verify technician privileges per facility policy.

### 🕵️ Detecting Forgery & Tampering

Technicians are responsible for flagging suspicious prescriptions before processing, especially for controlled substances.

#### Common Signs of Forgery

- **Tampering**: Erasures, overwriting, altered or unusual quantities/directions/ combinations
- **Theft**: Stolen or mismatched prescription pads
- **Mismatch**: Inconsistent handwriting or ink color
- **Inappropriate Scope**: Prescriptions outside prescriber’s scope  
  - 🔗 See **Prescriptive Authority Quick Reference** (`../ref/prescribers.md`)
- 🔐 Missing or invalid DEA number
  - ⚠️ Always ensure valid DEA numbers on prescriptions for controlled substances
  - 🔗 Manual checksum validation method: `../math/dea_numbers.md`

#### 🐻 x 🔐 California Security Features

Required for Written Controlled Rxs:

- Watermark
- Thermochromic ink
- Checkboxes for quantity
- Unique serial number

## ✍️ Step 2: Translating the Signa (Sig)

The signa (the "sig") can be best described as `instructions for use` is almost always heavily abbreviated and pharmacy techs are often required to transcribe them for computer entry.

🔗 ([Sig Translation Guide](../ref/sig_translation.md))

> Pharmacy software has automatic translation utilities based on patient preferences

## 📱 Step 3: Calculating Days Supply

The Days Supply refers to how long a prescription will last based on the quantity dispensed and the prescribed dosing instructions. This is used by insurers to determine refill eligibility during adjudication (i.e. The next fill date).

🔗 ([Days Supply Calculation Guide](../math/days_supply.md))

## 💻 Step 4: Initial Claim Submission & Adjudication

When prescriptions are entered, they are automatically checked by pharmacy software for drug-drug, drug-disease, and drug-allergy interactions. From here, claims must be submitted accurately to insurance.

`Most pharmacy software will not print prescriptions until payment is confirmed`

### Patient & Insurance Information

- **Cardholder/Member ID**: Unique ID number for the patient’s insurance cardholder/member.
- **Group Number/ RXGROUP**: The group number associated with the patient's insurance plan.
- **Patient Identifiers**: Patient Name, Birth Date, Sex
- **Relationship Code**: The patient’s relationship to the cardholder (e.g., C=cardholder, S=spouse, D=dependent, O=other).

### Prescription Data

- **Date Written**: The date when the prescription was originally written by the prescriber.
- **Product Selection Code**: Dispense As Written code indicating product selection rules.
- **Days Supply**: The number of days the medication is expected to last based on the dosage.
- **Prescriber ID Number**: Unique ID number for the physician who prescribed the medication.

### Dispensing Data

- **New or Refill**: Indicates if the prescription is new or a refill.
- **Pharmacy ID/ NPI**: Unique pharmacy identifier or National Provider Identifier (NPI) for the dispensing pharmacy.
- **Date Dispensed**: The date when the prescription was dispensed to the patient.
- **Quantity Dispensed**: The amount or quantity of the medication dispensed to the patient for the initial fill.
- **11-Digit NDC**: National Drug Code identifying the medication dispensed.

### Pricing Information

- **Ingredient Cost**: The cost of the medication’s active ingredients.
- **Dispensing Fee**: The fee charged by the pharmacy for dispensing the medication.
- **Total Price**: Total amount charged for the prescription (ingredient cost + dispensing fee).
- **Copay/Deductible**: The portion of the cost the patient is responsible for, based on their plan.
- **Balance Due**: The remaining balance due after insurance payment and copay/deductible.

> ⚠️ **Double-check all billing fields. Incorrect DAW codes, expired refills, or wrong days supply can trigger audits or denials.**

`WATCH FOR DUR ALERTS`

### 🛑 Common Third-Party Rejections & Resolutions

A Third-Party Rejection (TPR) occurs when a prescription claim is denied by the PBM or insurer. These denials appear with a reject code and an associated message.

> ⚠️ **Important**: Never override rejection codes or make clinical decisions. Always escalate unresolved issues or unclear messages to the pharmacist.

| Reject Code | Reason | Resolution |
| ------------- | -------- | ------------ |
| 70 | NDC Not Covered | Use formulary alternative or request PA |
| 75 | Prior Authorization Required | Start PA process per plan requirements |
| 76 | Plan Limitations Exceeded | Verify day supply, quantity, duration |
| 79 | Refill Too Soon | Confirm last fill date; resubmit later |
| 25 | Invalid Birth Date | Recheck DOB with patient or insurer |
| 26 | Invalid Person Code | Confirm relationship to cardholder |
| 41 | Invalid Cardholder ID | Verify and update insurance information |

> 📌 **Tech Tip**: Always verify **BIN/PCN/ID** against the latest insurance card. Incorrect values will route claims to the wrong PBM, resulting in instant rejections.

#### 📝 Prior Authorization (PA)

A **Prior Authorization (PA)** is a formal approval process required by insurance companies or PBMs before they will pay for certain prescriptions. A PA TPR is triggered when the insurer needs clinical justification for covering a drug that falls outside standard coverage rules.

> 📌 Some prescription drugs can still be purchased without insurance if the patient pays out-of-pocket.

🔑 **Common Reasons a PA Is Required**:

- **Non-formulary drugs**
- **Brand-name drugs** when generics are available
- **High-cost or specialty medications**
- **Drugs with step therapy requirements**
- **Medications flagged for safety concerns** (e.g., opioids, biologics)

> 🚨 These rules are set by PBMs and insurers—not by the pharmacy.

##### 🧾 PA Workflow

Pharmacy technicians may assist the pharmacist with the following PA tasks:

1. **Identify the rejection**
   - Look for `reject code 75` or `PA Required` messages.
   - Verify that the patient has no alternative coverage.
2. **Notify the pharmacist**
   - Pharmacist must confirm if a PA is appropriate or if a formulary alternative is preferred.
3. **Assist with documentation**
   - Gather relevant prescription data, insurance info, and rejection messages.
   - Help collect clinical data (e.g., diagnosis, trial history) from prescriber’s office.
4. **Submit PA request**
   - May use electronic PA (ePA) tools, insurer web portals, or fax forms (under pharmacist supervision).
   - Track submission and document status in the patient’s profile.
5. **Inform the patient**
   - Set clear expectations: PA approval typically takes **1–3 business days**.
   - Encourage follow-up with the prescriber for urgent requests.
   - 🛡️ Always inform the pharmacist immediately if the medication is urgently needed or if the patient is in distress.
6. **Resolving Denials**
   - The **pharmacist** may:
     - Notify the prescriber to review insurer notes and appeal if appropriate.
     - File an appeal or exception request, often requiring updated clinical documentation.
   - The **technician** may:
     - Assist in identifying the reason for denial.
     - Recheck documentation and ensure nothing was missed.
     - Track appeal submissions and timelines, but pharmacists handle clinical portions.
     - 🛡️ Appeals are time-sensitive. Always escalate denials immediately to the pharmacist or billing specialist.

> 🛡️ Note date/time of PA submission, patient notification, and any escalation.
> .
> 🚨 PAs are **not required for emergency/life-threatening prescriptions** under federal rules, but this must be determined by the pharmacist.

###### 📲 PBM Portals

Pharmacy technicians commonly access PBM portals to:

- Check real-time claim status
- Review drug coverage, formulary tier, and PA requirements
- Confirm patient eligibility and copays
- View or download PA forms and status updates
- Troubleshoot error messages or incomplete PA submissions

> 📌 Portals may vary by PBM. Examples include CoverMyMeds, SureScripts, OptumRx, Express Scripts, CVS Caremark, and Medi-Cal Rx.

---

## 🐻 Special Considerations (California)

- **CURES Reporting** (CA’s PDMP): All Schedule II–IV drugs must be reported to CURES within 1 business day of dispensing. Pharmacists are required to consult CURES before issuing or filling most Schedule II–IV prescriptions.
  - 🔗 [More Information on Controlled Substances](../law/csa_cmea.md)
- **Medi-Cal Claims**: May require **Treatment Authorization Requests (TARs)** and submission of **diagnosis codes**.
- **Technician Documentation**: Technicians must document actions in accordance with facility SOPs (e.g., initials on data entry logs, audit trails, or EMR time-stamped entries).

> 🖇 Certified e-prescribing systems must retain digital logs for auditing, especially for controlled substances.

### 🚫 Technician Limitations (BPC §4115)

Technician scope of practice is governed by **California Law (BPC §4115)**. These limitations are **state-level** and apply in all California practice settings. Federal law defers technician-specific practice rules to state boards.

Technicians **must not**:

- Take verbal orders
- Make clinical judgments
- Perform final prescription verification
- Override **Drug Utilization Review (DUR)** alerts or warnings
  - These are alerts notifying the pharmacist of a potential drug safety (**interactions or allergies**) or billing concern
  - Notify the pharmacist immediately

Technicians **may**:

- Enter data from valid prescriptions
- Assist with claim processing and troubleshooting
- Notify pharmacists of issues or red flags

> ⚠️ When in doubt, stop and escalate to the pharmacist.

### Verbal Orders

- **Non‑Controlled Verbal Orders**: Must be signed by the prescriber within **48 hours** (Title 22, §70747)
- 🔐 **Schedule II Emergency Verbal Orders**:
  - Allowed only in **bona fide emergencies**
  - Follow‑up written & signed prescription must include:
    - The phrase **“Authorization for Emergency Dispensing”**
    - The **date** of the oral order
  - Must be received within **7 days** of oral authorization
  - Failure to receive requires pharmacist to **notify the DEA**  
    (21 CFR §1306.11(d); CCR §1745)

### 🔐 Faxed Schedule II Prescriptions (Valid as Original Only If…)

- Patient is in a **Long‑Term Care Facility (LTCF)**
- Patient is in **hospice** (must be noted on Rx)
- Prescription is for a **compounded product** for direct administration (e.g., IV infusion)

---

## Navlinks

🔙🔗 Back to [**Prescription Processing Workflows**](./prescriptions.md#prescription-intake--billing)
