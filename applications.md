# OPUNÉ® Application Taxonomy

## Purpose

This document defines the application vocabulary used within the OPUNÉ® Material Ontology.

An application represents the industrial context in which a defined material system may be evaluated.

Application classification does not establish material suitability. Suitability must be demonstrated against the requirements of the specific construction, manufacturing process, operating environment, regulatory context, and application.

The core relationship is:

`Feedstock → Processing → Material Architecture → Material System → Application → Evaluation`

---

## Application Domains

The current application taxonomy includes:

1. Automotive Interiors
2. Footwear
3. Fashion
4. Leather Goods
5. Furniture
6. Architectural Interiors
7. Packaging
8. Luxury Accessories
9. Aviation
10. Industrial Products

These categories describe application contexts rather than guaranteed commercial uses.

---

## Automotive Interiors

Automotive interiors include material applications within vehicle interior environments.

Potential application areas may include:

- Interior trim
- Door-related surfaces
- Instrument-panel-related surfaces
- Console-related surfaces
- Seating-related material systems
- Other specified interior components

Relevant evaluation considerations may include:

- Surface characteristics
- Abrasion resistance
- Flexibility
- Dimensional behaviour
- Durability
- Processing compatibility
- Bonding or lamination
- Environmental exposure
- Odour requirements
- Application-specific regulatory requirements
- OEM or Tier-1 specifications

Material suitability must be established for the specific component and construction.

---

## Footwear

Footwear applications include material systems incorporated into footwear construction.

Potential application areas may include:

- Uppers
- Panels
- Linings
- Structural components
- Decorative components
- Other specified footwear constructions

Relevant evaluation considerations may include:

- Flexibility
- Bending behaviour
- Surface characteristics
- Abrasion
- Tear behaviour
- Adhesion
- Stitching compatibility
- Formability
- Moisture exposure
- Finishing
- Construction compatibility

Evaluation should be performed against the intended footwear construction.

---

## Fashion

Fashion applications include plant-based biomaterial systems developed for fashion products and related material constructions.

Potential application areas may include:

- Garment components
- Bags
- Accessories
- Panels
- Decorative material systems
- Other fashion constructions

Relevant evaluation considerations may include:

- Surface character
- Tactile properties
- Flexibility
- Construction
- Finish
- Colour and surface treatment
- Durability
- Manufacturing compatibility

Aesthetic suitability is application-specific and should be evaluated together with physical and manufacturing requirements.

---

## Leather Goods

Leather-goods applications include material systems used in products traditionally constructed using leather or leather-like material formats.

Potential application areas may include:

- Handbags
- Wallets
- Belts
- Small leather goods
- Cases
- Panels
- Accessories

Relevant evaluation considerations may include:

- Surface characteristics
- Flexibility
- Fold behaviour
- Edge behaviour
- Thickness
- Tear behaviour
- Abrasion
- Stitching
- Adhesion
- Finishing
- Construction compatibility

Suitability depends on the complete material system and manufacturing process.

---

## Furniture

Furniture applications include material systems incorporated into furniture products and components.

Potential application areas may include:

- Upholstery
- Panels
- Surface coverings
- Decorative components
- Interior furniture elements

Relevant evaluation considerations may include:

- Surface durability
- Abrasion
- Flexibility
- Tear behaviour
- Dimensional stability
- Cleaning requirements
- Finishing
- Bonding
- Construction compatibility

Evaluation must correspond to the intended furniture construction and use conditions.

---

## Architectural Interiors

Architectural interior applications include materials incorporated into interior spaces and architectural components.

Potential application areas may include:

- Wall-related surfaces
- Panels
- Interior coverings
- Acoustic-related material systems
- Decorative surfaces
- Interior architectural components

Relevant evaluation considerations may include:

- Surface durability
- Dimensional stability
- Fire-related requirements
- Acoustic requirements where applicable
- Moisture exposure
- Cleaning
- Installation method
- Structural requirements
- Regulatory requirements

Specific requirements depend on the building, component, jurisdiction, and intended use.

---

## Packaging

Packaging applications include material systems used for packaging structures and components.

Potential application areas may include:

- Packaging surfaces
- Rigid packaging
- Flexible packaging components
- Protective structures
- Presentation packaging
- Luxury packaging

Relevant evaluation considerations may include:

- Structural integrity
- Surface characteristics
- Formability
- Dimensional stability
- Barrier requirements
- Moisture exposure
- Finishing
- Manufacturing compatibility
- Product-contact requirements where applicable

Packaging suitability must be evaluated against the intended product and packaging system.

---

## Luxury Accessories

Luxury accessory applications include premium accessory products where material surface character, construction, and finishing may form part of the design specification.

Potential application areas may include:

- Small accessories
- Cases
- Bags
- Decorative components
- Product accessories

Relevant evaluation considerations may include:

- Surface character
- Tactility
- Finish
- Flexibility
- Construction
- Edge behaviour
- Durability
- Visual consistency

Application requirements remain product-specific.

---

## Aviation

Aviation applications include material systems considered for aircraft interiors or other aviation-related environments.

Potential application areas may include:

- Interior surfaces
- Panels
- Trim
- Seating-related components
- Decorative interior components

Relevant evaluation considerations may include:

- Fire, smoke, and toxicity requirements
- Weight
- Durability
- Abrasion
- Surface characteristics
- Cleaning
- Environmental exposure
- Bonding
- Regulatory and certification requirements

Aviation applications require application-specific qualification and compliance assessment.

No aviation suitability should be inferred from general material characterization.

---

## Industrial Products

Industrial applications include material systems developed for defined industrial products or components outside the primary application domains above.

Potential application areas may include:

