# Healthcare Coverage, Services, & Billing

## 😷 Healthcare Coverage

Health insurance is a financial agreement where a person or employer pays a **monthly premium** to an insurance company. In exchange, the insurer helps cover medical and prescription costs when care is needed.

Once **enrolled** in a **managed care plan**, patients are typically responsible for:

- An **annual deductible** (initial out-of-pocket spending)
- Then **copayments *and/or* coinsurance** (depending on plan design) after the deductible is met
- Until they reach the **out-of-pocket maximum (OOP Max)**, after which covered services are paid 100% by the plan for the rest of the benefit year.

| Term | Meaning | Key Info |
|------|---------|----------|
| 📅 **Enrollment** | The period when a patient can **sign up for or change** a plan. | Typically during **open enrollment** (fall) or due to a **qualifying life event** (e.g., marriage, birth, job change). |
| 💵 **Premium** | The **monthly payment** for health insurance, paid **regardless of use**. | Higher premium plans usually have lower deductibles or copays. |
| 💳 **Deductible** | The amount a patient pays **out of pocket** before coverage begins. | May be waived for preventive services or some generic drugs. |
| 🏥 **Managed Care Plan**  | A structured healthcare plan that limits costs by controlling how patients receive care. | Includes HMOs, PPOs, POS, and EPOs. Emphasizes coordination and efficiency. |
| 💸 **Copayment (Copay)** | A **fixed amount** (e.g., \$10 or \$50) paid for a service or medication when received. | Typically varies by drug tier or service level. |
| 📊 **Coinsurance** | A **percentage** of the cost paid by the patient after deductible is met (e.g., 20%). | Common for expensive procedures or specialty medications. |
| ⛔ **Out-of-Pocket Maximum (OOP Max)** | The **maximum total** a patient will pay in a year (including deductible, copays, coinsurance but not including premiums). | After this, insurance pays **100%** for covered services. |

### 💼 Pharmacy Benefit Manager (PBM)

Under these **Managed Care Plans**, drug benefits are managed by PBMs. These are *distinct* entities; meaning that they are third-party companies contracted to service plans on behalf of payers (e.g.insurers, employers, Medicare).

| Function | Description |
|----------|-------------|
| 🛍️ **Claims Processing** | Handle real-time claim adjudication. |
| 💲 **Reimbursement Rates** | Set copays and pharmacy payouts. |
| 📋 **Formulary Management** | Create and manage drug tiers. |
| 🔐 **Prior Authorizations** | Require clinical justification for certain drugs. |
| 🤝 **Manufacturer Rebates** | Negotiate discounts for formulary placement. |
| 📦 **Mail-Order Pharmacy** | Operate/contract mail pharmacies for long-term meds. |

> 🤯 CVS Caremark, Express Scripts, & OptumRx manage drug benefits for millions of patients nationwide.

### 💊 Formularies

A **formulary** is a list of prescription drugs that are approved for use and **covered by an insurer, pharmacy benefit manager (PBM), or healthcare institution**. Formularies determine which medications are preferred, **substitutable**, or **reimbursable**, helping control costs and ensure safe, effective therapy.

- **Open Formulary**  
  - Offers **broad coverage** with few restrictions  
  - **Most medications are covered**, including non-preferred drugs  
  - Allows greater flexibility but can result in higher overall costs

- **Closed Formulary**  
  - **Strictly limits** coverage to a specific list of medications  
  - **Non-formulary drugs are not reimbursed** without prior authorization  
  - Helps control spending and standardize treatment

🏥 **Institutional Settings**:

- Controlled by the **Pharmacy & Therapeutics (P&T) Committee**.
- Only stocked medications are dispensed.
- Non-formulary requests or therapeutic substitutions may be required.

🛍️ **In Retail/Insurance Settings**:

- Managed by PBMs (in retail/insurance settings).
- Drugs are divided into **tiers** that affect patient cost:

| Tier | Description |
|------|-------------|
| Tier 1 | Preferred generics (lowest cost) |
| Tier 2 | Preferred brand-name drugs |
| Tier 3 | Non-preferred brands |
| Tier 4+ | High-cost or specialty medications |

### 🏥 Managed Care Programs

Managed care plans are offered by insurers (public and private); structured to control healthcare costs and improve care coordination.

