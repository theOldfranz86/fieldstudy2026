---
name: course-quality-review
description: Audit Field Study 2 repository coherence and readiness after major changes or before weekly production, slide generation or course release. Check authoritative specifications, pedagogy, sequential methodology, milestones, materials and assessment without silently changing them.
---

# Course Quality Review

Audit the documented course design and distinguish defects, inferences, missing decisions and non-blocking improvements.

## Audit workflow

1. Read `COURSE_CONTEXT.md`, all root YAML files and `curriculum/PEDAGOGICAL_FRAMEWORK.md`.
2. Inspect curriculum, readings, slide design, weekly folders, project-management, evaluation and local skills.
3. Parse YAML and verify identifiers, dates, weights, deliverables and terminology.
4. Check pedagogical, methodological, ethical, organisational and production readiness.
5. Return evidence, consequence, qualification and correction for every finding.

## Required checks

- Official W01–W12 dates and exact `due_week`/`due_date` matches for M01–M04.
- 180-minute sessions with briefing, workshop, group work, coaching, debriefing and all four Kolb phases.
- Sequential qualitative → questionnaire → Sphinx → quantitative analysis → integrated recommendations.
- At least one interview per student, qualitative-to-item traceability and at least 300 complete usable quantitative responses.
- Quality-control record, data dictionary, evidence portfolio and individual accountability.
- A1 50%, A2 50%, A3 formative 0%; no written report.
- AI, privacy, raw-data publication, source attribution and ownership rules.
- Five-file weekly planning gate before PPTX production.
- No invented Maison Maye or institutional information.

## Verdict

Return exactly one:

- `READY_FOR_COURSE_PRODUCTION`
- `READY_WITH_NON_BLOCKING_GAPS`
- `NOT_READY_BLOCKING_GAPS`

Classify findings as `BLOCKING`, `HIGH`, `MEDIUM` or `LOW`. Do not alter files during an audit unless the user explicitly asks for implementation.
