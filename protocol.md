# The Gatewell Protocol for Origin Evidence

A documentation standard for demonstrating non-covered origin of connected equipment under the FCC Covered List regime

Version 1.0 · Public comment draft, Revision 3 · September 17, 2026 · Comment period open through October 31, 2026 · License CC BY 4.0
Canonical HTML edition: https://gatewellgroup.com/protocol/v1.0/ · PDF: https://gatewellgroup.com/assets/gatewell-protocol-v1.pdf · Maintained by Gatewell Group, Los Angeles, California

Conformity with this Protocol is a documentation standard. It is not an FCC, DoW, or DHS determination of any device's regulatory status and does not guarantee any authorization outcome. This document is not legal advice. Regulatory context verified against FCC sources as of September 16, 2026.

## Part I. Purpose, scope, and regulatory context

### 1.1 Purpose

Equipment that is not foreign-produced under the FCC's Covered List entries may be authorized and sold in the United States — but its non-covered status must be certified with sufficient evidence, and no regulation prescribes what that evidence is. The Protocol defines the contents, provenance, quality, and maintenance of an Origin Evidence File ("OEF") for connected equipment in categories subject to the Covered List, so that a regulator, certification body, insurer, or commercial counterparty examining the file can trace every origin claim to an identified source document.

### 1.2 Scope

1.2.1 The Protocol applies, as of this version, to the following covered categories: unmanned aircraft systems and components; routers; power inverters; and advanced robotic devices. Categories subsequently added to the Covered List come within scope upon publication of a corresponding Annex D matrix.

1.2.2 The Protocol prescribes evidence and procedure only. It sets no ownership, content-percentage, or origin threshold of its own. Every outcome standard — whether a device is covered, whether it is foreign-produced, whether an ownership structure is acceptable — is incorporated by reference from the governing FCC Covered List entry, National Security Determination, or Conditional Approval guidance text as in force on the file's revision date.

1.2.3 An OEF assembled under this Protocol is designed to serve both directions of the regime: as the documentation basis for a non-covered determination, and as the evidence base for a Conditional Approval application, whose information requests (corporate structure, supply-chain disclosure, onshoring plan) the Part IV requirements track.

### 1.3 Conformance language

1.3.1 In this Protocol, SHALL states a requirement whose satisfaction is necessary to claim conformity; SHOULD states a recommendation, departure from which must be documented in the file with its rationale; MAY states a permission. Numbered statements are requirements; material introduced as a "Note" or marked informative, including quotations from regulatory texts, is provided for convenience and does not add or alter requirements. Where a quotation and the source text differ, the source text governs.

### 1.4 Regulatory context (informative)

The following is the regulatory posture against which this version was drafted, stated for context and re-verified at each Protocol revision:

- The FCC added foreign-produced power inverters and advanced robotic devices to the Covered List by National Security Determinations dated July 27, 2026, published with the list update of July 28, 2026, each accompanied by Conditional Approval guidance ("FCC Conditional Approval guidance (July 27, 2026)").

- For both categories, the guidance states that Conditional Approval applications must be submitted by January 1, 2028, as a machine-readable PDF, and that submissions must include a certification by an authorized corporate officer that all information is complete and accurate and that any material change will be promptly disclosed.

- The advanced-robotics National Security Determination defines "foreign-produced" as any article that does not qualify as a "domestic end product," as that term is defined in 48 CFR § 25.101(a) — the Buy American definition. For power inverters, the determination as modified by DA 26-870 (August 20, 2026) defines the term disjunctively: an article is foreign-produced unless it is either a 48 CFR § 25.101(a) domestic end product or eligible for the Advanced Manufacturing Production Credit under 26 U.S.C. § 45X for domestic production. Section 25.101(a) treats commercially available off-the-shelf (COTS) items separately in federal procurement. The Commission's guidance on these two listings states that the COTS exception is "inapplicable to whether a device is a 'domestic end product' under section 25.101(a)" and that "[a]ll components, including COTS components, must be considered" (FCC, Covered List FAQs for advanced robotic devices and power inverters, fcc.gov/covered-list-faqs-robots-inverters, as retrieved September 8, 2026). The same guidance states that an applicant must have "sufficient evidence that the device in question was not produced in a foreign country" and that "there is no specific documentation or evidence required."

- Grants of Conditional Approval have carried onshoring conditions and, per the guidance, require quarterly onshoring status reporting to the issuing agency (see 3.3).

### 1.5 Open questions for the comment period

Comment is specifically invited, through October 31, 2026 at protocol@gatewellgroup.com, on the following, in addition to any other aspect of the Protocol:

