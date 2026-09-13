# OPUNÉ® Processing Taxonomy

## Purpose

This document defines the processing vocabulary used within the OPUNÉ® Material Ontology.

Processing describes the operations through which a feedstock or intermediate material is prepared, transformed, combined, formed, consolidated, finished, or converted into a defined material architecture.

Processing is distinct from feedstock identity and final material performance.

The principal relationship is:

`Feedstock → Preparation → Processing → Material Architecture → Material System → Application → Evaluation`

---

## Processing Classes

The current processing taxonomy includes:

1. Feedstock Preparation
2. Size Reduction
3. Separation
4. Fiber Preparation
5. Particle Preparation
6. Drying
7. Formulation
8. Mixing
9. Forming
10. Molding
11. Consolidation
12. Lamination
13. Surface Treatment
14. Coating
15. Finishing
16. Conversion

These classes may occur in different sequences depending on the material system.

---

## Feedstock Preparation

Feedstock preparation describes operations performed before the primary material-development process.

Potential activities include:

- Cleaning
- Sorting
- Removal of foreign matter
- Separation of unsuitable fractions
- Moisture adjustment
- Conditioning
- Preparation for downstream processing

The exact preparation sequence depends on feedstock characteristics and the intended material architecture.

---

## Size Reduction

Size reduction changes the physical dimensions of a feedstock or intermediate material.

Potential operations include:

- Cutting
- Chopping
- Milling
- Grinding
- Shredding
- Other defined size-reduction processes

Relevant parameters may include:

- Input form
- Output size
- Particle-size distribution
- Fiber dimensions
- Processing conditions
- Equipment configuration

Size reduction should be documented where it materially influences downstream processing or material structure.

---

## Separation

Separation isolates different physical fractions or constituents of a feedstock.

Potential approaches may include:

- Mechanical separation
- Sieving
- Screening
- Density-based separation
- Fiber / particle separation
- Removal of non-target fractions

Separation parameters should be documented according to the actual process used.

---

## Fiber Preparation

Fiber preparation describes operations used to prepare plant-derived fibers for material development.

Potential activities include:

- Fiber extraction
- Fiber separation
- Fiber opening
- Fiber cleaning
- Fiber sizing
- Fiber conditioning

Relevant characteristics may include:

- Fiber morphology
- Fiber dimensions
- Fiber distribution
- Moisture characteristics
- Surface characteristics

Fiber preparation influences subsequent architecture formation and should not be treated as equivalent across different feedstocks.

---

## Particle Preparation

Particle preparation describes operations used to prepare particulate feedstocks or intermediate materials.

Potential parameters include:

- Particle size
- Particle-size distribution
- Particle morphology
- Surface characteristics
- Moisture characteristics
- Screening or classification

Particle preparation may be relevant to particulate composites, molded forms, and other matrix-based architectures.

---

## Drying

Drying removes or adjusts moisture from a feedstock or intermediate material.

Relevant parameters may include:

- Initial moisture condition
- Target moisture condition
- Temperature
- Time
- Air conditions
- Drying method

Specific drying conditions should be documented from actual process data.

No universal drying condition should be assigned to all plant-derived feedstocks.

---

## Formulation

Formulation defines the composition of a material system before forming or consolidation.

A formulation may include:

- Plant-derived feedstock
- Matrix components
- Binders
- Reinforcement
- Fillers
- Substrates
- Other material components

Formulation should distinguish between:

`Feedstock`

and:

`Complete Material System`

The presence of a plant-derived feedstock does not establish that the complete formulation is plant-derived.

---

## Mixing

Mixing combines two or more constituents to achieve a defined distribution or formulation.

Potential parameters include:

- Component identity
- Component proportion
- Mixing sequence
- Mixing time
- Mixing conditions
- Dispersion
- Homogeneity

Mixing behaviour can influence the structure and performance of the resulting material.

---

## Forming

Forming transforms an intermediate material or formulation into a defined geometry or structure.

Potential operations include:

- Sheet formation
- Web formation
- Press forming
- Compression forming
- Layer formation
- Other defined forming processes

