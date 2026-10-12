# Glossary

The method's terms, defined once. A method document or skill uses a term as it is defined here
and never redefines it.

- **Task**: what one unit of work asks for. It is the description of a work item, or the
  words the human gives in the session.
- **Work item**: one unit of work on the work tracker. An **epic** is a work item that tracks
  its children and is never worked itself.
- **Work type**: what kind of artifact a task produces: an analysis document, a requirement,
  an architecture decision, a design document, code, tests, a process change. A work item
  carries its work type as its **context label**.
- **Work types catalogue**: one entry per work type, routing it to its **work file** (how the
  work is done), its **completion bar** (what must be true of the finished artifact), its
  **review checklist** (what only a reviewer can check) and the models each side runs on.
- **Change request**: the reviewable change on the change host that delivers one work item.
- **Work tracker** and **change host**: the two roles a project's tooling plays. The tracker
  holds work items, epics and milestones; the host holds change requests, reviews and the
  merge. Each is realised by a product file for the product in use.
- **Contribution workflow**: the method's chain from a work item to its merge, run by the
  `work` skill. A project has one when its `CLAUDE.md` routes to it.
- **Stand-alone**: a skill run on its own, outside the contribution workflow. It does its one
  job and leaves what surrounds it, such as branches and change requests, to the human.
- **The profile**: the values a project sets. A rule names a profile key; the value lives
  only in the profile.
- **The human**: the person the session works with. Every decision the method does not give
  the session is theirs.