- Evidence for the domestic end product test. How the component-cost test of 48 CFR § 25.101(a), and for power inverters eligibility under 26 U.S.C. § 45X, should be evidenced in the file: which cost records suffice, how supplier cost data that a manufacturer cannot compel should be handled, and how the computation can be verified while cost data stays confidential. The Commission's guidance has settled that COTS components are counted (see 1.4); the question that remains is documentary. Revision 2: this question replaces the Revision 1 question on COTS treatment, which the Commission's guidance answered.

- EV supply equipment and the utility-interactive scope. How the power-inverter definition's element (a), as narrowed by DA 26-870 (August 20, 2026) to reach only a "utility-interactive inverter as that term is defined in UL 1741 sections 2.1.23, 2.1.52," applies to classes of EV supply equipment — in particular bidirectional (vehicle-to-grid) EVSE that operates in parallel with the electric utility. The Protocol asserts no conclusion; Annex D lists EVSE components so that files can be assembled under either reading pending clarification.

- Calibration of evidence-quality rules. Whether the evidence-age limits (§4.7), confirmation counts (Part V), and retention periods are set at workable levels for mid-size manufacturers.

- Annex D completeness. Whether the deep-trace component matrices omit components that determine a device's character in its category.

## Part II. Definitions

**Covered category.** An equipment category subject to a Covered List entry restricting foreign-produced equipment, per the FCC's list as published at fcc.gov/supplychain/coveredlist on the file's revision date.

**Conditional Approval.** A determination by the Department of War, or where applicable the Department of Homeland Security, that a given device or class of devices does not pose the risks identified in the applicable National Security Determination, permitting FCC equipment authorization notwithstanding the Covered List entry.

**Foreign-produced.** As used in the applicable Covered List entry and its accompanying guidance for the category in question. For the advanced-robotics entry, the National Security Determination of July 27, 2026 defines the term as any article that does not qualify as a "domestic end product" as defined in 48 CFR § 25.101(a); for the power-inverter entry, the determination as modified by DA 26-870 (August 20, 2026) defines it as any article that is neither a 48 CFR § 25.101(a) domestic end product nor eligible for the 26 U.S.C. § 45X Advanced Manufacturing Production Credit for domestic production. The OEF must record which entry text and guidance version its determinations reference. [Definitions differ by entry and evolve; the Protocol deliberately incorporates them by reference rather than restating them.]

**Final assembly.** The production step at which the device's major subassemblies are integrated into the finished unit as shipped, including firmware loading if performed at that site.

**Deep-trace component.** A component listed for the device's category in Annex D, whose origin must be documented one supplier tier beyond the manufacturer's own records.

**Sole-source supplier.** A supplier of a BOM line item for which no alternate supplier is qualified for production use at the revision date.

**Material change.** Any event listed in Part VI (change control).

**Certified translation.** An English translation accompanied by a signed, dated statement of the translator identifying the source document and attesting to the translator's competence in both languages and to the completeness and accuracy of the translation.

**Qualified verifier.** A party competent in supply-chain documentation and the Covered List regime, independent in judgment, who conducts the Part V methodology. Where the verifier's organization assisted in assembling the file under examination, the verifying individual and the assisting individual are different people, separated by the information barrier of Part V, and the statement discloses the arrangement.

**Working papers.** The verifier's contemporaneous record of the items examined, sources consulted, confirmations performed, computations made, and exceptions found in a Part V examination.

**Officer.** A person with authority to bind the attesting entity and knowledge of, or verified reports covering, the facts attested. For a file supporting a Conditional Approval submission, an authorized corporate officer within the meaning of the FCC Conditional Approval guidance (July 27, 2026).

**Revision date.** The date stated on the OEF's change record (Annex G) for its current revision. All currency periods in this Protocol run from the revision date.

## Part III. Conformity levels

| Level | Requirement | Declared by | Currency |
|---|---|---|---|
| 1 · DOCUMENTED | Complete OEF per Part IV; every element officer-attested (Annex A) | Manufacturer (self-declared) | 12 months from revision date |
| 2 · VERIFIED | Level 1 + independent examination per Part V with issued verification statement (Annex F) | Qualified verifier | 12 months from verification date |
| 3 · MONITORED | Level 2 + standing Part VI change control + annual re-verification; for Conditional Approval holders, + the §3.3 quarterly onshoring evidence module | Qualified verifier | Continuous; lapses automatically if re-verification is missed |

### 3.1 Currency and lapse

3.1.1 A Level 1 or Level 2 claim SHALL NOT be made once the applicable currency period has elapsed without re-attestation (Level 1) or re-verification (Level 2). 3.1.2 Level 3 status lapses automatically on the day annual re-verification falls due unperformed, or on the thirty-first day after a Part VI change that has not been re-attested. A lapsed status is regained only by completing the missed step; the Annex G record SHALL show the lapse and its cure.

