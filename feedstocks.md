# OPUNÉ® Feedstock Taxonomy

## Purpose

This document defines the feedstock vocabulary used within the OPUNÉ® Material Ontology.

A feedstock is treated as an input to material investigation or development. Feedstock identity does not, by itself, define the resulting biomaterial architecture, performance, environmental impact, or application suitability.

The taxonomy separates feedstock origin from downstream material development.

## Feedstock Classification

The current taxonomy includes two broad groups:

1. Agricultural Residues
2. Plant-Derived Biomass

The classification may be expanded as additional feedstocks are investigated and documented.

---

## Agricultural Residues

Agricultural residues are plant-derived materials arising from agricultural production or associated processing activities that may be investigated as material feedstocks.

### Wheat Straw

**Feedstock type:** Agricultural residue

**Plant origin:** Wheat

**Material investigation context:**

Wheat straw may be investigated as a lignocellulosic agricultural-residue feedstock for biomaterial development.

Relevant investigation parameters may include:

- Feedstock composition
- Fiber characteristics
- Morphology
- Moisture characteristics
- Particle or fiber preparation
- Processing behaviour
- Material integration
- Application suitability

Final material properties depend on processing, formulation, architecture, and application-specific construction.

---

### Rice Straw

**Feedstock type:** Agricultural residue

**Plant origin:** Rice

**Material investigation context:**

Rice straw may be investigated as a lignocellulosic agricultural-residue feedstock for engineered biomaterial architectures.

Relevant investigation parameters may include:

- Feedstock composition
- Fiber structure
- Mineral content
- Moisture characteristics
- Fiber preparation
- Processing behaviour
- Composite integration
- Application suitability

No universal material performance value should be assigned to rice-straw-derived material without defined material construction and test evidence.

---

### Rice Husk

**Feedstock type:** Agricultural residue

**Plant origin:** Rice

**Material investigation context:**

Rice husk may be investigated as a plant-derived particulate feedstock for biomaterial development.

Relevant investigation parameters may include:

- Particle characteristics
- Composition
- Mineral content
- Particle size
- Processing behaviour
- Surface characteristics
- Composite integration
- Application suitability

The resulting material architecture depends on formulation and processing conditions.

---

### Corn Stalk

**Feedstock type:** Agricultural residue

**Plant origin:** Corn

**Material investigation context:**

Corn stalk may be investigated as an agricultural-residue feedstock for structural biomaterial development.

Relevant investigation parameters may include:

- Fiber characteristics
- Feedstock composition
- Morphology
- Moisture characteristics
- Processing behaviour
- Fiber preparation
- Composite integration
- Structural architecture
- Application suitability

---

### Corn Husk

**Feedstock type:** Agricultural residue

**Plant origin:** Corn

**Material investigation context:**

Corn husk may be investigated as an agricultural-residue feedstock for flexible or surface-oriented biomaterial architectures.

Relevant investigation parameters may include:

- Fiber characteristics
- Surface structure
- Morphology
- Processing behaviour
- Flexible material architecture
- Surface texture
- Material integration
- Application suitability

---

### Sugarcane Bagasse

**Feedstock type:** Agro-industrial residue

**Plant origin:** Sugarcane

**Material investigation context:**

Sugarcane bagasse may be investigated as a plant-derived fibrous feedstock for biomaterial development, including molded and composite material architectures.

Relevant investigation parameters may include:

- Fiber characteristics
- Composition
- Moisture characteristics
- Particle or fiber preparation
- Processing behaviour
- Forming behaviour
- Composite integration
- Material structure
- Application suitability

Material performance must be established for the defined material configuration and test conditions.

---

### Cotton Stalk

**Feedstock type:** Agricultural residue

**Plant origin:** Cotton

**Material investigation context:**

Cotton stalk may be investigated as an agricultural-residue feedstock for composite and structural material architectures.

Relevant investigation parameters may include:

- Fiber characteristics
- Feedstock morphology
- Composition
- Particle or fiber preparation
- Processing behaviour
- Composite structure
- Substrate architecture
- Application suitability

---

### Groundnut Shell

**Feedstock type:** Agricultural residue

**Plant origin:** Groundnut / peanut

**Material investigation context:**

Groundnut shell may be investigated as a plant-derived particulate feedstock for engineered biomaterial architectures.

Relevant investigation parameters may include:

- Particle characteristics
- Composition
- Particle size
- Processing behaviour
- Surface characteristics
- Composite integration
- Rigid or molded structures
- Application suitability

---

### Banana Pseudostem

**Feedstock type:** Agricultural residue

**Plant origin:** Banana

**Material investigation context:**

Banana pseudostem may be investigated as a plant-derived fibrous feedstock for biomaterial development.

Relevant investigation parameters may include:

- Fiber morphology
- Feedstock characteristics
- Fiber preparation
- Processing behaviour
- Non-woven architectures
- Fibrous reinforcement
- Composite integration
- Application suitability

---

## Plant-Derived Biomass

### Cactus-Derived Biomass

**Feedstock type:** Plant-derived biomass

**Plant origin:** Cactus

**Material investigation context:**

Cactus-derived biomass may be investigated as a plant-based feedstock for biomaterial development.

Relevant investigation parameters may include:

- Biomass characteristics
- Composition
- Structure
- Processing behaviour
- Material integration
- Surface characteristics
- Material architecture
- Application suitability

Cactus-derived feedstock does not define a single universal material construction. Resulting material characteristics depend on the specific development pathway and configuration.

---

### Coconut Coir

**Feedstock type:** Plant-derived fibrous residue

