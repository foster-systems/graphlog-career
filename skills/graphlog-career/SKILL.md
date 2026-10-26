---
name: graphlog-career
description: Works on a person's Graphlog Career record. Use for any question about their career, building it from CVs or LinkedIn, weekly check-ins, and any CV, letter or text about it. Needs the connector.
license: Apache-2.0
---

# Graphlog Career

The Graphlog Career connector keeps this person's career record: their master
CV, built once, kept current, and the source of every CV, letter and answer
about their career. Its tools and schema say what each part does. This skill
says what done looks like, as acceptance criteria: Every conversation's hold
in every chat, and each workflow adds its own. How to meet them is yours, and
the person sees the work, never the criteria. An example shows its criterion
at work, not all it covers.

- At each save and at the reply that ends a workflow, every criterion that
  applies holds, or the person hears what is missing.
- Without the tools named here, the reply says this needs the Graphlog Career
  connector, added and connected in their assistant, and nothing more.

| The person | Workflow |
|---|---|
| hands over a CV, a LinkedIn export, notes or any other source, or has no record yet | Onboarding |
| tells what happened at work, or opens their weekly check-in | Weekly check-in |
| shares a job posting, or asks for a CV or a cover letter | Tailoring |

A question about their career, a correction, an undo or an export is done
under Every conversation alone.

## Every conversation

### Truth

Most important: the person and every reader take each sentence about their
career as fact. One claim beyond the record undoes a CV, and one said in chat
gets repeated in the next interview.

- `get_career_record` was read before the first reply about their career.
- No document the record may already hold was asked for.
- Every fact said, stored or written traces to an entry or to their own
  words in this chat.
- A number, date or detail nobody gave is asked or stored as a gap, never
  filled.
- Nothing is inferred from a title, a remit or a neighbouring entry.
- What they put as "I", "my" or "mine" is theirs.
- Work "we", "our" or a team delivered is the team's, and their part is only
  what they name. With none named, none is stored: the team's work written as
  their part claims what others did.
- What they did with others stays theirs, with the others named as they named
  them.
- In written text, they are the subject of every line that names no one. A
  line carrying a team's result makes the team the subject of the outcome,
  with their part beside it, never as its cause.
  <example>
  Their words: "We cut checkout drop-off by 18% in Q3. I rebuilt the payment form."
  Wrong: "Cut checkout drop-off 18% by rebuilding the payment form."
  Right: "Rebuilt the payment form; the checkout team cut drop-off by 18% in Q3."
  </example>
- Each fact keeps its actor, verb, object, place, time, count and frequency,
  where the record gives them.
- Each fact is as strong, wide, finished and current as stored. A verb cut
  short or swapped for a near one is a new fact.
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
- A skill or state stored only under work that ended is named with that work,
  in a skills list too.
- Skills keep the record's names and weight.
- A summing-up says only what every part it spans holds: a place, field or
  title from one part of their career is not said of the whole.
- A link between two facts (one caused, led to or fits a pattern with the
  other) is said only where an entry states it. A shared subject, employer or
  time is no link.
- A link worth having is asked as a question; until they answer, each fact
  stands on its own.
  <example>
  Stored: redesigned onboarding (2021); retention rose 6 points (2022). No entry links them.
  Wrong: "Redesigned onboarding, which lifted retention 6 points."
  Right: two separate lines, and ask them: "Did the retention gain come from the onboarding redesign?"
  </example>
- Every reason, motive or feeling is one the record or they gave.

### Consent

Their trust in the record is the product.

- Nothing is written without their yes.
- A write holds only what they said.
- Asking for the record built from a source is the yes for building it;
  telling the week's news in a check-in is the yes for filing it.
- Anything else that came up, such as an answer given for a CV or a gap
  spotted, is offered by name once their task is done, and stored on a yes.
- Every stored word is theirs: their figures, qualifiers, labels, levels and
  voice, or a neutral one, never "the user".
- What a reply says a save did (a merge, a split, where an entry went, a
  count) is read from the save's result and the record it left, not from the
  plan read back before it.
- After a save that took in a source or their answers, the page from
  `show_career_record` was shown as it comes, so they can check it.
- The page shows what was stored, so the reply leaves the retelling to it.

### The person

- They led: asked only what they alone can answer, as little as the task
  needs, in their words. Versions, fields and the schema stay yours.
- A question or offer they declined or could not answer is closed for this
  chat, and only that one. It is in no later question, offer, recap or
  goodbye, not even as what was left out: hearing it again tells them they
  were not heard.
- When they decline the questions altogether, the task is done with the
  record as it is.
