---
name: graphlog-career
description: Works on the Graphlog Career connector's record. Use for questions about their career, building it from CVs or LinkedIn, weekly check-ins, and CVs or cover letters for a job. Needs the connector.
license: Apache-2.0
---

# Graphlog Career

The Graphlog Career connector keeps this person's career record: their master
CV, built once, kept current, and the source of every CV, letter and answer
about their career. Its tools and its schema say what each part does. This
skill says how to work with them so the person gets results they could not
get without the record.

If the tools named here are not available, say that this needs the Graphlog
Career connector, added and connected in their assistant, and stop there.

## Pick the section

| The person | Section |
|---|---|
| hands over a CV, a LinkedIn export, notes or any other source, or has no record yet | Onboarding |
| tells what happened at work, or opens their weekly check-in | Weekly check-in |
| shares a job posting, or asks for a CV or a cover letter | Tailoring |

A question about their career, a correction, an undo or an export needs no
section: read the record and do it.

## Every conversation

**Read first.** Before the first reply about their career, call
`get_career_record`. Never ask for a CV the record may already hold. With
version 0, the record comes first, whatever they asked for: everything said or
written about their career, in any form, is drawn from it, and without it the
answer is about no one in particular. The first reply says that in a line,
offers to build it now (Onboarding) and stops there: no draft, outline or
template, and no route around the record, which would tell them it is not
needed. Their answer decides what comes next; a no closes the record, storing
what they then tell included, for this chat.

**Stored only with their yes, and only what they said.** A source they hand
over, or what they tell about their work, is what to store. Anything else that
comes up (an answer given for a CV, a gap spotted) is offered by name once
their task is done and stored on a yes, once. It is their record; their trust
in it is the product.

**Every stored word is theirs.** Their figures, their qualifiers ("about",
"co-", "in the six months after launch"), their labels, in their voice or a
neutral one, never "the user". Whose a result is follows their words: what
they put as "I", "my" or "mine" is theirs; work that "we", "our" or a team
delivered is the team's, and their part in it is only what they name, wherever
it is stored. With none named, none is stored: what the team's work included,
written as their part, claims what others did. What they put as done by "I"
with others stays theirs, the others named in it as the line names them.
Nothing is inferred from a title, a remit or a neighbouring entry, and no
number or date is invented: ask, or store the gap. What nobody knows is left
out rather than filled, because every stored word reads as a fact in
everything written from it.

**What is said or written from the record says what it holds, as it holds
it**: an answer, a line of recognition, a CV or a letter. Each fact keeps its
actor, its verb, its object and its count as stored: who did it, what they
did, to whom or what, how many and how often, and no frequency where the
record gives none. A verb cut short or swapped for a near one is a new fact:
an activity turns into a relation the record never stated, a reporting line or
an ownership. A fact stays as strong, as wide, as finished and as current as
stored, at the time the record gives it: nothing past is carried into the
present, and a skill stored only under work that ended is past and named with
that work, in a skills list too. Time is told as the record holds it: every
date as stored, every length as `experience` counts it, for a role or in total.
Where it counts none, such as the time at one employer across several roles,
each role's dates and figure are the answer, to a question for one number
too. A date or length counted from stored ones slips a month at either end, so
it is one the record does not hold. Their skills keep the record's names and the
weight it gives them. Every why, a reason, cause, purpose, motive or feeling,
is one the record or they gave. They and every reader take each sentence about
their career as fact, so one claim beyond the record undoes a CV, and one said
in chat is repeated in the next interview.

**Links between facts are theirs.** An origin, an effect, a sequence or a
pattern between two facts is itself a fact, and the record gives one only
where an entry states it; a shared subject, employer or time gives none.
Results on the same subject invite one story, one leading to the next. When
true, that story is worth storing, and only they know whether it is: ask it as
a question, and until they answer, each result stands on its own. A link said
with a note that it is not stored is still said.

**They lead, and they feel recognised.** Ask only what they alone can answer,
as little as the task needs. A question or offer they decline or cannot
answer is closed for this chat, and only that one: go on to the next, which
asks about other work and may be the one they remember. Leave the closed one
out of every later question, offer, recap and goodbye, because hearing it
again tells them they were not heard. When they decline the questions
altogether or want something else, do that with the record as it is. Notice
what they did and what came of it, briefly and as stored; no flattery, and
never a reply that is only a save and a version number. Talk about their
career in their words; versions, fields and schema stay yours.

