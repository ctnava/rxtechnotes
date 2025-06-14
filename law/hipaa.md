# Health Information Privacy

## Health Information Portability & Accountability Act (HIPAA, 1996)

`requires all health-care professionals to protect patients' privacy`

<!-- Regulating how Covered Entities handle Protected Health Information (PHI) -->

HIPAA was originally enacted to protect individuals' access to health insurance when changing jobs or living with pre-existing conditions. It has since evolved into a broad federal standard for the protection of **Protected Health Information (PHI)** and governs how healthcare providers, insurers, and other entities handle patient information.

### 🔑 Primary Objectives

- Maintain continuity of health insurance coverage
- Standardize electronic health transactions
- Reduce administrative fraud and burden on consumers
- Protect patient health information from misuse, theft, or inappropriate disclosure

> 📌 HIPAA is enforced by the U.S. Department of Health and Human Services (HHS), primarily through the **Office for Civil Rights (OCR)**.

### 🔗 Covered Entities

`any person, business, or institution that provides healthcare or keeps records on patients`

**Covered Entities** are subject to HIPAA because they transmit health information (*in any form*) in connection with standard transactions. They include:

- **Healthcare Providers**: Physicians, clinics, hospitals, pharmacists, pharmacies
- **Health Plans**: Insurers, employer-sponsored plans, HMOs, Medicare, Medicaid
- **Healthcare Clearinghouses**: Third parties that process nonstandard data into standard formats

> 🛡️ Business Associates (e.g. billing services, IT contractors) are regulated under HITECH.

### 🕵️‍♀️ Protected Health Information (PHI)

PHI refers to any information, in any form, that can identify a patient and relates to their health status (*past, present, or future*), healthcare services, or payment. This includes:

- **Verbal**: oral communications or information (e.g. conversations about care or billing)
- **Paper Documents**: written communications or information (e.g. Charts, faxes, prescriptions, printouts)
- **Electronic (ePHI)**: digital communications or information (e.g. Emails, EHRs, cloud storage, mobile devices)
- **Identifiers**: in any form (e.g. Name, DOB, address, SSN, MRN, phone number, photographs)

> 🚨 PHI remains protected **50 years after death** unless an exception applies.

### 🔓 HIPAA Privacy Rule

`HIPAA requires health care providers to make their best efforts to protect patient information and share only the information needed with other health professionals.`

- **Notice of Privacy Practices (NPP)**:
  - Informs patients of their rights and how PHI is used
  - Patients must acknowledge receipt
  - Retention: 6 years from date of signature or last effective date.
- **Disclosure Protocol**: PHI may only be used or disclosed for treatment, payment, and healthcare operations (TPO) without patient authorization.
- **Minimum Necessary Rule**: Disclose only the least amount of PHI required for the purpose; keeping disclosures on a “need to know” basis and gathering the minimum amount of data.
- **Authorization Required**: For marketing, research, or sharing with third parties not involved in TPO.
- **National Provider Identifier**: A 10-digit, unique ID assigned to each covered provider. Required on all HIPAA-compliant transactions.

#### 🧾 Release of Information (ROI)

Patient authorization for PHI disclosure must be documented via a **valid ROI form**. These are typically used to transfer PHI to another healthcare facility or patient personal use. Valid authorization requests include:

- Specific description of the information
- Name of recipient
- Expiration date or event
- Signature and date

### 🛡️ HIPAA Security Rule

The **HIPAA Security Rule** specifically governs **electronic Protected Health Information (ePHI)**. It requires covered entities to implement **administrative, technical, and physical safeguards** to ensure the confidentiality, integrity, and availability of patient data.

#### 🔧 Administrative Safeguards

- Implement **written policies**, **procedures**, and **standard operating protocols (SOPs)**
- Conduct **employee training** on HIPAA and data security best practices
- Designate a **Security Officer** responsible for oversight and compliance
- Perform **risk assessments** to identify vulnerabilities in data protection
- Apply **role-based access controls** that define who can see or alter what data

#### 💻 Technical Safeguards

These apply to any electronic system that stores or transmits PHI:

- **Access Controls**:  
  - Systems must limit access to authorized personnel only  
  - Each user is given **unique login credentials** (username and password)  
  - Access is limited based on the user’s job function (e.g. technician vs pharmacist)  
    - 📌 **Role-Based Access** is mandatory under HIPAA: Staff should only have access to the **minimum necessary** PHI required to perform their assigned duties.

- **Encryption**:  
  - Data is transformed into an unreadable format using a digital key  
  - Only users with the correct decryption credentials can access the information  
  - Encryption is especially important during **data transmission** over networks (e.g. emails, uploads)

