# Nipuni Hansika Wijesinghe - Personal Website

A multi-page personal website covering my background, research, experience, education, publications, and projects as a PhD candidate in Human-Robot Interaction at the University of Canberra. Colour theme: white and shades of purple.

## Contents

- `index.html` - homepage (profile, research pillars, skills)
- `experience.html` - professional experience
- `education.html` - educational background
- `publications.html` - publications, conference presentations, media
- `projects.html` - research and personal projects
- `cv.html` - view or download a CV file
- `style.css` - shared stylesheet used by every page
- `profile.jpg` - placeholder for your photo (add your own file with this name)
- `cv.pdf` - placeholder for your CV file (add your own file with this name)

## Adding your photo

Add a photo file named `profile.jpg` in the same folder as `index.html`. It will appear automatically in the circular frame in the header. If you'd rather use a different filename or format (for example `profile.png`), open `index.html`, find this line near the top of the `<header class="hero">` section, and update the `src`:

```html
<img class="profile-photo" src="profile.jpg" alt="Photo of Nipuni Hansika Wijesinghe" onerror="this.style.display='none'">
```

If no photo is present, the circle is simply hidden rather than showing a broken image icon.

## Adding your CV

Add your CV file named `cv.pdf` in the same folder as `cv.html`. The page will both embed it in a preview pane and offer a direct download button. If your file has a different name, update the three `cv.pdf` references in `cv.html`.

## Viewing locally

Open `index.html` in any browser. All pages link to each other and to `style.css`, so keep all files in the same folder.

## Publishing with GitHub Pages

1. Create a new repository, for example `username.github.io` (replace `username` with your GitHub username) for a root-level site, or any repo name for a project site.
2. Add all files (the HTML pages, `style.css`, `profile.jpg`, `cv.pdf`) to the root of the repository and push.
3. In the repository, go to Settings > Pages.
4. Under "Build and deployment", set the source to "Deploy from a branch", choose the `main` branch and the `/ (root)` folder, then save.
5. GitHub will publish the site at `https://username.github.io` (or `https://username.github.io/repo-name` for a project repo) within a few minutes.

## Updating content

- Each page is plain HTML; sections are clearly labelled (Profile, Experience, Education, Publications, Projects).
- Each job, degree, publication, and project sits in its own block (`.entry`, `.pub`, or `.project-card`), so you can copy an existing block and edit it to add a new entry, or delete a block to remove one.
- Navigation links and footer links appear on every page; if you add a new page, copy the nav and footer from an existing page and update the `active` class on the matching link.
- Colours and fonts are controlled centrally in `style.css` under `:root` at the top of the file.

## Notes

- The publication list was sourced from my CV as of June 2026. Cross-check against my Google Scholar profile for anything more recent: https://scholar.google.com/citations?user=nkmKtdkAAAAJ&hl=en
