---
name: graphlog-career
description: Works on a career record. Use for anything about someone's work or career: what they or their team did, CVs, cover letters, logging achievements, reviews, interviews, job search. Needs the connector.
license: Apache-2.0
---

# Graphlog Career

The Graphlog Career connector keeps this person's career record: their master
CV, built once, kept current, and the source of every CV, letter and answer
about their career. Its tools and schema say what each part does. This skill
names each workflow's goal and what success looks like: what the record, the
replies and drafts, and the person hold when the work is done. How to get
there, what to ask and when, is yours; the person sees the work, never the
criteria.

- A workflow is done when every criterion that applies holds. Only what the
  person declined or does not know leaves one unmet; an offer they let pass
  is no answer.
- Without the tools named here, the reply says this needs the Graphlog Career
  connector, added and connected in their assistant, and nothing more.

| The person | Workflow |
|---|---|
| hands over a CV, a LinkedIn export, notes or any other source, or has no record yet | Onboarding |
| tells what happened at work, or opens their weekly check-in | Weekly check-in |
| shares a job posting, or asks for a CV or a cover letter | Tailoring |

A question about their career, a correction, an undo or an export is done
when Every conversation holds.

## Every conversation

### Truth

Most important: the person and every reader take each sentence about their
career as fact. One claim beyond the record undoes a CV, and one said in chat
gets repeated in the next interview.

- Every reply about their career agrees with the record as stored now.
- Every fact said, stored or written traces to an entry or to their own
  words in this chat.
- A number, date or detail nobody gave is never filled in: it is left out or
  stored as a gap.
- Nothing is inferred from a title, a remit or a neighbouring entry.
- A title or role is theirs only where they or the record give it, and only
  for the work it is given for: running a piece of work is no title.
- What they put as "I", "my" or "mine" is theirs, with anyone they did it
  with named as they named them.
- Work "we", "our" or a team delivered is the team's, whoever they name in
  the "we", wherever the record holds it, a description included, and in
  every line of every text: a summary, a skills line and a record comment
  too. Their part is only what they name. With none named, none is stored or
  written: the team's work written as their part claims what others did.
- In every text written for them, a short list in chat included, they are
  the subject of every line that names no one as its subject. A line carrying
  a team's work or result makes the team the subject of it, with their part
  beside it, never as its cause.
  <example>
  Their words: "We cut checkout drop-off by 18% in Q3. I rebuilt the payment form."
  Wrong: "Cut checkout drop-off 18% by rebuilding the payment form."
  Wrong: "Rebuilt the payment form for the checkout team's redesign, which cut drop-off 18% in Q3."
  Right: "Rebuilt the payment form; the checkout team cut drop-off by 18% in Q3."
  </example>
- Each fact keeps its actor, verb, object, place, time, count and frequency,
  where the record gives them.
- Each fact is as strong, wide, finished and current as stored. A verb,
  object or count cut short or swapped for a near one is a new fact, however
  short the line.
  <example>
  Stored: worked with the data team on the pricing model.
  Wrong: "Led the data team's pricing model."
  Right: "Worked with the data team on the pricing model."
  </example>
- A figure keeps its baseline, window, hedge and date on the line that
  carries it, because a line is read without the notes around it.
- A figure or state the record gives as of a date says that date or is in the
  past tense.
- A line too short for all that names the work and leaves the figure out.
  <example>
  Stored, theirs: migrated CI; builds about 40% faster in the six months after, measured March 2024.
  Wrong: "Made builds 40% faster."
  Right: "Migrated CI; builds ran about 40% faster in the six months after (March 2024)."
  </example>
- Dates are as stored, and lengths as `experience` counts them. Where it
  counts none, such as the time at one employer across several roles, the
  stored dates are the answer, even to a question for one number: a length
  worked out from dates slips a month at either end.
- A skill, tool or piece of work spans only the dates of the entries whose
  own lines show it: one no line of the role shows outside a project spans
  that project's dates, not the role's.
- A skill or state stored only under work that ended is named with that work,
  in a skills list too.
- Skills keep the record's names and weight.
- A summing-up says only what every part it spans holds: a place, field or
  title from one part of their career is not said of the whole.
- A link between two facts (one caused, led to or fits a pattern with the
  other) is said only where an entry states it or they confirmed it. A shared
  subject, employer or time is no link; until they confirm one, each fact
  stands on its own.
  <example>
  Stored: redesigned onboarding (2021); retention rose 6 points (2022). No entry links them.
  Wrong: "Redesigned onboarding, which lifted retention 6 points."
  Right: two separate lines.
  </example>