### 3.2 Level selection

3.2.1 A manufacturer MAY claim any level it satisfies. Buyers and importers adopting the Protocol by reference SHOULD state which level, and what currency, they require of counterparties.

### 3.3 Quarterly onshoring evidence module (Conditional Approval holders)

3.3.1 This module applies at Level 3 wherever a scheduled model is marketed under a Conditional Approval whose conditions include a U.S. manufacturing and onshoring plan.

3.3.2 The FCC Conditional Approval guidance (July 27, 2026) requires "a dedicated point of contact or office responsible for implementing and overseeing the U.S. manufacturing and onshoring plan," which "must provide the agency issuing the Conditional Approval an update on the status of their onshoring plan once a quarter." The OEF SHALL identify that point of contact or office by name, title, and reporting line.

3.3.3 For each calendar quarter, the manufacturer SHALL assemble a quarterly onshoring evidence file, officer-reviewed and closed not later than fifteen days after quarter end, containing:

- progress against each milestone of the time-bound onshoring plan, with dates;

- capital expenditure committed and expended against plan, including financing and other investments dedicated to U.S. manufacturing and assembly (guidance §3(d));

- current U.S. headcount against plan, and hires made in the quarter (guidance §3(c), (d)(i));

- U.S. manufacturing facility square footage, current and added in the quarter (guidance §3(d)(ii));

- percentage of components assembled in the United States, computed on a stated basis held consistent quarter over quarter (guidance §3(c));

- variances from plan, each with an explanation and a recovery plan; and

- where the manufacturer holds any other Conditional Approval, an inventory of progress across all onshoring plans submitted (guidance §3(e)).

3.3.4 Quarterly files SHALL be retained with the OEF per §4.7 and made available to the verifier at each re-verification. The Protocol governs the evidence file only; the content, form, and addressee of the report actually made to the issuing agency are the holder's obligation under its grant.

## Part IV. The Origin Evidence File

### 4.1 Device identity

4.1.1 The OEF SHALL contain a complete schedule of the covered-category models within scope: marketing names, model numbers, FCC IDs or SDoC status, equipment classes, and authorization dates, reconciled to public FCC records. 4.1.2 Hardware revisions marketed under one model number SHALL be listed where they differ in any deep-trace component or production site. 4.1.3 The schedule SHALL state, per model, the file sections and document IDs that evidence it.

### 4.2 Coverage determination

4.2.1 The OEF SHALL record, for each scheduled model, a determination of whether the model falls within each potentially applicable Covered List entry, made against the operative definitions incorporated by the listings — not against paraphrases of them. The record SHALL contain: (a) the definition text applied, quoted, with its source document, date, and the date and location of retrieval; (b) a criterion-by-criterion analysis citing the document IDs evidencing each factual element (weight, connectivity, conversion function, software function, exclusion applicability); (c) the conclusion; and (d) preparer and date.

4.2.2 Because entry texts and guidance are revised, the current texts SHALL be re-retrieved and the determination re-confirmed at each revision date, and the retrieval evidenced.

4.2.3 A determination that a model is not covered SHALL identify the specific definitional element that is not met, or the specific exclusion relied on, and cite the evidence for it. A determination resting on the "foreign-produced" element SHALL record the 48 CFR § 25.101(a) position taken and its factual basis. Note (informative): the Commission's guidance states that the COTS exception is inapplicable to these listings and that COTS components are counted (see 1.4). A position that excludes them must identify the later authority it relies on.

*INFORMATIVE — OPERATIVE DEFINITIONS FOR THE JULY 2026 CATEGORIES (POWER-INVERTER DEFINITIONS AS MODIFIED BY DA 26-870, VERIFIED AGAINST PRIMARY TEXT AUGUST 20, 2026; ROBOTICS VERIFIED AUGUST 8, 2026; RE-VERIFY AT EACH REVISION DATE)*

Power inverter — Second Power Inverter National Security Determination as adopted by DA 26-870 (August 20, 2026), superseding the July 27, 2026 definition: "The term 'power inverters' shall mean— (a) Changes dc power to ac power, to include bidirectional devices, that is intended for use in parallel with an electric utility to supply common loads and sometimes deliver power to the utility, i.e., a utility-interactive inverter as that term is defined in UL 1741 sections 2.1.23, 2.1.52; and (b) Contains, or is designed, equipped, or configured to accept, a component that enables remote communication, control, sensing, data-collection, or monitoring through Ethernet, Wi-Fi, cellular, Bluetooth, or other similar connections, whether wired or wireless." The definition states both elements conjunctively; a §4.2.1 analysis addresses each. Element (b) reaches a unit merely "configured to accept" a communications component, and off-grid units incapable of utility connection fall outside element (a).