- **Audit Logs**:  
  - Systems must keep **timestamped records of all user activity**  
  - This includes logins, logouts, system changes, medication orders, and patient record access  
  - Audit logs are used for **security audits**, **breach investigations**, and **accountability tracking**
  - **Do not share your login credentials** because all actions taken under your login are legally attributed to *you*

- **Automatic Logoff and Timeout Settings**:  
  - Systems should log off users automatically after a period of inactivity  
  - Prevents unauthorized access when a workstation is left unattended

#### 🏥 Physical Safeguards

Physical security protocols protect the hardware and locations where ePHI is accessed or stored:

- **Workstation Security**:  
  - Log out or lock the screen when stepping away from a computer  
  - Position screens away from public view (use privacy filters if needed)  
  - Never leave printed PHI unattended in public or shared spaces

- **Access Control to Facilities**:  
  - Use **ID badges**, **key cards**, or **biometrics** to restrict entry  
  - Only authorized personnel are allowed in medication rooms, server areas, or data storage locations

- **Secure Storage of Paper Records**:  
  - Even though the Security Rule applies to *ePHI*, paper documents often contain the same information  
  - Store printed records in **locked cabinets** and **shred** when no longer needed

> 🛡️ Pharmacy technicians are expected to follow all access control policies, maintain credential security, and report any suspected HIPAA violations immediately.

### 💊 Pharmacy-Specific HIPAA Requirements

Pharmacies must:

- Train staff on HIPAA at regular intervals
- Post and offer patients a Notice of Privacy Practices
- Provide access to PHI upon patient request (within 30 days)
- Appoint a **Privacy Officer** and maintain written policies
- Shred, de-identify, or securely dispose of all PHI **separately from other trash**
- Prevent unauthorized verbal disclosure (including casual conversations)
- have conversations about PHI in private areas

> 🚨 HIPAA prohibits disclosure of PHI to family or spouses without patient authorization. Generally speaking, do not provide information to anyone unless specifically directed by the pharmacist. Exception: if the patient is present and does not object, or if professional judgment determines it is in the patient's best interest.

### ⚠️ Violations & Penalties

#### 🛑 Common Violations

- Sharing PHI (e.g. with spouses and relatives) without **express consent** from the patient
- Discussing PHI in public areas (i.e. **gossip**)
- Accessing a patient’s chart without a valid reason
- Disposing of printed PHI in regular trash
- Failing to encrypt portable devices

> - 📌 Being in contact with PHI means that you are now governed under HIPAA
> - 🚨 While not *technically* a violation, accessing your own records without following proper protocol is considered bad practice

#### 📅 Breach Notification Rule

- **≥ 500 affected**: Notify OCR, affected individuals, and local media within **60 days**
- **< 500 affected**: Log and report to OCR **annually**

#### 💸 Civil & Criminal Penalties

| Violation Type | Penalty |
|----------------|---------|
| Unknowing | $100 to $50,000 per violation |
| Reasonable Cause | $1,000 to $50,000 |
| Willful Neglect (Corrected) | $10,000 to $50,000 |
| Willful Neglect (Uncorrected) | Minimum $50,000 |
| Knowingly misusing PHI | Up to $250,000 + up to 10 years in prison |

> ✅ Penalties are based on **harm caused**, **intent**, and **effort to correct** the violation.

#### 🚨 Special Situations

`HIPAA allows the sharing of PHI under emergency situations such as natural disasters where people may be evacuated and require healthcare.`

- **Emergencies & Disasters**: PHI may be shared for care coordination, family notification, and to reduce risk, but must still follow the “minimum necessary” standard. Privacy notices must be delivered as soon as practical.
- **Incidental Disclosures**: Not a violation if reasonable safeguards are in place (e.g., overheard info at a pharmacy counter with barriers).

### 📚 Supplemental Materials

- 🔗 VIDEO | [How Gossip Can Cause HIPAA Violations](https://www.youtube.com/watch?v=CXGDq7IHgSQ)
- 🔗 VIDEO | [HIPAA Training: What is Required for Compliance](https://www.youtube.com/watch?v=CXGDq7IHgSQ)
- 🔗 HANDBOOK | [HIPAA Survival Guide](./hipaa_survival_guide.pdf)

## 🤯 Health Information Technology for Economic & Clinical Health Act (HITECH, 2009)

`Amends HIPAA`

- Expands HIPAA by extending accountability to **Business Associates**
- Promotes **Electronic Health Records (EHR)** and defines **Meaningful Use** standards
- Requires secure **Electronic Data Interchange (EDI)** for billing and records
- Increases penalties for non-compliance

> 🤯 HITECH ties HIPAA compliance to federal incentive programs for technology adoption and mandates stricter breach reporting.

---

## 🗺️🔗 Nav Links

- 🦅 [Federal Law Reference Directory](../readme.md)
- 🔙 [Professional Communication Standards](../ref/pharmacy_communication.md#types-of-communication)
