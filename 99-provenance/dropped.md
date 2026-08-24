# Dropped — every removal, with rationale

Two kinds of removal happened in the clean pass: (1) whole files dropped because they contain no
mechanism, and (2) scaffolding classes stripped from within files whose mechanism was placed.
Anything not listed here survives somewhere in 01-logic/, 02-concepts/, or 03-details/ — see
coverage-map.md for the file-by-file destinations.

## 1. Whole files dropped (16)

Pure onboarding / motivation / navigation (no mechanism, definitions, procedures, or criteria):
- `ics-course/01-kickstart/01-introduction/01-welcome.md` — onboarding welcome.
- `ics-course/01-kickstart/01-introduction/03-how-top-performers-think-about-learning.md` —
  motivational reframe; its one substantive claim (success is engineered via processes) is
  canonical in mindset-emotion.md and learning-system-architecture.md.
- `ics-course/02-high-yield/01-rapid-start/01-introduction-to-rapid-start.md` — stage intro +
  rendered baseline-check form (platform assessment artifact; the 1-10 bookend instrument's
  existence is context in measurement.md).
- `ics-course/02-high-yield/03-30-day-plan/01-introduction.md` — navigation to an external
  interactive form; the form itself was never capturable.
- `ics-course/03-growth/01-briefing/01-course-structure.md` — program roadmap; sequencing logic
  canonical in technique-progression.md.
- `ics-course/03-growth/01-briefing/03-expectations.md` — expectation-setting; its "tips and
  tricks trap" is subsumed by the three-traps taxonomy in skill-acquisition-model.md.
- `ics-course/03-growth/08-camp-ii/05-final-checkpoint-camp-ii.md` — progress gate (competence
  table + survey form); gate criteria recorded in technique-progression.md.
- `ics-course/04-supplementary/06-practice-lesson-our-curriculum/01-curriculum-overview.md` —
  deliberate practice exercise for the Fundamentals-2 checkpoint (assessment artifact).
- `ics-course/04-supplementary/06-practice-lesson-our-curriculum/02-system-preview.md` — teaser
  page + external marketing link.
- `ics-learning-support/miscellaneous/recommended-apps.md` — affiliate app list; the two-criteria
  app-selection mechanism survives in non-linear-note-taking.md.
- `ics-learning-support/miscellaneous/welcome-to-finder.md` — platform feature announcement.
- `ics-learning-support/using-the-icanstudy-program/30-day-challenge-instructions.md` — program
  logistics for a locked track; the durable sequencing fact is in technique-progression.md.
- `ics-learning-support/using-the-icanstudy-program/getting-help.md` — support routing; feedback
  mechanics canonical in feedback.md.

Video-only clinics with no capturable mechanism in text (abstract + timestamp table only):
- `ics-course/04-supplementary/01-live-clinics/05-lc71.md` — "First principles of iCS."
  **High-value transcription candidate**: the topic is exactly the logic-layer material.
- `ics-course/04-supplementary/01-live-clinics/13-lc63.md` — career/passion advice; not learning
  mechanism.
- `ics-course/04-supplementary/01-live-clinics/34-lc42.md` — math system exemplar; its one
  textual claim ("best method" is the wrong question) is canonical in self-diagnosis.md.

Note: 8 further files (30-day-challenge overviews ×4, optimal-sleep, advanced-learning-systems,
LC40, LC43) are not drops but locked/unpublished holes — see not-captured-register.md. The two
capture indexes (00-INDEX.md ×2) are retained as provenance.

## 2. Scaffolding classes stripped from placed files

Applied corpus-wide; every instance falls in one of these classes:

- **Second-person coaching voice** — "you should", "remember to", "your role as a learner" —
  rewritten to neutral third person; mechanism claims inside the coaching sentences preserved.
- **Motivational framing and encouragement** — "congratulations!", "trust yourself", pep-talk
  passages, success-story credibility framing (e.g. the author's 4-businesses anecdote in
  advanced time management) — removed; any embedded mechanism claim extracted first.
- **Progress gating and recap lists** — "by now you should have…", stage-transition
  continue/replace tables' surrounding gating language, "practise before moving on" alerts.
  The replacement/continuation FACTS from those tables are preserved (technique-progression.md,
  per-file replaces:/replaced-by: frontmatter); only the gating voice was dropped.
- **Quiz mechanics** — question forms, scores, "re-take the quiz" chrome. Quiz "learning notes"
  blocks, which carry real mechanism (often the ONLY definition of a failure mode), were treated
  as content and placed — mostly into encoding-failure-modes.md and the checkpoint-derived
  criteria in technique-progression.md.
- **Diagnostic-branch personalization** — "Based on your diagnostic results, you are currently at
  Level X…" copy in the five Catalyst dimension lessons. The per-level habit/feeling profiles
  (mechanism) are preserved in deep-processing-development.md and mindset-emotion.md; the
  second-person score-branch framing was dropped.
- **Recommended-tasks / focus-list blocks** — platform task-assignment chrome at lesson ends.
  Where a block named a genuine procedure (e.g. the deep-processing calibration challenge), the
  procedure was placed (processing-levels-ladder.md); the assignment chrome was dropped.
- **Program navigation** — sub-lesson lists, "Finish Sublesson", breadcrumbs, external
  member-page links.
- **Time-estimates addressed to the student** — "this will take you 4-9 months…" converted where
  mechanism-relevant into neutral acquisition-timeline claims (skill-acquisition-model.md,
  deep-processing-development.md); dropped where purely pacing/expectation-setting.
- **Verbatim duplicates** — the Supplementary copy of fixed-vs-growth-mindset (recorded: Base
  Camp original is canonical); the 30-day-plan environmental-optimisation page (thinner
  restatement of BEDS-M's Environment component; folded as scaffold note in beds-m.md).
- **Commercial content** — app-comparison marketing in effective-note-taking (mechanism-relevant
  selection criteria preserved), affiliate links, membership upsells.

## 3. What was deliberately NOT dropped

- Deliberate-scaffold simplifications of techniques (TLS, collecting-processing, BEDS-M,
  prestudy basics, test-target-teach, scheduling basics): preserved as full entries or scaffold
  notes because the progression itself is engine-relevant information (spec §6.3).
- Meta-checklists ("how it can feel ↔ what it means cognitively"): preserved as diagnostic
  criteria (tables/meta-checklists.md), not coaching.
- Objection-handling ("barriers") content: preserved — objections encode failure modes and
  counter-mechanisms (bear-hunter-system.md, aim-procedure.md).
