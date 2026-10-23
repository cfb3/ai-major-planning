# Teach the AI software development course as TCSS 461

- **Author:** Charles
- **Date:** 2026-10-22
- **Type:** course
- **Maturity:** proposal

## The idea

Charles and Chris currently teach their AI software development course as TCSS 490 (Special
Topics: "Generative AI in Software Development"). To make it more permanent without the long lead
time of a new course through APC, teach it under the existing TCSS 461 instead. The 461
description is already close; it needs small edits to be more generic. The CSS faculty vote is
on 2026-11-06, aiming for Spring 2027 (see "Process and deadlines" below).

## Why it matters

A special-topics number doesn't read as a stable part of the curriculum. A permanent number gives students a course they can plan around, and gives a possible
AI/SWD certificate, minor, or major a course that already exists.

## Proposed description

**Current:**

> Analyzes system re-engineering, domain-specific languages, generative development, system design
> and service-oriented architecture. Also covers how to handle legacy systems, utilize model driven
> software development to automate code generation and understand low to high level architectures,
> by using software engineering methodologies, refactoring, UML, and the Eclipse framework.
> Prerequisite: TCSS 360.

**Proposed:**

> Analyzes system re-engineering, domain-specific languages, generative development, system
> design, and software architecture. Also covers how to handle legacy systems, utilize model-driven
> and automated approaches to code generation, and understand low- to high-level architectures, by
> using software engineering methodologies, refactoring, modeling, and modern development tools.
> Prerequisite: TCSS 360.

**What changed:**

| Current | Proposed | Why |
| --- | --- | --- |
| service-oriented architecture | software architecture | SOA is one 2000s-era style; the broader term covers it and what followed (microservices, cloud-native, event-driven) |
| model driven software development to automate code generation | model-driven and automated approaches to code generation | Keeps MDD and adds DSL compilers, templates, framework scaffolding; matches "generative development" |
| UML, and the Eclipse framework | modeling, and modern development tools | Drops a product name; tools change faster than catalog copy; "modeling" still includes UML |

The pitch to the committee deliberately does not use generative AI as the reason; each change
stands on its own as keeping the description current.

Also punctuation only: a comma before "and software architecture", and hyphens in "model-driven"
and "low- to high-level". Everything else is unchanged, including "generative development", which
already fits the course.

## How it might work

- Charles circulates the proposed description to faculty in advance, then brings it to the CSS
  faculty meeting on 2026-11-06 for a vote.
- Pitch: no change in scope. The edits remove a product name and a dated term and generalize one
  technique.
- If approved, the course is offered as TCSS 461 instead of 490. Prerequisite stays TCSS 360.
- Charles will also propose, at the same meeting:
  - **ABET design elective:** TCSS 461 is **already** on the approved design-elective list for
    the B.S. CSS (found 2026-10-22; see
    [research/abet-and-design-electives.md](../research/abet-and-design-electives.md)), so it
    already meets the graduation requirement TCSS 460 meets. No separate vote should be needed;
    confirm with Aubree. A design elective needs a design project for
    most of the quarter; the course's moonshot project meets that, and the course will do the
    ABET assessment work. Tom's advice (2026-10-22): present it as a **team-based capstone**
    that builds on the theory and practice from the whole quarter and uses several design
    elements (for example architecture, data, UI/UX, testing) to produce one final product.
  - **$75 course fee:** to pay for a Claude Team account for each student in the course.
- Meeting materials (claude.ai, private to Charles until shared):
  [slide deck](https://claude.ai/artifact/LTNGTN7kVbjG6oCKq45B2t) ·
  [agenda doc](https://claude.ai/artifact/MD9PQZP6BNFPYHGxDvvBCw)

## Process and deadlines

From emails on 2026-10-22: Tom met with Aubree Steffens (SET Academic Services), who is on board.
Michelle Miller (SET Academic and Finance Operations) handles the fee. Target: **Spring 2027**.

**2026-10-23:** Charles replied to Aubree and Michelle with the marked-up description. He asked
whether a new syllabus is needed at all, since the description only gets more general (and
whether a fee alone requires one), and offered the draft if so. He also said the fee survey starts
2026-10-23 in the TCSS 490 section (46 students) and stays open at least 5 days. Waiting on
Aubree's answer about the syllabus.

**2026-10-23, later:** Aubree says even a small description change needs a new syllabus, so the
generic Claude-drafted syllabus will be submitted. Before submitting, Charles will have Raghavi and
one more colleague review it (the recap says "Meneka"; confirm the name). See
[meetings/2026-10-23-charles-chris.md](../meetings/2026-10-23-charles-chris.md).

| Date | What |
| --- | --- |
| 2026-11-06 | CSS faculty meeting: vote on the description |
| 2026-11-25 | Aubree's deadline to submit to APCC |

**Course update (Aubree, entered in Kuali).** Tom and Chris have Kuali access; Charles's name
didn't come up when Aubree tried to add him. She needs:

- [ ] The updated catalog description
- [ ] A syllabus: learning objectives, weekly course outline, grading details. First draft:
      [courses/tcss-461-syllabus-draft.md](../courses/tcss-461-syllabus-draft.md). Grading: on
      2026-10-23 Charles and Chris agreed to keep labor-based grading out of the Kuali syllabus
      (a generic line about course projects instead). The course itself still uses it.
- [ ] CSS faculty vote results

**Course fee (separate process, through Michelle).** Send her:

- [ ] Justification: why the fee is needed, what students get, and an itemized table of the costs
- [ ] Estimated number of students per offering
- [ ] How many times a year the course is taught
- [ ] The student feedback process. Aubree's spring 2026 process: share the justification ("The
      proposed $75 fee covers the cost of …; we use this tool because …"), ask students for
      comments, keep the survey open at least 5 days, and download the results. Survey the
      current TCSS 490 students; what matters is showing the effort, even with few responses.
      Survey draft: [courses/tcss-461-fee-survey.md](../courses/tcss-461-fee-survey.md)

## Open questions / risks

- Can the CSS curriculum committee approve a description edit this small, or does it still need
  to go to APC? Check with whoever handles course changes in SET.
- Does anyone else teach 461, or count on its current content (MDD, UML, Eclipse)? Check before
  the meeting.
- Which approvals does a new course fee need beyond the CSS curriculum committee?
- Does reusing 461 make it harder to add a separate, dedicated AI/SWD course number later?

## Discussion

<!-- Add views from each contributor here, with initials and date. -->
