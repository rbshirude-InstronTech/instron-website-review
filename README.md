# Instron Technologies — Website Review (v2.2)

The complete 33-page review website is embedded in one index.html file, including its images, fonts, styles and scripts. Publish this repository root with GitHub Pages; no build step is required. JavaScript must be enabled for page navigation.

The contact page prepares an email draft or copies enquiry text locally. It has no form backend, automatic email sending, CRM integration, analytics or visitor-data storage.

## v2.2 (18 Nov 2026)
Aligned with the current decisions register and the WordPress master build:
- Process Skid Plants presented as the core solution; Industrial Automation and PlantON delivered with skids or on their own.
- Final locations: company offices Toronto and Pune (full addresses), regional presence Calgary, Saskatoon, Mumbai, Riyadh, Voorhout and Monterrey, Australia coming soon.
- Industries regrouped to the agreed five plus Research; Industrial Manufacturing page added.
- Approved proof added: client list, case studies, results, founders and core team, Ontario Made, "Engineering since 2013".
- Internal review notes removed from visitor-facing pages; ITW clarifier in the approved short form; IBM Plex Sans.

## v2.8 (19 Nov 2026)
How We Work: each phase (Basic Engineering & Feasibility, Detailed Engineering, Integrated Design & Build) now has its own section with what it does, best fit, outcome and typical deliverables; menu links land on these sections. Cost estimates named to AACE International classes (Class 4 at feasibility, Class 2 at detailed engineering), no accuracy ranges. Home page phase summaries aligned.

## Review tracker (added 18 Nov 2026)
`review-tracker.html` is the internal review, QA and design-options tracker (linked from the Website Index page). Its shared data lives in `tracker-data.json`: export from the tracker page and upload over this file to publish updates. The page is public on GitHub Pages, so never record passwords, keys, personal data or unfixed security weaknesses in it.

This compact deployment contains the website review only. Management records, approval files and source archives are maintained separately.

## v2.17 (22 Nov 2026): privacy and security baseline
Content-Security-Policy and Referrer-Policy meta tags on every page; draft global privacy notice and "Your privacy rights by region" on the Privacy page (marked draft for legal review); privacy notes beside the contact form and on Careers. The site still sets no cookies and loads no third-party resources. Tracker: new Regional compliance tab (RC-01 to RC-21).

## v2.18 (22 Nov 2026): privacy decisions applied
Responsible entity by region (Inc. for the Americas, Europe and Australia; LLP for India, the Middle East and Southeast Asia); privacy and grievance officer Rahul Shirude, privacy@instrontechnologies.com; retention 24 months for enquiries and 12 months for unsuccessful applicants; cookieless analytics only; French and Spanish notices planned for launch.

