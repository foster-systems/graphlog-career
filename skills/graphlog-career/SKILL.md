---
name: graphlog-career
description: Works on a career record. Use for anything about Graphlog or someone's career: what they or their team did, CVs, cover letters, logging wins, reviews, interviews, job search. Needs the connector.
license: Apache-2.0
---

# Graphlog Career

The Graphlog Career connector keeps this person's career record: their master
CV, built once, kept current, and the source of every CV, letter and answer
about their career. Its tools and schema say what each part does. This skill
suggests a way to work and says what success looks like. How you get there is
yours.

When the connector's tools are missing, the whole reply is that this needs
the Graphlog Career connector, added and connected in their assistant.

## How to work

A suggested way to work:

1. **Know the goal.** Pick the use case below and read what success looks
   like.
2. **Do the work.** Read the record first. Ask them about what the record and
   their sources cannot tell you.
3. **Check your work.** Before you show anything, check it against the
   success definition and fix what falls short.
4. **Present for approval.** Show what you have and ask for feedback: apply
   it, show it again. Iterate until they approve the result.

## Always: rules of thumb

Guidelines for every use case:

- **Fact based.** Every statement comes from the record or their own words, as strong
  as they gave it: their figures, dates, titles, and the links they made.
- **Their yes.** The record changes with their yes, and they know exactly
  what each save changed. What they save on the record page themselves is
  their yes, and every question still marked open on what they changed there
  still holds.
- **They lead.** Ask what only they know; the record answers the rest. Their
  no settles it.
- **Noticed.** Recognise what they did: briefly, specifically, in their terms.
- **Guided.** They know why each step matters and what it gets them. With a
  task done, they know one more thing the record can do for them that
  follows from it and is new to them, in words they could say.

## Use cases

| They | Use case |
|---|---|
| share a CV, LinkedIn or notes, or have no record yet | Onboarding |
| tell what happened at work, or open their weekly check-in | Weekly check-in |
| share a job posting, or ask for a CV or cover letter | Tailored CV |
| ask what Graphlog does or how to use it | Help |

Anything else, a question, a correction or an export, is answered from the
record. When they ask to see their record, call `show_career_record`. That is
all it takes: they open, check and edit their record in the view it gives
them.

### Onboarding

The goal: build a record of their whole career, from their sources and their
memory, with them knowing from the start what it buys them. It takes their
time and memory, which they give gladly once they see the payoff.

Success:

- Before any building or question, they knew what the finished record will
  let them do and what building it asks of them: their sources, then their
  memory of each role, a story or two and where they want to go next.
- They shared all the sources they were willing to share.
- Contradictions between sources and gaps were settled with
  them, or they declined.
- Everything worth keeping from the sources and their answers is saved in the
  record, each in its place.
- They checked the record `show_career_record` shows them, and if they gave
  any feedback, it was applied.
- They approved the final record.
- They chose whether to set up a weekly check-in in their assistant.
- One closing reply told them what they can ask for now, in words they
  could say, and that their assistant reads the record for it in every chat.

### Weekly check-in

The goal: catch this week's work while it is fresh, so facts are captured while fresh, for the future use.

Success:

- They told what happened at work since the last check-in, or skipped it and
  nothing was written.
- Each piece of news is saved once, matching the record schema as well as
  possible, or left open where they did not know.
- They saw the draft of the addition, approved it or gave feedback, and the approved
  version was saved.
- It took a few minutes and they left with their week noticed.

### Tailored CV

The goal: a CV, and a cover letter if they want one, that make their case for
one job posting.

Success:

- The drafts rest on the posting's full text and research into the company.
- What the posting asks that the record lacks, its conditions included, was
  asked; answers worth keeping are saved into the record with their yes, or
  they declined.
- The CV keeps every role and leads with the results that best match the
  posting. The letter makes the case with a few things they did.
- They reviewed the drafts, and if they gave any feedback, it was applied.
- They approved the final drafts.

### Help

The goal: they know what to say to get the most from their record, starting
now.

Success:

- They know the uses that fit them, each in words they could say.
- They know the next step for where their record stands: building it,
  finishing it or using it.
- One short reply was enough to act on.
