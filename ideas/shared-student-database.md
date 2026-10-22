# Shared Student Database

- **Author:** Chris
- **Date:** 2026-10-20
- **Type:** pedagogy / infrastructure
- **Maturity:** seed

## The idea

Faculty host a small database that students can use for their projects, so they don't have to
pay for backend storage.

## Why it matters

It removes a cost barrier and pushes students toward real persistence instead of browser-only
state (see [observed-gaps-from-student-demos.md](observed-gaps-from-student-demos.md)).

## How it might work

Options raised:

- **Two self-hosted instances,** one run by Charles and one by Chris, to spread the load
- **Cloud-hosted** (Chris)

## Open questions / risks

- Cost, security, and who maintains it
- **Tension with DevOps learning:** if we hand students a managed cloud DB, they miss learning to
  stand up and operate one themselves (Charles).

## Discussion

- **Chris (2026-10-20):** Backend storage is usually free; was thinking cloud.
- **Charles (2026-10-20):** Maybe two, to spread the load. If cloud, there's value in students
  doing the DevOps themselves. This is what put DevOps into the skeleton.
