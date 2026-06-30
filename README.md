# Nipuni Hansika Wijesinghe - Personal Website

A single-page personal website summarising my background, research, and publications as a PhD candidate in Human-Robot Interaction at the University of Canberra.

## Contents

- `index.html` - the full site (profile, research pillars, experience, education, publications, skills). No separate CSS or JS files; everything is contained in this one file.

## Viewing locally

Just open `index.html` in any browser. No build step or server required.

## Publishing with GitHub Pages

1. Create a new repository, for example `username.github.io` (replace `username` with your GitHub username) for a root-level site, or any repo name for a project site.
2. Add `index.html` to the root of the repository and push it.
3. In the repository, go to Settings > Pages.
4. Under "Build and deployment", set the source to "Deploy from a branch", choose the `main` branch and the `/ (root)` folder, then save.
5. GitHub will publish the site at `https://username.github.io` (or `https://username.github.io/repo-name` for a project repo) within a few minutes.

## Updating content

All text lives directly inside `index.html`, grouped by section (Profile, Research Pillars, Experience, Education, Publications, Skills). To update:

- Edit the relevant text between the HTML tags for that section.
- Each job, degree, and publication is its own block (`<div class="entry">` or `<div class="pub">`), so you can copy an existing block and edit it to add a new entry, or delete a block to remove one.
- Links (LinkedIn, Google Scholar, email) appear twice, once in the header and once in the footer; update both if they change.

## Notes

- The publication list was sourced from my CV as of June 2026. Cross-check against my Google Scholar profile for anything more recent: https://scholar.google.com/citations?user=nkmKtdkAAAAJ&hl=en
- Colour palette: dark teal background with gold accents, intended to echo the "dimmer switch" framing used in my research.
