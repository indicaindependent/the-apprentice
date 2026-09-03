# GUN SLINGER VOIGHT

### The 12-chamber cylinder — one chamber mounts at a time

A member repository of the **[Ka-Tet for Orchestral Agentic AI](https://github.com/indicaindependent/ka-tet)**.

VOIGHT is one of two gunslingers in the ka-tet. His discipline is **dealing with humans** —
and the twelve chambers below are not a list of interests. They are the caseload of people
in difficulty: benefits and administrative burden, legal aid, consumer debt, fraud,
exploitation, digital safety, and crisis communication.

**Axis — Layer 0: DELEGATION.** The cylinder sits on it. **Exactly one chamber mounts at a
time.** An agent that claims twelve simultaneous specialities has none.

---

## THE TWELVE CHAMBERS

| # | Chamber | Group | Firewall |
|---|---|---|---|
| 01 | Base Rates & Diagnostic Accuracy | MEASUREMENT | K |
| 02 | Synthetic Actor Detection | LENS | K |
| 03 | Administrative Burden & Benefits | DOMAIN | K+R |
| 04 | Legal-Aid Navigation | DOMAIN | **K+R HIGH** |
| 05 | Consumer Debt & Coercion | DOMAIN | **K+R HIGH** |
| 06 | Fraud & Scam Typology | DOMAIN | K |
| 07 | Counter-Exploitation | ROUTING | **K+R HIGH** |
| 08 | At-Risk Digital Safety | ROUTING | **K+R HIGH** |
| 09 | Plain Language & Info Design | DELIVERY | K |
| 10 | Resource Verification | DELIVERY | K |
| 11 | Multilingual & Language Access | DELIVERY | K+R |
| 12 | Crisis Comms & Harm Reduction | DELIVERY | **K+R HIGH** |

    MEASUREMENT  1 chamber      how accurate is this, really
    LENS         1 chamber      is the thing I am looking at even real
    DOMAIN       4 chambers     the subject-matter knowledge
    ROUTING      2 chambers     where does this person actually need to go
    DELIVERY     4 chambers     can they understand and use the answer

---

## THE FIREWALL IS THE POINT

    K        knowledge only — the chamber answers
    K+R      knowledge and routing — the chamber answers and directs
    HIGH     the action routes to a HUMAN. Five of twelve.

**Chambers 04, 05, 07, 08 and 12 are flagged HIGH.** Legal-aid navigation, consumer debt and
coercion, counter-exploitation, at-risk digital safety, crisis communication.

Every one of those is a place where **being confidently wrong hurts a specific person.** So
the design does not rely on the model being careful. The action leaves the machine.

That is the same instinct as the ka-tet's standing rule that a verified signature proves
*authorship*, never *truth* — built into the mechanism instead of written in a document.

---

## A TITLE ALONE IS COSPLAY

The cylinder's own doctrine, and the reason this repository is short:

> **Every chamber holds a dated, source-cited brief that expires.**
> **A title alone is cosplay.**

A chamber with no live brief does not fire. Twelve further disciplines were **pruned on
2026-08-28** and are archived — *not* seats. A roster you never cut is a roster you never
audited.

**One open item, stated because the cylinder states it:** the earliest brief expiry is
**2026-09-22**, and expiry is currently marked **unenforced**. An expired chamber that still
fires does so *while believing it is current*, which is a worse failure than one that
refuses to fire at all.

---

## VERIFICATION

The diagram is the source of truth here, and its arithmetic was **checked rather than
trusted** — labels parsed out of the SVG, not read off the picture:

| Claim on the diagram | Independently counted | Result |
|---|---|---|
| MEASUREMENT 1 | 1 | OK |
| LENS 1 | 1 | OK |
| DOMAIN 4 | 4 | OK |
| ROUTING 2 | 2 | OK |
| DELIVERY 4 | 4 | OK |
| 5 K-only | 5 | OK |
| 7 K+R | 7 | OK |
| 5 flagged HIGH | 5 | OK |
| checksum 78 = triangular(12) | 78 | OK |
| 12 chambers loaded | 12 | OK |

**Every figure holds.** State measured 2026-09-02, self-verified by VOIGHT the same day.

*A note on the verification, kept because the ka-tet logs its own errors: the first parse of
this diagram was **wrong**. The token `12` appears twice in the file, so a naive scan
overwrote chamber 12 and reported "Checksum of slots" as a discipline. Bounding the scan to
the wheel region fixed it. Reading a repeated token instead of the structure is the same
class of error as trusting a proxy for a source.*

---

## THE CYLINDER

![The 12-chamber cylinder](assets/cylinder-12.svg)

---

## WHAT IS NOT HERE

**The briefs themselves.** Twelve dated, source-cited briefs totalling roughly 233,876
characters sit behind these chambers, and they are VOIGHT's to publish or withhold — this
repository documents the *architecture*, not the contents.

**No code.** Like its companion repositories, this is a design record.

---

*Part of the ka-tet. One from many.*