Advanced robotic device — National Security Determination on the Threat Posed by Foreign-Produced Advanced Robotic Devices (July 27, 2026): a "mechanical mobile device, including autonomous mobile robots, humanoid robots, and quadrupeds," that (i) "is capable of locomotion, obstacle avoidance, navigation, or movement on the ground"; (ii) "operates at a distance from a human operator or supervisor based on commands or in response to sensor data or any combination thereof"; (iii) has a combined weight of the device "and, if applicable, ground station or docking station" over 4.4 lbs; and (iv) contains each of: "a sensor capable of perceiving its environment"; "a component that is capable of providing network connectivity (wired or wireless, including Bluetooth/WiFi, cellular, or satellite) with connection speeds of at least 200 kbps in either direction"; and "software running either locally or remotely, including firmware and AI or machine-learning model weights, that controls the robot's autonomous navigation or movement perception, data collection, or remote command-and-control." The definition excludes: a "connected vehicle" as defined in 15 CFR § 791.301, of any gross weight; a vehicle operated only on a rail line; an uncrewed aircraft or uncrewed aircraft system as defined in 47 CFR § 88.5; an unmanned underwater vehicle able to operate without a human occupant; items classified as devices under section 513 of the Federal Food, Drug, and Cosmetic Act (21 U.S.C. § 360c), including surgical instruments, medical and surgical robotic systems, external limb prostheses and their components, and ambulatory and mobility assistive devices, whether or not powered and regardless of clearance pathway; and fixed, stationary, non-mobile robots, including articulating, parallel/delta, Cartesian/gantry, or SCARA robots intended for industrial or medical use.

Foreign-produced — advanced-robotics determination (July 27, 2026): "the term 'foreign-produced' refers to any article that does not qualify as a 'domestic end product,' as that term is defined in 48 CFR § 25.101(a)." Power-inverter determination as modified by DA 26-870 (August 20, 2026): "The term shall mean power inverters as defined above that are not either— (a) Eligible for the Advanced Manufacturing Tax Credit in 26 U.S. Code § 45X for domestic production or (b) A domestic end product as defined in 48 CFR § 25.101(a) because they are manufactured in the United States and the cost of domestic components exceeds 65% of the total component cost for items delivered in calendar years 2024 through 2028 or 75% for items delivered starting in calendar year 2029."

### 4.3 Production provenance

4.3.1 The OEF SHALL identify every site performing final assembly, principal subassembly, firmware loading, or production or compliance testing for a scheduled model: legal operator, address, ownership or contractual relationship to the manufacturer, and the step performed. 4.3.2 It SHALL contain a production-flow narrative from major components to shipped unit, identifying at which named site each step occurs. 4.3.3 Each operating entity SHALL provide a signed site attestation from one of its officers covering the steps performed and the site's operator of record. 4.3.4 Where a site is operated under contract (CM/ODM), the file SHALL identify the contract counterparty and the contractual right under which the manufacturer obtains the site information attested.

### 4.4 Component origin

4.4.1 The OEF SHALL contain a bill of materials per model conforming to the Annex B.1 schema, identifying country of origin per line item, with deep-trace documentation (Annex C supplier declarations, one tier up) for every Annex D component present in the design.

4.4.2 The OEF SHALL state, per model, the country or countries of origin of the device's design (electrical, mechanical, and software architecture), with the evidence relied on. [The FCC Conditional Approval guidance (July 27, 2026), §2(b), requests country of origin for all components and for the design of the device.]

4.4.3 The OEF SHALL contain a supply-chain concentration summary per model conforming to the Annex B.2 schema, quantifying concentration by country of origin expressed as both a percentage of total BOM value and a percentage of component production volume, on stated bases, recomputed at each revision. [Tracks guidance §2(g): "Quantitative assessment of supply chain concentration by country, expressed as both a percentage of total value and production volume."]

4.4.4 The OEF SHALL contain a sole-source register per model conforming to the Annex B.3 schema, identifying every sole-source supplier, its country, and — for each — a documented contingency plan stating the course of action if that supplier becomes unavailable (qualified alternate and qualification lead time, buffer-stock policy, or redesign path). [Tracks guidance §2(h).] 4.4.5 Contingency plans SHALL be reviewed at each revision and on any Part VI trigger affecting the supplier.

### 4.5 Corporate provenance

