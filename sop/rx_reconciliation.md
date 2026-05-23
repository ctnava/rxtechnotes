# Medication Reconciliation for Assisting with MTM Services

## Definitions

### Medication Reconciliation

**Medication Reconciliation** is the process of comparing medications a patient is taking (and should be taking) with newly ordered medication in order to resolve discrepancies or potential problems.

This process was developed to ensure clinicians do not inadvertantly add, change, or leave out medications, write duplications, or cause unwanted interactions, and to communicate accurate information to all relevant caregivers.

### NPSG.03.06.01

The Joint Commission developed National Patient Safety Goal (NPSG) **NPSG.03.06.01** to maintain & communicate accurate patient medication information.

This goal applies to:

- Ambulatory Care
- Behavioral Health Care
- Critical Access Hospitals
- Home Care
- Hospitals
- Long Term Care
- Office-based Surgery Settings

#### NPSG Performance Recommendations

- Obtain and/or update information on medications the patient is currently taking. This information is documented in a list or other format that is useful to those who manage medications.
- Compare the medication information the patient brought to the organization/ is currently taking with the medications ordered for the patient by the organization in order to identify & resolve discrepancies.
- Provide the patient (or family as needed) with written information on the medications the patient should be taking when they leave the organization's care.
- Explain the importance of managing medication information to the patient (individual).

### The Joint Commission's Definition of Medication

**Medications**, as defined by TJC, are:

- prescription medications
- sample medications
- herbal remedies
- vitamins
- nutraceuticals
- vaccines
- Over-the-Counter Drugs
  - *prescription optional*
- diagnostic & contrast agents used on or administered to diagnose, treat, or prevent disease or other abnormal conditions
- radioactive medications
- respiratory therapy treatments
- parenteral nutrition
- blood derivatives
- Intravaneous Solutions (plain, with electrolytes and/ or drugs)
- any product designated by the FDA as a drug

### For the Purpose of Reconciliation

**Medications**, for the purpose of reconciliation, include:

- Prescriptions, over-the counter drugs, herbal & dietary supplements
- Substances that may have an impact on the patient's care & treatments
- Substances that may interact with other therapies potentially used during the medical care episode

---

## Personnel

### Pharmacy Technician

Pharmacy technician's main responsibilities are to:

- Research & document patient medication histories
  - Noting omissions or unclear information
- Support physicians, nurses, & pharmacists in program facilitation
- Assist with the logistics of patient medication transfer
- Provide translation assistance services for patients not fluent in English

### Pharmacist

The pharmacist will perform clinical review of the collected medication history; noting omissions, duplications, contraindications, or unclear information. This report is passed to the provider.

### Physician

The provider will make clinical decisions based on the pharmacist's input & provided reconciliation report.

---

## Medication Reconciliation Workflow

```mermaid
flowchart TD

    %% --- Pharmacy Technician Lane ---
    subgraph TECH[Pharmacy Technician]
        A["Develop List of Current Medications"]
        B["Develop List of New Medications (To Be Prescribed)"]
        I["Communicate Final Medication List to Caregivers & Patient"]
    end

    %% --- Pharmacist Lane ---
    subgraph PHARM[Pharmacist]
        C["Compare Current vs New Medication Lists"]
        D["Identify Omissions, Duplications, Interactions, Contraindications"]
        E["Communicate Findings to Physician"]
    end

    %% --- Physician Lane ---
    subgraph MD[Physician]
        F["Review Pharmacist Recommendations"]
        G["Make Clinical Decisions & Finalize Medication Plan"]
    end

    %% --- Workflow Connections ---
    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> I
```

---

## Medication History Workflow

Medication history collection begins with a **direct patient interview** and is the foundation of accurate medication reconciliation.

A high‑quality history reduces medication errors, improves MTM outcomes, and ensures safe transitions of care.

### Medication History Tips

- Ask **open‑ended questions** that cannot be answered with yes/no.  
- Prompt the patient or caregiver to think beyond “typical” medications.  
- Document clearly, concisely, and consistently.  
- Verify information using **multiple sources** whenever possible.

