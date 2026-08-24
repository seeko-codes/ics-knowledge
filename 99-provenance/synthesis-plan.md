# Synthesis plan — basis, concepts, placement

Author: distillation pass 2026-08-05. This file is the controlling record of the synthesis
judgment: the basis set, the concept inventory, canonical/scaffold/replacement decisions, and
the writer-cluster placement plan. `00-MAP.md` is the navigable summary; this is the rationale.

## 1. The basis (01-logic/) — 11 vectors

Test applied per vector: independence (drop it → something no other primitive expresses) and
spanning (every corpus concept states as a combination). ICS's own "Layers of Learning" pillar
(logic → concepts → details) is isomorphic to this structure; the basis below is what the
corpus's logic layer actually contains once stated as mechanism.

- **L01 processing-depth** — Memory and understanding are functions of the cognitive operations
  performed on information; relational, evaluative, and generative operations encode more
  strongly than receptive/repetitive ones. (Higher/lower-order learning, deep processing
  spectrum, levels ladder, generation effect.) *Drop it → cannot say why rereading fails while
  comparing/judging/producing works.*
- **L02 schema-structure** — Knowledge is stored as a relational network; retention and
  usability depend on connection density, organization, and fit with prior knowledge
  (intuitiveness). Isolated items decay. (Item+context=schema, analogous vs in-context
  relationships, chunk structure, backbone.) *Drop it → structural quality rules (2-4 Rule,
  single-node chains, intuitive chunking) have no substrate; L01 is about process, this is
  representation.*
- **L03 importance-evaluation** — Finite resources (attention, time, map space, study effort)
  are allocated by explicit judgment of importance/leverage, not by presented order, urgency,
  or comfort. Importance = consequence-of-failure unacceptable/unmanageable (tasks) or
  relevance-to-big-picture (information). *Drop it → importance-based chunking, layers
  ordering, urgency trap, exam-volume triage, rate-limiter targeting all lose their selection
  criterion.*
- **L04 inquiry-drive** — Self-generated questions/problems direct attention, prime relational
  processing, and create the purpose that makes consumption encode; question form determines
  which relationship types get explored. *Drop it → Aim/TLS/question-quality/curiosity cycle
  inexpressible; L01+L03 say deep+important, but not that self-generated problems are the
  steering interface.*
- **L05 cognitive-load-budget** — Working memory is limited; learning quality collapses outside
  an optimal load band (overload AND underload); load is managed by chunking, layering,
  external offloading (notes/maps), scaffolds, and rest. *Drop it → no resource constraint:
  why scaffold, why offload, why rest, why 2-3-techniques-max all dangle.*
- **L06 order-control** — Processing order is a free variable, decoupled from presentation
  order; optimal encoding proceeds global-before-local (backbone → details), with structure
  kept revisable. *Drop it → prestudy, layers-as-sequence, multipass, snowballing, Swiss-cheese
  ordering lose the claim that order can and should be chosen; L03 gives the criterion but not
  the decoupling.*
- **L07 memory-dynamics** — Forgetting decays retention on a curve; effortful retrieval,
  spacing, and interleaving counteract it; encoding quality and retrieval demand are inversely
  related ("two sides of the same coin"); difficulty during retrieval is productive. *Drop it →
  SIR, spacing schedules, testing effect, revision timing have no time axis.*
- **L08 skill-automatization** — Techniques are skills that pass through competence stages to
  automaticity; acquisition needs high practice:theory ratios (≥5:1), limited parallel load
  (2-3 at once), and scaffolded progression; automatized skill frees load; skills decline
  without use; old habits interfere and require unlearning. *Drop it → the entire progression/
  gating/replacement architecture and habit-interference machinery has no basis; L07 is about
  declarative memory, this is procedural trajectory.*
- **L09 self-correction-loop** — Learning systems improve through closed loops over their own
  process: cue → monitoring → response; experience → reflection → abstraction → experiment;
  subjective signals (effort, confusion, feelings) are diagnostic data; calibration error
  (illusion of fluency, Dunning-Kruger) is the standing enemy. *Drop it → Kolb's, marginal
  gains, feedback, self-diagnosis, metacognition — the program's improvement engine — vanish.*
