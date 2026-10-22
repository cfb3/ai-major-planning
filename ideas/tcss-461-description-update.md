# Teach the AI software development course as TCSS 461

- **Author:** Charles
- **Date:** 2026-10-22
- **Type:** course
- **Maturity:** proposal

## The idea

Charles and Chris currently teach their AI software development course as TCSS 490 (Special
Topics). To make it more permanent without the long lead time of a new course through APC, teach
it under the existing TCSS 461 instead. The 461 description is already close; it needs small
edits to be more generic. Charles plans to propose the change at the next CSS curriculum meeting
(date not yet set).

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

- Charles brings the proposed description to the next CSS curriculum meeting.
- Pitch: no change in scope. The edits remove a product name and a dated term and generalize one
  technique.
- If approved, the course is offered as TCSS 461 instead of 490. Prerequisite stays TCSS 360.
- Charles will also propose, at the same meeting:
  - **ABET design elective:** count TCSS 461 as a design elective (the description already
    centers on system design and architecture).
  - **$75 course fee:** to pay for a Claude Team account for each student in the course.
- Meeting materials (claude.ai, private to Charles until shared):
  [slide deck](https://claude.ai/artifact/LTNGTN7kVbjG6oCKq45B2t) ·
  [agenda doc](https://claude.ai/artifact/MD9PQZP6BNFPYHGxDvvBCw)

## Open questions / risks

- Can the CSS curriculum committee approve a description edit this small, or does it still need
  to go to APC? Check with whoever handles course changes in SET.
- Does anyone else teach 461, or count on its current content (MDD, UML, Eclipse)? Check before
  the meeting.
- What does the ABET review need to see to accept 461 as a design elective?
- Which approvals does a new course fee need beyond the CSS curriculum committee?
- Does reusing 461 make it harder to add a separate, dedicated AI/SWD course number later?

## Discussion

<!-- Add views from each contributor here, with initials and date. -->