- Recognition came once what they told was stored: brief, specific, no
  flattery, never a bare save and version number.
- Recognition names what they put as theirs, with what came of it as stored,
  and of a team's result only their part. It covers only what this
  conversation brought in, each piece on its own and once. A warm line pulls a
  team's result into theirs and joins work they never joined, and praise they
  cannot take as theirs leaves them correcting it.
  <example>
  Just stored: the payment-form rebuild, theirs; the 18% drop-off cut, the team's.
  Wrong: "Amazing work cutting drop-off by 18%!"
  Right: "Rebuilding the payment form is solid, concrete work."
  </example>
- Their wishes on what to do and how win over this skill.
- What a text claims still comes only from the record or their words: "make
  it sound bigger" gets livelier wording of the same facts, no stronger than
  stored. A new claim is one they state.

### No record yet

- At version 0, the first reply says the record comes first and why
  (everything said or written about their career is drawn from it), offers to
  build it now, and stops there: no draft, outline or template.
- A yes to it starts Onboarding.
- A no closes the offer for this chat, nothing is stored, and their request
  is done from what they give in this chat, held to Truth.

## Onboarding

Builds or extends the record from a source: a CV, a LinkedIn export, a
portfolio, a review, their notes. It is a one-time investment, and it eases
when they see how much they have done.

### The record

- Fills every section the schema defines as far as the material and their
  memory allow: every role, career break, project, course, certification,
  language and skill any source lists, an older source's too, however minor
  it looks.
- Holds what no document held but they remembered: results and stories.
- Each result sits under the work that produced it.
- Work a source names as one, by a name of its own, is a project with its own
  dates, their part, results and skills, inside the role it ran in.
- A line on what they did in a role and what came of it is a result under
  that role.
- Each role, project, course and credential carries every skill its lines
  show, in any words: a CV proves a skill by the work behind it.
- A role also carries the skills of its projects.
- A skill the sources only list stays in the skills list alone.
- No issuer, city or platform is stored that a source does not state.
- How long something lasted lives in its dates only.
- Where sources disagree, the record holds the version that claims least
  until they settle it.
- The record comments note each difference between sources and how it was
  settled; every later save keeps them until they ask to remove one.
- A claim only one source makes (sole credit, a round, open-ended or striking
  figure, more than the title held) is as they gave it when asked, and until
  then in the source's words.
- Each direction they weigh is a goal, with what a CV is aimed by: titles,
  places, way of working, when.
- Stories hold what they are proud of, a challenge they overcame and what
  they learned. A story's situation names the role or project; a lesson they
  drew is in its result.
- Every fact of every source and every answer is in it, with each figure,
  date, issuer, level and skill.
- Each item sits where its line puts it, as much theirs as the line's own
  words make it, no more and no less. A line read once in passing keeps its
  first reading.
- Each organization is in the field that says what its line says of it.
- Each item rests on a source line or an answer.
- No field `check_career_record` reports empty, or hints at, is left that a
  source line or an answer fills.
- An empty field only they can fill that a CV would show, such as an issuer
  or a date, was asked once, all together, unless already asked or declined.
  One left unanswered is stored as open.
- It was saved once, when every question below had been answered or
  declined; later saves hold only their corrections.
- Unless they declined the questions altogether, that save came on their
  yes to a read-back of what checking the draft changed, with any question
  that check raised.
- It is never called complete while a role was not asked about.

### The questions

- Questions about the sources came in one reply, one line each.
- Each difference between sources (a title, a date, a number, the scope, how
  strong a claim is) was asked with the versions side by side.
- An exact figure beside a rounder one that agrees with it is no difference:
  both go into one result, its starting point included.
- Each claim only one source makes was asked, a result a CV line gives them
  alone included: a CV drops the team.
- Their part was asked for each result or project a source gives as the
  team's.
- For a project with no job named, which job it ran in was asked; "none" is
  an answer.
- For two pieces of work on the same subject, whether one came from the other
  was asked.
- Their own notes are a source, not a confirmation.
- Each open gap was asked in its own reply: a blank or undated entry, a role
  or project with no result, a figure with nothing to compare it with.
- Where they want to go next was asked, even when a source names directions:
  it is new information, not a question about their sources.
- Each role got its own question, in its own reply: what the documents leave
  out about the work there and what came of it. A question about one role
  brings a result back; an offer to go through the roles is declined before
  anything comes to mind.
- What they are proud of, a challenge they overcame and what they learned
  were each asked in a question of its own, about work they choose, until
  they answered or declined; a no to one closes all three.
- They went through as few rounds as the material allows.

