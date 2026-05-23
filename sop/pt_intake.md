# 🛠️ SOP - New Patient Intake

## 📜 Notification of Privacy Practices (NPP)

Before entering any patient data, the patient must review and sign the **Notice of Privacy Practices (NPP)**, as required by **HIPAA**. This confirms the patient understands how their health information will be used and protected.

## 👤 Patient Profile Creation

Once privacy documentation is complete, create the patient profile in the **pharmacy management system**. This includes entering key information that ensures accuracy during claim adjudication and compliance with regulations.

### 🔑 Required Fields

- 🆔 **Identifiers**
  - Full legal name  
  - Date of birth  
  - Legal sex  
  - Address (from government-issued ID) and contact information (e.g. phone number)
  - (If system allows) **Preferred name** for respectful communication
- 💳 **Insurance & Billing Information**
  - Use current insurance card  
  - See section below for required fields
- 📋 **Clinical Documentation**
  - Allergies (or "NKA" if none)  
  - Health conditions (e.g. diabetes, asthma)  
  - Medication history
- 📦 **Service Preferences**
  - Automatic Refills
  - Child-resistant packaging waiver  
  - Mail Delivery
  - Manufacturer/formulation preferences  
  - Messaging (SMS/ Phone/ e-mail)
    - prescription ready notice
    - refill reminders/ confirmation
    - insurance dispute notifications
    - other important alerts
- 🏥 **(Institutional Only)**
  - Principal Diagnosis
  - Room/bed assignment
  - Hospital ID number (if applicable)

> 🛡️ Always confirm details directly with the patient and verify against ID and insurance card. Errors may cause claim rejections or clinical risks.

## 💳 Insurance & Billing Information

Patients with prescription drug benefits through private healthcare plans are often issued **separate Prescription Drugs Benefits Cards** for billing.

Enter all pharmacy benefit data **exactly as it appears** on the insurance card. Use the **member name and sex as printed**, even if different from government-issued identification documents, to prevent claim rejection during adjudication.

> ⚠️ Always use the **most recent** card. Outdated info results in Third Party Rejections.

✅ **Required Insurance Fields**

| Information | Category | Description |
| ------------- | ---------- | ------------- |
| **Card Issuer Name/Logo** | Insurer Identifier | Name or logo of the insurance company issuing the card. |
| **Card Issuer ID** | Insurer Identifier | If Applicable; Unique ID for the insurance company that issued the card. |
| **Member Name** | Patient Identifier | As Printed on card; Full name of the patient as listed on the insurance card. |
| **Member ID** | Patient Identifier | Required for Billing; Unique identification number for the patient under the plan. |
| **Person Codes** | Patient Identifier | If Listed; Identifiers for specific individuals covered (e.g., primary member, spouse). |
| **Group Number** | Patient Identifier | Identifies the patient's insurance plan group. |
| **Gender/ Sex** | Patient Identifier | As Listed on Insurance Card; Gender/ Sex of the patient. |
| **Date of Birth** | Patient Identifier | Required for Adjudication; The patient's date of birth. |
| **Card Issue/Effective Date** | Billing & Claims | Date when the insurance coverage began or card was issued. |
| **RXBIN** | Billing & Claims | If Listed; Bank Identification Number for pharmacy claims processing. |
| **RXPCN** | Billing & Claims | If Listed; Processor Control Number used for managing prescription claims. |
| **RXGROUP** | Billing & Claims | If Listed; Group Plan Identifier (Use **Group Number** if not listed). |
| **Co-pay Info** | Billing & Claims | If Listed/ More Informative for Patients; Co-payment amounts for different services (e.g., medications). |
| **Name and Address of Benefit Administrator** | Billing & Claims | Company or agency responsible for managing benefits. |
| **Pharmacy Help Desk Number** | Billing & Claims | Contact number for pharmacies to resolve claim issues. |
| **Phone Number for Member Help Desk** | Patient Use Only | Customer service phone number for patient inquiries. |

> ⚠️ Always verify insurance information annually or when the patient reports a change.

🔄 **Rules for Determining Insurance Hierarchy for Coordination of Benefits (COB)**