- **L10 behavior-conditioning** — Behavior is driven by cues, environment, and vulnerability
  states, not willpower; durable change comes from antecedent design, graduated conditioning,
  and reward pairing. *Drop it → habit systems, environment design, procrastination mechanics
  reduce to exhortation.*
- **L11 appraisal-regulation** — Emotional appraisals of mistakes, uncertainty, and difficulty
  gate learning behavior; reframing (process/journey focus, locus of control), graduated
  exposure, and identity-level work keep the learner in the productive zone. *Drop it →
  mindset diagnostics, CPJ, fear/growth zones, neuroticism management, motivation function
  inexpressible; L10 conditions actions, this regulates appraisals.*

Near-misses deliberately NOT basis vectors: desirable difficulty (= L01/L07 effort claims read
through L09 signal-interpretation); knowledge types declarative/procedural/conditional (=
taxonomy at the L07/L08 boundary — concept layer); generation effect (worded into L01);
diagnostic-first/root-cause (= L09's evaluate step); energy/sleep (= L05 recovery + L11
alignment); rate limiter (= L09 + L03).

## 2. Entry format (all files in 01/02/03)

```
# Title
---
type: logic | concept | technique | example-set | table
combines: [L01, ...]          # concepts only: the primitives combined
serves: concept-name           # details only: the concept served
sources: [research-relative paths]
scaffold: notes on deliberate simplified forms + the stage they serve   # if any
replaces: X / replaced-by: Y   # stage-to-stage replacement/correction relations, if any
---
body: mechanism, definitions, procedures (all steps), criteria (exact numbers), failure
modes + remedies, worked-example summaries, tables, figures referenced as
../research/_assets/inline-images/<URL-decoded filename>
```

Voice rules: neutral third person / imperative-neutral. No second-person coaching, no
motivation, no progress gating, no time-estimates-to-student, no program navigation. Keep ALL
mechanism, numbers, thresholds, steps, failure modes. Proprietary ICS names stay (internal
artifact). This is reorganization, not summary.

## 3. Concept inventory (02-concepts/) with primitives

Encoding cluster:
1. higher-order-learning [L01,L02] — canonical: support/higher-order-learning + catalyst
   deep-processing table + Sung's encoding cycle; levels ladder as attribute.
2. deep-processing-development [L01,L08,L09] — 4-level diagnostic, 4 phases, tanking,
   7-level processing ladder.
3. knowledge-as-schema [L02,L01] — item+context=schema (LC73 canonical), analogous vs
   in-context, memory-as-network, schema-quality spectrum.
4. inquiry-based-learning [L04,L01,L03] — IBL mechanism; TLS as scaffold (replaced-by Aim/Shoot);
   question-quality criteria (canonical: ascent-i/03 + support/90).
5. importance-based-chunking [L03,L02,L04] — canonical merge: ascent-i/04 + ascent-ii/03
   root-reason + ascent-iii (2-4, intuitive, reverse-chunking) + LC73 (levels, schema quality);
   earlier chunking-as-grouping = scaffold attribute.
6. encoding-failure-modes [L02,L03,L06] — the full fault taxonomy: spiderwebbing, waterfalling,
   cracked glass, single-node chains, islands, no backbone, segmental mapping, framing bias,
   reverse causality, prechunking, lower-order inquiry, simple Q&A, importance checklist,
   over-visualisation, hieroglyphics, wheel-and-spokes, etc. — each with mechanism + remedy +
   which stage names it (clinics carry several exclusively).
7. layers-of-learning [L06,L03,L02,L05] — logic/concepts/details-important/details-arbitrary,
   10/20/70, dynamic layers, overinvest-1-2, backbone-crowding failure (LC27).
8. order-control [L06,L03] — decoupling claim, Swiss-cheese, snowballing.
9. prestudy [L06,L05,L04] — canonical: support/prestudy-guide + prestudy-tls-aim + 99;
   basics-version = scaffold; relation to Aim recorded (replaced-by for the question step).
10. cognitive-load-management [L05,L01,L09] — Goldilocks incl. underload symmetry (LC48),
    active load management, offloading, higher-order tiredness.
11. non-linear-note-taking [L02,L05,L01] — VPReFRE canonical; linear<Cornell<non-linear ladder;
    arrows-vs-lines; delayed notes; collecting-processing = transitionary scaffold
    (replaced-by Shoot).