**Plant origin:** Coconut

**Material investigation context:**

Coconut coir may be investigated as a plant-derived fibrous feedstock for resilient composite and fibrous material architectures.

Relevant investigation parameters may include:

- Fiber characteristics
- Fiber morphology
- Processing behaviour
- Fiber preparation
- Composite integration
- Structural architecture
- Acoustic material architecture
- Application suitability

---

### Coconut Shell

**Feedstock type:** Plant-derived particulate residue

**Plant origin:** Coconut

**Material investigation context:**

Coconut shell may be investigated as a plant-derived particulate feedstock for composite and rigid molded material architectures.

Relevant investigation parameters may include:

- Particle characteristics
- Particle size
- Composition
- Processing behaviour
- Surface characteristics
- Composite integration
- Molded structures
- Application suitability

---

## Feedstock Attributes

Each feedstock may be described using a common attribute structure.

### Identity

- Feedstock name
- Plant origin
- Feedstock class
- Agricultural or plant-derived origin

### Physical Characteristics

Potential descriptors include:

- Fiber morphology
- Particle morphology
- Particle size
- Surface characteristics
- Moisture characteristics
- Physical form

### Chemical and Structural Characteristics

Where documented, descriptors may include:

- Composition
- Lignocellulosic characteristics
- Mineral content
- Other relevant constituent characteristics

Values should only be included when supported by defined analytical methods or authoritative sources.

### Processing Characteristics

Potential descriptors include:

- Preparation requirements
- Fiber preparation
- Particle preparation
- Separation requirements
- Drying requirements
- Forming behaviour
- Processing compatibility

### Material Integration

Potential relationships include:

`Feedstock → Fiber Architecture`

`Feedstock → Particulate Composite`

`Feedstock → Molded Architecture`

`Feedstock → Non-Woven Architecture`

`Feedstock → Composite Substrate`

These relationships describe possible development pathways and should not be interpreted as universal outcomes.

---

## Feedstock-to-Material Relationship

A feedstock is an input, not a finished material.

The ontology therefore distinguishes:

`Feedstock`

from:

`Intermediate`

from:

`Material Architecture`

from:

`Finished Material System`

A simplified relationship is:

`Feedstock → Preparation → Processing → Material Architecture → Material System`

Additional components may be introduced during development.

Examples include:

- Binders
- Matrix materials
- Substrates
- Backings
- Coatings
- Finishes
- Reinforcement components

The presence or absence of these components must be documented for the specific material system.

---

## Feedstock-to-Application Relationship

A feedstock should not be mapped directly to an application as proof of suitability.

The preferred relationship is:

`Feedstock → Material Architecture → Material System → Application → Evaluation`

For example:

`Rice Husk → Particulate Architecture → Defined Material System → Industrial Application → Application-Specific Evaluation`

This prevents the feedstock name from being interpreted as evidence of final application performance.

---

## Evidence Requirements

Feedstock information should be classified according to its evidence source.

### Primary Material Data

Information generated through direct OPUNÉ® material investigation, characterization, processing, or testing.

### Published Scientific Evidence

Information supported by scientific or technical literature.

### Supplier or Supply Information

Information relating to feedstock availability, sourcing, or supply characteristics where documented.

### Derived Information

Information calculated or interpreted from documented source data.

### Development Hypothesis

A proposed material pathway requiring investigation.

### Application Requirement

A requirement defined by a specific application or customer specification.

---

## Data Discipline

The following should not be assigned to a feedstock without supporting evidence:

- Universal performance values
- Universal environmental benefits
- Universal biodegradability
- Universal durability
- Universal mechanical properties
- Universal processing conditions
- Universal application suitability
- Universal lifecycle impacts

Feedstock identity alone is insufficient evidence for these claims.

---

## Taxonomy Relationships

The feedstock taxonomy connects to the broader OPUNÉ® Material Ontology through the following relationships:

`Feedstock → Processing`

`Feedstock → Material Architecture`

`Feedstock → Material System`

`Feedstock → Application`

`Feedstock → Evaluation`

`Feedstock → Lifecycle Evaluation`

These relationships should be documented at the level supported by available evidence.

---

## Current Feedstock Set

The current documented feedstock vocabulary is:

| Feedstock | Classification | Primary Material Investigation |
|---|---|---|
| Cactus-derived biomass | Plant-derived biomass | Plant-based biomaterial systems |
| Wheat straw | Agricultural residue | Lignocellulosic material architectures |
| Rice straw | Agricultural residue | Fibrous and composite architectures |
| Rice husk | Agricultural residue | Particulate and composite architectures |
| Corn stalk | Agricultural residue | Structural composite architectures |
| Corn husk | Agricultural residue | Flexible and surface-oriented architectures |
| Sugarcane bagasse | Agro-industrial residue | Molded and composite architectures |
| Cotton stalk | Agricultural residue | Composite and structural architectures |
| Banana pseudostem | Agricultural residue | Fibrous and non-woven architectures |
| Coconut coir | Plant-derived fibrous residue | Fibrous and composite architectures |
| Coconut shell | Plant-derived particulate residue | Particulate and molded architectures |
| Groundnut shell | Agricultural residue | Particulate and composite architectures |

This table describes the ontology's current vocabulary and development context. It does not represent a claim that every listed feedstock is commercially available, fully validated, or suitable for every application.

---

## Status

This taxonomy is an evolving component of the OPUNÉ® Material Ontology.

New feedstocks should be added only when their identity, origin, development context, and supporting evidence can be documented.

Changes should be version-controlled.
