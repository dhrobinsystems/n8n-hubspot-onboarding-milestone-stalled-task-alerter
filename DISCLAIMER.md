# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-hubspot-onboarding-milestone-stalled-task-alerter`) are provided for educational and architectural demonstration purposes.

## No Liability

The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. This includes, without limitation, missed, late, duplicated or incorrect alerts; overdue or at-risk onboarding tasks that were not flagged; tasks flagged without reason; delayed go-lives, missed contractual or service commitments, client dissatisfaction or churn; incorrect or overwritten HubSpot custom object properties; disclosure of client project information in Slack or other channels; disputes arising from the use of alerts to assess staff; exposure of tokens or webhook URLs; service interruptions; and API rate-limit or quota exhaustion.

## No Warranty

All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement.

No warranty is given that delay calculations, grace periods, weekend handling, severity tiers or staleness detection match your onboarding plans, contracts or working calendars; that completed, client-blocked or test records are always recognised; that PM routing reaches the right person; that cooldowns prevent every duplicate alert; that HubSpot custom object schemas, search, association or batch update responses remain compatible with this workflow; or that Slack and webhook deliveries succeed.

## Production Testing Required

Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, with `SANDBOX_MODE=true`, `DRY_RUN=true`, `SEND_SLACK_ALERTS=false` and `WRITE_TO_HUBSPOT=false` enabled, before you connect live HubSpot or Slack credentials. Map your object type, properties and status values, review the dry-run audit for every alert and every skipped record, send alerts to a test channel first, and confirm that write-back properties and option values exist before enabling `WRITE_TO_HUBSPOT`.

Treat every severity tier as a prompt for a project manager to check the task. It is not a verdict on a client, a deliverable or a colleague, and it must not be used on its own to evaluate employee performance or to take action against a client.

## Third-Party APIs & Compliance

You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA and equivalents), employment and works-council requirements, contractual confidentiality obligations, and security policies of HubSpot, Slack, your webhook receiver and any connected services. That includes:

- granting the private app only the scopes listed in the README;
- restricting the Slack channels that receive client names and project status;
- confirming that automated monitoring of task timeliness is permitted by your employment and internal policies;
- keeping client contact details out of alerts unless there is a clear need;
- securing, rotating and restricting access to the HubSpot token, Slack webhook URLs and alert webhook token;
- limiting access to n8n execution data and applying a retention period that matches your policies;
- reviewing every automatically updated record.

## No Affiliation

HubSpot, Slack and n8n are trademarks of their respective owners. This project is independent and is not affiliated with, endorsed by, or sponsored by any of them. All object types, record IDs, companies, people, email addresses, owner IDs and Slack member IDs in the fixtures, sample payloads and pinned data are fictitious.

## Not Professional Advice

Nothing in this repository constitutes legal, employment, privacy, security, or financial advice. Consult qualified professionals for your specific circumstances.

---

Released under the MIT License. Copyright (c) 2026 DH Robin (dhRobin Systems). See [LICENSE](LICENSE).

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 dhRobin Systems · Provided as-is, see the disclaimer.
