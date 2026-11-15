# FLARE-SI

Fire safety insights from NASA microgravity combustion data. 2026 NASA Space Apps Challenge, "Flame in Freefall".

A static website: an investigation dashboard, a data page, two data-driven simulators and a fire-safety page.

## Run

The whole site is one file, `index.html`. Open it in a browser or put it on any static host.

GitHub Pages: create a public repository, upload `index.html` to the root, then Settings → Pages → Deploy from branch → `main` / root. The site appears at `https://<user>.github.io/<repo>/`.

## Data

NASA Physical Sciences Informatics repository (https://psi.nasa.gov), combustion science experimental tables, CC0-1.0, retrieved 14 November 2026. Accessions and DOIs are listed in `FLARE-SI_SpaceApps_Submission_v6.md` and on the site's Data page.

## AI use

The website code, the extraction of test outcomes from the PSI tables and the draft text were generated with Claude (Anthropic) during development. Experimental values are NASA's and were not altered; every extracted row keeps its PSI test ID. No AI model runs on the site: the evidence assistant is rule-based retrieval. No AI-generated images, video or audio. `VERIFICATION_solid_fuel_rows.csv` lists the 41 extracted solid-fuel rows for checking against the PSI tables.

## Licence

Apache License 2.0 (add the standard LICENSE file). Fonts: Inter and JetBrains Mono, SIL Open Font License. Not affiliated with or endorsed by NASA.