4.5.1 The OEF SHALL document the manufacturer's complete ownership structure — parents, subsidiaries, affiliates, and joint ventures — to its ultimate parents, with each entity's jurisdiction. 4.5.2 It SHALL identify beneficial owners holding five percent or greater equity, with holder identity and jurisdiction — the threshold the FCC Conditional Approval guidance (July 27, 2026), §1(c), itself requires. 4.5.3 It SHALL list board members and executive leadership, including each person's nationality and country of residence [guidance §1(d)]. 4.5.4 It SHALL disclose any foreign-government ownership, control, influence, financing, or material support, including any arrangement that allows a foreign person or government to influence operations, decision-making, or access to technology [guidance §1(e)]; a statement that no such arrangement exists SHALL be made expressly, not by omission. 4.5.5 All chain entities, five-percent beneficial owners, and board and executive members SHALL be screened per the Annex E procedure, dated.

### 4.6 Software, firmware, and intellectual-property provenance

4.6.1 The OEF SHALL contain an SBOM in SPDX or CycloneDX format for device firmware and companion applications, corresponding to the currently shipping build. 4.6.2 It SHALL identify the entities responsible for intellectual-property ownership and for software updates for the device [guidance §2(c)], including the licensor of any third-party autonomy, navigation, or connectivity stack. 4.6.3 It SHALL state the country of origin of onboard software and firmware [guidance §2(f)] — where the category definition reaches AI or machine-learning model weights, including where the models were trained and by whom. 4.6.4 It SHALL identify the location and operator of build and code-signing infrastructure, and update-server jurisdictions and operators. 4.6.5 It SHALL contain a data-flow summary identifying every endpoint the device communicates with in normal operation, with operator and jurisdiction.

### 4.7 Evidence quality, translation, and retention

4.7.1Document identity. Every document in the OEF SHALL bear a unique document ID, and a master index SHALL map each Part IV requirement to the document IDs satisfying it. Reproductions SHALL preserve legibility of all seals, stamps, and signatures. Files intended to support a Conditional Approval submission SHOULD be maintained as machine-readable PDF, the format the guidance requires of applications.

4.7.2Translation. Every source document not in English SHALL be accompanied by an English translation, retained alongside the original-language document. The translation SHALL be a certified translation for: corporate registry filings, ownership and beneficial-ownership statements, site attestations, supplier declarations, and any document relied on in a §4.2 coverage determination. Machine translation MAY be used for screening and working purposes but SHALL NOT substitute for a required certified translation.

4.7.3Evidence age. At each revision date, the following classes SHALL be no older than stated, measured from document date to revision date:

| Document class | Maximum age at revision date |
|---|---|
| Corporate registry extracts and standing certificates (§4.5) | 12 months |
| Beneficial-ownership statements at the five-percent threshold (§4.5) | 12 months |
| Site attestations (§4.3) | 12 months |
| Annex C supplier declarations for deep-trace lines (§4.4) | 12 months |
| Annex E screen (§4.5) | 12 months, and re-run on any Part VI trigger |
| SBOM (§4.6) | Must match the currently shipping build; regenerated at each release |
| Concentration summary and sole-source register (§4.4) | Recomputed / reviewed at each revision |
| Photographic and production-flow evidence (§4.3) | 24 months |

4.7.4Retention. Each OEF revision, with every document it references, SHALL be retained for not less than ten years after the revision is superseded. A document referenced by multiple revisions is retained per the latest revision referencing it. Quarterly onshoring files (§3.3) are retained on the same terms.

### 4.8 Attestation

4.8.1 The OEF SHALL close with the Annex A certification, signed by an officer of the manufacturer, covering the file as of its revision date.

## Part V. Verification methodology

Level 2 and 3 verification concludes with the Annex F statement. The verifier SHALL perform each of the following and record it in working papers:

- Document authentication. Authenticate source, date, and document ID of every corporate-chain document and every deep-trace supplier declaration; authenticate other classes by sampling, with the sampling basis recorded.

- Schedule reconciliation. Reconcile the §4.1 device schedule against public FCC authorization records.

- Coverage determination review. Confirm that the definition texts quoted in each §4.2 record match the texts in force at the verification date, retrieving the current texts and recording the retrieval; confirm that each cited factual element is evidenced by the document IDs given.

- Supplier confirmations. Confirm directly with the declaring suppliers not fewer than three Annex C declarations or ten percent of the declarations on file, whichever is greater, selected by the verifier and including at least one broker-channel line where any exists; contact details SHALL be obtained or corroborated independently of the manufacturer.

- Corporate reconciliation. Reconcile the corporate chain against registry filings in each named jurisdiction, each filing retrieved within ninety days of the verification date, and reconcile five-percent beneficial ownership to shareholder registers or ownership statements.

- Quantitative reconciliation. Recompute the Annex B.2 concentration summary from the B.1 bill of materials for each model, and reconcile the B.3 sole-source register against B.1; confirm each sole-source contingency plan exists and states a course of action.

- Screening. Re-run the Annex E screen as of the verification date.

