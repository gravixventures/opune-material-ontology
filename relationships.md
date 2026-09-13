# OPUNÉ® Ontology Relationships

## Purpose

This document defines the relationships connecting feedstocks, processing pathways, material architectures, material systems, applications, evaluation, and lifecycle assessment within the OPUNÉ® Material Ontology.

The relationship model is intended to describe how material-development concepts connect without treating a feedstock, process, architecture, or application as an isolated category.

## Core Relationship

The primary material-development relationship is:

`Feedstock → Processing → Material Architecture → Material System → Application → Evaluation`

This relationship represents a development pathway.

It does not imply that every feedstock can produce every architecture or that every material system is suitable for every application.

## Feedstock Relationships

A feedstock may be related to:

`Feedstock → Preparation`

`Feedstock → Processing`

`Feedstock → Material Architecture`

`Feedstock → Material System`

`Feedstock → Lifecycle Evaluation`

A feedstock relationship should identify the documented development or investigation context where possible.

## Processing Relationships

Processing connects material inputs to resulting structures.

`Feedstock → Processing`

`Intermediate → Processing`

`Processing → Material Architecture`

`Processing → Material System`

`Processing → Process Evaluation`

`Processing → Lifecycle Evaluation`

Processing conditions should be associated with the specific material pathway where documented.

## Material Architecture Relationships

Material architecture connects processing to a defined material system.

`Processing → Material Architecture`

`Material Architecture → Material System`

`Material Architecture → Application`

`Material Architecture → Evaluation`

A material architecture does not independently establish application suitability.

## Material System Relationships

A material system represents the complete material configuration being evaluated.

A material system may contain relationships to:

- Feedstock
- Processing
- Material architecture
- Matrix
- Reinforcement
- Filler
- Substrate
- Backing
- Surface layer
- Coating
- Finish
- Application
- Evaluation
- Lifecycle assessment

The complete material system should be treated as the primary object when assessing application performance.

## Application Relationships

The application relationship is:

`Material System → Application`

Applications may also connect to:

`Application → Application Requirement`

`Application Requirement → Material Specification`

`Material Specification → Test Method`

`Test Method → Result`

`Result → Assessment`

`Assessment → Validation`

This structure separates intended use from demonstrated performance.

## Evaluation Relationships

Evaluation connects a defined material system to evidence.

`Material System → Evaluation`

`Evaluation → Test Method`

`Test Method → Result`

`Result → Evidence`

`Evidence → Assessment`

`Assessment → Validation`

A test result should remain connected to the material configuration, test method, conditions, and scope under which it was produced.

## Requirement Relationships

Requirements define what a material system needs to satisfy for a particular application.

The relationship is:

`Application → Requirement`

A requirement may define:

- Performance
- Physical characteristics
- Mechanical characteristics
- Surface characteristics
- Durability
- Processing compatibility
- Regulatory requirements
- Certification requirements
- Customer specifications

A requirement is not evidence of achieved performance.

## Specification Relationships

A specification translates defined requirements into measurable or verifiable criteria.

`Requirement → Specification`

A specification may contain:

- Parameter
- Unit
- Test method
- Acceptance criterion
- Material configuration
- Application context

A target specification must not be represented as an achieved result.

## Testing Relationships

Testing establishes a defined measurement or assessment.

`Specification → Test Method`

`Material System → Test Method`

`Test Method → Result`

The test method should identify the relevant procedure, conditions, specimen configuration, and measurement approach where applicable.

## Validation Relationships

Validation determines whether defined requirements are supported within a defined scope.

`Requirement → Evaluation`

`Evaluation → Evidence`

`Evidence → Assessment`

`Assessment → Validation`

Validation should identify the material, application, requirement, and evidence scope.

Validation for one application should not automatically be transferred to another application.

## Qualification Relationships

Qualification represents a defined assessment process for a material, process, component, or system.

`Material System → Qualification`

`Application → Qualification`

`Requirement → Qualification`

`Qualification → Qualification Status`

Qualification status should only be assigned where supporting documentation exists.

## Lifecycle Relationships

Lifecycle evaluation connects material-development stages with environmental assessment.

`Feedstock → Lifecycle Evaluation`

`Processing → Lifecycle Evaluation`

`Material System → Lifecycle Evaluation`

`Application → Lifecycle Evaluation`

Lifecycle evaluation should retain its:

- Functional unit
- System boundary
- Inventory data
- Assumptions
- Methodology
- Impact assessment approach
- Interpretation

## Evidence Relationships

Evidence should remain connected to the claim or result it supports.

`Claim → Evidence`

`Result → Evidence`

`Assessment → Evidence`

Evidence types include:

- Primary data
- Laboratory data
- Published evidence
- Derived information
- Specification
- Target
- Hypothesis
- Validation result

The evidence type should not be confused with the technical status of the material.

## Development Status Relationships

Material-development status may be represented separately from technical evidence.

Potential statuses include:

- Investigation
- Development
- Under Evaluation
- Characterized
- Tested
- Validated
- Qualified
- Commercial Application

A status should only be assigned when supported by documented evidence.

## Feedstock-to-Application Relationship

The ontology deliberately avoids treating this as a direct suitability relationship:

`Feedstock → Application`

Instead, the preferred structure is:

`Feedstock → Processing → Material Architecture → Material System → Application → Evaluation`

This distinction prevents feedstock identity from being interpreted as proof of application performance.

## Processing-to-Application Relationship

The preferred relationship is:

`Processing → Material Architecture → Material System → Application`

A processing method alone does not establish suitability for an application.

## Architecture-to-Application Relationship

The relationship:

`Material Architecture → Application`

represents an application-development pathway.

It does not mean:

`Material Architecture = Application Suitability`

Application suitability requires defined requirements and evaluation.

## Application-to-Evaluation Relationship

The preferred relationship is:

`Application → Requirement → Specification → Evaluation`

This allows the ontology to distinguish application requirements from measured performance.

## Evaluation-to-Validation Relationship

The relationship is:

`Evaluation → Evidence → Assessment → Validation`

Validation should identify the scope of the assessment.

A validated characteristic is not necessarily a validated complete material system.

## Material-to-Lifecycle Relationship

The preferred lifecycle relationship is:

`Material System → Lifecycle Assessment`

rather than:

`Feedstock → Environmental Benefit`

The latter is insufficient because lifecycle outcomes depend on the complete system, processing pathway, data, assumptions, and defined boundaries.

## Multi-Component Relationships

A material system may contain multiple components:

`Material System → Feedstock`

`Material System → Matrix`

`Material System → Substrate`

`Material System → Backing`

`Material System → Surface Layer`

`Material System → Coating`

`Material System → Finish`

Component relationships should be documented when relevant to the material's technical description.

## Multi-Layer Relationships

A multilayer material may be represented as:

`Material System → Layer 1`

`Material System → Layer 2`

`Material System → Layer 3`

with each layer having its own:

- Material identity
- Function
- Thickness
- Processing
- Surface characteristics
- Evidence

Layer relationships should not be collapsed into a single material identity when doing so would obscure the actual construction.

## Machine-Readable Relationship Pattern

A relationship can be represented conceptually as:

```text
Subject → Predicate → Object
