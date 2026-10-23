# TCSS 461 Advanced Software Engineering: Syllabus Draft

<!-- Draft for Aubree's Kuali update (needs learning objectives, weekly outline, grading).
     Melded from the TCSS 490 Autumn 2026 syllabus (SET-Course-Forge
     TCSS490-26-AUTUMN: docs/syllabus.md, docs/weeks/index.md, docs/grading/index.md,
     planning/SYLLABUS-PROPOSAL.md). Written 2026-10-22 by Claude for Charles and Chris.
     [Brackets] mark things to confirm or decide. -->

**Status:** first draft, 2026-10-22. Not yet reviewed by Charles or Chris.

**Deadline context:** CSS faculty vote 2026-11-06; Aubree submits to APCC by 2026-11-25; first
offering Spring 2027. See [the 461 idea](../ideas/tcss-461-description-update.md).

## What changed from TCSS 490

To work as a permanent, design-elective course, the draft makes 490 more formal:

| TCSS 490 (Autumn 2026) | TCSS 461 draft | Why |
| --- | --- | --- |
| Five artifacts; the moonshot runs 5 of 10 weeks, solo or team | Three one-week foundation builds, then a **team capstone for weeks 4–10** | A design elective needs a design project for most of the quarter, team-based (Tom, 2026-10-22) |
| Artifact 4 (pairs, for someone else) | Folded into the capstone: teams build for a real user | Keeps the "for someone else" practice inside the capstone |
| Lectures in weeks 2, 3, 5 only | A topic every week, tied to a capstone design milestone | Weekly outline for Kuali; theory feeds the capstone each week |
| Capstone deliverable is the product | Product **plus design artifacts**: architecture, data design, UI/UX, test plan | Shows several design elements used to produce one final product |
| 14 objectives in three pillars | Same pillars, plus design and re-engineering objectives matching the 461 description | Aligns objectives with the catalog description |
| Claude access handed out in class | Claude Team account paid by the $75 course fee | Pending the separate fee approval |

## Course Information

- **Course:** TCSS 461 Advanced Software Engineering, [5] credits
- **Prerequisite:** TCSS 360
- **Format:** studio course. Students build throughout the quarter, ending in a team capstone
  project. [Meeting pattern to match the Spring 2027 time schedule.]
- **Instructors:** [Charles Bryan and Chris Marriott, co-taught]

### Catalog Description

Analyzes system re-engineering, domain-specific languages, generative development, system design,
and software architecture. Also covers how to handle legacy systems, utilize model-driven and
automated approaches to code generation, and understand low- to high-level architectures, by
using software engineering methodologies, refactoring, modeling, and modern development tools.
Prerequisite: TCSS 360.

### Course Overview

This course develops the skills and judgment to engineer software systems with modern
development tools, including AI coding assistants. It rests on four connected areas: development
workflows, tools, and practice; software engineering and project management; system design and
architecture; and re-engineering existing systems. Students learn to decompose complex problems,
manage context across tools and sessions, verify and evaluate generated code, and make sound
architectural decisions.

The quarter opens with three one-week builds that establish the tools and workflow. From week 4
on, students work in teams on a **capstone project**: a substantial software system built for a
real user. The capstone accumulates the theory and practice introduced each week. Teams produce
and use several design elements (system architecture, data design, user interface design, and a
test design) to deliver one final product.

## Learning Objectives

By the end of this course, students will be able to:

**Workflows, tools, and practice**

1. Select and configure development tools, including AI coding assistants, appropriate to a task
2. Manage context effectively across tools, sessions, and collaborators
3. Verify and critically evaluate generated code and design suggestions
4. Recognize when automated assistance is counterproductive and work effectively without it

**Software engineering and project management**

5. Decompose a complex problem into specified, testable subtasks
6. Plan, version, and document a team project with appropriate traceability
7. Manage a development workflow within a team, and communicate technical decisions to
   collaborators and stakeholders

**System design and architecture**

8. Design a software system's architecture from low-level components to high-level structure,
   and justify the design with models
9. Design the data, interface, and test strategy of a system and integrate them into one product
10. Evaluate design trade-offs, including cost, latency, reliability, and security

**Re-engineering and generative development**

11. Navigate, refactor, and extend large, unfamiliar or legacy codebases
12. Apply model-driven and automated approaches to code generation, including domain-specific
    languages and AI tools, and reason about their limits