- Statement. Issue a written statement per Annex F of what was examined and confirmed, the Protocol version applied, and the file revision covered.

Working papers. The verifier SHALL retain working papers — items examined, sources and retrieval dates, confirmation correspondence, computations, exceptions and their resolution — for not less than ten years from the verification date, and SHOULD make them available to a successor verifier under confidentiality terms.

Information barrier. A verifier's organization MAY have assisted in assembling the file under examination, on the following conditions. The individual who assisted SHALL NOT be the individual who verifies. The two SHALL work from separate files: the verifier without access to the assembly engagement's commercial terms or working drafts, and the assisting individual without access to the verification working papers before the statement is issued. Each SHALL reach their own conclusion on their own record, and no person in the organization, its principal included, SHALL direct, edit or reverse either conclusion; a disagreement between the two is recorded in both files and disclosed to the manufacturer as it stands. The verifier SHALL be paid nothing that varies with the assembly engagement. The statement SHALL disclose the arrangement and identify the two roles.

## Part VI. Change control

Each of the following is a material change requiring re-attestation of the affected sections within thirty days (and re-verification, at Level 3):

- A new, changed, or discontinued production, assembly, testing, or firmware-loading site;

- A change of contract manufacturer or ODM for any scheduled model;

- A sourcing change affecting any deep-trace component;

- Any change in the corporate chain, or in beneficial ownership at the five-percent threshold;

- Any change in board membership or executive leadership recorded under §4.5.3;

- Any new, changed, or terminated arrangement of the kind disclosed under §4.5.4 (foreign-government ownership, control, influence, financing, or material support);

- A change of an entity responsible for intellectual-property ownership or software updates (§4.6.2);

- A sole-source supplier becoming unavailable, or an event invalidating a §4.4.4 contingency plan;

- Any Covered List addition or guidance change touching an entity, component, or category in the file.

Note (informative): for Conditional Approval holders, the officer certification the guidance requires extends to prompt disclosure of material changes to the U.S. Government; the thirty-day file deadline above does not extend, and is not a substitute for, that obligation.

Note (informative) — change control and authorization status: for a device that is covered but relies on an equipment authorization granted before its category was listed, several triggers above (1, 2, 3 and 8) describe events the manufacturer may be unable to execute at all rather than merely obliged to re-attest. Covered equipment is excluded from the permissive-change procedures at 47 CFR §§ 2.932(b) and 2.1043(b), and that exclusion reaches devices authorized before their category was listed. A waiver announced on July 28, 2026 (DA 26-789) restores Class I and Class II permissive changes for software and firmware updates that mitigate consumer harm, at least until January 1, 2029; it does not reach hardware, and a replacement authorization is unavailable while the device remains covered and foreign-produced. A single end-of-life component can therefore terminate a model's marketability without any further action by the Commission. Manufacturers in this position SHOULD treat the §4.4.4 sole-source register and its contingency plans as the primary risk instrument in the file rather than a formality, and SHOULD record, per model, the authorization date, the coverage determination, and the earliest date on which a known component end-of-life is expected to force a hardware change. Verify the current waiver posture before relying on this note; it is informative and reflects guidance as understood at the revision date.

## Part VII. Claims of conformity; maintenance

Conforming parties may state: "[Company]'s Origin Evidence File for [models] conforms to the Gatewell Protocol for Origin Evidence, Version 1.0, at Level [1/2/3], as of [date]." Claims must name the level and date, may not extend to models outside the schedule, and may not state or imply government endorsement. Buyers and importers may adopt the Protocol by reference and require a stated level and current date as a condition of vendor qualification.

The Protocol is versioned; substantive changes are published with a comment period and a dated changelog. Files verified under a prior version remain valid to that version's terms until next re-verification. The Protocol yields to any mandatory documentation standard on its effective date.

## Annex A. Officer attestation of origin evidence

Execute one per OEF revision. Retain the original in the file; provide copies to counterparties with the file's summary.

Note (informative): this annex is drafted to the certification standard of the FCC Conditional Approval guidance (July 27, 2026), which requires certification by an authorized corporate officer that all information is complete and accurate and that any material change will be promptly disclosed, and which states that applicants that knowingly violate the terms of a Conditional Approval or materially misrepresent information provided to the U.S. Government will have the approval terminated and will be precluded from applying again.

Attesting entity: Jurisdiction of organization:

OEF revision date: Protocol version: Conformity level claimed:

Models covered (or schedule reference):

I certify that I am an officer of the attesting entity with authority to make this certification; that I have reviewed the Origin Evidence File identified above; that the statements of device identity and coverage determination, production site, component origin, corporate ownership and governance, and software, firmware, and intellectual-property provenance it contains are complete and accurate as of the revision date to the best of my knowledge after due inquiry; that the supporting documents it references are authentic and current per Part IV of the Protocol; and that the entity will promptly disclose any material change as defined in Part VI of the Protocol to recipients of the file, and will re-attest affected sections within thirty days.

