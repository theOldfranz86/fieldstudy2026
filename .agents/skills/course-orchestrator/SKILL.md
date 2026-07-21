---
name: course-orchestrator
description: Coordinate the Field Study 2 – Application repository when changing course specifications, schedules, milestones, assessments, methodology, pedagogy or dependent artifacts. Use for cross-file alignment and course-production readiness.
---

# Course Orchestrator

Coordinate authoritative artifacts before producing derivative materials. Treat the local repository as authoritative over obsolete remote scaffolds.

## Read first

1. `COURSE_CONTEXT.md`
2. `COURSE_SPEC.yaml`
3. `COURSE_SCHEDULE.yaml`
4. `MILESTONES.yaml`
5. `ASSESSMENT_SPEC.yaml`
6. `curriculum/PEDAGOGICAL_FRAMEWORK.md`
7. `teaching-materials/readings/SOURCE_REGISTRY.yaml` when teaching materials are affected

## Workflow

1. Identify affected LO, W, M, A, dates, deliverables and file paths.
2. Modify the authoritative YAML source first.
3. Propagate the decision to curriculum, readings, templates, project management, evaluation and local skills.
4. Preserve the sequential design: qualitative evidence → questionnaire → Sphinx → quantitative quality control and analysis → integrated recommendations.
5. Check all dependent Markdown files for obsolete terms, dates, deliverables or criteria.
6. Report changed files, remaining TBD values and decisions requiring course-owner confirmation.

## Decision rules

- `COURSE_SPEC.yaml`: identity, outcomes, 180-minute format, methodology and stable course rules.
- `COURSE_SCHEDULE.yaml`: official dates and weekly sequence.
- `MILESTONES.yaml`: submissions, checkpoint workflow, status and quality gates.
- `ASSESSMENT_SPEC.yaml`: assessment evidence, weights and remaining examination decisions.
- Preserve `LO01`–`LO06`, `W01`–`W12`, `M01`–`M04` and all assessment IDs.
- Use `null` or `TBD` instead of inventing institutional, ethical, logistical or client information.
- Keep the written report excluded unless the course owner explicitly changes that decision.

## Production gate

Before a weekly PPTX, require and validate in the week folder:

1. `SESSION_PLAN.md`
2. `SLIDE_BRIEF.md`
3. `COACHING_GUIDE.md`
4. `DELIVERABLE.md`
5. `QUALITY_CHECKLIST.md`

## Minimum validation

- Parse every YAML file.
- Verify all referenced identifiers.
- Verify that graded weights total 100 and A3 remains formative at 0%.
- Verify milestone `due_week` against the official date.
- Verify 180 minutes, Sphinx availability, one interview per student and the 300-response target where relevant.
- Verify that no material invents the Maison Maye managerial problem before the brief.
