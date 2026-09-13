# OPUNÉ® Evidence Taxonomy

## Purpose

This document defines the evidence vocabulary used within the OPUNÉ® Material Ontology.

Evidence establishes the basis on which a technical statement, measurement, relationship, specification, assessment, or validation status may be supported.

The ontology separates evidence from claims, targets, hypotheses, specifications, and conclusions.

The fundamental relationship is:

`Claim → Evidence → Assessment → Status`

For measured material information:

`Material System → Test Method → Result → Evidence → Assessment`

---

## Evidence Classes

The current evidence taxonomy includes:

1. Primary Material Data
2. Primary Process Data
3. Laboratory Test Data
4. Laboratory Reports
5. Published Scientific Evidence
6. Technical Standards and Methods
7. Regulatory and Government Sources
8. Supplier or Supply Evidence
9. Customer or Application Requirements
10. Derived Information
11. Comparative Evidence
12. Lifecycle Data
13. Validation Evidence
14. Qualification Evidence

The appropriate evidence class depends on the origin and purpose of the information.

---

## Primary Material Data

Primary material data is information generated directly from the investigation, development, characterization, measurement, or testing of a defined material system.

Examples may include:

- Material composition measurements
- Physical measurements
- Mechanical test results
- Surface characterization
- Dimensional measurements
- Material architecture observations
- Processing observations

Primary data should identify the material configuration and relevant measurement or test conditions.

A primary measurement does not automatically establish suitability for every application.

---

## Primary Process Data

Primary process data is information generated from an actual material-processing activity.

Examples may include:

- Processing conditions
- Temperature
- Pressure
- Time
- Moisture condition
- Formulation
- Material ratios
- Process yield
- Equipment conditions
- Output characteristics

Process data should be associated with the specific feedstock, material configuration, and processing pathway where applicable.

---

## Laboratory Test Data

Laboratory test data consists of measurements generated through a defined laboratory evaluation.

A laboratory result should, where available, identify:

- Material
- Material architecture
- Specimen configuration
- Test method
- Test conditions
- Units
- Result
- Laboratory or testing source
- Date
- Relevant standard or procedure

A laboratory result should not be detached from its test context.

---

## Laboratory Reports

A laboratory report is a documented record containing laboratory evaluation information.

A report may contain:

- Test identification
- Material identification
- Specimen information
- Test method
- Test conditions
- Results
- Observations
- Interpretation
- Laboratory information
- Report date
- Report reference

A report provides evidence for the documented scope of testing.

It does not automatically establish certification, regulatory compliance, or universal application suitability.

---

## Published Scientific Evidence

Published scientific evidence consists of information available through scientific literature or other established technical publications.

Potential sources include:

- Peer-reviewed research
- Academic publications
- Scientific databases
- Technical conference publications
- Established research reports

Published evidence should be represented with sufficient bibliographic information to identify the source.

Where a published result concerns a different material, feedstock, architecture, process, or test condition, that difference should be preserved.

---

## Technical Standards and Methods

Technical standards and methods provide defined procedures, terminology, classifications, or requirements.

Examples may include:

- Testing standards
- Measurement standards
- Material test methods
- Industry specifications
- Laboratory procedures

A standard or test method is not itself evidence that a material passed the method.

The distinction is:

`Standard / Method → Defines Evaluation`

and:

`Evaluation → Produces Result`

---

## Regulatory and Government Sources

Regulatory and government sources may provide authoritative information concerning:

- Legal requirements
- Regulatory classifications
- Environmental requirements
- Product requirements
- Material restrictions
- Government programs
- Official statistics
- Official technical guidance

Regulatory information should be interpreted according to the relevant jurisdiction, product category, and application.

A government source should not be treated as evidence of a material property unless it actually provides such evidence.

---

## Supplier or Supply Evidence

Supplier or supply evidence concerns information relating to feedstock sourcing, availability, physical form, or supply conditions.

Potential information includes:

- Feedstock origin
- Supply form
- Available quantity
- Moisture condition
- Processing condition
- Geographic source
- Supplier specifications

Supplier information should be distinguished from independently measured material data.

Supplier-provided characteristics should not automatically be treated as independently validated.

---

## Customer or Application Requirements

Customer or application requirements define requirements associated with a specific commercial or industrial use.

Potential requirements include:

- Performance
- Dimensions
- Surface characteristics
- Durability
- Processing compatibility
- Regulatory requirements
- Certification requirements
- Manufacturing requirements

A customer requirement is evidence of an application requirement.

It is not evidence that the material satisfies the requirement.

---

## Derived Information

Derived information is calculated, transformed, or interpreted from documented source data.

Examples include:

- Calculated values
- Ratios
- Aggregations
- Conversions
- Statistical summaries
- Model outputs
- Interpretations based on documented evidence

Derived information should retain a relationship to its source data.

The preferred structure is:

`Source Data → Calculation / Interpretation → Derived Information`

Derived information should not be presented as primary measurement.

---

## Comparative Evidence

Comparative evidence is generated by comparing two or more defined materials, processes, architectures, or systems.

A meaningful comparison requires:

- Defined comparison subjects
- Comparable conditions
- Defined methodology
- Consistent units
- Appropriate interpretation

Comparative evidence should not be generalized beyond the compared configurations.

For example:

`Material A performs differently from Material B under Test X`

does not establish:

`Material A is universally superior to Material B`

---

## Lifecycle Data

Lifecycle data provides information used within lifecycle assessment or related environmental analysis.

Potential lifecycle data categories include:

- Feedstock inputs
- Energy inputs
- Water inputs
- Processing inputs
- Material quantities
- Transport
- Conversion
- Use
- End-of-life
- Waste streams

Lifecycle data should be associated with:

- Functional unit
- System boundary
- Dataset
- Geography
- Time period
- Allocation approach where applicable
- Methodology

Lifecycle data should not be converted into universal environmental claims without a defined assessment.

---

## Validation Evidence

Validation evidence supports a conclusion that a defined requirement has been evaluated and satisfied within a defined scope.

The relationship is:

`Requirement → Evaluation → Evidence → Assessment → Validation`

Validation evidence should identify:

- Requirement
- Material system
- Evaluation method
- Result
- Assessment
- Scope

Validation is always bounded by the requirements and conditions assessed.

---

## Qualification Evidence

Qualification evidence supports a defined qualification process for a material, process, component, supplier, or system.

Potential qualification evidence may include:

- Test reports
- Process records
- Application trials
- Manufacturing evaluations
- Regulatory documentation
- Customer specifications
- Qualification reports

Qualification status should only be assigned when the relevant qualification process has been completed and documented.

---

## Evidence Metadata

An evidence record may contain:

```text
Evidence ID
Evidence Type
Title
Source
Source Organization
Publication Date
Document Date
Material System
Feedstock
Material Architecture
Processing
Application
Requirement
Test Method
Result
Units
Geography
Scope
Version
Evidence Status
Reference
Notes
