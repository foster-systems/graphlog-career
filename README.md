# Graphlog Career

Your career record, kept by your AI assistant. Build it once from your old
CVs and LinkedIn profile, keep it current with a two-minute weekly check-in,
and get a CV and cover letter tailored to every job you apply for, written
from the whole truth of your career. $20 a year
([pricing](https://graphlog.ai/pricing)). More at [graphlog.ai](https://graphlog.ai).

Graphlog Career comes in two parts:

- **The connector** keeps your career record and the job applications you
  send, and gives your assistant the tools to read and update them. It works
  on its own.
- **The skill**, in this repository, tells your assistant what a good
  record, weekly check-in, tailored CV and kept application look like, and
  how to guide you. With it, you get the best out of Graphlog.

## 1. Add Graphlog to Claude

You need a Claude account with code execution on, which skills need:
**Settings → Capabilities → Code execution and file creation**. Then pick the
steps for your plan; it takes about five minutes and no technical knowledge.

### Pro, Max, Team or Enterprise

1. In Claude, open **Customize → Plugins**, click **Add**, then
   **Add marketplace**.
2. Type `foster-systems/graphlog-career` and confirm.
3. Find **Graphlog Career** in the list and click **Install**. Turn on
   **Sync automatically**, so you always have the latest version.
4. Open the plugin's **Connectors** tab and click **Connect** next to
   Graphlog Career.

### Free

1. **Add the connector.** Open
   [this link](https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=Graphlog%20Career&connectorUrl=https%3A%2F%2Fcareer.graphlog.ai%2Fmcp),
   click **Add**, then **Connect**.
2. **Download the skill:**
   [graphlog-career.zip](https://github.com/foster-systems/graphlog-career/releases/download/skill/graphlog-career.zip).
   Keep it zipped.
3. **Add the skill.** Open **Customize → Skills**, click **+**, then
   **Create skill** and **Upload a skill**, and choose the file you
   downloaded.

To update the skill later, download the file again and upload it the same way.

If **Customize → Skills** shows no **+** or no **Upload a skill** on your
plan, skip steps 2 and 3: the connector works on its own, without the skill.

## 2. Sign in

**Connect** opens Graphlog's page. Enter your email address and type the
six-digit code we send you; your first sign-in creates your account. Your
first week is free, with no card. On **You're set**, **Continue to your
assistant** takes you back to Claude.

After the free week, Graphlog Career is $20 a year; we email you the link to
subscribe. Until you do, your assistant can still read and export your record,
but saves nothing new.

## 3. Say "Graphlog"

Open a new chat and say:

> Graphlog

It's the one word to remember. Your assistant shows Graphlog's card: where
your record stands and what to do next. Tap a button to copy its words, then
paste them into your message and send.

The first time, tap **Build my record** and attach what you have to that
message: old CVs, your LinkedIn profile saved as a PDF, performance reviews,
certificates. Your assistant tells you what the record will do for you, reads
everything, and asks about what your documents miss: your results, a story or
two, where you want to go next. It shows you your whole career on one page to
check, and saves only what you agree to. You build it once; every CV after
draws on it.

## Then just ask

In your own words, any time. For example:

- Paste a job posting: **"Tailor my CV for this."**
- After a week at work: **"Here's what happened this week."**
- **"Show my career record."**
- **"I sent the application."** Later: **"Where do my applications stand?"**
- **"Prepare me for my interview at …"**

Not sure what to ask? Say **"Graphlog"**.

## What it runs

The skill is plain text: no code, no scripts. For tailoring, your assistant
opens the job link you give and looks up the company. The
connector is the Graphlog Career server at `https://career.graphlog.ai/mcp`,
which stores your career record in the EU.
It never calls an AI model; your assistant does all the thinking. Read the
[privacy notice](https://graphlog.ai/privacy).

Questions: support@graphlog.ai.
