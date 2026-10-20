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
4. Document the pattern source and confidence in contacts.md / outreach-log.md before sending.
5. On bounce (especially 550 5.1.1 or inactive): immediately log it and send the next highest-confidence pattern from the research. Do not repeat the failed pattern.
6. Always send from hello@horizontalentgrp.com with includeSignature: true.
7. Parallel LinkedIn outreach when a profile URL is available.

## Stack Notes

- Zoho suite (Mail, Recruit ATS, Invoice, CRM) for low/no-cost operations
- Lean daily outreach cadence while employed full-time
- Always include default signature on outgoing emails
- Bounce and Status Monitor automation checks Zoho and updates data/ files

Last updated: 2026-10-20
