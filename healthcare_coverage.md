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

## ⚙️ Adjudication, Claims, & Billing

- **Claims** refer to the electronic submissions that a pharmacy sends to an insurance company or PBM (Pharmacy Benefit Manager) to request payment for a dispensed prescription.
- **Adjudication** is the real-time process where insurance (via the PBM) evaluates a prescription claim. It determines coverage, patient cost, and whether the prescription is accepted or rejected.
- **Billing** is the step that follows adjudication. If the claim is accepted, billing finalizes the transaction: the PBM pays the pharmacy a contracted reimbursement amount, and the patient is charged their portion.
- **Third Party Rejections (TPR)** are claim denials from the insurance due to eligibility or processing errors that may be resolved with corrections.

### 👤 Patient Intake & Coordination of Benefits (COB)

Before a prescription can be processed or billed, a patient profile must be created in the pharmacy management system. This includes entering key information that ensures accuracy during claim adjudication and compliance with regulations.

🔗 See: [New Patient Intake SOP](./sop/new_patient_intake.md)

When patients have more than one plan, **COB** determines which is billed first and it:

- Prevents duplicate payments for the same service or prescription.
- Ensures the correct insurer is billed first to avoid claim denials or delays.
- Helps the pharmacy calculate the patient’s true out-of-pocket cost.

| Term | Meaning |
|------|---------|
| **Primary Insurance** | Pays first up to its coverage limits. |
| **Secondary Insurance** | Pays some or all of what the primary didn’t cover. |
| **Tertiary Insurance**  | Rare third plan that covers remaining costs. |

#### 🔑 Rules for Determining Insurance Hierarchy

The correct order of insurance coverage is based on **standard coordination rules** used by insurers and PBMs. Pharmacy technicians must gather all active insurance cards and apply the following logic:

1. **Non-Medicare Adults (Two or More Private Insurances)**
   - The plan that **covers the patient as a subscriber** (employee, policyholder) is **primary**.
   - The plan that **covers the patient as a dependent** (e.g., through a spouse) is **secondary**.
2. **Dependent Children: The Birthday Rule**
   - The parent whose **birth month and day (MM/DD)** occurs first in the calendar year has the **primary plan**.
     - Example: Parent A (March 10) vs. Parent B (July 5) → Parent A’s plan is primary.
     - 📍 The year of birth is *not* considered—only month and day.
   - If both parents share the same birthday, the plan that has **covered the parent longer** becomes primary.
3. **Children with Divorced or Separated Parents**
   - If a court order specifies which parent is financially responsible for healthcare, **follow that order**.
   - If no court order:
     1. The plan of the parent **with custody** is primary.
     2. Then the plan of the **custodial parent’s spouse** (stepparent) is secondary.
     3. The plan of the **non-custodial parent** is tertiary.
4. **Tricare and VA**
   - **VA prescriptions must be filled at VA pharmacies**. Do not bill Tricare or commercial plans for VA-issued scripts.
   - **Tricare** may be primary or secondary depending on whether the patient has other coverage. Confirm eligibility through Tricare’s system.
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
|-----------|----------|------------------------|
| **Subscriber vs. Dependent** | Two private insurances on an adult | Applies only to adults |
| **Birthday Rule** | Two parents insuring a child, no divorce | Yes, takes precedence over subscriber rule for children |
| **Divorce Rule** | Child of divorced or separated parents | Yes, overrides the birthday rule |
| **Medicare Coordination** | Patient has Medicare + other coverage | Medicare’s federal rules override private plan conventions |
| **Tricare / VA** | Military or veteran coverage involved | VA prescriptions not billed externally; Tricare billing rules apply separately |
| 🐻 **Medi-Cal as Payer of Last Resort** | Dual-eligible patients in CA | Yes, Medi-Cal always billed last |

> 🛡️ Incorrect COB setup leads to claim denials or full patient cost. Watch for Third Party Rejections like “other coverage primary”. Verify COB at patient intake and refer unclear COB issues to pharmacist or billing staff.

<!-- todo implement -->
| Term | Meaning | Key Info |
|------|---------|----------|
| ⚠️ **Prior Authorization (PA)** | A **requirement for approval** before certain drugs or services are covered. | Often applies to expensive or non-preferred medications. |
