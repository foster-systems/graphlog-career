# Graphlog Career

Your career record, kept by your AI assistant. Build it once from your old
CVs and LinkedIn profile, keep it current with a two-minute weekly check-in,
and get a CV and cover letter tailored to every job you apply for, written
from the whole truth of your career. $29 a year
([pricing](https://graphlog.ai/pricing)). More at [graphlog.ai](https://graphlog.ai).

Graphlog Career comes in two parts:

- **The connector** keeps your career record and the job applications you
  send, and gives your assistant the tools to read and update them. It works
  on its own.
- **The skill**, in this repository, tells your assistant what a good
  record, weekly check-in, tailored CV and kept application look like, and
  how to guide you. With it, you get the best out of Graphlog.

## 1. Add Graphlog to Claude

<details name="plan" open>
<summary>Pro, Max or Ultra</summary>

1. In Claude, open **Customize → Plugins**, click **Add**, then
   **Add marketplace**, and enter `foster-systems/graphlog-career`.
2. Select **Graphlog Career** and click **Add**. Turn on
   **Sync automatically** for the marketplace to get every update.
3. On its **Connectors** tab, add Graphlog Career and **Connect**. Sign in
   with your email address and the code we send you.

</details>

<details name="plan">
<summary>Free</summary>

1. Open [this link](https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=Graphlog%20Career&connectorUrl=https%3A%2F%2Fcareer.graphlog.ai%2Fmcp),
   click **Add**, then **Connect**. Sign in with your email address and the
   code we send you.
2. Download
   [graphlog-career.zip](https://github.com/foster-systems/graphlog-career/releases/download/skill/graphlog-career.zip).
   Keep it zipped.
3. Open **Customize → Skills**, click **+**, then **Create skill** and
   **Upload a skill**, and choose the file.

</details>

<details name="plan">
<summary>Team or Enterprise</summary>

1. An owner of your organization adds the connector first:
   **Organization settings → Connectors**, **Add**, **Custom**, **Web**, with
   the URL [https://career.graphlog.ai/mcp](https://career.graphlog.ai/mcp).
2. In Claude, open **Customize → Plugins**, click **Add**, then
   **Add marketplace**, and enter `foster-systems/graphlog-career`. No
   **Add marketplace**? Ask the owner to add it in
   **Organization settings → Plugins & skills** and make Graphlog Career
   available to members.
3. Select **Graphlog Career** and click **Add**. If you added the
   marketplace, turn on **Sync automatically** for it.
4. On its **Connectors** tab, **Connect** Graphlog Career. Sign in with your
   email address and the code we send you.

</details>

Your first week is free, with no card. Then $29 a year.

## 2. Say "Graphlog"

Open a new chat and say:

> Graphlog

It wakes Graphlog up: your assistant shows its home, where your record
stands and a choice of what to do next.

## What it runs

The skill is plain text: no code, no scripts. For tailoring, your assistant
opens the job link you give and looks up the company. The
connector is the Graphlog Career server at `https://career.graphlog.ai/mcp`,
which stores your career record in the EU.
It never calls an AI model; your assistant does all the thinking. Read the
[privacy notice](https://graphlog.ai/privacy).

Questions: support@graphlog.ai.