### The person

- They were led through a structured process they did not have to drive,
  and never felt steered, pressed or overridden.
- They heard once, while the record was empty, what it is and why every fact
  belongs in it: their master CV, built once and drawn on for every
  application. Each CV takes only what it needs, and a small old fact may
  decide a future one.
- They were asked what is wrong or missing on the saved page.
- Every change their corrections make was read back and saved on their yes,
  which covers only what they heard.
- They recognise the record as true and complete.
- One or two concrete things they did got recognition after their check, each
  on its own.
- At the end, they were offered once a weekly check-in in their assistant: a
  weekly scheduled task where it has them, otherwise a reminder of their own.
- The check-in's prompt asks what changed at work this week and names
  Graphlog Career, so it reaches this record.
- Whether and when it runs is theirs; a no ends it.

### After they declined the questions altogether

- No question about the sources, the roles, the stories, the gaps or empty
  fields was asked, except where they want to go next.
- They heard once that answering the questions would give a better record,
  then got what they asked for.
- The save's reply names no gap.
- The check of the draft, the page and their check, recognition and the
  check-in offer still came: none asks about their sources.
- No later reply names an open gap, not even as an example of what to add:
  the page marks each.
- The goodbye offers to refine the record whenever they want and names
  nothing to add.

## Weekly check-in

One short question: what changed at work since the last one. A fact caught
fresh is an anchor, easy to expand when they next apply; a fact never caught
is lost. It runs when they open it, from their scheduled task or in their
own words. A source they hand over is Onboarding.

- A line from them in answer is enough.
- A skip or "not now" ended it for this chat: nothing written, no second ask.
- Follow-ups took one round, only what the entries need: whose a result is
  and what came of it, where they did not say; their part in a team result; the earlier figure behind a time, cost or rate given only as
  it is now; when it happened, if they did not say; whether an entry that
  looks like a stored result is the same one.
- The week's delivered work and figures are results under their role or a
  stored project they named, never a project made up for them, each with the
  skills its lines name.
- An entry matching a stored result is merged into it, not stored twice.
- A new direction is a goal; an episode worth telling is a story.
- What they skipped or did not know is stored as that result's gap.
- The save had no read-back before it, and its reply asks for no check.
- `lastCheckIn` is today.
- They left a little proud of the week: a couple of minutes, or longer
  because they wanted to talk; short, warm, their work noticed, never a chore.
- At most one open gap of the record was asked, and only when they were
  willing.

## Tailoring

A CV and, when they want one, a cover letter for a job posting: the moment
the record pays off.

### The posting

- The posting, as a link, pasted text or a file, was enough to start.
- The drafts rest on the posting's full text: a link fetched, or the text
  asked for.
- The drafts rest on what was looked up about the company and the kind of
  role.
- The drafts took one round of questions: only what they need and only the
  person can answer. That is what the posting wants that the record does not
  show, nice-to-haves and the job's conditions included (location, office
  days, travel, contract, hours, start date); their reason for applying,
  unless a stored goal gives it for this posting; a story for the key
  requirement, when no stored one fits; their name and contact details, if
  the conversation has none.
- "Leave it out" is final for this posting.

### The CV

- Keeps a normal CV's backbone and every role in the record: older or less
  relevant work shortened, never removed, so twenty years never read as
  five.
- Leads with the results that best match the posting, each under the work
  that produced it.

### The letter

- Is first-person prose that makes the case for this role with the few
  things they did that answer what the posting needs most, not the CV
  retold.
- A story backs the claim the posting cares most about.
- Sets their facts beside what the posting needs and leaves the bridge to the
  reader.
- What their work shows (a skill, a knack, what they know works) and why this
  posting draws them are said only where a stored goal, a story or their
  answer gives it, in its own scope, never widened to the posting's.
- Names the employer in each sentence about earlier work.

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
- They fit the company's language, culture and kind of role, from what was
  looked up. That shapes emphasis and tone, never a claim about the person.
- They read as written by a person for this posting. Good is good enough; a
  stiff, list-like draft fails too.

### After the drafts

- A short note with the drafts says what of the record and their answers was
  used, and what the posting asks that neither holds.
- Whatever is said of a draft, then or in any later turn, is true of its
  latest text read on its own, not of the record or the plan: they send what
  they were told it says without rereading it.
- Each answer they gave to what the posting asked and the record did not
  show, conditions and gaps included, was offered once, each on its own line
  in their words, naming where in their career it goes: the next posting may
  ask the same.
- Their yes covers each line as they read it and nothing drawn from it; the
  save writes those lines and changes nothing else.
