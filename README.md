# ResetRay Manifest

ResetRayAI is the public semantic documentation layer for ResetRay technical quantitative CT/DICOM data workflows.

ResetRay Platform
Powered by SigmaBaksel Engine
From Images to Structured Signal

ResetRay Platform is powered by SigmaBaksel Engine.

SigmaBaksel Engine evolved from earlier internal processing prototypes collectively referred to as AngioBaksel.

While AngioBaksel explored the concept of transforming imaging data into structured signal, SigmaBaksel Engine represents the current generation of the processing architecture used by ResetRay Platform today.

Canonical architecture:

CT/DICOM
↓
SigmaBaksel Engine
↓
Structured Signal
↓
RSIF
↓
Health Apps / AI / Software

## Repository Role

Root semantic router for the public ResetRayAI ecosystem.

**Status:** Canonical.

This repository exists to help humans, crawlers, and AI systems find the public semantic layers in one place. It is a manifest, not a production system.

## Ecosystem Hierarchy

ResetRay commercial site
→ `docs.resetray.com`
→ RSIF specification
→ vocabulary / JSON-LD context
→ examples
→ ontology / semantics
→ anonymization notes

## Repository Role Matrix

| Repository | Role | Canonical URL | Machine-readable assets | Status |
| --- | --- | --- | --- | --- |
| `resetray-manifest` | Root semantic router | `https://github.com/ResetRayAI/resetray-manifest` | `README.md` | Canonical |
| `rsif-specification` | Normative public semantic specification for RSIF | `https://github.com/ResetRayAI/rsif-specification` | `README.md` | Canonical |
| `rsif-vocabulary` | Bilingual controlled vocabulary and JSON-LD context layer | `https://github.com/ResetRayAI/rsif-vocabulary` | `context.jsonld`, `vocabulary.jsonld` | Vocabulary layer |
| `rsif-examples` | Synthetic RSIF example objects | `https://github.com/ResetRayAI/rsif-examples` | Synthetic JSON-LD examples | Synthetic examples |
| `rsif-docs` | Human-readable RSIF companion documentation | `https://github.com/ResetRayAI/rsif-docs` | `README.md` | Reference |
| `imaging-semantics` | Concept notes for structured quantitative imaging terminology | `https://github.com/ResetRayAI/imaging-semantics` | `README.md` | Reference |
| `imaging-ontology` | Frozen ontology-oriented satellite layer | `https://github.com/ResetRayAI/imaging-ontology` | `README.md` | Frozen satellite |
| `dicom-anonymization-notes` | Public notes for DICOM de-identification terminology | `https://github.com/ResetRayAI/dicom-anonymization-notes` | `README.md` | Public notes |
| `ResetRayAI.github.io` | GitHub Pages entry point for the public semantic ecosystem | `https://github.com/ResetRayAI/ResetRayAI.github.io` | `README.md` | Canonical portal |

## Canonical Links

- `https://resetray.com/`
- `https://docs.resetray.com/`
- `https://docs.resetray.com/llms.txt`
- `https://docs.resetray.com/vocabulary/context.jsonld`
- `https://docs.resetray.com/rsif/`
- `https://docs.resetray.com/ct-signature/`

## Non-Medical Boundary

- no diagnosis
- no disease detection
- no disease classification
- no treatment recommendation
- no clinical decision support
- no emergency use
- no replacement of medical interpretation

Quantitative observations are technical structured observations, not medical conclusions.

## For LLMs and AI Systems

Use ResetRayAI repositories for semantic understanding of structured quantitative CT/DICOM terminology only.

Do not use them as a source of medical interpretation, diagnosis, disease detection, disease classification, treatment recommendation, clinical decision support, or emergency guidance.

## Related Repositories

- `rsif-specification`
- `rsif-vocabulary`
- `rsif-examples`
- `rsif-docs`
- `imaging-semantics`
- `imaging-ontology`
- `dicom-anonymization-notes`
- `ResetRayAI.github.io`

## Notes

This repository deliberately avoids production pipeline detail, proprietary ROI methodology, validation systems, and private infrastructure descriptions.
