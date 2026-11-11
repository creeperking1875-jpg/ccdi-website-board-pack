# CCDI Website - Decision Log

Every decision behind ccdilab.com and its posting rules, with the reasoning and when it was made. All decisions are Matthew's unless noted. Compiled November 11, 2026.

## Decisions

### 1. No prices on the website
Source: CCDI Marketing Strategy node (governing principle, confirmed Oct 26, 2026).

- Competitor labs phone in to harvest CCDI's prices and undercut them. Public pricing arms them.
- Competing on price is indefensible: anyone can claim "lower," and it commoditizes the lab.
- Medical buying runs on trust, so CCDI markets on education, speed (no long lines, same-day), care, and legitimacy (DOH-accredited, established Cebu lab).
- Price is given on contact, never broadcast. Walk-ins get "message us / walk in"; corporate gets "book a consult."

Implementation (approved Oct 29, 2026): a /price-list request form. The visitor leaves their details and consents to follow-up; the price list is emailed to them. Rates never appear on the public page. A separate, unticked box covers newsletter/promo consent, and the list is still sent without it. The list itself carries "Updated as of [date]" and "Prices are subject to change." Corporate and client-specific rates never go in the general list.

### 2. Equal doors, split funnel (Oct 26, 2026)
Walk-in patients and corporate HR teams get equal weight on the site. "Visit Us" sits beside "For HR Teams." The corporate filter happens at the CTA (the Book Call button), not by hiding either audience.

### 3. Call-first, low friction (Oct 26, 2026)
The goal is the phone ringing, not a booking app. Bookable corporate call slots are deliberately scarce.

### 4. Corporate intake rework (Oct 26, 2026)
Two paths: "Book call now" (pick a slot) and "Book period call" (leave info plus a preferred period, CCDI calls back). Richer intake questions (service needed, timing, openness to multi-year) so calls are not empty. Plus an FAQ covering fasting, what to bring, results timing, and HMO.

### 5. What public content may say (Oct 31, 2026)
- IN: services, operations, years in operation, services for company clients.
- OUT: anything monetary, anything backend or management-internal.
- Unconfirmed claims stay out (example: DOLE compliance, because it is not confirmed yet). Test prep and results timing are not stated as fact until confirmed.
- Never imply the doctors on site are CCDI staff, and never share their schedules.

### 6. Language and tone (Nov 6, 2026)
Customers often write in Visaya/Cebuano or mixed language. The chat assistant must understand without forcing English. Tone: friendly, clear, plain language for patients and company HR.

### 7. Website chat assistant (Oct 31 - Nov 9, 2026)
"CCDI Chat Assistant" runs in GoHighLevel in suggestive mode: it drafts replies and staff approve them. It is fed by a separate CCDI-only knowledge repo, kept read-only, with no patient data and no internal files reachable. Safeguards: no diagnosing, no invented prices or turnaround times, no booking promises.

### 8. SEO and AI visibility (Oct 29-30, 2026)
Published: new homepage title ("CCDI Lab | Diagnostic Laboratory & Medical Clinic in Consolacion, Cebu"), per-route metadata, sitemap.xml, robots.txt, llms.txt, and a MedicalClinic JSON-LD block. Approved: a homepage intro naming "CCDI Lab (Consolacion Community Doctors, Inc.)" under the H1. An ai-catalog.json file is saved but not yet published.

### 9. Photography
The photo placeholder was a deliberate honest call. Real commissioned clinic photography is the top backlog item.

## Still undecided (waiting on Matthew)

- Whether the employer names on the "Trusted by Cebu Employers" section stay public, given the partner-names-confidential rule.
- Book Call availability: November currently shows zero open days; intended or not.
- Rate confirmation for the price list, the scope of the student package offer, and thyroid test availability.
- How the chat assistant reads the knowledge repo (not yet connected).
- Wording of the "24-48 hr results" claim and accreditation wording.
- Whether form contacts are saving to GoHighLevel, and confirmation emails.
