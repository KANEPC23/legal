# legal
KANE PC Legal and case management app — single-file demo (law.kanepc.com), branded for Hasapidis Law Offices (civil appellate practice, NY & CT).

**Demo only:** firm name, offices and the principal's public contact details come from nyappellateattorneys.com; every matter, party, referring firm, staff member, rate and figure is fictional seed data, DEMO ribbon, no backend. Timer state and
submitted slips persist in the viewer's browser (localStorage) and nowhere else.

## Demo features
- **Matter timer** (topbar, every screen) — start/pause/resume per matter, one
  running at a time, full start/stop log, survives tab switches and reloads,
  rounds up to 0.1 hr and drafts the time slip on stop.
- **Docket** — month calendar, Tasks & Reminders with overdue items requiring a
  disposition, dashboard and Deadlines driven from the same docket data.
- **Matter record** — General, Events (chained deadlines), Inquiry
  (WIP / billed / paid / A/R / trust / budget), Notes.
- **Billing & payment links** — invoices and retainer requests, each tagged
  Operating or IOLA Trust; processing fees never come out of trust (Rule 1.15).
  Demo shows the hosted-checkout preview only: no keys, no card fields, no
  network calls; "Simulate paid" stands in for the processor webhook.
- **Integrations** — Clio, MyCase, LEAP connectors and a ProLaw bridge: consent
  screen with least-privilege scopes, per-object sync direction and system of
  record, sync log with conflict handling, dashboard status card. Simulated in
  the demo; production follows the Kane PC Secure API Integration standard.
- **Appellate deadline calculator** — App. Div. 2d Dept. chains
  (CPLR 5513(a), 2103(b)(2); 22 NYCRR 1250.9(a), (c)); weekend roll-forward.
  Demo rule set — court holidays not applied; verify before reliance.
