# Courseware QA report

Course: Generative AI for Script Development and Storytelling (`TGS-2025056983`)
Version: `v2.0`
QA date: 19 September 2026

## Overall verdict

PASS after one fix-and-rerender cycle.

## A. PPT quality audit — PASS

- 222 slides for a 2-day / 16-hour course; the 200-slide minimum is met.
- 200 instructional slides carry explicit technical anchors in `build/slide_map.csv`; zero unanchored instructional slides.
- Native editable charts: 15. Generated course visuals: 3 source images used on the cover and topic dividers.
- 222/222 slides contain transitions; zero shapes extend past the slide bottom.
- Mean 21.3 shapes/slide; median 23; mechanism units vary among process, timeline, storyboard-grid, comparison, evidence and chart layouts.
- Separate visual trainer-template and Dr Alfred Ang profile slides are present.
- Download Course Material slide contains a visible, clickable LMS-TMS URL.
- Assessment Flow is a diagram. The Practice Exam slide links to the current Tertiary Exams portal and states that learners should use the matching course exam when available; no course-specific `TGS-2025056983` exam is currently published there.
- Cover contains one version label (`v2.0`), the correct title/code, provider and UEN.
- Full-slide PDF render inspected in five contact sheets before remediation and a 222-slide contact sheet after remediation; no overlap, clipping or missing-slide defect remained.

## B. Assessment audit — PASS

| Instrument | Count | Timing | Coverage | Result |
|---|---:|---:|---|---|
| WA / SAQ | 10 open-ended questions | 60 min | K1–K10 | PASS |
| PP | 3 practical tasks | 60 min | A1–A9 | PASS |

- Instrument types, counts, mappings and timings match the version-1 papers recovered from the verified Drive folder.
- Each of the four DOCX files has the correct WSQ cover. Question-paper page 2 contains only trainee information, instructions, the clickable LMS link, and grading/sign-off; questions start on page 3.
- Answer keys repeat the same codes. PP model evidence provides the detailed lab procedure and acceptance evidence for all three tasks.
- Explicit pagination: one answer per answer-key page; no question/box or answer table split in the rendered PDFs.
- Only the two question papers are eligible for learner publication. Both answer keys remain local/trainer-only and are ignored by Git.

## C. Lesson Plan — PASS

- Correct WSQ cover, visible version history (`v1.0` then `v2.0`), TOC field, Arial body, and Page X of Y footer.
- Topic tables use the current slide ranges: 10–49, 52–91, 94–133, 136–175, and 178–217.
- Tables were separated by topic with explicit page breaks; the final six-page render has no orphan continuation rows or clipping.
- Day totals are 8 hours each; assessment timings are WA 60 minutes and PP 60 minutes.

## D. Learner Guide — PASS

- Correct WSQ cover, visible version history, Word TOC field plus a visible static topic/lab contents list, Arial body, and Page X of Y footer.
- Eighteen-page render inspected with no clipping or broken layout.
- All ten labs include detailed numbered procedures in the LG; each lab adds three task-specific production steps on top of preparation, generation, revision, review, rights/provenance and human-approval steps.
- The Markdown mirror and DOCX are produced from the same source data.

## E. Labs and alignment — PASS

- Ten lab folders; each includes `README.md/.pdf`, `prompts.md/.pdf`, evidence template, continuity and rights CSVs, and unique story brief, character cards and scene slate in both Markdown and PDF.
- Each PP ability maps to the lab procedure used in class. Nothing in the assessment sits outside the slide/LG/lab scope.

## F. Files, privacy and distribution — PASS

- One live `v2.0` courseware version; PPTX/PDF, LG DOCX/PDF/Markdown, and LP DOCX/PDF are present.
- Assessment, reference ebooks, `.env`, `.claude`, build QA, assets and answer keys are excluded from GitHub by `.gitignore`.
- Secret scan over candidate public files returned no credential or private-key matches.
- Fresh assessment and courseware renders match the distributed PDFs inspected in this pass.

## Assessment coverage map

| Code | Question/task | Taught in |
|---|---|---|
| K1 | WA Q1 | Slides 10–49; Labs 01–02 |
| K10 | WA Q2 | Slides 52–91 and 148–151; Labs 03 and 07 |
| K2 | WA Q3 | Slides 178–217; Labs 09–10 |
| K3 | WA Q4 | Slides 68–71 and 110–113; Labs 03–07 |
| K4 | WA Q5 | Slides 136–143; Lab 07 |
| K5 | WA Q6 | Slides 190–197; Lab 09 |
| K6 | WA Q7 | Slides 102–117 and 46–49; Labs 05–06 |
| K7 | WA Q8 | Slides 152–175; Labs 07–08 |
| K8 | WA Q9 | Slides 94–113; Lab 05 |
| K9 | WA Q10 | Slides 52–83; Labs 03–04 |
| A3, A4, A5, A7 | PP Task 1 | Labs 01–03 and 06 |
| A2, A6, A8 | PP Task 2 | Labs 03–04 |
| A1, A9 | PP Task 3 | Labs 07–10 |
