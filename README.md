# Property & Contents Value Documentation in NERIS/NFIRS: Virginia Fire Department Guidance

## Executive Summary

Property and contents value documentation in NERIS (and its predecessor NFIRS) is **required by rule only for fire incidents (100-series incident types)**. Virginia has no state law mandating dollar value entry for non-fire calls, and federal NFIRS/NERIS specifications mark these fields as **Optional** for all incident types. However, there is strong operational and policy guidance — from both USFA/FEMA and fire data professionals — about *when* and *how* these values add meaningful data, as well as significant risks when the practice is inconsistent. The key distinction: **always document values on fire incidents; apply a consistent, SOP-driven policy on non-fire calls**.

***

## Part 1: What the Law and Regulations Actually Say

### Virginia State Law

Virginia does **not** have a specific statute mandating the documentation of property or contents dollar values in fire incident reports. Title 27 of the Code of Virginia (Fire Protection) addresses fire investigation, fire prevention code enforcement, and arson reporting requirements, but contains no provision specifying how fire departments must calculate or enter property values in incident reports.[^1][^2]

Virginia's reporting framework has historically been voluntary for incident reporting purposes, with the Virginia Department of Fire Programs (VDFP) managing data submission to NFIRS via the state portal. As of the 2025 General Assembly session, legislation was passed requiring fire departments to report emergency incidents to NERIS as a condition of receiving **Aid to Localities (ATL)** grant funding, with the policy taking effect July 1, 2026. This legislation mandates incident *reporting*, not the specific documentation of property values on all incident types.[^3][^4][^5]

Virginia's fire prevention code (adopted under the Statewide Fire Prevention Code Act, § 27-95 et seq.) governs fire safety standards in buildings but does not regulate how fire departments enter loss estimates in incident reports. Local fire marshals are required to investigate origins and causes of fires (§ 27-31), but this relates to origin-and-cause investigation, not the financial documentation fields in NERIS.[^6][^7]

### Federal NFIRS/NERIS Specification

Under the federal NFIRS 5.0 specification (which governed Virginia reporting until January 2026), the specification document explicitly marks both **Property Value** and **Property Loss** as **"Optional"** fields. This means the system will accept and process an incident report without these fields, though a "warning error" (not a critical error) may be generated if they are missing on a fire incident where losses are known.[^8][^9][^10]

The authoritative guidance from multiple state NFIRS coding references is consistent and direct:

> "Dollar loss should be documented for **fire incidents (100 series) only**. It is an estimate of the total pre-incident value for the property and property contents in terms of replacement of the damaged items and property."[^11][^9]

Under NERIS (which replaced NFIRS beginning January 1, 2026), incident types are reorganized into broader categories — Fire, Hazardous Situation, Medical, Public Service, Rescue, No Emergency, and Law Enforcement Support. The principle from NFIRS carries forward: property and contents loss/value fields are expected for **Fire** incident types, not for alarm activations, good-intent calls, or false alarms.[^12][^13]

### The Critical Rule: Pre-Incident Value is Required IF Loss Is Entered

One important validation rule applies in both NFIRS and NERIS: **if you enter a property or contents loss, you must also enter the corresponding pre-incident value**. Failure to do so generates a critical error that prevents the report from validating. This means you cannot document $5,000 in property loss without also entering the property value. The reverse, however, is not true — you can enter a pre-incident value with $0 (None) loss to show that property was present but undamaged.[^9]

***

## Part 2: When Documentation IS Required — Fire Incidents (100-Series / NERIS "Fire" Type)

### The Mandatory Practice for Fire Incidents

For any incident coded as a **fire** (NFIRS 100-series / NERIS incident type "Fire"), entering both pre-incident property value and the estimated loss is expected and strongly encouraged by USFA — even if no guidance labels it as a hard-coded system requirement. Multiple state fire reporting agencies describe it as "required for all fires when obtainable". USFA's own NFIRSGram guidance states: "When a fire occurs, enter the best estimate of the loss for the property and any contents, as well as the estimated pre-incident values."[^14][^15]

This applies to all fire types, including:
- Structure fires (building fires, room-and-contents fires, confined fires)
- Vehicle fires
- Brush, grass, and wildland fires
- Outside fires with property involved