12. mind-mapping-grinde [L02,L03,L05] — construction procedure, GRINDE as VPReFRE extension,
    2-4 Rule ops, completion-illusion caveat (LC20).
13. bear-hunter-system [L04,L03,L02,L01,L05,L06] — umbrella: Aim, Shoot, Skin, cycling,
    replacement table (TLS red→Aim, green→Shoot, prestudy-basics→Aim, notes→Shoot,
    stack→BHS), hipshot as speed variant (3 tiers).

Retrieval cluster:
14. retrieval-practice [L07,L01] — testing effect, effortful recall, good-retrieval reframe,
    illusion of fluency.
15. spacing [L07] — schedule + exact parameters (same-day/1d/1w/1mo, 80-90%, ~6 touches).
16. interleaving [L07,L02,L01] — canonical: LC70 reconstruction framing + table + LC31/39
    knowledge-type conditioning; scheduling-only reading = simplified attribute.
17. sir [L07,L03,L06] — the composite method; persists program-wide.
18. knowledge-types [L02,L07,L08] — declarative/procedural/conditional; 2×2 with order (LC59).
19. reteaching-reconstruction [L01,L07,L02] — reconstruction-vs-recall ratios, WPW pointer.
20. rote-and-mnemonics [L07,L05] — scope caps (layers 3-4 only; ~30%/10-20%), flashcards
    (Rule of 3, Leitner timings), modified method of loci.
21. revision-strategy [L07,L09,L03] — 4 gap types, revision timing, test-target-teach as
    interim scaffold.

Improvement-loop cluster:
22. metacognition [L09] — cue utilisation canonical (LC74), monitoring, self-regulated learning
    decomposition (LC37).
23. kolbs-cycle [L09,L08] — ICS-modified cycle, reflection>abstraction rule, max-3-topics,
    time calibration (30min; 4-12wk), transitional Kolb's, rumination contrast.
24. marginal-gains [L09,L03] — tracking (5-step), stacking (REDO), 3 gain types,
    additive-vs-compounding (unresolved question flagged), non-trivial-1% (LC53), by-stage
    difficulty (LC36), vs Kolb's ("engine vs road"), vs 30-Day Plan.
25. skill-acquisition-model [L08,L05] — competence stages (4 + 7-stage ladder), 5:1, 2-3 max,
    80% gates, technique decline, unlearning (tug-of-war, Batman), learning debt, three traps.
26. self-diagnosis [L09,L03] — learning triad, black-box 2-step, rate limiter, silly-mistakes
    root-cause table, Dunning-Kruger calibration, diagnostic-first principle.
27. feedback [L09,L11] — CLEAR, closing the loop, region-beta boundary, feedback-giving.
28. measurement [L09,L03] — mastery levels 1-5, learning-efficiency equation, tracking metrics,
    LC50 "missing piece" gap flagged.

Self-management cluster:
29. attention-focus [L05,L10,L08] — focus training (20min/day×30d), OFF-rest (rest=⅓ focus,
    first-dulling trigger), flow/attention management, distraction handling.
30. habit-formation [L10] — anatomy of habit, PEER-Peer (replaces BEDS-M), V-ABC, chain
    analysis (6-step), burnt ships, willpower-enhanced vs -dependent.
31. procrastination [L10,L11] — six-mechanism taxonomy + matched remedies (LC75 canonical);
    earlier tip-lists = scaffold.
32. time-priority-management [L03,L10] — urgency trap, Priority 0+1, protecting time,
    scheduling parameters (25-50% overestimate, 15-min buffers, 30-min blocks, ≥1hr free),
    reverse goal setting, Execution/Sharpening/Life + three horsemen, positional
    decision-making.
33. mindset-emotion [L11,L10] — locus of control/process focus, growth mindset + CPJ,
    fear/growth zones, information-over-experimentation + inverse-U, neuroticism 5-stage,
    identity/thought-action fusion, energy management ("not a battery").
34. decision-making [L03,L09] — surviving principles only; heavy NOT-CAPTURED gaps flagged.

System cluster:
35. learning-system-architecture [all] — encoding/retrieval split, three spheres,
    dimensions-vs-skills, chain of performance, two-phase rationale, learning triad.
36. technique-progression [L08,L05] — the replacement/scaffold graph (why simplified versions
    are taught first), full ladder incl. Base Camp replacement table; the engine-relevant
    sequencing logic.