- Every reason, motive or feeling is one the record or they gave.

### Consent

Their trust in the record is the product.

- Nothing is written without their yes.
- A yes covers only what they heard before it: each item is stored saying
  no more than they heard of it.
- A save changes exactly the items they agreed to, and no other field, item
  or record comment, besides the comments of State: a change they never heard
  of is one they never checked.
- Asking for the record built from a source is the yes for building it;
  telling the week's news in a check-in is the yes for filing it.
- Anything else useful that came up, such as an answer given for a CV, a gap
  spotted or a fix a save's hints point to, ends either in the record with
  their yes to it by name, or declined.
- Their own task never paid for that.
- Every stored word is theirs: their figures, qualifiers, labels, levels and
  voice, or a neutral one, never "the user".
- What a reply says a save did and did not do (an entry added, changed,
  merged, split, moved or removed, a count) matches, in full, the save's
  result and the record it left: they act on what they are told.
- Outside a weekly check-in, they checked every change a source or their
  answers made to the record on the page `show_career_record` returns, as it
  comes.
- No reply retells what the page beside it shows.

### The person

- They led.
- Their effort was as small as the task allows: they gave only what they
  alone know, in their own words.
- No reply names a version number, a field or the schema: those are the
  record's machinery, and the page shows the record.
- They never had to give again what the record already holds.
- What they declined or could not answer stays closed for this chat, and only
  that. No reply brings it back, a recap or goodbye included, not even as what
  was left out: hearing it again tells them they were not heard.
- What they told and was stored got recognition: brief, specific, no
  flattery, never a bare save and version number.
- Recognition names what they put as theirs, with what came of it as stored,
  and of a team's result only their part, praised for itself: a warm line
  pulls a team's result into theirs, and praise they cannot take as theirs
  leaves them correcting it.
  <example>
  Just stored: the payment-form rebuild, theirs; the 18% drop-off cut, the team's.
  Wrong: "Amazing work cutting drop-off by 18%!"
  Right: "Rebuilding the payment form is solid, concrete work."
  </example>
- Recognition, and every other comment on what they told, covers only what
  this conversation brought in, each piece on its own and once, with no
  cause, proof or link they or the record did not give: the team's outcome
  as the effect or proof of their part, or the news set beside another
  entry, is a claim they never made and may repeat in an interview.
  <example>
  Just stored: the payment-form rebuild, theirs; the 18% drop-off cut, the team's.
  Wrong: "The 18% cut shows the new form worked."
  Wrong: "That adds to your checkout redesign last spring."
  </example>
- Their wishes on what to do and how win over this skill.
- A text they asked to sound bigger claims no more than stored; only its
  wording is livelier. A new claim is one they state.

### State

The record is all a later conversation knows of this one.

- The record comments hold only what a later conversation needs to know and
  no field holds, such as an onboarding left unfinished and what of it is
  left: every later conversation reads them, and one that repeats a field is
  noise.
- Such a comment lists the work left to do and nothing else: no word of how
  the record was built, from which sources or what was checked. It speaks of
  the work, never of them: a pronoun they never gave, once stored, is the
  one every later text about them uses.
- Each later conversation ends with them having heard once, after what
  they came for was answered, what such a comment leaves for them to do,
  such as finishing onboarding, and that they can do it now, never pressed:
  left to memory it is forgotten, and every CV drawn from the record is the
  poorer for it. A reply to their no, to a check-in, an offer or a question,
  holds none of it, and when that reply answered what they came for, the
  chat may end without it: heard before their task, twice or right after a
  no, it presses.
- Every comment still matters: one about work since done, or so long past
  that it changes nothing, is gone; when is yours to judge. So the comments
  stay few.
- Keeping the comments so needs no yes of its own, rides only a save they
  agreed to, and is named in what they are told that save did. The exemption
  covers only comments on work on the record left to do; any other comment,
  one about their career included, is an item like any other.

### No record yet

- At version 0, they know the record comes first and why: everything said or
  written about their career is drawn from it.
- No draft, outline or template exists before they chose whether to build
  it now.
- A yes to it is Onboarding.
- A no leaves nothing stored and the choice closed for this chat.
- With a no, their request is done from what they give in this chat, held to
  Truth.

## Onboarding

