# Rejoice Christian — Engineering Portfolio

A portable version of the existing portfolio, ready for GitHub Pages. Includes the professional headshot, About section, engineering projects, experience, skills, education, contact links, and résumé download.

This website uses plain HTML and CSS. No installation, build command, framework, or paid hosting service is required for this package. You can open `index.html` directly in your browser to preview it.

## Publish on GitHub Pages

The website files are stored in this repository:
[RejoiceChr14/-Rejoice-Christian-Mechanical-Engineering-Portfolio](https://github.com/RejoiceChr14/-Rejoice-Christian-Mechanical-Engineering-Portfolio).

1. Open this repository's [Settings → Pages](https://github.com/RejoiceChr14/-Rejoice-Christian-Mechanical-Engineering-Portfolio/settings/pages).
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select **main**, choose **/ (root)**, and click **Save**.
4. After GitHub finishes publishing, open the website address shown on the same settings page.

Your expected website address after activation is:
`https://rejoicechr14.github.io/-Rejoice-Christian-Mechanical-Engineering-Portfolio/`

The address becomes available after Pages is enabled and its deployment succeeds. Uploading these files alone does not enable GitHub Pages. Publishing makes the portfolio, its contact details, and its résumé available online.

All asset links use relative paths so the site works both in a project repository and at a personal domain's root.

Official instructions: [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [Configuring a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Make it your own

| What to change | File and location |
| --- | --- |
| Intro, project descriptions, experience, skills, About, education, and contact details | `index.html`; search for the section's heading or its `id` |
| Colors | `styles.css`, in the `:root` section at the top |
| Spacing, fonts, portrait crop, and mobile layouts | `styles.css` |
| Headshot | Replace `assets/rejoice-christian-headshot.webp`; use the same filename or update the image links in `index.html` |
| Résumé | Replace `assets/rejoice-christian-resume.pdf` with your latest PDF |
| Browser-tab icon | Replace `assets/favicon.svg` |
| Copyright year | Search for the copyright text in `index.html` |

Edit a file in GitHub and commit the change to `main`; Pages will publish the update. To add a project, copy one complete `<article class="project-card">` block inside the Selected work section and replace its contents. Keep the file and folder names consistent with the links in `index.html`.

The About section uses the existing portrait crop. Adjust `.portrait-frame img` in `styles.css` to change its position. Mobile layouts are defined near the bottom of that file.

UL Solutions examples use the existing high-level descriptions. Continue to exclude internal standards, test setups, data, pricing, and other confidential materials from future updates.

## Included files

- `index.html` — the complete editable webpage, including embedded vector icons.
- `styles.css` — the portfolio's design and responsive layouts.
- `assets/` — headshot, résumé, favicon, browser reset styles, and third-party license notices.
- `.nojekyll` — tells GitHub Pages to serve the prepared static files.

The browser reset is from Tailwind CSS (MIT license); the embedded icons are from Lucide (ISC/MIT notices). Their license files are included in `assets/`. Personal content and supplied assets remain their owners' property.
