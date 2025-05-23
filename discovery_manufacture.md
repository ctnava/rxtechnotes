# Production, Marketing, & Distribution of Medicine

🦅 The **U.S. Food and Drug Administration (FDA)** is the primary federal agency responsible for ensuring that drugs are manufactured, labeled, and marketed in compliance with public safety standards. Under the **Federal Food, Drug, and Cosmetic Act (FDCA)**, the FDA enforces rules prohibiting:

- **Adulteration**: Contamination or failure to meet specified purity and quality standards.
- **Misbranding**: False, misleading, confusing, or incomplete labeling, or if the product is harmful when used as labeled.

## 🏭 Manufacturing

Drug manufacturers must comply with stringent FDA standards during production and distribution. **Good Manufacturing Practices (GMP)** are FDA-enforced standards ensuring drug consistency, safety, and quality. Strengthened by the 🦅 **Kefauver-Harris Amendment (1962)**, GMPs apply to all manufacturers.

GMP compliance requires manufacturers to:

- Use validated, standardized manufacturing processes
- Maintain hygienic, climate-controlled facilities
- Employ qualified personnel with documented training
- Keep detailed batch and quality control records
- Conduct internal audits and allow FDA inspections

🚨 Failure to meet GMP standards may result in:

- Product recalls
- Civil and criminal penalties
- Suspension or revocation of manufacturing licenses

📌 *Pharmacy technicians may encounter GMP topics during FDA recalls, QA investigations, or sterile/non-sterile compounding workflows.*

There exist two commercial categories of drugs:

- **Brand Name Drugs**: Original drugs developed by pharmaceutical companies, protected by patents, and marketed under proprietary names
- **Generic Drugs**: Copies of brand-name drugs that have the same active ingredients, strength, dosage form, and route of administration, but sold under generic chemical names or different brand names after the original patent expires

## Drug Development, Manufacturing Authorization, & Marketing

### Brand Name Drug Development

In order for a newly patented, *Brand Name* drug to come to market, the FDA must first approve it. The process generally is as follows

Step 1: **Research & Development** (3-6 Years)

- Identify a biological target
- Screen compounds for activity and specificity
- Select ~25% of promising candidates for preclinical testing

Step 2: **Preclinical Testing** (1 Year)

- Conduct **in vitro** (human cells) tests for efficacy & toxicity
- Conduct **in vivo** (animal) tests to study ADME (Absorption, Distribution, Metabolism, and Excretion) processes
- Test in at least two mammalian species.
- Submit results and a clinical plan to the FDA's CDER in an ***Investigational New Drug (IND)*** application. This application additionally requires a plan for human testing and manufacturing details to comply with the ***Good Manufacturing Practices (GMP)*** provisioned by the Kefauver-Harris Amendment.

Step 3: **Clinical Trials** (4-7 Years)

Clinical trials involve human research subjects and are conducted in three phases. Participants must give informed consent and the information necessary to provide it (per Kefauver-Harris Amendment). They are free to leave as they wish.

- **Phase 1 (20 - 80 People)**: Determine ***safety*** first by collecting a profile of side effects in a small group of healthy volunteers over ***several months***.
- **Phase 2 (100-300 People)**: Determine ***efficacy*** by testing it on a group of patients with the condition that the drug is trying to treat while also staying on the look out for side effects for ***several months to 2 years***. Controlled trials are also used to compare the drug's activity against a placebo. This test is double-blind, meaning that neither the patients nor the prescribers are aware that the drug is a placebo.
- **Phase 3 (1,000 - 3,000 People)**: Confirm ***efficacy*** while collecting ***additional safety*** data in a larger population. Also gathering data on interactions and effects at different ***dosages*** for ***1 to 4 years***.

> 📌 Pediatric clinical trials can take place after Phase 2 or 3 Adult trials if the company is trying to get the drug approved for use in children.

Step 4: **Review & Approval** (1-2 Years)

- Pharmaceutical company files a ***New Drug Application (NDA)*** with the FDA
- FDA reviews for safety, efficacy, and labeling
- Drug is either approved for marketing (regulated by the Kefauver-Harris Amendment) or denied by the FDA and request further testing

