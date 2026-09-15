# Unconference Sessions

The Unconference Sessions run alongside the Practical Clinical Modelling Workshop (see the [Agenda](README.md#agenda)).


## Background

The format of these sessions follow the very successful openEHR modelling Highmed UnConference organised by Antje Wulf in Jan 2026.

Listed below are the topics requested by the participants in advance, grouped into some borad themes, including some overlapping questions but this is designed as a highly interactive exercise, where participants may offer as a may answers/ experiences as questions

The first task of the day will be to review the list of topics and self-organise into breakout groups with supporting convenors.

We will ask you to indicate your preferred groups to help balance numbers but you are free to change your mind or switch group at any point.

## Candidate topics

### ADL2 and template naming/versioning

- Archetype and template design — specialisations, naming conventions and ADL2 namespaces

- ADL and template lifecycle — ADL 1.4→2.0, conversion, versioning and production

- Template versioning and production

- Archetype specialisations

- label Draft archetypes as v1-alpha instead of .v0 to smooth local 'publication'

### External integration and context

- External Care context — patients, encounters, caregivers, self-care

  - Connecting timelines with patients, encounters, caregivers, self-care, clinics and complex inpatient/outpatient prescriptions.
  
  - Modelling context about an archetype, including department codelists and composition context.
  
  - RM versus metadata clusters in COMPOSITION context
  
- Cross-model choices — preserving meaning across openEHR, FHIR and OMOP boundaries

  - Mapping openEHR with HL7 FHIR, HL7v2 and OMOP, including custom archetypes.
  
  - Conformance for openEHR and openEHR/FHIR mapping.
  
### Internal architecture and context

- Large and complex use cases — reusable modelling strategies

  - Modelling strategies for large and complex use cases; reuse, duplication and provenance of clinical data across compositions
  
  - Composition categories and persistent/episodic/event context
  
  - Treatment decision modelling.
  
  - Reuse and provenance — preserving meaning while avoiding duplicated clinical data
  
  - Conformance in practice — what to standardise, test and demonstrate
  
- Implementation guidance and conformance — practical standards for consistent implementations
  
  - Where do EHR Slices fit?

### Workflow - INSTRUCTIONS and ACTIONS

- Clinical workflows ... INSTRUCTION/ACTION pairs and ISM in practice
  
- Real-world use of the Instruction State Model, INSTRUCTION/ACTION pairs.
  
- INSTRUCTION and ACTION archetypes in templates

- Workflow_id - does anyone use it?

  
### Terminology

- Terminology — value sets, coded quantities, terminology servers and FHIR terminology sharing

- Use of terminologies, sharing terminologies with FHIR, and runtime use of terminology servers.

- Alignment with FHIR terminology?

- Should we adopt FHIR terminology inside archetypes/templates (ADL3!) atCodes as 'contained' FHIR Codesystem/Valuesets
  
- Is FHIR CodeableConcept a better alternative ot CodedText/Text
  
### Specialist modelling issues

- Modelling Anatomical Pathology cancer reporting protocols based on International Collaboration on Cancer Reporting protocols.

- openEHR as a data collection and curation platform for special solutions.

- Modelling PREMS

- Coded-text value sets in QUANTITY fields such as dosage;