[Mapping to 490: 1–4 ← 490 LO 1, 2, 4, 6; 5–7 ← 490 LO 3, 7, 9, 10; 8–10 ← 490 LO 11–13 plus
design; 11–12 ← 490 LO 8, 14 plus the 461 description.]

### ABET Student Outcomes

[Confirm against the CSS program's ABET mapping.] As a design elective, the course contributes
mainly to:

- Designing, implementing, and evaluating a computing-based solution to meet a set of
  requirements (the capstone and its design artifacts)
- Functioning effectively as a member of a team (the team capstone)
- Communicating effectively in a variety of professional contexts (design reviews, final
  presentation)
- Applying computer science theory and software development fundamentals to produce solutions
  (objectives 8–12)

## Weekly Outline

| Week | Topic | Capstone milestone | Build |
| --- | --- | --- | --- |
| 1 | Generative AI and LLMs: what they are; course workflow | | Build 1: portfolio site (solo) |
| 2 | AI-assisted workflow: context, agents, and tools | | Build 2: a tool you will use (solo) |
| 3 | How LLMs work; designing systems with an unreliable component | Form teams; find a real user | Build 3: a model inside the product (solo) |
| 4 | Requirements, specification, and decomposition; team process | **Proposal and requirements** | Capstone |
| 5 | Distributed application architecture: client and server, shared state, databases, third-party APIs | **Architecture and data design** | Capstone |
| 6 | User interface and experience design: usability heuristics | **UI/UX design** | Capstone |
| 7 | Re-engineering: legacy code, refactoring, DSLs, model-driven and generative development | **Working prototype; design review** | Capstone |
| 8 | Testing and verification strategies; code review | **Test plan and verification report** | Capstone |
| 9 | Security and deployment | **Security review; deployed release** | Capstone |
| 10 | Professional practice: authorship, disclosure, ownership of generated work | **Final product, presentation, retrospective** | Capstone |

Each week also has a reading, a reading quiz, a reflection, and a team or learning-group meeting,
as in TCSS 490. Readings come from the course site (no textbook). [Map the 490 readings to weeks:
gen-ai-defined, how-machines-learn, communication-with-agents, tools-on-top-of-llms,
llms-under-the-hood, systems-with-an-unreliable-component, specification-and-decomposition,
review-and-verification, security-when-the-attacker-writes-prose,
authorship-ownership-and-disclosure. Week 5–7 topics need readings written.]

## The Capstone Project

- **Team-based:** teams of [3–4], formed in week 3.
- **Runs weeks 4–10** (seven of ten weeks).
- **Built for a real user** outside the team.
- **Cumulative:** each week's topic feeds the matching milestone.
- **Design elements, each a graded deliverable:** requirements; architecture (with models of its
  components and their interactions); data design; UI/UX design; test plan and verification
  report; security review.
- **Final product:** a working, deployed system, a final presentation, and a team retrospective.
- **Individual accountability:** weekly reflections and peer evaluations. [Decide the peer
  evaluation method.]

## Grading

[Decision: keep 490's labor-based contract, or switch to weighted grading for a formal 461. The
draft keeps labor-based grading, with the capstone design deliverables as required components.]

Every deliverable is marked **complete (on time)**, **complete (late)**, or **incomplete**.
Incomplete work can be resubmitted.

| Grade | Late allowed | Incomplete allowed |
| --- | --- | --- |
| B (3.1) | 8 | 0 |
| C (2.1) | 12 | 1 |
| D (1.1) | 16 | 2 |

Completing all work on time earns a B. Optional extra labor raises the grade above a B. [Carry
over 490's extra-labor options.]

**Deliverables:**

- Three foundation builds (weeks 1–3)
- Seven capstone milestones (weeks 4–10), including the design artifacts above
- A weekly reading quiz, reflection, and meeting minutes
- No exams

## Course Materials

- No textbook; readings are published on the course site
- A laptop that can install software, a GitHub account
- A Claude Team account, paid by the $75 course fee [pending fee approval]

## AI Policy

Carry over the TCSS 490 policy: AI use is expected; students own the outcome, the decisions, and
the verification; some work requires a disclosure of how it was made; a false disclosure is an
academic integrity violation. Students who choose not to use AI are held to the same standard.

## Campus Policies

Standard UW Tacoma statements: academic integrity, accommodations, religious accommodations,
safety, and student support. [Carry over 490's campus-policies page.]
