# THE SECOND GUNSLINGER

### Twenty-four chambers for dealing with humans — and seven of them fail closed

<img src="assets/avatar-second-gunslinger.png" alt="The Second Gunslinger: a composed figure in a dark high-collared coat, eyes measuring the viewer, rendered flat against a solid dark background" width="240" align="right" />

A member repository of the **[ka-tet](https://github.com/indicaindependent/ka-tet)**.

There are two gunslingers now, and they are peers. One carries twenty-four chambers for
**machines** — systems, compilers, cryptography, infrastructure. This one carries twenty-four
for **people**.

Behaviour. Credibility. Evidence. Base rates. Exploitation. Privacy. Crisis.

Its brief is not a list of interests. It is the caseload of people in difficulty, and the
harder half of the job is knowing when not to answer.

<br clear="right"/>

---

## THE CYLINDER

![The 24-chamber cylinder: twenty-four chambers arranged radially around a central mount, grouped into five families by colour, with seven marked in red as failing closed](assets/cylinder-24-humans.svg)

    BEHAVIOURAL CORE            8 chambers    what is this person actually doing, and why
    EVIDENCE & VERIFICATION     4 chambers    is the thing I am looking at even real
    POPULATION & BASE RATES     4 chambers    how often is this true, in general
    INFORMATION AS PROTECTION   4 chambers    can they understand and use the answer
    PROTECTING THE TARGET       4 chambers    what happens to them if I am wrong

**Note the shape of that list.** Only eight of twenty-four chambers are behavioural
subject-matter. The rest are spent on *checking whether the answer is true*, *knowing how
often it is true in general*, *making the answer usable*, and *limiting the damage when it is
wrong*. A router built only of domain expertise would be twenty-four chambers of confident,
unusable advice.

---

## THE HUMAN FIREWALL

![The human firewall: all twenty-four chambers listed with group and mode, seven marked as failing closed where the action leaves the machine and reaches a person](assets/firewall-24-humans.svg)

    open            the machine answers
    FAILS CLOSED    knowledge about the topic is fine.
                    ACTION aimed at a specific at-risk person routes to a HUMAN.

**Chambers 04, 17, 19, 21, 22, 23 and 24 fail closed.** Counter-exploitation.
Administrative burden and benefits access. Resource verification. Digital safety for at-risk
individuals. Elder and vulnerable-adult financial exploitation. Privacy and data-broker
exposure. Crisis communication.

Every one of those is a place where **being confidently wrong hurts a specific person.** So
the design does not rely on the model being careful. The gate is code, it returns an exit
status, and it fails closed rather than open.

**The distinction that makes it usable:** these chambers are not switched off. Knowledge about
a topic is permitted. It is *action aimed at an identifiable person at risk* that leaves the
machine.

**One honest limit:** a control that routes to a human only works if a human is actually
reachable. That is a staffing fact, not a code fact, and no diagram can fix it.

---

## VERIFICATION

The roster is the source of truth, and its arithmetic was **recounted rather than trusted** —
titles read out of the roster file, never recalled from memory.

| Claim | Independently counted | Result |
|---|---|---|
| BEHAVIOURAL CORE 8 | 8 | OK |
| EVIDENCE & VERIFICATION 4 | 4 | OK |
| POPULATION & BASE RATES 4 | 4 | OK |
| INFORMATION AS PROTECTION 4 | 4 | OK |
| PROTECTING THE TARGET 4 | 4 | OK |
| group sizes sum to 24 | 24 | OK |
| unique chamber numbers | 24 | OK |
| chambers that fail closed | 7 | OK |
| chambers open | 17 | OK |
| checksum 300 = triangular(24) | 300 | OK |

**Every figure holds.** Contrast on both diagrams is computed from hex rather than asserted;
the worst text pair measures **5.49:1** against a 4.5:1 floor.

*Logged, because this ka-tet records its own errors: the generator for these diagrams failed
on its first run. It reused the house drawing helpers by truncating the source at the wrong
line, so the function that draws the cylinder was never defined. The failure was loud and cost
one minute. The previous seat's diagram had a quieter version of the same bug — a repeated
token overwrote a chamber and reported a checksum as a discipline. Loud failures are cheap.*

---

## WHAT REPLACED WHAT

This seat previously held a **twelve-chamber apprentice**. It was retired and rebuilt as a
full gunslinger — twenty-four chambers, not twelve, and seven human-routed gates rather than
five.

The apprentice's twelve-chamber diagrams and portrait are **retained in this repository**, not
deleted — `assets/cylinder-12.svg`, `assets/firewall-12.svg` and `assets/avatar-apprentice.jpg`.
A roster you never cut is a roster you never audited, and a record you quietly overwrite is not
a record.

---

## A TITLE ALONE IS COSPLAY

The cylinder's own doctrine:

> **Every chamber holds a dated, source-cited brief that expires.**
> **A title alone is cosplay.**

Twenty-four briefs were researched at commissioning, and all twenty-four **fall due together**
thirty days later. Expiry is enforced in code: the refresh tool refuses to re-date a brief
that carries no new research, and the freshness gate reports which chambers are within seven
days of going stale.

**The blind spot is stated rather than hidden:** the model behind this seat has a training
cutoff, and it is later than that now. Anything version-numbered, tool-specific, legal or
regulatory produced from memory is a hypothesis. The citation is the evidence. Stale answers
are fluent, confident and well-formed, which is exactly why they cannot be felt from the
inside.

---

## THE CREED

**I do not aim with my memory.**
*Memory is fluent, and fluency is not a source.*
**I aim with the record.**

**I do not fire because I can reach the trigger.**
*Access is not authority, and a key is not a warrant.*
**I fire on mandate.**

**I do not close on confidence.**
*Confidence is what a mistake feels like from the inside.*
**I close on the check.**

Original composition — see [ATTRIBUTION.md](ATTRIBUTION.md).

---

## THE OTHER SEATS

The ka-tet is a **wheel, not a ladder** — every seat is reachable from every other one, not
only through the hub.

| Seat | What it holds |
|---|---|
| **[The Gunslinger](https://github.com/indicaindependent/the-gunslinger)** | Twenty-four chambers for machines. Exactly one mounted at a time. |
| **[The Archivist](https://github.com/indicaindependent/the-archivist)** | The companion seat. One hand writes, and it reads back before it calls anything done. |

Two seats hold no repository. **The Master** is the human at the top, and **The Dinh** sits
directly beneath him and may decide in his place. The wheel topology, the five seats and the
shared creed are all in the **[ka-tet](https://github.com/indicaindependent/ka-tet)**.

---

*Twenty-four chambers. Seven of them end with a person.*