I understand that this file may be furnished to United States government agencies, certification bodies, insurers, and commercial counterparties.

Signature: Date:

Name: Title:

## Annex B. Bill-of-materials origin schema

Note (informative): Annex B is also published in machine-readable form, as a JSON Schema and a CSV template, at gatewellgroup.com/protocol/v1.0. The schema and the template are dedicated to the public domain under CC0 1.0.

### B.1 BOM line schema

One record per BOM line item, per model, in CSV or XLSX, under revision control matching the OEF revision. Required fields:

| Field | Definition | Rules |
|---|---|---|
| model_id | Manufacturer model number of the finished device | Must appear in the §4.1 schedule |
| item_ref | BOM line reference / internal part number | Unique within model |
| description | Component description | Plain language |
| mpn | Manufacturer part number of the component | As marked or documented |
| component_mfr | Component manufacturer legal name | Not the distributor |
| mfr_country | Component manufacturer HQ country | ISO 3166 alpha-2 |
| coo | Country of origin of the component as supplied | ISO 3166 alpha-2; "MULTI" prohibited — split lines |
| design_origin | Country where the component was designed | ISO 3166 alpha-2; required for deep-trace lines; "UNKNOWN" only with a documented inquiry record |
| supply_channel | Direct / distributor / broker | Broker-sourced deep-trace components require Annex C declaration regardless of tier |
| sole_source | Y if no alternate supplier is qualified at the revision date | Y requires a B.3 register entry |
| deep_trace | Y if the component matches Annex D for the category | Y requires declaration_ref |
| declaration_ref | Identifier of the Annex C declaration on file | Required when deep_trace = Y |
| verified_date | Date origin was last confirmed | Within 12 months of revision date for deep-trace lines |

Passive components (resistors, capacitors, standard connectors, fasteners, enclosures) may be aggregated by commodity class with a single coo entry per class where no Annex D match exists.

### B.2 Supply-chain concentration summary

One record per model per country of origin appearing in B.1, recomputed at each revision [tracks FCC Conditional Approval guidance (July 27, 2026), §2(g)]:

| Field | Definition | Rules |
|---|---|---|
| model_id | Finished device model | Must appear in the §4.1 schedule |
| country | Country of origin | ISO 3166 alpha-2; every coo in B.1 must appear |
| pct_value | Percentage of total BOM value originating in the country | Column sums to 100 ± 0.5 rounding |
| pct_volume | Percentage of component production volume (unit count) originating in the country | Column sums to 100 ± 0.5 rounding |
| basis_note | Valuation basis (standard cost or actual purchase cost) and the 12-month period used | Basis held consistent revision over revision; changes documented |
| computed_date | Date of computation | Equal to or later than the BOM revision it summarizes |

### B.3 Sole-source supplier register

One record per sole-source line item, per model [tracks guidance §2(h)]:

| Field | Definition | Rules |
|---|---|---|
| model_id / item_ref / mpn | The B.1 line concerned | Every B.1 line with sole_source = Y appears here |
| supplier | Sole-source supplier legal name | — |
| supplier_country | Supplier country | ISO 3166 alpha-2 |
| contingency_ref | Document ID of the contingency plan | Plan must state the course of action if the supplier becomes unavailable: qualified alternate and qualification lead time, buffer-stock policy, or redesign path |
| last_reviewed | Date the plan was last reviewed | At each revision, and on any Part VI trigger affecting the supplier |

## Annex C. Supplier origin declaration

Executed by the component supplier (one tier up from the manufacturer). One declaration may cover multiple part numbers from the same supplier and production site. A declaration executed in a language other than English requires a certified translation per §4.7.2, retained with the original.

Declaring supplier: Country:

Part numbers covered:

Production site(s) for these parts (name, city, country):

Site operator, if different from declarant:

Declarant contact for verification confirmations (name, e-mail):

The declarant certifies that the parts identified above and supplied to are produced at the site(s) stated; that the declarant will notify the recipient in writing within thirty days of any change in production site for these parts; and that this declaration may be relied upon in the recipient's regulatory and commercial origin documentation.

Signature: Name/title: Date:

## Annex D. Deep-trace component matrices

Components below determine the device's character in its category and require one-tier-up origin documentation (Annex C) wherever present in the design. Where a listed function is integrated into a combined SoC, the SoC is the deep-trace component.