| Plan Type | Description | Referrals Needed? | Out-of-Network Coverage? |
|-----------|-------------|-------------------|-------------------------|
| 🟦 **HMO** (Health Maintenance Organization) | Most restrictive. Requires you to choose a **Primary Care Provider (PCP)** who coordinates all care. | ✅ Yes, for specialists | ❌ No (life-threatening emergencies only) |
| 🟧 **PPO** (Preferred Provider Organization) | Flexible. No need for referrals. Higher cost for out-of-network care. | ❌ No | ✅ Yes (higher cost) |
| 🟨 **POS** (Point of Service) | Hybrid of HMO & PPO. Requires in-network PCP and referrals, but offers some out-of-network coverage. | ✅ Yes | ✅ Yes (with extra cost) |
| 🟪 **EPO** (Exclusive Provider Organization) | Like an HMO, but **no referrals required**, still **no out-of-network coverage** (except life-threatening emergencies). | ❌ No | ❌ No |

> 🛡️ Check insurance cards or PBM portals for plan types. Copays are often tiered based on drug cost.

### Public Health Insurance

Public health insurance refers to a system of healthcare coverage provided by government agencies, such as federal, state, or local governments. It aims to make healthcare accessible and affordable for individuals who may not be able to obtain private health insurance.

🔗 See [Public Healthcare](./insurance/public_health_insurance.md) for more details.

## ⚙️ Claims, Adjudication, & Billing

- **Claims** refer to the electronic submissions that a pharmacy sends to an insurance company or PBM (Pharmacy Benefit Manager) to request payment for a dispensed prescription.
- **Adjudication** is the real-time process where insurance (via the PBM) evaluates a prescription claim. It determines coverage, patient cost, and whether the prescription is accepted or rejected.
- **Billing** is the step that follows adjudication. If the claim is accepted, billing finalizes the transaction: the PBM pays the pharmacy a contracted reimbursement amount, and the patient is charged their portion.
- **Coordination of benefits (COB)** is the process of determining which plan is billed first when patients have more than one plan. It prevents duplicate payments for the same service or prescription, ensures the correct insurer is billed first to avoid claim denials or delays, and helps the pharmacy calculate the patient’s true out-of-pocket cost.
- **Third Party Rejections (TPR)** are claim denials from the insurance due to eligibility or processing errors that may be resolved with corrections.
  - **Prior Authorizations (PA)** are a requirement for approval before certain drugs or services are covered. This often applies to controlled, expensive, or non-preferred medications.

### 👤 Patient Intake & Coordination of Benefits (COB)

Before a prescription can be processed or billed, a patient profile must be created in the pharmacy management system. This includes entering key information that ensures accuracy during claim adjudication and compliance with regulations.

| Term | Meaning |
|------|---------|
| **Primary Insurance** | Pays first up to its coverage limits. |
| **Secondary Insurance** | Pays some or all of what the primary didn’t cover. |
| **Tertiary Insurance**  | Rare third plan that covers remaining costs. |

> 🛡️ Incorrect COB setup leads to claim denials or full patient cost. Watch for Third Party Rejections like “other coverage primary”. Verify COB at patient intake and refer unclear COB issues to pharmacist or billing staff.

🔗 See: [New Patient Intake SOP](./sop/new_patient_intake.md)

#### 🛠️ Workers’ Compensation (Workers’ Comp)

Workers’ compensation is a specialized form of insurance that pays for medical expenses, including prescription drugs, when an employee is injured on the job or develops a **work-related** illness. Workers’ comp claims are standalone and bypass commercial or government payers entirely. They are processed through a **separate billing system**, not the patient's standard PBM or insurance. Most workers’ comp plans use a **dedicated claims processor or pharmacy network** (e.g., Coventry, One Call, Mitchell ScriptAdvisor).

🔑 **When Handling these Claims**:

- **Verify and enter claim information**:
  - Employer’s name
  - Date of injury
  - Workers’ comp claim number
  - Insurance carrier or TPA (Third Party Administrator)
- **Follow billing instructions** provided by the workers’ comp network or adjuster.
- Do **not** bill the patient’s regular insurance.
  - 📍 Incorrect billing to a PBM can delay medication access and violate payer agreements.
- Do **not** collect copays unless specifically instructed by the workers’ comp payer.
  - 📍 Patients typically pay **$0 out of pocket**, but **only for medications authorized by the claims adjuster**.
- If a medication is **denied or not listed**, refer to the pharmacist or contact the claims adjuster.

### 🔁 The Billing Cycle

The billing cycle is a real-time loop that occurs every time a prescription is submitted for insurance billing. It ensures the pharmacy receives reimbursement and the patient is charged correctly.

