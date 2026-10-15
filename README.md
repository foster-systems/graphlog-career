# Graphlog Career

Your career record, kept by your AI assistant. Build it once from your old
CVs and LinkedIn profile, keep it current with a two-minute weekly check-in,
and get a CV and cover letter tailored to every job you apply for, written
from the whole truth of your career. $20 a year
([pricing](https://graphlog.ai/pricing)). More at [graphlog.ai](https://graphlog.ai).

Graphlog Career comes in two parts:

- **The connector** keeps your career record and gives your assistant the
  tools to read and update it. It works on its own.
- **The skill**, in this repository, teaches your assistant how to use those
  tools well: how to build your record, run your weekly check-in and tailor
  your CV. With it, you get the best out of Graphlog.

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

## Start

A new account needs a subscription first: your assistant's first answer gives
you the link to subscribe. Pay at Link's checkout, then carry on.

In a new chat, attach your CVs or LinkedIn profile and say
**"Create my career record."** Your assistant asks a few questions, stores
nothing without your yes, and shows you your whole career on one page.

Then, any time: paste a job posting and say **"Tailor my CV for this."**

## What it runs

The skill is plain-text instructions: no code, no scripts. For tailoring it
has your assistant open the job link you give and look up the company. The
connector is the Graphlog Career server at `https://career.graphlog.ai/mcp`,
which stores your career record in the EU.
It never calls an AI model; your assistant does all the thinking. Read the
[privacy notice](https://graphlog.ai/privacy).

Questions: support@graphlog.ai.