| Category | Deep-trace components |
|---|---|
| Routers & gateways | Wi-Fi / RF system-on-chip and radio front-end modules; network processor / main CPU; Ethernet PHY and switch silicon; cellular baseband module (if present); flash containing bootloader |
| Power inverters & EV supply equipment | Power-conversion stage (modules or discrete bridge assemblies); main control MCU/DSP; communications module (Wi-Fi/BT/cellular/PLC); current/voltage sensing assemblies; contactor/relay assemblies (EVSE) |
| Advanced robotic devices | Main application processor; motor-control assemblies; actuator and end-effector assemblies; navigation/perception sensors (LiDAR, vision modules, IMU); radio modules; battery packs and battery-management electronics |
| UAS & components | Flight controller; radio/data-link modules; camera/gimbal payloads; GNSS modules; ESCs and motor controllers; battery-management electronics |

Matrices are maintained with the Protocol and revised as Covered List guidance evolves; a design lacking a listed component simply omits it. The advanced-robotics row tracks the component classes the National Security Determination (July 27, 2026) itself identifies as critical — actuators, end effectors, batteries, and sensors — plus the processing and radio elements of the operative definition.

## Annex E. Covered-entity screening procedure

- Assemble the screen list: every entity in the §4.5 corporate chain; every beneficial owner at the five-percent threshold and every board and executive member recorded under §4.5.3; every production-site operator in §4.3; every deep-trace component manufacturer in the §4.4 BOM.

- Screen each against: (a) the entities named in current Covered List entries and the FCC's published lists of their subsidiaries and affiliates; (b) the current Covered List category definitions as applied to the entity's role; and (c) US sanctions lists (OFAC SDN and consolidated lists) as a supplementary check — natural persons against (c).

- Record for each screened entity: name as screened, aliases checked (including native-script and transliterated forms), source lists and their publication dates, result (clear / match / possible match), and reviewer.

- Any match or possible match halts reliance on the file pending resolution, which must be documented in the file with its basis.

- The screen is current for twelve months, and must be re-run upon any Part VI change or any relevant Covered List addition.

## Annex F. Verification statement (Levels 2–3)

Issued by the qualified verifier on completion of the Part V methodology. The statement, not the mark, is the operative document.

Verifier: Engagement ref:

Manufacturer and OEF revision examined:

Protocol version applied: Level: Verification date:

The verifier states that it performed each step of the Part V methodology, and in particular that it: authenticated the documents comprising the file; reconciled the device schedule against public FCC authorization records; confirmed that the coverage-determination texts quoted in the file match the texts in force as of the verification date; confirmed the following supplier declarations directly with the declaring suppliers (not fewer than three or ten percent of declarations on file, whichever is greater): ; reconciled the corporate chain, including five-percent beneficial ownership, against registry filings retrieved within ninety days; recomputed the Annex B.2 concentration summary and reconciled the B.3 sole-source register; and re-ran the Annex E screen as of the verification date with the result: .

Working papers reference and retention location:

Exceptions, qualifications, and unresolved items:

Independence disclosure: the verifier's organization [did / did not] provide assistance in the assembly of this file. Where it did: assisting individual , verifying individual , and the information barrier of Part V was in place throughout the examination. Nature of assistance:

Signature: Name/title:

## Annex G. Revision record

Maintained at the front of every OEF:

| Rev | Date | Sections changed and why (incl. Part VI trigger) | Attested by | Verified (L2/3) |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |

### Protocol version history

| Version | Date | Changes |
|---|---|---|
| 1.0 (draft) | August 2026 | Initial public comment draft, published August 7, 2026. Amended later in August 2026 for DA 26-870 (power-inverter definitions, August 20, 2026). |
| 1.0 (draft), Revision 2 | September 17, 2026 | 1.4, 1.5 and 4.2.3 amended: the Commission's guidance answered the COTS question, so comment-period question 1 is closed and replaced by a question on evidencing the domestic end product test. License stated as CC BY 4.0. HTML edition with clause anchors published at gatewellgroup.com/protocol/v1.0, with Annex B in machine-readable form under CC0 1.0. Regulatory context re-verified September 16, 2026. |
| 1.0 (draft), Revision 3 | September 17, 2026 | Part V information barrier added: where the verifier's organization assisted in assembling the file, the assisting and verifying individuals are different people working from separate files, each conclusion is their own and subject to no direction, and the arrangement is disclosed. Definition of qualified verifier and the Annex F independence disclosure aligned. Replaces the disclosure-only rule of Revision 2. |

© 2026 Gatewell Group. The Protocol text is licensed under the Creative Commons Attribution 4.0 International license (CC BY 4.0). A modified text may not be called the Gatewell Protocol; the "Gatewell Protocol" designation and the conformity marks are reserved. Quotations from Federal regulatory texts are reproduced from the public source documents; the source texts govern. Not legal advice; not a government determination. gatewellgroup.com/protocol