1. **Prescription Entry**
   - A valid prescription is entered into the pharmacy management system.
   - Key data: prescriber NPI, patient demographics, drug NDC, quantity, days' supply, and DAW code.
2. **Insurance Claim Submission**
   - The system electronically submits the claim to the patient’s **primary insurer** via the PBM.
   - Format: Uses **NCPDP Telecommunication Standard** (e.g., D.0).
   - Includes BIN, PCN, Group ID, Member ID, relationship code, and coordination of benefits if needed.
3. **Real-Time Adjudication**
   - The PBM processes the claim in seconds.
   - It checks:
     - **Eligibility**
     - **Drug coverage and formulary status**
     - **Quantity limits**
     - **Copay tiers**
     - **Prior authorization requirements**
     - **Coordination of benefits (COB)**
4. **Response Returned to Pharmacy**
   - If **accepted** or `paid`:
     - The PBM returns the **approved reimbursement amount** for the pharmacy and the **patient’s copay**.
   - If **rejected**:
     - A `reject` code is returned (e.g., "70 = Product/Service Not Covered", "75 = Prior Authorization Required").
     - The technician must **troubleshoot** or **refer to pharmacist**.
       - `Other Coverage Primary` indicates that COB is incorrect and technicians must confirm plan billing order.
       - `Pending PA` indicates that the plan requires prior authorization and technicians must notify pharmacist to initiate.
       - `Plan Not Found` indicates possible data entry error (e.g. Insurance ID or BIN) and technicians must reverify the card or contact the PBM helpdesk.
5. **Patient Pickup & Payment**
   - If accepted, the patient pays their portion (copay, coinsurance, deductible).
   - If issues persist, patient may be asked to contact insurer or provider.
6. **Secondary/Tertiary Claims (if applicable)**
   - If a secondary or tertiary insurance exists, the remaining balance is submitted to the next payer.
   - Claim uses coordination of benefits fields (e.g., Amount Paid by Primary Plan).
   - Adjudication repeats for the next plan.
7. **Reconciliation & Rebilling**
   - Pharmacies later receive remittance advice and reconcile claims against actual payments.
   - Underpaid, reversed, or clawed-back claims may require **reversal and resubmission**.

> 🛡️ Always verify that the correct insurance plan and COB are set up before submission. Even minor data errors can cause denials or underpayments.

<!-- TODO: Insert Claims & Billing SOP -->

#### 🛑 Common Third-Party Rejections & Resolutions

A Third-Party Rejection (TPR) occurs when a prescription claim is denied by the PBM or insurance. These denials are flagged with a reject code and message explaining the issue.

| Reject Code | Reason | Resolution |
|-------------|--------|------------|
| 70 | NDC Not Covered | Use formulary drug or request PA |
| 75 | Prior Authorization Required | Start PA process |
| 76 | Plan Limitations Exceeded | Check days’ supply, quantity |
| 79 | Refill Too Soon | Check last fill date |
| 25 | Invalid Birth Date | Verify with patient |
| 26 | Invalid Person Code | Confirm patient relationship |
| 41 | Invalid Cardholder ID | Correct insurance info |

> 📍 Always confirm the BIN/PCN/ID from the most recent insurance card. These fields determine where the claim is sent.

##### 📝 Prior Authorization (PA)

A **Prior Authorization (PA)** is a formal approval process required by insurance companies or PBMs before they will pay for certain prescriptions. A PA TPR is triggered when the insurer needs clinical justification for covering a drug that falls outside standard coverage rules.

> 📍 Some prescription drugs can still be purchased without insurance if the patient pays out-of-pocket.

🔑 **Common Reasons a PA Is Required**:

- **Non-formulary drugs**
- **Brand-name drugs** when generics are available
- **High-cost or specialty medications**
- **Drugs with step therapy requirements**
- **Medications flagged for safety concerns** (e.g., opioids, biologics)

> 🚨 These rules are set by PBMs and insurers—not by the pharmacy.

#### 🧾 PA Workflow

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
>
> 🚨 PAs are **not required for emergency/life-threatening prescriptions** under federal rules, but this must be determined by the pharmacist.

##### 📲 PBM Portals

Pharmacy technicians commonly access PBM portals to:

- Check real-time claim status
- Review drug coverage, formulary tier, and PA requirements
- Confirm patient eligibility and copays
- View or download PA forms and status updates
- Troubleshoot error messages or incomplete PA submissions

> 📍 Portals may vary by PBM. Examples include CoverMyMeds, SureScripts, OptumRx, Express Scripts, CVS Caremark, and Medi-Cal Rx.