Step 5: **Post-Market Surveillance** (Ongoing)

- Manufacturer maintains exclusive rights (~20 years) to offset research & development cost
- Continuous monitoring of long-term safety and efficacy after the drug is released to the market

### Generic Drug Manufacturing Authorization

Once a patent for a brand name drug expires, other manufacturers may copy the drug and release it under its generic name. Generic drugs require FDA approval but do not require full R&D because clinical trials for safety & efficacy were already established by the original producer. To obtain approval, generic manufacturers only need to demonstrate equivalency; shortening the process to 1 - 3 years.

Step 1: **Bioequivalence Studies**

During this process, the manufacturer must prove that their drug is both pharmaceutically and therapeutically equivalent because their inactive ingredients have been altered.

- **Pharmaceutically Equivalent Drugs** contain identical amounts of the same active ingredients in the same dosage form.
- **Therapeutically Equivalent Drugs** produce the same clinical effect.

Studies are conducted on a small group of healthy volunteers to compare the generic and brand-name drug's effects on ADME processes. After which, the manufacturer submits an **Abbreviated New Drug Application (ANDA)** to the FDA.

Step 2: **Manufacturing & Quality Assurance**

The FDA checks for trademark violations. Packaging and labeling must be distinct from brand name. Inactive ingredients may vary to lower production cost, but a facility inspection is also conducted to ensure compliance with the aforementioned ***Good Manufacturing Practices (GMP)***.

Step 3: **Post-Market Surveillance**

If the ANDA meets FDA requirements, the generic drug is approved for marketing. Generic drugs are also subject to the same post-market safety monitoring as brand name drugs.

## 🏷️ Labeling & Distribution

<!-- TODO Needs work -->

Drug labeling serves both clinical and legal functions. It communicates critical product information and is regulated by multiple federal laws to ensure safety, traceability, and proper usage.

- The name and place of business of the manufacturer, packer, or distributor (FPLA)
- An accurate statement of the quantity of the contents (by weight, measure, or count) (FPLA)
- A clear declaration of the product’s identity and intended use (FPLA)
- National Drug Code (per the Drug Listing Act)
  - 🤯 NATO Stock Number (NSN) is the military analog to the NDC.
- All prescription drugs must be labeled with a unique product identifier, including a Global Trade Identification Number (GTIN), serial number, lot number, and expiration date. barcodes too (DSCSA)
  - **Linear Barcodes (1D)** appear as stripes that can be read forward or backwards and encodes NDC. Used for stock checks.
  - **Matrix Barcodes (2D)** appear as squares with black or white pixels; encoding NDC, batch, and expiration. Used in prescription filling to verify the correct product is being used.
- label controlled drugs with their classification or schedule. (CSA)
- **Tall Man Lettering** (ISMP-endorsed) is encouraged to distinguish look-alike/sound-alike medications (e.g. **hydrOXYzine** vs **hydrALAZINE**).

National Drug Code (NDC)

***11-digit National Drug Code (NDC)***; a 3-segmented universal identifier.

| Segment | Digits | Description |
|---------|--------|-------------|
| Labeler Code | 5 | Identifies the manufacturer or distributor (FDA-assigned) |
| Product Code | 4 | Identifies drug, strength, and dosage form |
| Package Code | 2 | Identifies package size and type |

> 📌 NDCs can appear as 10-digit variations on packaging. For databases and claims, they are normalized to **11-digit** format with leading zeros (e.g. `0517-0420-01` ➡ `00517-0420-01`).

## Public Safety

### Risk Evaluation & Mitigation Strategies (REMS)

In some cases, the FDA may require additional safety measures for high-risk medications after they are brought to market. **Risk Evaluation & Mitigation Strategies (REMS)** are required safety programs for medications with known or potential serious risks that must be managed to ensure that the drug’s benefits outweigh its risks; particularly those that are addictive (e.g. Opioids, Stimulants, Benzodiazepines), hazardous (e.g. Birth Control, Oncologics, Biologics), or understudied (e.g. Gabapentin).