Even when loss appears to be zero (e.g., a small cooking fire that was fully contained with no damage), departments should enter the pre-incident property value and mark the loss as **"None" / $0** — not leave the fields blank. Leaving them blank means the value is *unknown*, while marking "None" means there was genuinely zero loss.[^14]

### How to Estimate Pre-Incident Value

The International Code Council's **Building Valuation Data (BVD)** formula is the recommended standard method:

**Total Square Footage × Square Foot Construction Cost = Pre-Incident Value**

For example: A 1,200 sq. ft. wood-frame single-family residence at $140.33/sq. ft. = ~$168,396 pre-incident value. Alternative sources include:[^14]
- Local tax assessor property records (highly recommended for accuracy)
- County real estate assessment databases
- Other loss calculators published by state fire marshal offices

Contents value is estimated separately. For a residential structure, typical contents are estimated at 50% of the structure value; for commercial occupancies, this varies widely and the tax assessor or the building owner/occupant can be consulted.[^16][^14]

### The "Saved Property" Statistic

One of the most compelling reasons to document values on *every fire incident* is the ability to calculate **"saved" property value** — the difference between pre-incident value and actual loss. This metric directly demonstrates the fire department's effectiveness and return on public investment. For example, if a $400,000 home sustains $20,000 in damage because the fire department intervened early, the "property saved" is $380,000. Without entering the pre-incident value, this effectiveness is invisible in annual statistical reports.[^17][^16]

> "One highly useful statistic that every fire department should compile is the 'saved' property value... Many times the amount of saved property is a shockingly high number."[^17]

This is precisely the concern raised in the original question: without pre-incident values, a year's worth of fire incidents shows only losses — and the department appears to have done nothing to protect the community's assets.

***

## Part 3: When Documentation Is Appropriate (But NOT Required) — Non-Fire Incidents

### General Rule: Not Required for Non-Fire Calls

For incident types outside the fire category — including:
- **700-series**: False alarms, fire alarm activations, detector activations (NFIRS); equivalent NERIS "No Emergency" types
- **600-series**: Good intent calls, smoke scares, wrong locations
- **500-series**: Service calls
- **400-series**: Hazardous conditions (no fire)
- **300-series**: EMS calls
- **MVAs, hazmat incidents, etc.**

…property and contents value **should not be entered** as a standard practice. Entering values on these incident types inflates data, introduces inconsistency, and does not serve the national fire data collection purpose for which these fields were designed. As noted in one NFIRS reference: "Be careful with this statistic that the FD is only using values for fire-related incidents. Some departments mistakenly enter value/damage for car accidents and HazMat incidents."[^9][^17]

### When It Makes Sense to Enter Value on a Non-Fire Incident (The "Good Outcome" Problem)

This is the nuanced operational question your department is grappling with. There are legitimate scenarios where entering a pre-incident property value on a non-fire call provides useful community risk reduction data — but only when done **consistently, as a matter of written policy**.

The situations where entering property value on a non-fire incident can be *appropriate and beneficial* include:

**1. Alarm activations at residential properties — successful outcome, minor/no damage**
If units respond to a residential smoke detector activation (NFIRS 745/743; NERIS "No Emergency – Alarm Activation") and find a cooking fire that was self-extinguished with minor scorching, the department may choose to document the property value to demonstrate the value of the early detection system. This tells the story: the alarm worked, the fire department confirmed safety, and a $250,000 home was protected. This practice supports community risk reduction narratives in annual reports.[^18]

**2. Situations where minimal damage occurred but value was at risk**
If a candle fire was extinguished before units arrived but the entire living room (valued at $30,000 in contents) could have been destroyed, some departments document property value and a very small or zero loss to show the near-miss outcome.

**The key caveat:** Entering values on these calls should only be done when your department has a written SOP specifying *exactly which incident types* warrant value documentation and what methodology is used. Without a policy, different shifts will make different judgment calls — which is the core problem your department is trying to avoid.

### The Industrial Complex Problem — Why Consistency Matters

The concern about large industrial facilities (factories, warehouses, data centers) is well-founded and reflects a recognized data quality challenge. If an industrial complex with a $50 million property value triggers frequent alarm activations, and different shifts document this value differently — one crew entering $50M, another $10M, another nothing — the year-end data becomes meaningless at best and misleading at worst.