When patients have more than one plan, which can sometimes be revealed by Third Party Rejections (e.g. “other coverage primary"), they must be billed in correct order (i.e. primary → secondary → tertiary).

The correct order of insurance coverage is based on **standard coordination rules** used by insurers and PBMs. Pharmacy technicians must gather all active insurance cards and apply the following logic when entering insurance plans:

1. **Non-Medicare Adults (Two or More Private Insurances)**
   - The plan that **covers the patient as a subscriber** (employee, policyholder) is **primary**.
   - The plan that **covers the patient as a dependent** (e.g., through a spouse) is **secondary**.
2. **Dependent Children: The Birthday Rule**
   - The parent whose **birth month and day (MM/DD)** occurs first in the calendar year has the **primary plan**.
     - Example: Parent A (March 10) vs. Parent B (July 5) → Parent A's plan is primary.
     - 📌 The year of birth is *not* considered—only month and day.
   - If both parents share the same birthday, the plan that has **covered the parent longer** becomes primary.
3. **Children with Divorced or Separated Parents**
   - If a court order specifies which parent is financially responsible for healthcare, **follow that order**.
   - If no court order:
     1. The plan of the parent **with custody** is primary.
     2. Then the plan of the **custodial parent's spouse** (stepparent) is secondary.
     3. The plan of the **non-custodial parent** is tertiary.
4. **Tricare and VA**
   - **VA prescriptions must be filled at VA pharmacies**. Do not bill Tricare or commercial plans for VA-issued scripts.
   - **Tricare** may be primary or secondary depending on whether the patient has other coverage. Confirm eligibility through Tricare's system.
5. **Medicare Coordination Rules**
   - **Medicare is usually secondary** if:
     - The patient is **still actively working** and covered by an **employer group health plan** (EGHP).
     - The patient has **retiree insurance** or a **union-sponsored plan** that pays first.
   - **Medicare is primary** if:
     - The patient has **no other insurance** or only has **Medicare Part D** for prescriptions.
   - 🦅x🐻 Some patients may have both **Medi-Cal** and **Medicare**. In that case, Medicare is billed first, and **Medi-Cal is the payer of last resort**.

🤖 **Rule Overrides**

> 🛡️ Choose the **correct rule** based on the **patient's situation**.

| Rule Type | Use When | Overrides Other Rules? |
| ----------- | ---------- | ------------------------ |
| **Subscriber vs. Dependent** | Two private insurances on an adult | Applies only to adults |
| **Birthday Rule** | Two parents insuring a child, no divorce | Yes, takes precedence over subscriber rule for children |
| **Divorce Rule** | Child of divorced or separated parents | Yes, overrides the birthday rule |
| **Medicare Coordination** | Patient has Medicare + other coverage | Medicare's federal rules override private plan conventions |
| **Tricare / VA** | Military or veteran coverage involved | VA prescriptions not billed externally; Tricare billing rules apply separately |
| 🐻 **Medi-Cal as Payer of Last Resort** | Dual-eligible patients in CA | Yes, Medi-Cal always billed last |

> 🛡️ Refer unclear COB issues to pharmacist or billing staff.

## 🧾 Clinical Documentation

### 🧪 Allergies

Ask: “Are you allergic to any medications or anything else?”

- Record all allergies (medications, food, environment)
- If none, document as **NKA** (No Known Allergies)

### 🩺 Health Conditions

Ask if the patient has any diagnosed conditions, chronic or acute:

- Examples: Asthma, diabetes, epilepsy, hypertension

### 💊 Medication History

Ask for a **complete list** of:

- Prescription medications
- OTC drugs (e.g., acetaminophen, diphenhydramine)
- Vitamins and supplements
- Herbal or homeopathic products

**Ask targeted questions** to capture missed items:  
> “Do you take anything for sleep, pain, or colds?”

#### ⚠️ OTC Drug Risks

OTC medications are not automatically safe. They can cause:

- **Drug interactions**
- **Duplicate therapy**
- **Toxicity** (e.g., acetaminophen overuse)

🔗 [More Guidance on OTC Analgesics](../medications/otc_analgesics.md)

> 🩺 **Refer patients to the pharmacist** for counseling if potential issues arise  

---

## ✅ Final Reminders

- Verify and update all records **annually**, or sooner if the patient reports a change.
- Do not delay entry of allergy, insurance, or health condition information.
- All **clinical questions or discrepancies** must be referred to a pharmacist.
- Use discretion when recording sensitive information. Ensure compliance with HIPAA and company policy.

---

## 🗺️🔗 Nav Links

- 🔙 Back to [**Core Pharmacy Workflows & Standard Operating Procedures (SOP)**](../core_operations.md#new-patient-intake)
- 🔙 Back to [**Prescription Intake**](./rx_intake.md#️-step-0-pre-entry-checklist)
- 🔙🔗 Back to [**Healthcare Coverage, Services, & Billing**](../healthcare_coverage.md#-patient-intake--coordination-of-benefits-cob)