Depending on the drug, a REMS program may include one or more of the following:

- Mandated **Medication guides** or **patient package inserts (PPIs)**
- Prescriber training and certification requirements
- Pharmacy certification and restricted dispensing systems
- Enrollment of patients in registries or special monitoring programs

> **Example**: The drug isotretinoin (Accutane), which can cause severe birth defects, is subject to a REMS program called iPLEDGE that requires prescribers, pharmacies, and patients to follow strict steps before dispensing or receiving the medication.

### Monitoring & Recalls

While drug approval processes are thorough, it is impossible to account for everything. The FDA maintains reporting programs called **MedWatch** and the **Vaccine Adverse Event Reporting System (VAERS)** that allow anyone to report adverse effects that occur from the use of approved drugs or vaccines. If the FDA determines that any drug or vaccine poses a public health risk, then they may file an injunction to prevent distribution; seize the drug from the manufacturer; or issue a recall of the drug.

<!-- Todo: 🔗 Filing MedWatch & VAERS Complaints SOP Document Link -->

> Recalls are the most cost-effective because they leverage the manufacturer's current infrastructure and knowledge to retrieve offending drugs. Shipping manifests are used to identify where a drug has been delivered in order to focus efforts on that area.

There are 3 numerical classes of recalls.

| Class                 | Description|
|-----------------------|------------|
|1 (Highest Urgency)    | Likely to cause serious harm or death |
|2 (Moderate Urgency)   | May cause reversible harm; serious effects are unlikely |
|3 (Lowest Urgency)     | Not likely to cause harm; violates labeling or manufacturing standards |

Recalls are generally handled in 4 steps.

1. **Reports of Adverse Effects** The FDA receives enough reports of adverse effects or misbranding (through MedWatch or VAERS) that it decides the product is a threat and contacts the manufacturer to recall.
2. **Manufacturer Notice** The manufacturer establishes a plan to recall that addresses severity, warns the public, and a means for checking the effectiveness of the recall.
3. **Public Notice** The manufacturer contacts customers (e.g. wholesalers, pharmacies, & more) to notify them that a product of a certain name, size, lot number, serial number, or any other identifiers are being recalled. This notice includes the nature of the recall and the amount of danger involved so that they may protect their clients. They are also supplied with instructions on what to do with affected products, beginning with the cessation of distribution.
4. **Public Listing** These recalls are listed in the weekly FDA enforcement report.

> 🤯 The Environmental Protection Agency's (EPA) Resource Conservation Recovery Act (RCRA) governs the generation, management, storage, treatment, and disposal of hazardous wastes. This includes medication and other drugs.

#### Other Recalls

- **Manufacturer Recalls**: are initiated when they detect a defect, contamination, or labeling error. When this happens, they are legally required to notify the FDA and take appropriate action.
- **Pharmacy Chain & Distributor Recalls**: Large pharmacy chains and wholesalers may voluntarily recall products from their shelves to to internal quality checks or concerns raised by pharmacists. They may also respond to manufacturer or FDA recalls by removing affected products from circulation. This can happen in the event that it's discovered that medication was held in improper storage conditions that could compromise effectiveness.

#### The Role of a Technician

<!-- TODO: Move this into an SOP for recall handling (link in pharmacy inventory chapter) -->

Technicians must stay up to date with recalls posted online. When a recall is brought to their attention, they must alert the pharmacist and store management; providing information for patient outreach. Recalls are generally handled in the pharmacy with the following methodology:

| Step      | Description |
|-----------|-------------|
| Verify    | Verify the recall details (lot number, expiration date, affected batches) to see if affected lot numbers are present on shelves.  |
| Remove    | Remove affected products from inventory and quarantine them. |
| Notify    | Notify affected patients and healthcare providers (with online alerts, telephone calls, and physical notices) to instruct them to discontinue use. Additionally, arrange for refunds & exchanges. |
| Follow    | Follow manufacturer or FDA instructions for return or disposal of products. Stay alert for further guidance. |
| Document  | Document actions taken for pharmacy records to report compliances to regulatory authorities as required. |