Forming conditions should be linked to the resulting material architecture.

---

## Molding

Molding produces a defined three-dimensional material geometry using a mold or forming tool.

Potential parameters include:

- Mold geometry
- Material formulation
- Forming pressure
- Temperature
- Time
- Consolidation conditions
- Drying or curing conditions

Specific parameters must be documented for the actual process.

---

## Consolidation

Consolidation increases structural coherence within a material architecture.

Potential mechanisms may include:

- Pressure
- Heat
- Bonding
- Matrix formation
- Fiber bonding
- Compression
- Other defined mechanisms

Consolidation may be used in:

- Fibrous structures
- Non-woven architectures
- Composite substrates
- Particulate composites
- Molded forms

---

## Lamination

Lamination joins two or more material layers into a combined structure.

Potential components include:

- Surface layers
- Substrates
- Backings
- Composite layers
- Supporting structures

Relevant parameters may include:

- Adhesive system
- Bonding method
- Pressure
- Temperature
- Time
- Layer compatibility
- Surface preparation

Lamination behaviour must be evaluated for the specific materials and construction.

---

## Surface Treatment

Surface treatment modifies a material surface to achieve a defined functional, physical, or aesthetic outcome.

Potential processes include:

- Surface preparation
- Mechanical treatment
- Chemical treatment
- Plasma or other defined treatments
- Surface conditioning

The treatment should be documented according to the actual process.

---

## Coating

Coating applies a defined material layer to a surface.

Potential purposes include:

- Surface modification
- Protection
- Appearance
- Functional modification
- Barrier modification
- Other application-specific requirements

A coating is a separate material component unless documented otherwise.

Coating presence must therefore be considered when describing the complete material system.

---

## Finishing

Finishing describes downstream operations that establish or modify the final material surface or appearance.

Potential processes include:

- Surface finishing
- Texture development
- Surface treatment
- Colour application
- Protective finishing
- Other conversion processes

Finishing should be distinguished from the intrinsic characteristics of the underlying material.

---

## Conversion

Conversion describes operations that transform a developed material into a form suitable for a defined product or application.

Potential operations include:

- Cutting
- Stitching
- Die cutting
- Folding
- Forming
- Bonding
- Lamination
- Component assembly
- Other application-specific operations

Conversion requirements depend on the target product and manufacturing process.

---

## Processing Sequence

A processing pathway may be represented as:

`Feedstock → Preparation → Size Reduction → Separation → Fiber / Particle Preparation → Drying → Formulation → Mixing → Forming → Consolidation → Finishing → Conversion`

Not every material system requires every stage.

The actual sequence should be documented according to the material-development pathway.

---

## Processing and Feedstock

Processing requirements are feedstock-specific.

Factors that may influence processing include:

- Feedstock morphology
- Fiber characteristics
- Particle characteristics
- Composition
- Moisture
- Contaminants
- Physical form
- Supply condition

A processing method developed for one feedstock should not automatically be assumed to apply to another.

---

## Processing and Material Architecture

Processing directly influences material architecture.

Examples include:

`Fiber Preparation → Fibrous Architecture`

`Web Formation → Non-Woven Architecture`

`Particle Preparation → Particulate Composite`

`Formulation + Molding → Molded Form`

`Layer Formation + Lamination → Composite Substrate`

`Surface Treatment + Coating → Surface-Layer System`

These are process relationships, not universal outcomes.

---

## Processing and Material Performance

Processing conditions can influence:

- Material structure
- Density
- Porosity
- Fiber distribution
- Particle distribution
- Layer adhesion
- Surface characteristics
- Dimensional behaviour
- Mechanical response

Performance conclusions require measurement under defined conditions.

Processing terminology alone does not establish a performance value.

---

## Processing Parameters

Where technically relevant, a processing record may contain:

```text
Process ID
Feedstock
Input Material
Process Class
Process Step
Equipment
Processing Conditions
Temperature
Pressure
Time
Moisture Condition
Material Ratio
Output Material
Resulting Architecture
Operator / Facility
Date
Notes