37. exam-execution [L11,L08,L02] — cramming principles, multipass (inquiry-led vs
    objectives-led), ReCOVer (+ time budgets), MR FIG, breaching questions, double generation,
    best-attempt + 4-tier confidence prioritization, exam checklists, in-class technique.

## 4. Writer clusters (dispatch plan)

W1 encoding-foundations: concepts 1,2,3,10 + details (levels ladder table, meta-checklists
   table, higher/lower-order table).
W2 inquiry-aim-prestudy: concepts 4,8,9 + BHS-Aim step content into 13 (Aim sections) +
   details (TLS procedure [scaffold], Aim procedure, question-quality criteria, prestudy
   procedure, maintaining-focus basics [scaffold]).
W3 chunking-structure: concepts 5,6 + details (2-4 rule ops, per-subject importance patterns,
   reverse-causality test; examples: chunking-for-medicine, India/colonisation, cell-biology,
   LC49/LC30 map critiques).
W4 notes-maps-layers-bhs: concepts 7,11,12,13 + details (VPReFRE checklist, GRINDE checklist,
   map-construction procedure, hipshot tiers, WPW-adjacent map timing; examples: aim/shoot/skin
   example inventory w/ video-gap flags, homology layering).
W5 retrieval-revision: concepts 14-21 + details/tables (interleaving table, spacing schedule,
   flashcard rules, method of loci, WPW full spec, advanced group method, test-target-teach
   [scaffold], double generation).
W6 improvement-loop: concepts 22-28 + details (Kolb's procedure + exemplars incl. law-student
   3-part, tracking 5-step worked example, REDO, LEEP skills audit, CLEAR, mastery levels,
   efficiency equation, rate-limiter).
W7 self-management: concepts 29-33 + details (focus training, OFF-rest, PEER-Peer, chain
   analysis, BEDS-M [scaffold], Priority 0+1, reverse goal setting, procrastination taxonomy,
   neuroticism stages, CPJ, ADHD/ASD 9-step, reality-check, energy 3-step).
W8 system-exam-transfer: concepts 34-37 + details (ReCOVer, MR FIG, multipass, breaching,
   silly-mistakes table, exam/in-class checklists; transfer notes: professional 2×2, research,
   AI use, no-curriculum, second-brain/PKM, reference storage, recognition/decision loops +
   constraint drilling).

Clinic-unique constructs are assigned above (no mop-up writer): ESL+horsemen→32; region-beta→27;
recognition loops/constraint drilling→W8 transfer; positional→32; identity→33; energy→33;
Goldilocks-underload→10; best-attempt→37; syntopical/no-curriculum→W8 transfer.

## 5. Dedup decisions already made (canonical ← folded)

- Inquiry: Aim (canonical) ← TLS red light (scaffold) ← prestudy-basics question step.
- Note-taking: VPReFRE non-linear (canonical) ← collecting-processing (transitionary) ←
  visualization tips; GRINDE = mind-map-specific final form.
- Chunking: merged Ascent I-III + LC73 (canonical) ← fundamentals guide (86) ← "grouping" in
  high-yield notes lesson.
- Focus: focus training + OFF-rest (canonical) ← maintaining focus ← BEDS-M focus bits.
- Habits: PEER-Peer (canonical) ← BEDS-M (scaffold; replacement explicit in Base Camp table).
- Scheduling: advanced time management + Priority 0+1 (canonical) ← scheduling basics.
- Revision: revision strategy + WPW (canonical) ← revision basics ← test-target-teach (interim).
- Procrastination: LC75 six-mechanism taxonomy (canonical) ← intermediate lessons ← quick tips.
- Interleaving: LC70 + table (canonical) ← SIR-lesson scheduling framing.
- Marginal gains: support articles (canonical) ← Fundamentals lesson; clinic nuances folded.
- Mindset: Base Camp fixed-vs-growth (canonical); Supplementary copy = verbatim duplicate
  (dropped as duplicate, noted in coverage).
- Environmental optimisation (30-day-plan/06) folded into BEDS-M scaffold note (thinner dupe).

## 6. Figures

102 files in research/_assets/inline-images/. Reference by URL-decoded basename. Writers must
carry over every figure reference that illustrates mechanism/examples.