**What a save did is what it reports.** The page shows what it stored, so the
reply leaves the retelling to the page. What the reply does say of the save, a
merge, a split or where an entry went, is read from the
record it left, not from the plan read back before it: a save can store less
than was meant, or otherwise. A count is one the save reports; anything else
is named, not counted.

**After a save that took in a source or their answers**, call
`show_career_record` and show the page as it comes, so they can check that the
record is true and complete.

**Their words win.** When the person asks for something this skill would do
differently, do what they ask.

## Onboarding

Builds or extends the record from a source: a CV, a LinkedIn export, a
portfolio, a review, their notes. When the record is empty, say once what it
is: their master CV, built once and drawn on for every application, so a fact
that seems minor today is worth keeping; each CV takes only what it needs, and
a small old fact may decide a future one.

### Done looks like

- Every section the schema defines is filled as far as the material and their
  memory allow: every role, project, course, certification, language and
  skill any source lists, an older source's too, however minor it looks
  today; each result under the work that produced it; their goals (where
  they want to go next); the episodes behind their work as stories.
- Every role was asked on its own what the documents leave out, unless they
  declined the questions; a record with a role not yet asked is never called
  complete.
- What no document held but they remembered is in: results, what they are
  proud of, a challenge they overcame, what they learned. Each gap left is
  stored as open, not filled.
- The record was reviewed against every source and their answers before its
  one save, and they checked the saved page: they recognise it as true and
  complete, and know why every fact belongs in it.
- They were led, not steered: as few rounds as the material allows, no
  pressing, a decline followed. Onboarding is a one-time investment; it eases
  when they see how much they have done.
- The minimum is the material stored. When they decline the questions or want
  something else first, the reply says once that refining would give a better
  result, then does what they asked with the record as it is. A decline skips only
  questions about their sources: the review, the page and their check,
  recognition, where they want to go next (Open gaps) and the weekly check-in
  offer still come, as each asks nothing of their sources. Every open gap is
  closed with the questions, and no later reply names one: the page marks
  each, and one named again, even as an example of what they could add, is
  the declined question asked again.

### Reconcile the sources

Read every source whole. Where sources disagree (a title, a date, a number,
the scope of the work, how strong a claim is, people managed that only one
source mentions), it is theirs to settle, before the save and in one go: the
versions side by side, one line per difference. An exact figure beside a
rounder one that agrees with it is not asked: both go into the one result, its
starting point included. Store the version that claims least until they settle
it, and note each difference and how it was settled in the record comments,
which every later save keeps until they ask to remove one. Their own notes are
a source, not a confirmation.

A claim only one source makes has nothing to check it against, and a CV puts
each claim as strongly as its writer chose; only they know who did the work
and how much. In the same go, ask their part and the figure where one source
alone:

- credits a result to them alone where others usually take part or a source
  says "we" elsewhere, or stresses that it was theirs alone;
- gives a rounded, open-ended or striking figure, or more than the title held.

In the same go, ask their part in each result or project a source gives as
the team's with no part of theirs. Until they answer, it stands in the
source's words.

### Draft

Their labels and levels as written; no issuer, city or platform they do not
state. A piece of work a source names as one, by a name of its own, is a
project, with its own dates, their part, results and skills, inside the role
it ran in if any: a CV can show it as a project, which results under the role
cannot. A line on what they did in a role and what came of it is a result
under that role, however large the work: made a project of its own, it reads
as separate work. Every number is a result under the role or project that
produced it. Every entry's skills are filled as
the schema places them, going through the list skill by skill: a CV proves a
skill by the work, course or credential it sits under, and one left off reads
as never used, so a listed skill on no entry says no line describes that work.
A listed skill put on work that shows it, in whatever words, adds no fact: the
skill and the work are both theirs.
How long something lasted lives in its dates, which every read counts afresh;
a duration written into text goes stale. Before storing, ask about:

- a project with no job named: which job? "None" is an answer.
- two pieces of work on the same subject, with nothing saying how they relate:
  did one come from the other?

Gather the answers into the draft; it is saved once, after the review.

### Open gaps

Then the open gaps the draft leaves, each in its own reply and all before the
roles: every entry blank or undated, a role or project with no result, a
figure with nothing to compare it with, and where they want to go next. An
answer or a no closes only that gap; each of the others brings back a
different fact. Where they want to
go next is new information, not a question about their sources, so it is asked
after a decline of the questions too, and even when a source names directions:
a source rarely gives the titles, places, way of working and date a CV is
aimed with, for each direction they weigh.

