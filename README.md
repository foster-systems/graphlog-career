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
  record, weekly check-in, tailored CV and kept application look like. With it, you get the
  best out of Graphlog.

## Install in Claude

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
   Graphlog Career. A page opens: enter your email address and type the
   six-digit code we send you. Your first sign-in creates your account.

### Free

1. **Add the connector.** Open
   [this link](https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=Graphlog%20Career&connectorUrl=https%3A%2F%2Fcareer.graphlog.ai%2Fmcp),
   click **Add**, then **Connect**, and sign in with your email address and
   the six-digit code we send you.
2. **Download the skill:**
   [graphlog-career.zip](https://github.com/foster-systems/graphlog-career/releases/download/skill/graphlog-career.zip).
   Keep it zipped.
3. **Add the skill.** Open **Customize → Skills**, click **+**, then
   **Create skill** and **Upload a skill**, and choose the file you
   downloaded.

To update the skill later, download the file again and upload it the same way.

If **Customize → Skills** shows no **+** or no **Upload a skill** on your
plan, skip steps 2 and 3: the connector works on its own, without the skill.

## Start

A new account subscribes while connecting: after your email code, **Continue
to payment**, pay at Link's checkout, then **You're set**. A free code, if you
were given one, goes in its field on the first page instead.

In a new chat, attach your CVs or LinkedIn profile and say
**"Create my career record."** Your assistant builds it with you, stores
only what you gave or agreed to, and shows you your whole career on one page.

Then, any time: paste a job posting and say **"Tailor my CV for this."**

## What it runs

The skill is plain text: no code, no scripts. For tailoring, your assistant
opens the job link you give and looks up the company. The
connector is the Graphlog Career server at `https://career.graphlog.ai/mcp`,
which stores your career record in the EU.
It never calls an AI model; your assistant does all the thinking. Read the
[privacy notice](https://graphlog.ai/privacy).

Questions: support@graphlog.ai.
