# Reverse-causality test

---
type: technique
serves: encoding-failure-modes
sources: [ics-learning-support/encoding/87.md, ics-course/04-supplementary/01-live-clinics/52-lc24.md, ics-course/04-supplementary/01-live-clinics/29-lc47.md]
---

## Statement

Reverse causality is when information is justified as important purely by reference to another
piece of information that itself has to be memorised, creating a closed loop between the two:
remembering *why* something is important ends up depending on rote-learning the connection
itself. This defeats the purpose of forming a chunk or relationship in the first place — instead
of reducing memorisation load by making things logical, it adds one more item to memorise.

**Worked illustration (verbatim intent).** Consider a topic with five concepts: A, B, C, D, E.
If A is said to be important because it is needed to create B, this claim relies entirely on
memorising the fact that A creates B — it does not connect A to any prior knowledge or to any
concept outside the pair {A, B}. This is the closed loop: the only connection that can be drawn
is a single arrow from A to B, and that arrow itself has to be memorised because nothing else
allows A's importance to be logically inferred except that it creates B.

Figure: `../research/_assets/inline-images/CleanShot 2023-09-01 at 19.00.40.png` (a single arrow
from A to B).

The alternative is to justify A's importance through its influence on C and D, and through being
created by E — connecting A to a wider network. Once A is placed in that network, learning that A
also creates B places B in the context of the wider network too, rather than in an isolated pair.

Figure: `../research/_assets/inline-images/CleanShot 2023-09-01 at 19.01.26.png` (a network
between A, B, C, D, and E).

## The diagnostic test (verbatim)

1. State the claim in the form: *"___A___ is important because ___B___."*
2. Ask: *"Would I only know that if I memorised that B is due to A?"*
3. If the answer is yes, the importance of A is being justified through rote memorisation rather
   than through prior knowledge or other relationships within the topic — reverse causality is
   present.

## Related constructs

- **Intuitive chunking** (importance-based-chunking.md) is stated to help *prevent* reverse
  causality — a chunk structure that already leverages prior knowledge is less likely to fall
  back on a bare, self-referential A→B justification.
- **Importance checklisting** and **simple question-and-answer** (encoding-failure-modes.md) are
  stated to *increase* the risk of reverse causality — both cut the inquiry process short before
  a genuine network of relationships has a chance to form, leaving a single, closed-loop
  justification standing in its place.

## Worked instance from supplementary material: Domain/range (LC24)

The clearest self-caught, concretely-worded instance of reverse causality found in the corpus
comes from a student's own submission in Live Clinic 24, given as an example of a broader
problem where "the answers to my 'why is it important' questions are almost identical to my
'what is it' questions":

> Domain (in Maths) is the set of all possible X values that makes a function work and it is
> important because well, it provides the information needed to find the range of the given
> function.

The student flags this themselves as circular: Domain's importance is justified only by its role
in finding Range, and nothing else — an unresolved instance of exactly the closed-loop pattern
the diagnostic test above is built to catch. Applying the test: "Domain is important because it
provides the information needed to find the range" → "Would I only know that if I memorised that
[finding the range] is due to [domain]?" → yes, which flags reverse causality. No correction or
resolution from the course is captured in the source text; this file range only ever captures the
student side of the exchange (see mindmap-critiques.md for the general pattern of live-clinic
video-gapping).

## Prevention guidance

- Apply the diagnostic test to any "A is important because B" answer that feels close to
  restating A's own definition rather than describing a genuine downstream consequence or
  external relationship.
- Prefer answers that connect the concept to something *outside* the immediate A–B pair — prior
  knowledge, a wider network of concepts, or a real-world consequence — over answers that only
  reference the other half of the pair being justified.
- Because reverse causality is formally introduced as an advanced (Ascent 3+) diagnostic concept
  (see encoding-failure-modes.md, Reverse causality — Stage-gating), a learner who has not yet
  encountered the named concept may still be experiencing the underlying pattern; the test above
  does not require Ascent-3-level standing to apply.
