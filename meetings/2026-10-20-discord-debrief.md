# Discord Debrief: What the Student Demos Showed — 2026-10-20

- **Participants:** Charles, Chris (algorithm0r)
- **Format:** Discord chat, ~11:13–11:35 AM
- **Context:** Reaction to student app demos from the day before. Students had built full
  applications in a short window, described as both "2 weeks" and "only 1 week" in the chat.

## Starting observation

Students stored application state "just in the browser." That is exactly the kind of domain
knowledge vibe coding misses. Even senior CS students may not know this unless they have built a
full distributed application.

## Gaps observed in the demos

1. **Persistence and distributed-system basics:** where state lives, and why the browser isn't enough.
2. **UI/UX:** most apps looked impressive but had mediocre usability.
3. **Attention to detail:** almost every demo had small pieces that didn't work or weren't
   finished. Production software needs those cleaned up, and that is where most of the time goes.
   (Could partly be a time-limit artifact.)
4. **Testing (possible gap):** it's unclear whether any project added formal testing.

## Emerging curriculum skeleton

Charles's sketch of the content areas:

- **Systems** (not low-level). Chris adds sub-areas: full stack, UX, dev flow and documentation.
- **Data:** flow, processing, storage
- **UI/UX**
- **Process:** e.g., agile / scrum
- **Testing / Verification / QA**
- **DevOps:** surfaced during the database discussion below

Chris: "this is fleshing out the skeleton we talked about before."

## Scope: major vs. minor / certificate (unresolved)

| Charles | Chris |
| --- | --- |
| Doesn't see an AI/SWD **major**; at most a ~6-course minor or certificate. | Thinks the certificate can be grown into a major. |
| Doesn't see 90 credits, though adding service-style courses might get there. | Candidate additions: business start-ups, community-driven development, Josh's labor course (Chris would teach). |
| Idea: partner with Milgard so a business minor covers ~30 credits. | Wants Friday focused on **the majors on the table**. Bringing minors and certificates means "we will debate options and develop none." |

## Other ideas raised

- **Pilot with non-majors or 142-level students.** Run the course with them to find out what can
  stay paired with the major and what must stay in. Possible data for Friday.
- **Talk to students new to the major** who were in the class, to hear about their experience.
- **UX guest session:** invite Josh or Raghavi to talk about UI/UX for an hour.
- **Shared student database.** Chris proposed hosting a small DB so students don't have to pay.
  Variants discussed:
  - Two instances (one each) to spread the load (Charles)
  - Cloud-hosted (Chris)
  - Counterpoint (Charles): if we go cloud, students lose the value of learning to do the
    DevOps themselves. That led to DevOps being added to the skeleton.

## Agreed

- **Friday 2026-10-23, 12:30:** CS colleagues meeting. Lightning show-and-tell ("shock and awe"):
  - Chris: 5-minute demo of what students built
  - Charles: 5 minutes on the gaps
- **Friday 2026-10-23, 11:00:** Charles and Chris meet to put together a plan for an AI/SWD
  major to bring to the 12:30 meeting.
- **Channels:** discussion on Discord; agents on Slack; Claude's work goes into this repo.