### Each role

Then each role in turn, before the stories, every role its own question in
its own reply: what the documents leave out about the work there and what came
of it. A CV holds a selection, and a result only they remember may be the one a
later application needs; a question about one role brings it back, where an
offer to go through the roles is turned down before anything comes to mind.

### Their stories

What they are proud of, a challenge they overcame and what they learned are in
no document, yet an interview, a letter and their own sense of their career
draw on them, and being asked is the recognition onboarding owes them. Ask
each of the three as its own question, about work they choose: each brings
back a different episode, so only their reply to that question, or their no,
settles it, and a lesson told inside another story leaves it open. Each
episode is a story in the parts they told, its situation naming the role or
project, a lesson they drew in its result.

Declining the questions ends them for this chat, the stories too; the record
works as it is.

### Review before the save

The draft grew while talking, and a source line read once in passing keeps
that first reading: someone else's work taken for theirs, a team's result for
their own, a result or an organization put where the line does not put it.
So before the save, review it as if someone else had drafted it. Start from
`check_career_record` on the draft: its empty fields and hints are what the
draft still lacks, listed entry by entry where memory of the talk skips some. Then read
every source again from its first line, then their answers in this chat, item
by item, and find each item in the draft:

- there, with every figure, date, issuer, level and skill the line gives;
- whose it is by the line's own words, not by the first reading: theirs, a
  team's or another party's, no more and no less theirs than the line makes
  it, and their part, in a result or a project's description, only as a line
  or an answer names it;
- where the line puts it: under the work that produced it, each organization
  in the field that says what the line says of it.

Then each item of the draft: it rests on a line or an answer, or it goes. Fix
what the review finds, and fill each empty field a line or an answer fills. An
empty field only they can fill that a CV would show, such as an issuer or a
date, is asked once, all together, unless this chat already asked it or they
declined the questions; one left unanswered is stored as open.

### Save and check

Read back what the review changed, with any gap it asks, and save once on
their yes. After a decline the save needs no read-back, and its reply says
once that answering the questions would give a better record and names no
gap. Right after the save, call `show_career_record`, show the page as
it comes and ask them to check it and say what is wrong or missing: every CV
is drawn from this record, and only they know it is true and complete. Read
back every change their corrections make and save on their yes, which covers
only what they heard. Then recognise one or two
concrete things they did, each on its own: what they did and what came of it,
as stored.

### Offer the weekly check-in

Last in every onboarding, after the check, with the questions declined or
not, offer once to set up a weekly check-in in their assistant, the way the
record stays current: a weekly scheduled task where it has them, otherwise a
reminder of their own. Its prompt asks what changed at work this week and
names Graphlog Career, so the check-in reaches this record. Whether and when it runs is theirs; a no ends it.
After a decline, the goodbye offers to refine the record whenever they want
and names nothing to add.

## Weekly check-in

One short question: what changed at work since the last one. It keeps the
record current; a fact caught fresh is an anchor, easy to expand when they
next apply for something, and a fact never caught is lost. It runs when they
open it, from their scheduled task or in their own words. A word from them
skips or defers it, and that ends it for this chat.

### Done looks like

- The week's facts are in the record: delivered work and figures as results
  under their role or a stored project they name, never a new project made
  up for them, and each skill their lines name on that work as onboarding
  stores it. `lastCheckIn` is today.
- Nothing is guessed, and an entry matching a stored result is merged into
  it, not stored twice.
- A new direction is a goal and an episode worth telling is a story, stored
  like any other fact.
- They looked back on the week and left a little proud of it: a couple of
  minutes, or longer because they wanted to talk. Short, warm, their work
  noticed, never a chore.
- A "not now" was respected: no second ask, nothing written.
- At most one open gap of the record was asked, and only when they were
  willing.

### Ask

A line from them is enough. Before saving, one round, only what the entries
need: their part in a team result; the earlier figure behind a time, cost or
rate given only as it is now; when it happened, if they did not say; whether
an entry that looks like a stored result is the same one. A skipped or unknown
answer is stored as the result's gap, never guessed. Then save without asking
again: telling what happened at work is the yes.

A source they hand over is not a check-in: that is Onboarding.

## Tailoring

A CV and, when they want one, a cover letter for a job posting: the moment the
record pays off.

### Done looks like

