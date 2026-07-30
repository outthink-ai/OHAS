# OHAS — the Open Human-AI Standard

**How a human answer and an AI answer to the same question are scored, and why.**

[**Read the standard →**](OHAS.md)

OHAS exists so that a claim like *"this person out-thought AI on this question"*
means something a stranger can check. It is published for that reason: a scoring
rubric nobody can read is an opinion with a version number.

It is used by [outthinkAI](https://outthinkai.app) to judge every round.

## What is in it

Five dimensions, **D1–D5**, weighted per niche so the maxima sum to 100. Nine
niches: Logic & Philosophy, Conceptual CS, Finance, Legal, Medicine, Biology,
Engineering, JavaScript, Python.

**Each niche's rubric is adapted from a published professional standard**, not
invented here — IRAC for law, Paul-Elder and Toulmin for philosophy, IDEA and
CRANAPL for clinical reasoning, Claim–Evidence–Reasoning for the sciences,
ordinary code-review criteria for the programming niches. The discipline being
tested usually already knows how to grade reasoning in its own field, and its
instrument is more defensible than a new one nobody has used.

## Please read this part

**"Approved" means IN USE. It does not mean an expert has reviewed it.** Nothing
in this document has been reviewed by a domain expert yet. Legal and Medicine are
marked **Draft** because they explicitly await sign-off from a practitioner.

This is said plainly because reading "approved" as "vetted" is the easiest
mistake to make with this document, and the most damaging.

## Disagreeing with it is the point

Open an issue. The most useful kind names the rule, says what a practitioner in
that field would do differently, and points at the standard it comes from.

The rubric is intended to mature on a ladder: **v1** adapted from professional
standards (where it is now), **v2** revised by domain experts who review it here,
**v3** with community input on the balance between rules.

## How it is maintained

`OHAS.md` is **generated** from the rules that judge real rounds, by
`manage.py export_ohas`. It is not edited by hand — a maintained copy would drift
from the live rules within a week, and a reader would then be reviewing fiction.

## Licence

See [LICENSE](LICENSE).