This is not merely an internal quality issue. NFIRS and NERIS data are used by:
- State and federal agencies to allocate fire prevention resources
- Grant-making bodies to assess community risk
- ISO rating bureaus to evaluate department capability
- Insurance industry actuaries (though fire department loss estimates don't bind insurance settlements)[^16]

Inconsistent high-value entries at recurring industrial locations create the appearance of massive year-over-year property value fluctuation — making it look like the department responded to a very different risk profile from run to run, when in reality it was the same building.

**Best practice for high-value industrial facilities:** If your department chooses to document values on alarm activations at these properties, the recommended approach is to use a **pre-established, fixed pre-incident value** sourced from the county tax assessor or a pre-fire plan, and save that value in your ImageTrend system as a preset or in the property pre-plan record. This ensures every crew documents the same value regardless of the incident outcome. ImageTrend Elite supports preset values and supplemental questions at the property level, which can be configured to populate value fields automatically.[^19][^20]

***

## Part 4: Virginia-Specific Considerations Under NERIS

### The Transition to NERIS in Virginia

Virginia departments were eligible to begin NERIS onboarding on September 4, 2025, with NFIRS officially sunsetting January 1, 2026. NFIRS stopped accepting new incident data at that point, and Virginia fire departments must now report through NERIS to remain eligible for ATL grant funding effective July 1, 2026.[^21][^4][^22]

Under NERIS, the fire module fields for property and contents value/loss are still present, and the same philosophical approach applies — enter values on fire incidents, avoid arbitrary entries on non-fire calls. NERIS's custom required fields feature (available in ImageTrend Elite and similar platforms) allows departments to set field-level validation rules triggered by specific incident types, so you can make property value a **required field** for fire-type incidents while leaving it optional for alarm activations.[^23][^12]

### ImageTrend NERIS Validation Configuration

In ImageTrend Elite (the platform VDFP uses and recommends for NERIS compliance), you can configure:

- **Local Validation Rules**: Make property value/loss required when incident type = "Fire" → "Structure Fire"
- **Visibility Rules**: Show or hide property value fields based on incident type, reducing confusion for non-fire calls
- **Preset Values**: Pre-populate property values from pre-fire plans or tax assessor data for known high-value occupancies
- **Supplemental Questions**: Add local data fields to capture notes on why values were or were not entered[^20][^19]

The data flow model adopted by VDFP follows the agency → state → NERIS pathway, which means Virginia's state-level compliance fields and custom validations are preserved even as data flows to the national NERIS platform.[^24][^25]

### Virginia Fire Prevention Code Plan Goals

VDFP's 2024-2025 Virginia Fire Prevention and Control Plan explicitly acknowledges that Virginia does **not currently mandate** fire incident documentation and reporting, calling it "a major impairment to research and analysis of fire casualty and property loss information." The transition to NERIS and the ATL funding linkage are steps toward improving this, but property value documentation specifically remains a best-practice area rather than a state-mandated field requirement.[^26]

***

## Part 5: Recommended Validation Rule Framework for ImageTrend NERIS

Based on the above research, the following framework is recommended for building your ImageTrend NERIS validation rules for property and contents value fields:

### Required (Error-Level Validation)

| Incident Type | Rule | Rationale |
|---|---|---|
| Fire → Structure Fire (all subtypes) | **Property Value required; Property Loss required** | NFIRS/NERIS guidance and USFA best practice for all fire incidents[^14][^15] |
| Fire → Structure Fire | **If Property Loss > $0, Contents Value required** | System validation prevents loss without value[^9] |
| Fire → Vehicle Fire | **Property Value required; Property Loss required** | Same as structure fire[^11] |
| Fire → Outside Fire (vegetation, brush, grass) | **Property Loss required; Property Value if structure threatened** | Supports wildland fire data quality[^17] |

### Recommended (Warning-Level Validation)

| Incident Type | Rule | Rationale |
|---|---|---|
| Fire → Confined Fire (cooking, chimney) | **Warning if Property Value blank** | Even confined fires should show value vs. loss[^14] |
| No Emergency → Alarm Activation (residential, 1-2 family) | **Warning to consider entering value** | Supports "saved property" narrative for residential calls[^18] |

### Not Required (Fields should be optional or hidden)

| Incident Type | Rule | Rationale |
|---|---|---|
| No Emergency → Alarm Activation (industrial/commercial, recurring) | **Fields visible but not prompted; use pre-plan value if entering** | Prevents shift-to-shift inconsistency at high-value properties[^17] |
| Hazardous Situation (no fire) | **Do not enter property value** | NFIRS guidance explicitly excludes hazmat[^9] |
| Medical / EMS | **Do not enter property value** | Not applicable per NFIRS/NERIS design[^9] |
| Good Intent / False Alarm (600/700 series) | **Do not enter property value** | Not applicable per coding guidance[^9] |

### SOP Guidance for Specific Scenarios

**Residential Alarm Activation — Successful Outcome (e.g., cooking fire, detector activation, no damage)**
- Enter property value using county tax assessor data for the address
- Mark property loss as "None" ($0)
- Document the successful outcome in Remarks/narrative
- This supports the saved-property story in annual reporting[^16]

**Industrial/Commercial Alarm Activation — No Fire Found**
- Default: leave value fields blank unless your SOP specifies otherwise
- If your SOP calls for entering value: use a fixed, pre-established value from the pre-fire plan or tax assessor only — never estimate on-scene
- Document source of value in Remarks
- Use ImageTrend preset values at the property level to enforce consistency across shifts[^19]

**Fire Incident at Industrial Facility — Any Amount of Fire**
- Always enter property value (from tax assessor or ICC BVD formula) and estimate the loss
- Loss should reflect actual damage to structure and contents from fire, smoke, water, and overhaul — not the entire facility value unless fully involved[^14]
- Document estimation methodology in Remarks

***

## Conclusion

There is no Virginia state law or NERIS federal rule that mandates property and contents value documentation on every incident type. The legal floor is: **enter these values for all fire (100-series / NERIS "Fire" type) incidents**. Above that floor, the decision of when to document values on non-fire calls — such as residential alarm activations — is a department-level policy choice.

The practical guidance is:
1. **Always document on fire incidents** — it is expected by USFA and required for data quality[^15][^11][^14]
2. **Apply a written SOP to non-fire calls** — specify exactly which incident types will have value entered, what source (tax assessor, ICC BVD, pre-fire plan) will be used, and save preset values in ImageTrend to ensure cross-shift consistency[^20][^17]
3. **Never enter values ad hoc at industrial/high-value occupancies** — this creates the inconsistency problem your department rightly wants to avoid[^17]
4. **Use ImageTrend's validation rule and preset value tools** to enforce your policy programmatically, reducing reliance on individual crew judgment[^12][^19][^20]

The goal — showing the value of fire department service, not just losses — is best achieved through consistent pre-incident values on fire incidents, supported by selective, policy-driven documentation on residential non-fire incidents with successful outcomes.

---

## References

1. [Statewide Fire Prevention Code Act - Virginia Law](https://law.lis.virginia.gov/vacodepopularnames/statewide-fire-prevention-code-act/) - An initial verbal report shall be made within three days of the discovery of the taking or disappear...

2. [Code of Virginia - Virginia Law](https://law.lis.virginia.gov/vacodefull/title27/) - The local fire marshal shall immediately report to the authorities identified in § 27 ... required o...

3. [National Fire Incident Reporting System - Virginia Department of ...](https://www.vafire.com/virginia-fire-incident-reporting-system-vfirs/) - NFIRS is an all-type incident reporting system. Fire departments should be reporting all their emerg...

4. [Virginia Fire Services Board Approves Changes to the Aid to ...](https://www.vaco.org/county-connections/virginia-fire-services-board-approves-changes-to-the-aid-to-localities-policy-fire-reporting-as-a-condition/) - As previously reported, the policy requires that VDFP run a compliance report twice a year. If a dep...

5. [Public Comment Requested for Implementation of the National ...](https://www.vaco.org/county-connections/public-comment-requested-for-implementation-of-the-national-emergency-response-information-system-neris-fire-reporting-notice/) - Public Comment Requested for Implementation of the National Emergency Response Information System (N...

6. [Title 27. Fire Protection - Code of Virginia (2025 Updates)](https://law.lis.virginia.gov/vacodeupdates/title27/) - Title 27. Fire Protection (2025 Updates). Chapter 9. Statewide Fire Prevention Code Act. § 27-95: De...

7. [§ 27-31. Investigation of fires and explosions - Virginia Law](https://law.lis.virginia.gov/vacode/title27/chapter3/section27-31/) - Such fire marshal shall make an investigation into the origin and cause of every fire and explosion ...

8. [Property Value - NFIRS - Responserack](https://www.responserack.com/nfirs/element/property-value-59/) - NFIRS 5.0 relational edit validation rules are provided to ensure NFIRS data is consistent and corre...

9. [[PDF] NFIRS 5.0 Coding Questions and Answers A Reference Guide](https://www.nfic.org/docs/CT_nfirs_coding_guide.pdf) - Dollar loss should be documented for fire incidents (100 series) only. It is an estimate of the tota...

10. [NFIRS 5.0 Element: 'Property Value' - APX Data](https://apxdata.com/nfirs/elements/property-value/) - Relational Edit Rules for 'Property Value'. NFIRS defines relational edit rules to ensure data consi...

11. [[PDF] Estimating Fire Dollar Loss and Property Value](https://www.lasfm.org/media/3oaftoea/estimating_fire_dollar_loss_and_property_value.pdf) - incident involving a fire (Incident Type Codes 100's) is responsible for recording property dollar l...

12. [NERIS Custom Required Fields - FireWorks Documentation](https://docs.eprfireworks.com/neris/v1/neris-custom-required-fields) - In the Subject column, select the Incident Type. · In the Assert Role column, select Error or Warnin...

13. [NERIS Incident Types - Responserack](https://www.responserack.com/neris/spec/values/incident/) - All of the incident top groups, presented together. Value, Definition. Fire, FIRE. Hazardous Situati...

14. [NFIRSGram: Calculating fire loss on NFIRS forms - USFA.FEMA.gov](https://www.usfa.fema.gov/nfirs/coding-help/calculating-fireloss/) - This NFIRSGram explains how to calculate fire loss to accurately document a fire incident in the Nat...

15. [NFIRS 5.0 Element: ‘Property Loss’ - APX Data](https://apxdata.com/nfirs/elements/property-loss/)

16. [SFMD Newsletter](https://dps.mn.gov/divisions/sfm/for-fire-departments/sfmd-newsletter/Pages/estimating-property-valuation-loss.aspx)

17. [Fire Department Use of NFIRS](http://www.nfic.org/docs/FireDepartmentUseofNFIRS.pdf)

18. [Annual Report Components | MTAS - Serving Tennessee City Officials](https://www.mtas.tennessee.edu/reference/annual-report-components) - Items that may be part of a fire department annual report include: Budget, Incident responses from t...

19. [Stay NERIS Ready with Flexible Fire Data Collection - ImageTrend](https://www.imagetrend.com/blog/neris-secondary-schemas-fire-data/) - Use ImageTrend Elite to document investigations and local data not yet in NERIS. Stay compliant now ...

20. [NERIS Transition Checklist for Fire Departments - ImageTrend](https://www.imagetrend.com/blog/neris-checklist-fire-reporting/) - Prepare for the NFIRS to NERIS transition with this fire reporting checklist. Get steps for setup, t...

21. [Recent legislation requires that fire departments report emergency ...](https://www.facebook.com/VaFirePrograms/posts/recent-legislation-requires-that-fire-departments-report-emergency-incidents-to-/1214848460678085/) - Recent legislation requires that fire departments report emergency incidents to NERIS to receive Aid...

22. [Preparing for Your Transition to NERIS - Virginia Department of Fire ...](https://www.vafire.com/preparing-for-your-transition-to-neris/) - NFIRS will stop accepting new incident reports after 2025 and sunset in January 2026. While historic...

23. [Incident Types - FireWorks Documentation](https://docs.eprfireworks.com/neris/v1/incident-types) - Incident classification is a critical component of NERIS reporting and determines which modules and ...

24. [ImageTrend Issues Policy Position Statement on NERIS Data Flow](https://www.imagetrend.com/press-releases/imagetrend-neris-policy-announcement/) - NERIS has communicated in its documentation that incident data is to flow directly from agencies to ...

25. [ImageTrend Policy Position Statement on NERIS Data Flow](https://www.imagetrend.com/blog/neris-data-flow-policy/) - ImageTrend supports an agency → state → NERIS data flow to preserve compliance, oversight, and data ...

26. [[PDF] Virginia Fire Prevention and Control Plan](https://www.vafire.com/wp-content/uploads/2024/06/Addendum-1-6.24.pdf) - 2024-2025 academic year and (ii) the URL of or a. QR Code that directs ... notification as required ...