- Equipment components
- Industrial panels
- Protective structures
- Technical surfaces
- Composite components
- Other specified industrial constructions

Relevant evaluation considerations depend on the intended function and operating environment.

---

## Application Attributes

Each application may be described using a common attribute structure.

### Application Domain

The broad industrial sector.

Examples:

- Automotive
- Footwear
- Fashion
- Furniture
- Packaging
- Aviation

### Product Context

The specific product or component being evaluated.

### Construction

The way the material is incorporated into the product.

Potential descriptors include:

- Surface covering
- Panel
- Layer
- Upholstery
- Composite component
- Molded component
- Flexible construction

### Manufacturing Process

The conversion process used to incorporate the material.

Potential descriptors include:

- Cutting
- Stitching
- Adhesive bonding
- Lamination
- Molding
- Forming
- Pressing
- Other application-specific processes

### Performance Requirements

Requirements defined by the intended application.

Potential categories include:

- Mechanical
- Surface
- Thermal
- Environmental
- Durability
- Dimensional
- Processing
- Regulatory

Requirements should be defined by the relevant application or specification.

---

## Application Requirements

An application is not a performance claim.

The ontology therefore distinguishes:

`Application`

from:

`Application Requirement`

from:

`Material Performance`

from:

`Application Validation`

The preferred relationship is:

`Application → Requirement → Material Specification → Testing → Validation`

This prevents a material from being classified as suitable solely because it is associated with an application category.

---

## Application-Specific Evaluation

Evaluation should be performed against the actual application context.

For example:

`Automotive Interior → Defined Component → Defined Material Construction → Required Tests → Application Evaluation`

rather than:

`Plant-Based Feedstock → Automotive → Suitable`

The second relationship is insufficient because feedstock identity does not establish application performance.

---

## Application and Material Architecture

Different applications may require different material architectures.

Examples include:

`Fibrous Architecture → Automotive Interior`

`Flexible Bio-Layer → Fashion`

`Composite Substrate → Footwear`

`Particulate Composite → Packaging`

`Surface-Layer System → Furniture`

These relationships represent potential development pathways and do not constitute universal suitability claims.

---

## Application and Evaluation

Application-specific evaluation may include:

- Physical characterization
- Mechanical testing
- Surface testing
- Abrasion testing
- Flexibility evaluation
- Durability assessment
- Dimensional assessment
- Processing evaluation
- Environmental exposure testing
- Regulatory testing
- Application-specific validation

The selected methods should correspond to the material construction and application requirements.

---

## Application and Lifecycle Evaluation

Lifecycle evaluation may vary according to application because different applications can involve different:

- Material quantities
- Manufacturing processes
- Conversion processes
- Use conditions
- Maintenance requirements
- Service lives
- Replacement cycles
- End-of-life pathways

Lifecycle conclusions therefore require a defined system boundary and documented methodology.

---

## Evidence Classification

Application information should distinguish between:

### Application Requirement

A requirement defined by a customer, manufacturer, specification, regulation, or documented application context.

### Primary Validation Data

Data generated through testing or evaluation of a defined material system in relation to an application.

### Published Evidence

Information supported by publicly available scientific or technical literature.

### Development Hypothesis

A proposed application pathway requiring investigation.

### Target

A future application objective that has not yet been demonstrated.

### Commercial Application

A documented commercial use supported by appropriate evidence.

Commercial application status should not be inferred solely from a material development project or laboratory investigation.

---

## Application Mapping Rules

The ontology follows these rules:

1. Feedstock identity does not establish application suitability.
2. Material architecture does not establish application suitability.
3. A general material test does not establish compliance with every application requirement.
4. Application claims should identify the relevant material system where possible.
5. Application-specific validation should be distinguished from general characterization.
6. Regulatory or certification claims require supporting documentation.
7. Commercial-use claims require evidence of actual commercial deployment.
8. Future applications should be identified as development pathways or targets rather than established uses.

---

## Application Relationship Map

The principal relationships are:

`Material System → Application`

`Application → Application Requirement`

`Application Requirement → Material Specification`

`Material Specification → Evaluation`

`Evaluation → Application Validation`

Additional relationships include:

`Material Architecture → Application`

`Application → Manufacturing Process`

`Application → Lifecycle Evaluation`

---

## Current Application Vocabulary

| Application Domain | Example Context | Evaluation Context |
|---|---|---|
| Automotive Interiors | Vehicle interior components | Surface, durability, processing, application-specific requirements |
| Footwear | Footwear constructions | Flexibility, abrasion, construction, durability |
| Fashion | Fashion products and material constructions | Surface, tactility, flexibility, finish |
| Leather Goods | Bags, wallets, belts and related goods | Surface, flexibility, construction, durability |
| Furniture | Upholstery and furniture surfaces | Abrasion, surface durability, cleaning, construction |
| Architectural Interiors | Interior panels and surfaces | Surface, durability, installation, regulatory requirements |
| Packaging | Packaging structures and surfaces | Structure, formability, barrier and product-specific requirements |
| Luxury Accessories | Premium accessory constructions | Surface, tactility, finish, construction |
| Aviation | Aircraft interior applications | Fire, smoke, toxicity, weight, durability, certification |
| Industrial Products | Defined industrial components | Function-specific performance and regulatory requirements |

The table describes application categories and evaluation contexts. It does not establish that a particular OPUNÉ® material is validated or commercially approved for every listed application.

---

## Status

This application taxonomy is an evolving component of the OPUNÉ® Material Ontology.

Application categories should be expanded or modified only when there is a meaningful technical distinction supported by documented application requirements, material-development activity, scientific evidence, testing, regulatory information, or documented commercial use.

All substantive changes should be version-controlled.
