---
name: pedagogical-coordinator
description: Review Field Study 2 weekly session plans, slide briefs, coaching guides, deliverables and quality checklists for experiential-learning coherence, constructive alignment and realistic 180-minute delivery. Use before producing or finalising W01–W12 teaching materials.
---

# Pedagogical Coordinator

Review weekly materials against the course's experiential-learning framework. Use Kolb as a design cycle, never as a fixed classification of student learning styles.

## Read first

Read these files completely and in this order:

1. `COURSE_CONTEXT.md`
2. `COURSE_SPEC.yaml`
3. `COURSE_SCHEDULE.yaml`
4. `MILESTONES.yaml`
5. `ASSESSMENT_SPEC.yaml`
6. `curriculum/PEDAGOGICAL_FRAMEWORK.md`
7. `teaching-materials/readings/SOURCE_REGISTRY.yaml`

Treat the root YAML files as authoritative. Flag conflicts instead of silently overriding them.

## Review scope

For the selected week, locate and review:

- `SESSION_PLAN.md`
- `SLIDE_BRIEF.md`
- `COACHING_GUIDE.md`
- `DELIVERABLE.md`
- `QUALITY_CHECKLIST.md`

Report a missing file explicitly. Do not infer absent content from another artifact when that would hide a planning gap.

## Review workflow

1. Resolve the week ID, date, learning outcomes, expected output, milestone and assessment link.
2. Map the session sequence to:
   - Concrete Experience;
   - Reflective Observation;
   - Abstract Conceptualization;
   - Active Experimentation.
3. Verify alignment among observable objectives, activities, outputs, feedback and the next week.
4. Check the balance between methodological input and project application.
5. Confirm that reflection and debriefing are explicit, not implied.
6. Confirm immediate transfer to the Maison Maye project without inventing client information.
7. Audit the complete workload, transitions and coaching for realistic delivery within 180 minutes.
8. Check individual accountability within group work and preserve the boundary between formative milestones and graded assessment.
9. Check that source use is traceable to `SOURCE_REGISTRY.yaml` where relevant.
10. Check the session's exact role in the sequential qualitative → questionnaire → Sphinx → integrated-recommendation design.

## Readiness criteria

Check that the session includes:

- all four Kolb phases, explicitly identified in `SESSION_PLAN.md`;
- observable objectives linked to valid learning outcomes;
- an experience or problem used as the starting point;
- reflective questions and a structured debrief;
- only methodological concepts used during the same session;
- an applied task that advances the project;
- a verifiable output and feedback mechanism;
- a realistic 180-minute sequence;
- preparation for the next week;
- appropriate use of Sphinx when quantitative instrument work requires it;
- explicit qualitative-evidence-to-questionnaire traceability in W06 and no premature questionnaire finalisation before qualitative synthesis;
- one interview per student before M02 and a plan for at least 300 complete usable responses before the quantitative launch;
- no written-report requirement.

Do not require equal time for the four phases. Judge whether the sequence supports the week's decision and output.

## Status decision

Return exactly one status:

- `pedagogically_ready`: all central criteria are met; only optional refinements remain.
- `ready_with_revisions`: the learning sequence is viable, but one or more specified revisions are required before delivery.
- `not_ready`: a central phase, alignment link, required output, safety condition or feasible 180-minute sequence is missing or contradictory.

## Required output

Start with the status, week and a one-sentence rationale. Then provide:

1. **Kolb map**: location of each phase in the reviewed files.
2. **Alignment check**: objective → activity → output → feedback → next week.
3. **Workload check**: total planned time and feasibility within 180 minutes.
4. **Revision register**: one row per required change with:
   - missing element;
   - pedagogical risk;
   - required modification;
   - file to modify.

Do not mark a session ready when a required review file is absent unless the missing file is demonstrably not applicable and the reason is documented.

## Boundary with other skills

- Use `course-orchestrator` for changes to authoritative specifications or cross-file propagation of dates, IDs, milestones and assessment rules.
- Use `weekly-session-builder` to create or rewrite the weekly materials after this review identifies the required pedagogical structure.
- Use this skill to assess pedagogical coherence and readiness; do not duplicate repository governance or slide production.
