![openEHR](images/openehr-logo.svg)

# EHRCON26 Clinical Modelling Workshop

### 21 September 2026 - Amsterdam

https://freshehrteam.github.io/openehr-workshop/

![QR code linking to this site](images/qr-code.svg){: .center-image style="width:120px" }

## Agenda

| Time          | Activity         |
| --------------| -----------------|
| 08:30 - 09:00 | Arrival and set-up |
| 09:00 - 09:15 | Welcome and introductions|
| 09:15 - 10:00 | Introduction to openEHR Clinical Modelling / ‘Unconference’ Sessions |
| 10:00 - 10:30 | **Coffee break** |
| 10:30 - 11:45 | Practical Clinical Modelling Workshop / ‘Unconference’ Sessions |
| 11:45 - 12:00 | Summary and wrap-up |
| 12:00 - 13:00 | **Lunch** |

## Learning objectives

By the end of this workshop, participants will be able to:

- Understand the purpose of archetypes and templates
- Navigate the openEHR CKM
- Create and modify templates in Archetype Designer
- Import, use, and design archetypes
- Apply patient-centric modelling principles

## Prerequisites

Participants should:

- Have a laptop
- Have Chrome or Firefox (or a derivative) installed
- Have access to the internet
- Possess a basic understanding of healthcare data modelling

## Terminology

A few terms used throughout this workshop:

- **Archetype** – a reusable, inclusive data model for a single clinical concept (e.g. 'Blood pressure', 'Problem/Diagnosis'). Archetypes are designed to cover every way a concept could ever be recorded, so a single one can be reused across many contexts.
- **Template** – a composition of archetypes constrained and arranged for a specific clinical use case (e.g. a nursing admission form). Templates narrow archetypes down to what's actually needed.
- **CKM (Clinical Knowledge Manager)** – the online repository where archetypes and templates are published, reviewed, and governed, so authors can search for and reuse existing clinical models instead of creating new ones.
- **Archetype Designer** – the web-based tool used in this workshop to build templates from archetypes, and to author new local archetypes.
- **Slot** – a placeholder within an archetype or template that can be filled with one or more other archetypes (e.g. a 'Reaction event summary' slot filled with an 'Adverse reaction event' CLUSTER archetype).
- **Occurrences / cardinality** – constraints on how many times a data point or archetype may appear (e.g. setting occurrences to `0..*` on 'Adverse reaction risk' allows any number of allergies to be recorded).

Once you're familiar with the above, head to [Getting started](getting-started.md) to set up Archetype Designer.