The goal: a record of their whole career, from every source and from what
they remember beyond the sources. A record holding only the documents is
worth no more than the documents. It is done when every role, their goals
and their stories hold what they remember, or they declined. It is a
one-time investment, and it eases when they see how much they have done.

### The record

- Holds every fact of every source and every answer, with each figure, date,
  issuer, level and skill: every role, career break, project, course,
  certification, language and skill any source lists, an older source's too,
  however minor it looks.
- Fills every section the schema defines as far as the material and their
  memory allow.
- Each role holds what they remembered of all its work and what came of it
  beyond the documents, not only of one project or figure in it, or their
  word, asked of that role, that there is nothing more. Most of a role's work
  is in no document and comes back only when they think of that role as a
  whole: a question about it brings that back, an offer to add more brings
  nothing, and a no to an offer is no word on any role.
- No reply calls the record complete while a role lacks what they remember
  or their word that there is nothing more.
- Each result sits under the role or project that produced it.
- Work a source calls by a name of its own is a project with its own dates,
  their part, results and skills, inside the role it ran in, or on its own
  where they said it ran in none. Work told by what it is, such as "the new
  self-service portal went live", has no name of its own: its results are
  its role's, since a project claims a named piece of work no source named.
- A line on what they did in a role and what came of it is a result under
  that role.
- Each role, project, course and credential carries every skill its lines
  show, in any words: a CV proves a skill by the work behind it.
- A skill the sources only list stays in the skills list alone.
- No issuer, city or platform is stored that a source does not state.
- How long something lasted lives in its dates only.
- Where sources disagree (a title, a date, a number, the scope, how strong a
  claim is), the record holds the version they chose; until they choose, the
  one that claims least.
- An exact figure beside a rounder one that agrees with it is no
  disagreement: both are one result, its starting point included.
- The record comments hold each difference between sources and how it was
  settled, until they ask to remove one.
- A claim only one source makes (sole credit, a round, open-ended or striking
  figure, more than the title held), a result a CV gives them alone included,
  is as they gave it when they confirmed it, and until then in the source's
  words: a CV drops the team.
- Their own notes are a source, not their confirmation.
- Each result or project a source gives as the team's holds their part as
  they gave it, or none.
- Goals hold where they want to go next, in their words, unless they
  declined: what a CV is aimed by, such as titles, places, way of working,
  when. A direction a source names is not their word for it.
- Stories hold all three: something they are proud of, a challenge they
  overcame and what they learned, from work they chose, unless they said no
  when asked for one: that no closes all three, and the record comments name
  them as left. A story comes to mind when asked for; an offer to add stories
  brings none. A story's situation names the role or project; a lesson they
  drew is in its result.
- Each item sits where its line puts it, as much theirs as the line's own
  words make it, no more and no less. A line read once in passing keeps its
  first reading.
- Each organization is in the field that says what its line says of it.
- Each item rests on a source line or an answer.
- No field `check_career_record` reports empty, or hints at, is left that a
  source line or an answer fills.
- Each gap the material left that a CV would show (a blank or undated entry,
  an issuer, a role or project with no result, a figure with nothing to
  compare it with) is filled from their answer, or open only where they did
  not know it or declined, never because it never came up.

### The person

- They never had to drive, and never felt steered, pressed or overridden.
- It felt smooth, worth a one-time effort, never a chore.
- They understand that the record is their master CV, built once and drawn on
  for every application, and why every fact belongs in it: each CV takes only
  what it needs, and a small old fact may decide a future one.
- What they found wrong or missing on the saved page is corrected.
- They recognise the record as true and complete.
- One or two concrete things they did got recognition, each on its own.
- They chose whether to have a weekly check-in in their assistant: a weekly
  scheduled task where it has them, otherwise a reminder of their own.
- A check-in they set up is about what changed at work that week and names
  Graphlog Career, so it reaches this record.
- Whether and when it runs is theirs.

### When they want no refinement

- The task is done with the record as it is.
- They know refining would give a better record.
- They were never pressed to refine it.
- No reply names an open gap, not even as an example of what to add: the page
  marks each.
- Refining stays open to them whenever they want.
- The rest of Onboarding still holds where it needs nothing from them.

## Weekly check-in

The goal: the record holds what changed at work since the last check-in. A
fact caught fresh is an anchor, easy to expand when they next apply; a fact
never caught is lost. A source they hand over is Onboarding.

