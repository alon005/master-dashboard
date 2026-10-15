# The master dashboard

**One view across four systems, to run a call center, its leads and its money.**

*Showcase page. The code is private because it ran a live business; a walkthrough is available on request.*

---

## What it did

Before we had our own CRM, the business ran on several systems that didn't talk to each other. The master dashboard joined them:

- **Workiz** (our field-service platform at the time), through its API: jobs, technicians, statuses and money.
- **Google Ads:** spend, clicks and conversions by campaign and area.
- **RingCentral VoIP:** every call, line and agent.

Combined in one place, it let us manage and analyse the call center and the leads together: which ads brought calls, which calls became jobs, and which jobs made money.

## Where it led

- The voice agent, Ava, was first built on top of it (see [ava-voice-agent](https://github.com/alon005/ava-voice-agent)).
- When Workiz's API couldn't give us transparent enough data, it led to building our own CRM (see [ava-connects](https://github.com/alon005/ava-connects)).

**Stack:** Google Apps Script · Workiz API · Google Ads · RingCentral API · Google Sheets

— Alon Schneidman · [GitHub](https://github.com/alon005) · [LinkedIn](https://www.linkedin.com/in/alonschneidman)
