# Iffa Aulia Hakim — Data Analyst Portfolio

## Publish on GitHub Pages

1. Extract the ZIP and upload its contents to the root of your portfolio repository. Keep the `images/` folder structure intact.
2. Ensure the homepage is named `index.html`.
3. In GitHub, open Settings → Pages → Deploy from a branch → main → / (root).

No build step, package installation, external fonts, or JavaScript is needed. The site uses relative links, so it works for both username.github.io and repository-based Pages URLs.

## Files

- `index.html`: portfolio homepage.
- `style.css`: shared portfolio styles.
- `medical-appointment.html`: visual case study.
- `case-study.css`: case-study layout and mobile styles.
- `images/`: two conceptual illustrations, the original dashboard, and ten standalone charts in SVG and PNG.

## Editing

To add a project, duplicate the project card in `index.html`, copy the case-study HTML, and update the new page's content and card link. Replace the “More insights coming soon” block with your new card. GitHub, LinkedIn, and email contact links are included. The homepage also links to `documents/iffa-aulia-hakim-cv.pdf`; keep the documents folder when uploading, and replace that PDF to update the downloadable CV.

## Data and visual notes

The case study is based on the README, SQL script, and dashboard preview from:
https://github.com/iffaaulia/medical-appointment-no-show-analysis

Original dataset: public healthcare appointment data from Brazil, obtained from Kaggle:
https://www.kaggle.com/datasets/joniarroba/noshowappointments

After cleaning, 110,521 rows remained. Each row represents an appointment, not a unique patient. The cleaned appointment count (110,521) and overall no-show rate (20.19%) come from the published dashboard. The attended share is calculated as 100% minus the reported no-show rate. Lead-time and SMS comparisons are based on dashboard labels and bar heights and are explicitly marked approximate. These charts do not claim a new raw-data calculation or causal effect.

The dashboard screenshot is the original project asset. The two supporting illustrations were created with imagegen for this case study. They are conceptual visuals, not photographs of actual patients or the study setting. The prompts depicted a quiet clinic waiting room and a smartphone reminder beside an appointment card, using a soft lavender, off-white, indigo and coral palette. All website assets are included locally.

The business recommendations describe potential areas for operational investigation; no future-investigation section or chart-values download is included. No development sessions, measured interventions, predictive accuracy, or savings have been invented.

Risk tier definitions follow the existing SQL: high risk at lead time >=8 days; neighbourhood comparisons include at least 100 appointments. The reminder-targeting explanation is identified as requiring validation. Added age and risk-tier values come from supplied screenshots.
