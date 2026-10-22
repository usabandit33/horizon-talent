# Horizon Talent Group

Permanent placement recruiting agency focused on vertical SaaS sales roles (construction tech, field service, logistics, proptech). Contingency model preferred.

## Overview

This repository tracks researched target companies, key contacts, hiring signals, and outreach status for the Horizon Talent Group (hello@horizontalentgrp.com).

## Structure

- `companies.md` - Target company list with vertical and notes
- `contacts.md` - Key contacts with LinkedIn, likely emails, and titles
- `outreach-log.md` - Outreach attempts, delivery status, and next steps
- `data/companies-contacts.json` and `data/contacts.csv` - Structured tracking for automation

## Email Pattern Protocol (to prevent bounces)

1. Always research company email format percentages first (RocketReach, Prospeo, ContactOut, SignalHire) before guessing.
2. Prefer the highest-percentage pattern (most common is often first_initial + last, e.g. ctzortzis@domain.com). Avoid defaulting to first.last unless data supports it.
3. If direct pattern confidence is medium or lower, start with a verified public address (info@, jobs@, sales@, talent@, careers@) and address the named contact. This reduces permanent bounces.
4. After any permanent bounce on a name pattern (550 5.1.1, 5.2.1, 5.4.1 or inactive), immediately switch to the verified public set in this priority order: sales@ → talent@ → careers@ → jobs@ → info@. Address the named contact in the body. Do not treat public inboxes as optional.
5. Document the pattern source and confidence in contacts.md / outreach-log.md before sending.
6. On bounce: log it the same day and send the next highest-confidence pattern (or next public address). Never repeat a failed address.
7. Always send from hello@horizontalentgrp.com with includeSignature: true and mailFormat html.
8. Parallel LinkedIn outreach when a profile URL is available.

## Stack Notes

- Zoho suite (Mail, Recruit ATS, Invoice, CRM) for low/no-cost operations
- Lean daily outreach cadence while employed full-time
- Always include default signature on outgoing emails
- Bounce and Status Monitor automation checks Zoho and updates data/ files

## Recent Updates

2026-10-22: Strengthened Email Pattern Protocol so public inboxes (talent@, careers@, jobs@) become mandatory after any permanent name bounce. Added Public Inbox Priority section to contacts.md for all companies that have already seen name failures.

2026-10-20: Added Linarc, Fleetio, Bringg, Altana, Afresh, WorkWave, EverPro, Clue Insights, Kargo with contacts, public emails, and best-guess patterns for scheduling.

Last updated: 2026-10-22
