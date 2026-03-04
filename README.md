# Help Amy & the SCA Community — FDA Advocacy Tool

A one-page advocacy website that helps supporters of Amy Messigian send personalized emails to FDA leadership and their elected representatives, urging approval of Troriluzole for Spinocerebellar Ataxia Type 1 (SCA1).

🌐 **Live site:** [Your GitHub Pages URL will appear here after deployment]

---

## What It Does

1. Visitor fills in their name, zip code, and optional personal message
2. Tool automatically looks up their U.S. Senators and House Representative by zip code
3. Click **"✉️ Preview Email"** — their default email app opens with **To, CC, BCC, and Subject pre-filled**
4. The full email body is copied to clipboard — visitor pastes it in and hits Send
5. Every email goes to FDA leadership + the visitor's own representatives

---

## Email Recipients (auto-filled)

| Field | Recipients |
|-------|-----------|
| **To** | commissioner@fda.hhs.gov |
| **CC** | FDA Chief Scientist, CDER Director, and other FDA leadership + visitor's Senators & House Rep |
| **BCC** | eehoops@gmail.com |
| **Subject** | Urgent: Approve Troriluzole with Regulatory Flexibility |

---

## About the Cause

Amy Messigian has Spinocerebellar Ataxia Type 1 (SCA1) — a fatal, progressive neurodegenerative disease with no FDA-approved treatment. She has experienced life-changing results on Troriluzole, yet the FDA issued a Complete Response Letter (rejection) with no clear path to approval.

There is a waiver petition pending that could be approved today.

**Contact Amy:** [email] | [phone number]

---

## Technical Notes

- Pure HTML/CSS/JavaScript — no frameworks, no backend, no dependencies
- Works in any modern browser
- Mobile responsive
- Uses Google Civic Information API for representative lookup
- No server required — can be hosted anywhere as a single file

---

## Files

| File | Description |
|------|-------------|
| `index.html` | The complete advocacy tool |
| `README.md` | This file |
| `FDAplan.md` | Full project plan and development history |