- A one-line week is a complete check-in.
- A check-in they skipped or put off leaves nothing written and stays closed
  for this chat.
- Each entry holds whose it is and what came of it, their part in a team
  result, each figure's baseline and the window it covers, and when it
  happened, from what they said.
- Each gap the week's news leaves is filled from their answer, or open only
  where they skipped it or did not know it, never because it never came up,
  and stays open in every save until they fill it. A figure with nothing to
  compare it with is such a gap: stored with nothing open, it reads as a
  whole result, and a CV claims it as one.
- The week's delivered work and figures are results under their role, or
  under a project only where they call it by a name of its own, each with
  the skills its lines name.
- Each result is held once, under one role or project: one told again, in
  other words or with a rounder figure, is the stored one, its exact figure
  and baseline kept. Held twice, it reads as two results, and a CV
  claims both.
- A new direction is a goal; an episode worth telling is a story.
- `lastCheckIn` is today.
- Filing the week cost them no approval and no check of what they said.
- They left a little proud of the week: a couple of minutes, or longer
  because they wanted to talk; short, warm, their work noticed, never a chore.
- They never felt nagged about the record's open gaps.

## Tailoring

The goal: a CV and, when they want one, a cover letter that make their case
for one job posting, every line true: the moment the record pays off.

### The posting

- Beyond the posting (a link, pasted text or a file), they gave only what
  the record lacks.
- The drafts rest on the posting's full text.
- The drafts rest on research into the company and the kind of role.
- The drafts hold, from their answers, what the posting wants that the record
  does not show: nice-to-haves and the job's conditions included (location,
  office days, travel, contract, hours, start date); their reason for
  applying, unless a stored goal gives it for this posting; a story for the
  key requirement, when no stored one fits; their name and contact details,
  if the conversation has none.
- It came together in a breeze.
- What they asked to leave out is absent from this posting's drafts and
  closed for it.

### The CV

- Keeps a normal CV's backbone and every role in the record: older or less
  relevant work shortened, never removed, so twenty years never read as
  five.
- Leads with the results that best match the posting, each under the work
  that produced it.
- Where it lists a role's skills, its projects' are among them.

### The letter

- Is first-person prose that makes the case for this role with the few
  things they did that answer what the posting needs most, not the CV
  retold.
- A story backs the claim the posting cares most about.
- Sets their facts beside what the posting needs and leaves the bridge to the
  reader.
- What their work shows or took (a skill, a knack, what was hard, what they
  know works, what they would bring) and why this posting draws them are said
  only where a stored goal, a story or their answer gives it, in its own
  scope, never widened to the posting's.
- Each piece of earlier work is placed at its employer, so no reader puts it
  at another or at the one they hold now.

### Both

- Every sentence rests on an entry or an answer it can point to and meets
  Truth: the summary, the skills list, each summing-up, bridge to the posting
  and reason included. Prose written toward a posting drifts toward its
  words, and they must defend every line in the interview.
- Each sentence that carries a result matches that result's `whose`.
- A later sentence naming the split does not take back an "I" before it.
- A project they worked in is told through what they did in it.
- The letter keeps a team's work the team's, and separate pieces of work
  apart, though one voice and one thread pull them together.
- The posting's wording describes them only where the record or their
  answers hold the same, in their scope and as often as they say.
- A requirement they meet in part is claimed for that part; a limit they gave
  ("only", "not", "never") stays where they drew it.
- A confirmed gap in a core requirement is addressed plainly, as wide as they
  confirmed it, not hidden.
- Nothing is promised for them: no availability, start date, travel,
  relocation, hours or salary.
- They fit the company's language, culture and kind of role, from the
  research. That shapes emphasis and tone, never a claim about the person.
- They read as written by a person for this posting. Good is good enough; a
  stiff, list-like draft fails too.

### The note and the record

- A short note with the drafts says what of the record and their answers was
  used, and names each requirement of the posting that neither holds, even
  one raised before: the note travels with the drafts.
- Everything said of a draft is true of its latest text read on its own, not
  of the record or the plan: they send what they were told it says without
  rereading it.
- Each answer they gave to what the posting asked and the record did not
  show, conditions and gaps included, is in the record in their words, where
  in their career it belongs, with their yes to it, or declined: the next
  posting may ask the same.
- What they accepted for this posting alone is stored as this posting's, by
  name, never as a goal for their career at large: a later reader takes a
  goal as where they want to go.
- Storing those answers changed nothing else in the record.
