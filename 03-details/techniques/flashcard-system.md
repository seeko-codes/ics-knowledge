# Flashcard system (full spec)
---
type: technique
serves: rote-and-mnemonics
sources: [ics-course/03-growth/07-camp-i/02-flashcards.md]
---

## Overview

A flashcard is a card with a question or prompt on one side and an answer on the other (digital
apps may support more than two "sides"). The prompt can be a question, a fill-in-the-blank, or
image occlusion (filling in the blanks of an image).

Two things to avoid:
1. **Too many flashcards** — creates overwhelm and requires a high, recurring time investment.
   Only layers 3 and 4 should be put on flashcards.
2. **Testing too many things in a single prompt** — makes it hard to judge a card as "correct" or
   "incorrect" when the answer is a mix of right and wrong.

**Flashcards vs. summary cards**: flashcards test information; summary cards are discrete cards
that provide a summary of information. Unlike flashcards, summary cards do not produce a generative
effect on learning.

Some learners accumulate hundreds or thousands of flashcards — this is inefficient and
unsustainable, and can be reduced by proper layers of learning, as more information becomes
naturally relevant and deeply encoded through higher-order methods instead.

**Key benefits of flashcards**: enables spaced retrieval practice for lower-order information;
functions as a "second brain" reference source; easy to use; enables microlearning.

## Microlearning

Flashcards enable microlearning — short bursts of studying (e.g. while taking the bus). Conceptual
learning usually cannot be done in short bursts, which makes flashcards a good tool for filling
small gaps in a schedule. Long study sessions do not activate microlearning conditions and are thus
less effective for flashcards specifically; keep sessions to short bursts of **3 to 10 minutes**.

## Go digital

Physical flashcards are harder to access for microlearning. Digital apps (e.g. Anki) are more
accessible and effective, since they calculate the best review time for each card using
spaced-repetition algorithms — a level of flexibility, control, and convenience impossible with
physical cards. The (extremely minor) benefit of handwriting a card is insignificant compared to
the benefits of going digital.

## General flashcard guidelines

1. Use digital flashcards (e.g. Anki).
2. Only use flashcards for layers three and four (the important and arbitrary details).
3. Reduce the total number of flashcards as much as possible — a topic should not need more than
   **50 flashcards**. More than that suggests a mistake in conceptual learning.
4. Each flashcard should have a targeted question and a discrete fact; no more than two or three
   facts on a single card.
5. Always attempt a best guess before checking the answer, even without knowing it — this is about
   generating an answer and correcting it, not about getting it right, in order to activate the
   generation and hypercorrection effects.

## Key mechanisms

**Generation effect**: generating an answer produces more learning than simply checking one — e.g.
reading the answers for a practice exam is less effective than taking the time to write real
answers.

**Hypercorrection effect**: a mistake followed by correction produces a higher level of learning
than getting it right the first time. The higher the confidence in the incorrect answer, the higher
the resulting level of learning.

## Leitner system

The Leitner system is an implementation strategy of spaced repetition commonly adapted for
flashcards and microlearning. (Source diagram: Leitner system box diagram, Wikipedia — external
asset, not present in the captured figure set.)

Incorrect flashcards move backwards through the boxes; correct cards move forwards. A single card's
movement might trace as follows:

1. Answered correctly.
2. Moves to box 2, due for a repeat in **1 hour**.
3. Answered correctly again.
4. Moves to box 3, due for a repeat in **4 hours**.
5. Answered correctly again.
6. Moves to box 4, due for a repeat in **16 hours**.
7. Answered incorrectly.
8. Moves back to box 3, due for a repeat in 4 hours.
9. Answered incorrectly.
10. Moves back to box 2, due for a repeat in 1 hour.

One benefit of the Leitner system is that it prioritises weak areas. A disadvantage is that cards
accumulate quickly if many are answered incorrectly — with a large deck (e.g. 200+ cards), it
becomes difficult to get them all correct, and earlier-stage boxes start "overflowing," making it
hard to stay on top of the deck. This is what the flashcard management guidelines (Rule of 3) below
are designed to address.

## Rule of 3 method for managing flashcards

Three rules: **Combine**, **Cut**, **Critique**.

### Combine

**Trigger: a flashcard is answered correctly three times in a row.**

Merge it with another conceptually related card that has also been answered correctly three times
in a row, to create a higher-order question. Example: a card on the definition and purpose of
judicial law, and another on the definition and purpose of parliamentary law, could combine into
"What are the key differences between the definitions and purposes of judicial law compared with
parliamentary law?" — or an even more higher-order combination, "How important is judicial law
compared to parliamentary law in heavily litigious industries?" This reduces the number of cards in
the deck while testing at higher orders. When combining, ensure the lower-order information from
each original card is retained as prerequisite knowledge needed to answer the new higher-order
prompt — do not combine two conceptually related cards into a prompt asking a completely different
angle that does not build on the existing knowledge.

### Cut

**Trigger: a flashcard is answered correctly three times in a row, with no conceptually related
card to combine it with.**

Remove the card from the deck. This rule is flexible: if uncertain, leave the card in the deck and
let the spacing algorithm naturally extend the delay between attempts; if the deck feels cluttered,
these cards should be the first removed. At minimum, reword the card to avoid a **recognition
trap** — being unable to recall the information without this highly specific cue.

### Critique

**Trigger: a flashcard is answered incorrectly three times out of five attempts.**

Return to the material and learn more deeply about it — go outside the scope of the curriculum,
consider its applications, and build a more robust conceptual understanding, giving the information
more relevance to prevent repeated forgetting. Cards that are consistently wrong take up
disproportionate time because they are never cleared from the deck; invest **5 to 10 minutes** to
consolidate more deeply rather than continuing with a lower-order approach that has already proven
ineffective.

## Pointer

For the scope caps governing when rote/flashcard techniques should be used at all (vs. relational
encoding), see 02-concepts/rote-and-mnemonics.md.