## v2.23 (24 Nov 2026): Milind's review
- Privacy, Terms & Accessibility: internal checklists and draft wording removed from the public page; the to-dos are tracker point LEG-08.
- Sitewide: pill buttons and tags; the menu tab of the current page is highlighted.
- Home: shorter hero so the proof strip shows on the first laptop screen; icons on the customer-type tiles; applications as icon cards; Instron Technologies zone drawn inside the TRL chart; project title above the image with Project Portfolio and Case Studies buttons.
- Project Portfolio and Case Studies: title above the image.
- Tracker: MS-01 to MS-13 (Milind's points), CT-20 to CT-22 (accuracy reads), LEG-08.

## v2.24 (24 Nov 2026): round-2 page feedback
- Industries: new hero; stats are 300+ industrial solutions and Engineering since 2013 (Canadian figures moved to the Toronto office card on Global Presence; Portfolio strip updated the same way); industry card lines and CTA description.
- Energy Transition & Critical Minerals and Research & Technology Development: new heroes; Process Skid Plants shown as the core solution with Pilot & Demonstration Plants and Industrial Process Skids inside it, then Industrial Automation and PlantON; Research stakeholder, start and closing sections rewritten; funding wording removed.
- PlantON: hero slideshow of three dashboards (pasteurizer, OEE, loss analysis), OEE in the hero line, loss-analysis image and role icons, connected deployment steps.
- Production Visibility & OEE: new OEE and loss-analysis dashboards (illustrative, sample data) and the downtime calculation.
- Sitewide: PlantON trademark mark larger; FAQ questions with the PlantON wordmark no longer split.
- Tracker: SR-01 to SR-07 (SR-07 is the open Saudi wording decision).

## v2.24.1 (24 Nov 2026)
- Saudi research-university claim now reads "8+ projects with one research university since 2024" (Research & Technology Development, Project Portfolio, Case Studies). Tracker SR-07 closed.
- v2.24.2: wording aligned sitewide to "8+ research projects in Saudi Arabia since 2024", matching Our Company; no "one university" claim.
- v2.24.3: PlantON described as keeping its own database (PlantON page how-it-works, new database card, callout and FAQ; Industrial Automation information layer).

## v2.28 (25 Nov 2026): partners section
- Global Presence & Partners: new "Our partners" section after the company offices, listing BusinessDMX (Mexico), Mafave (Mexico) and Chemponics (Netherlands) by name and country (Rahul, 25 Nov). Logo slots are in place and hidden until logo files arrive (tracker SR3-02). The locations list stays partner-free.
- Sitewide: sales@instrontechnologies.ca replaced by sales@instrontechnologies.com (79 places), matching the 24 Nov decision already applied in the preview build.
- Round-3 page feedback (Sumit, 71 notes): dispositions in project doc claude/sumit-feedback-review-2026-11-25.md; remaining changes not yet applied.

## v2.29 (25 Nov 2026): round-3 page feedback (Sumit, 71 notes)
- Industry pages (Chemicals, Food, Pharma, Manufacturing, plus Energy Transition and Research links): proof strips removed; "Common challenges" headings; Process Skid Plants first with the Core solution badge (Manufacturing shows Industrial Automation and PlantON, with OEE inside PlantON); new recovery and delivery steps; CTA description lines; PlantON in Where to go next; "See all ... projects" links open the matching industry filter.
- Project Portfolio: new industry filter row; solution filter and the 15-card "show more" limit work again (a `display:grid !important` card rule had overridden them).
- How We Work: scoped to Process Skid Plants (Automation and PlantON point to their own delivery steps); phase sub-links removed from the header menu on every page; hero strips removed; five project inputs; compact phase strip; decision at the end of each phase; engagement steps and CTA updated.
- Our Company: company story; three solutions only (Project delivery card removed); four customer groups; "Our engineering philosophy"; founder photos on the people card.
- Leadership: founders shown without titles or degrees (Rahul, 25 Nov); manager degrees removed; Digital and information technology discipline added.
- Global Presence: new H1, "One engineering team, close to your project", international CTA. Trust: credentials-on-request line, assurance CTA. Careers: careers@instrontechnologies.com, discipline names, application checklist, CTA. Insights: new hero and heading, category cards removed.
- Tracker: SR3-03 implemented; SR3-04 to SR3-06 open (ecosystem logos, CSR photos, careers@ mailbox).

## v2.30 (25 Nov 2026): pilot-plant wording (industry advisor feedback)
- Pilot page: title and H1 "Pilot Plants & Demonstration Plants" (menu and breadcrumb keep the short name); new card "Proven in refinery research" in Research and pilot systems, linking to the refinery research pilots case; case label now "Carbon capture and hydrogen pilots for refinery research, India".
- Home: banner sentence and page description say "from pilot plants and demonstration plants to industrial skids".
- Preview build: search titles "Pilot Plants & Process Skid Plants | Instron Technologies" (Home) and "Pilot Plants & Demonstration Plants | Instron Technologies" (pilot page), with matching descriptions and share image.
- Oil & gas industry naming is still a separate open decision.

## v2.35 (26 Nov 2026): design layouts (Sumit's suggestions, approved by Rahul)
- Section layouts from Sumit's "Design Layout Suggestions" (26 Nov), chosen page by page by Rahul in the design review (https://claude.ai/artifact/Ft5h8Azz3pbrxEu3pKUuRD). Layout only: no copy, figures or claims changed.
- Home (11 sections), Process Skid Plants (9), Pilot & Demonstration Plants (3), Industrial Automation (6 changed, project cards kept), PlantON (8), How We Work (4), Project Portfolio (stage rail) and Case Studies (link cards).
- One icon set (Lucide, ISC licence). Page styles in `<style id="instron-v235">` on each changed page; builder: tools/v235_review.py in the preview repo (re-runnable from this repo's committed index.html).
- Preview-only parts (live theme): closing band with photo and green diagonal on every page, footer location chips, IRA start-card tint, and the IRA "Not sure this fits your process?" prompt as a light card (fixes grey text on navy).
- Still to come: About Us pages (Sumit's captures due 27 Nov).
