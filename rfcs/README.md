# RFCs (Requests for Comments)

This directory contains formal proposals for standards, amendments, and other significant changes.

---

## What is an RFC?

An RFC is a formal proposal for a change to:

- The Treaty itself (governance amendments)
- Technical standards (Article II)
- Procedures (voting, dispute resolution)

---

## RFC Lifecycle

| Phase | Description |
| :--- | :--- |
| **Draft** | Initial proposal, open for discussion |
| **Comment** | Public comment period (minimum 30 days) |
| **Revised** | Updated based on feedback |
| **Final** | Ratified by rough consensus |
| **Active** | Adopted and implemented |
| **Retired** | Superseded or obsolete |

---

## RFC Template

```markdown
# RFC-NNN: [Title]

**Status:** Draft | Comment | Revised | Final | Active | Retired

**Author:** [Name/Project]

**Date:** [YYYY-MM-DD]

---

## Summary

Brief description of the proposal.

## Motivation

Why is this change needed?

## Specification

Detailed technical or governance changes.

## Impact

How does this affect signatories?

## Backwards Compatibility

Does this break existing implementations?

## Alternatives Considered

What other approaches were considered and why were they rejected?

## Discussion

Link to PR, issues, or meeting notes.

---

*Last updated: [YYYY-MM-DD]*
```

How to Submit an RFC
Copy the template above.

Save as rfcs/rfc-NNN-title.md (use the next available number).

Open a Pull Request.

Engage in discussion.

Follow the amendment process in Article III for governance changes.


---

## `meeting-notes/README.md`

```markdown
# Meeting Notes

This directory contains records of summits, working groups, and community calls.

---

## Format

Each meeting should be recorded as a markdown file with the following format:

```markdown
# Meeting: [Title]

**Date:** YYYY-MM-DD

**Attendees:** [List of participants]

**Agenda:**
1. Item 1
2. Item 2
3. Item 3

**Discussion:**
- Notes on item 1
- Notes on item 2

**Decisions:**
- Decision 1
- Decision 2

**Action Items:**
- [ ] Action 1 (Owner: Name)
- [ ] Action 2 (Owner: Name)

Upcoming Meetings
```
Date	Title	Location
TBD	First Commons Summit	TBD
```
-Past Meetings
```
Date	Title	Notes
2026-08-05	Initial Treaty Drafting	[Link]
```

---

## LICENSE

Since we agreed no license, just this notice:

This document is a work of the community, for the community.

It is dedicated to the public good under the Notice of Public Commons.

You may share and distribute it freely.
You may not sell it or use it commercially without the explicit consent of the active Signatories.
You may propose amendments through the process defined in Article III.
You may not publish modified versions as "The Decentralized Commons Treaty"—only the official version maintained by the Steward carries that name.

Enforcement of these terms lies with the community, not with any court or legal system.


---

## Final Repo Structure
```
decentralized-commons-treaty/
├── README.md
├── treaty.md
├── CONTRIBUTING.md
├── LICENSE
├── signatories/
│ └── registry.md
├── governance/
│ ├── README.md
│ ├── steward-selection.md
│ ├── amendment-process.md
│ ├── dispute-resolution.md
│ └── voting.md
├── standards/
│ └── README.md
├── rfcs/
│ └── README.md
└── meeting-notes/
└── README.md
```