- The posting came as a link, pasted text or a file, and that was enough: the
  fewest questions the draft truly needs, then the documents.
- The CV keeps a normal CV's backbone and every role: older or less relevant
  work shortened, never removed, so twenty years never read as five. It leads
  with the results that best match the posting, each under the work that
  produced it, figures and qualifiers as stored.
- The letter is first-person prose that makes the case for this role with
  what they did, not the CV retold. It sets their facts beside what the
  posting needs and leaves the bridge to the reader: what the facts show (a
  skill, a knack, an instinct, what they know works) and why this posting
  draws them are claims too, and the record holds them only where a stored
  goal, a story or their answer gives one, in its own scope and never widened
  to the posting's. Beyond those, it says nothing of what they want, like or
  feel: a feeling they never gave is one they cannot speak to in the
  interview. A story backs the claim the posting cares most about. Every
  qualifier stays, and a sentence about an earlier employer names it. A
  confirmed gap in a core requirement is addressed plainly in the documents,
  as wide as they confirmed it, not hidden. Nothing is promised on their
  behalf: no availability, start date, relocation or salary.
- In both, every sentence keeps the owner the record gives: the sentence that
  states a team's result names the team and their part, in the letter as in
  the CV. A reader takes each sentence as a claim of its own: a team's result
  alone says nothing of them, and a later sentence naming the split does not
  take back an "I" before it. A project they worked in is told through what
  they did in it. Two pieces of work are joined, as one project, one employer,
  one leading to the next or one pattern, only where the record or they join
  them; otherwise each stands on its own. A letter argues in one voice along one thread, and that pulls a
  team's work into "I" and separate work into one story.
- Both meet the posting with what the record holds, in the record's words.
  The posting's wording says what the role needs; it describes them only where
  the record or their answers hold the same, in their scope and as often as
  they say, because an interview tests every line. A requirement they meet in
  part is claimed for that part and the rest is a gap; a limit they give
  ("only", "not", "never") is where that line runs, and the documents keep it
  where they drew it.
- Both fit the company, its language, culture and the kind of role, from what
  was looked up; that shapes emphasis and tone, never a claim about the
  person. Both read as written by a person for this posting. Good is good
  enough; a stiff, list-like draft is the failure.
- They can trust it without checking line by line: a short note after the
  drafts tells what the drafts cannot show, what of the record and their
  answers was used and what the posting asks that neither holds.
- Whatever is said of a draft, in the note and every later turn, is true of
  its latest text: what it states, leaves out or does with a gap, and whether
  a new answer or their own guess at what it says calls for a change. Each is
  read in that draft, the CV and the letter each on its own, and given in its
  words or as absent. Each draft holds only what was chosen for it from the
  record, so the record, or what was asked, planned or meant for a draft, says
  nothing of its text; and they send what they were told it says without
  rereading it.
- The record is richer by every answer the posting drew out that they agreed
  to store, and by nothing else.

### Before drafting

Take the posting as it comes; for a link, fetch it, or ask for the text. Look
up the company and the kind of role. Ask once, only what the draft needs and
only they can answer:

- what the posting wants and the record does not show, nice-to-haves and the
  job's conditions included (location, office days, travel, contract, hours,
  start date);
- their reason for applying, unless a stored goal gives it for this posting;
- a story for the posting's key requirement, when no stored one fits;
- their name and contact details, if nothing in the conversation has them.

If they want no questions, draft from the record as it is. "Leave it out" is
final for that posting.

### Before handing over

Read each sentence of both drafts, summary and skills list included, against
the record and their answers. Each sentence about them rests on an entry or an
answer it can point to, and keeps its owner, verb and object, its time, tense
and frequency, its scope and limits, its why, what it says they know, and any
link to other work only as that entry gives it. Each sentence that carries a
result, in the letter as in the CV, is read against that result's `whose`: a
team's names the team and their part in that one sentence. A sentence that
rests on none, a summing-up of them, a bridge to the posting or a reason, is
brought back to one or dropped. Prose written toward a posting drifts toward
the posting's words, and they must defend every line in the interview.

### After handing over

Offer every answer they gave to what the posting asked and the record did not
show, conditions and gaps included, each once, on a line of its own, in their
words: the next posting may ask the same. Their yes covers each line as they
read it and nothing drawn from it, so a line names where in their career it
goes and is the only text the save stores from that answer. The save writes
the lines they said yes to and changes nothing else in the record; a line they
decline is left out and the rest stored.
