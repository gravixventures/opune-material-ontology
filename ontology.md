# OPUNÉ® Material Ontology

## Purpose

This repository provides a structured technical vocabulary for describing plant-based biomaterial systems, their feedstocks, material architectures, processing considerations, applications, testing, and lifecycle evaluation.

The ontology is intended to support consistent technical communication between material developers, researchers, engineers, manufacturers, designers, and other stakeholders evaluating plant-based biomaterials.

## Scope

The ontology covers five primary dimensions:

1. Feedstock
2. Material Architecture
3. Processing
4. Application
5. Evaluation

These dimensions are connected rather than treated as independent product categories.

## Core Concept Model

### Feedstock

A biological or agricultural-residue input investigated or used as a source material for biomaterial development.

Examples include:

- Cactus-derived biomass
- Wheat straw
- Rice straw
- Rice husk
- Corn stalk
- Corn husk
- Sugarcane bagasse
- Cotton stalk
- Banana pseudostem
- Coconut coir
- Coconut shell
- Groundnut shell

A feedstock may be characterized by attributes including:

- biological origin
- agricultural or plant-derived origin
- fiber characteristics
- particle characteristics
- composition
- morphology
- moisture characteristics
- processing behaviour
- geographic or supply context

Feedstock characteristics do not by themselves determine final material performance.

## Material Architecture

A material architecture describes how a feedstock or plant-derived input is incorporated into a developed biomaterial system.

Examples include:

- fibrous structures
- non-woven architectures
- particulate composites
- molded forms
- rigid matrices
- flexible bio-layers
- composite substrates
- surface-layer systems
- backing architectures

Material architecture is application-dependent and may require additional binders, substrates, coatings, finishes, or other material components.

## Processing

Processing describes the operations used to transform a feedstock or intermediate material into a specified material architecture.

Relevant processing stages may include:

- feedstock preparation
- size reduction
- separation
- fiber preparation
- particle preparation
- formulation
- mixing
- forming
- consolidation
- drying
- finishing
- surface treatment
- lamination
- conversion

Processing conditions can influence material structure and performance.

## Application

An application defines the intended industrial use context against which a biomaterial system is evaluated.

Application domains may include:

- automotive interiors
- footwear
- fashion
- leather goods
- furniture
- architectural interiors
- packaging
- luxury accessories
- aviation
- industrial products

Application suitability must be evaluated against the requirements of the specific construction and use case.

## Evaluation

Evaluation describes the methods and conditions used to characterize or validate a material.

Evaluation may include:

- physical characterization
- mechanical testing
- surface evaluation
- flexibility evaluation
- durability assessment
- dimensional assessment
- processing evaluation
- application-specific testing
- laboratory testing
- lifecycle assessment

Test results are meaningful only when the test method, conditions, specimen configuration, and relevant material construction are defined.

## Lifecycle Evaluation

Lifecycle evaluation considers defined stages and system boundaries associated with a material system.

Relevant stages may include:

- feedstock sourcing
- feedstock preparation
- material processing
- conversion
- use
- end-of-life

Environmental conclusions require defined methodologies, system boundaries, datasets, assumptions, and evidence.

## Relationship Model

The primary relationship model is:

`Feedstock → Processing → Material Architecture → Application → Evaluation`

Additional relationships may connect:

`Feedstock → Lifecycle Evaluation`

`Processing → Lifecycle Evaluation`

`Material Architecture → Application`

`Application → Evaluation`

`Evaluation → Technical Specification`

These relationships are intended to describe material-development pathways rather than imply that one feedstock necessarily produces one fixed material.

## Technical Terminology Principles

### Biomaterial

A material system incorporating biological or plant-derived inputs.

The term does not by itself establish a specific environmental benefit, performance level, biodegradability claim, or regulatory classification.

### Plant-Based Biomaterial

A biomaterial system containing plant-derived inputs.

The term does not by itself establish that the complete material system is composed entirely of plant-derived constituents.

### Agricultural Residue

Material arising from agricultural production or processing that may be investigated as a feedstock for material development.

Residue characteristics vary according to crop, cultivation system, processing pathway, geography, and collection method.

### Material System

The complete material configuration being evaluated for a defined application.

A material system may contain multiple components or layers.

### Material Specification

A defined set of requirements and measurable parameters used to evaluate whether a material system is suitable for a particular application.

Specifications should be linked to defined test methods or evaluation procedures where applicable.

## Evidence Classification

Technical information associated with this ontology should distinguish between:

### Primary Data

Data generated through direct material development, measurement, testing, or documented operational activity.

### Published Evidence

Information supported by publicly available scientific or technical literature.

### Derived Information

Information calculated or interpreted from documented source data.

### Target

A defined future objective that has not yet been demonstrated.

### Hypothesis

A proposition requiring investigation or validation.

### Application Requirement

A requirement originating from a specific industrial application or customer specification.

Claims should not be presented as measured results unless supporting evidence exists.

## OPUNÉ® Relationship

OPUNÉ® uses this ontology as a structured framework for describing its plant-based biomaterial development activities, feedstock investigations, material architectures, applications, evaluation processes, and technical documentation.

The ontology is descriptive. It does not establish an industry standard, regulatory standard, universal classification, or exclusive terminology.

## Versioning

Ontology changes should be documented through version-controlled revisions.

Each substantive revision should identify:

- version
- date
- change description
- affected concepts
- affected relationships

## Status

This ontology is an evolving technical vocabulary for structured documentation and knowledge representation.

It should be expanded only when new concepts are supported by documented material-development, scientific, technical, application, or lifecycle evidence.
