# Portfolio refresh notes

## Approval workflow

- Before making any code, content, configuration, or other repository changes, summarize the planned actions and wait for the user's explicit approval.
- Do not begin implementation until that approval has been received.

## Approved repository changes

- Ignore PDF files so personal source documents, including the local CV, are never committed or deployed.
- Replace the placeholder homepage with a minimal, text-led professional profile.
- Use CV-derived public email, LinkedIn, GitHub, Google Scholar, and a concise experience summary. Present these contact paths as clickable, accessible icons in a horizontal row below the profile portrait. Use the approved headline: “Machine Learning Engineer · Applied Scientist · Data Scientist.”
- Exclude the phone number, CV download, project repository links, and live project links. Include the full experience and education histories, plus the CV-listed publications. Add publication URLs only when they are present in the CV.
- Use `assets/images/profile.jpg` as the public profile portrait. Include complete author lists for all listed publications, verified from their publication records.
- Use these focus areas: Machine Learning, Routing & Maps, Geospatial Analysis, Computer Vision, Forecasting, and Data Platforms.

## Site context

- This is a GitHub Pages portfolio using Jekyll (`jekyll-theme-cayman`).
- Keep the live site focused on a concise professional profile, selected work, skills, and contact paths rather than reproducing the full CV.
- The approved visual direction is a quiet, typography-led personal site inspired by the restraint of Daksh Pareek and Cassidy Williams, without copying either site.
- Use a deep charcoal-plum background, light lavender text, muted lavender secondary text, and a soft violet accent. Use JetBrains Mono for an understated coding-screen feel.

## Deployment guardrails

- Do not add CV PDF files to Git or reference them from the public site unless the owner explicitly requests a publishable version.
- Preserve GitHub Pages compatibility and avoid build dependencies unless needed.