**Common Errors to Watch For**:

- Omitted medications  
- Medications listed but **not actually being taken**  
- Missing information (dose, route, frequency)  
- LASA (Look‑Alike Sound‑Alike) medication confusion  
- Errors in transcription or data entry

Always document **where each piece of information came from** (patient, caregiver, pill bottles, pharmacy, EHR, etc.).

### 1. Interview preparation

Before speaking with the patient:

- Review available EHR data, prior medication lists, and recent provider notes.  
- Identify high‑risk medications or disease states requiring closer attention.

Ask the patient to bring **all medications**, including:

- Creams, lotions, solutions, syrups  
- Sprays, inhalers, eye drops  
- Insulin vials, pens, injections  
- Nasal sprays, nebulizers  
- Over‑the‑counter medications  
- PRN (“as needed”) medications  
- Herbal products  
- Food supplements

### 2. Introductions

Begin with a professional, patient‑centered introduction:

- Confirm patient identity using **name and date of birth**.  
- Explain the purpose of the medication history and how it improves their care.  
- Ask about:
  - Medication allergies  
  - Food allergies  
  - Environmental allergies  
  - Reactions (not just “yes/no”)
- Determine how many pharmacies (including mail‑order) and providers the patient uses.  
- Identify each pharmacy and prescriber for later verification.

### 3. Determine Medications

Review and individually verify **each medication** (OTC & Rx) with the patient or caregiver.

For every medication, obtain:

- **Name** (brand/generic, abbreviations, formulations)  
  - Patient may know brand or generic name
- **Dosage form**  
- **Dose & strength**  
  - To determine amount of active ingredient
- **Frequency** (directions for use)  
- **Duration** (how long they’ve taken it)  
- **Route of administration**  
- **Indication** (why they take it)  
  - indication is critical for MTM and deprescribing decisions

> Any information the patient provides may be incomplete or incorrect.  
> Verification is essential.

Also gather the same information for **herbal medications, supplements, and OTC products**.

Helpful prompts:

- “What do you take for pain?”  
- “What medications do you take only sometimes or as needed?”  
- “What do you buy off the shelf?”  
- “What do you take if you have allergies?”

### 4. Determine Compliance & Identify Possible Issues

Clarify **how** the patient is actually taking their medications:

- “In the last week, how many doses did you miss?”  
- “When was the last time you took your blood pressure medicine?”  

Identify barriers:

- Side effects  
- Cost  
- Forgetfulness  
- Difficulty opening bottles or using devices  
- Misunderstanding directions

If the patient is non‑compliant, ask:

- “What do you not like about your medications?”  
- “Is cost ever a factor?”  
- “Have you noticed any side effects?”

### 5. Educate the Patient on the Importance

Explain why maintaining and carrying an accurate medication list matters:

- Many providers are unaware of medications prescribed by others.  
- OTCs and supplements can interact with prescription drugs.  
- An accurate list reduces the risk of medication errors.  

Encourage the patient to:

- Update their list after **every** provider visit or hospital discharge.  
- Bring the list to **all** appointments, pharmacy visits, and care transitions.  

### 6. Cross-Examination

Ask for permission to contact family or caregivers to fill in gaps:

- “Is there someone at home who can read your medication labels to us?”  

After the interview:

- Call **all pharmacies** the patient uses to cross‑reference active prescriptions.  
- Document any discrepancies found.

### 7. Gather Pending Medications

Review pending or newly ordered medications in the EHR:

- Identify new prescriptions  
- Identify discontinued medications  
- Identify dose changes

### 8. Submit Report to Pharmacist & Provider

Provide the completed medication history to the pharmacist for clinical review.

The pharmacist will:

- Compare current vs new medications  
- Identify omissions, duplications, interactions, contraindications  
- Communicate findings to the provider  

The provider will:

- Make clinical decisions based on the reconciliation report  

---
