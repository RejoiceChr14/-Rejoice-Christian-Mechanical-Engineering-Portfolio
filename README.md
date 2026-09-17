# Rejoice Christian — Engineering Portfolio

A project-focused personal website built with plain HTML and CSS. The homepage begins with an introduction and portrait, then presents personal and course projects, followed by expandable team and industry project summaries.

**Live site:** [Rejoice Christian’s portfolio](https://rejoicechr14.github.io/-Rejoice-Christian-Mechanical-Engineering-Portfolio/)

## Edit the website

| Content | File |
| --- | --- |
| About me, project cards, SAE and UL project summaries, contact links | `index.html` |
| ME 347 gear-ratio fidget project | `projects/gear-fidget.html` |
| Catapult project | `projects/catapult.html` |
| iPhone repair project | `projects/iphone.html` |
| Bluetooth speaker project | `projects/speaker.html` |
| Colors, type, spacing, image crops, and mobile layouts | `styles.css` |
| Portrait | `assets/rejoice-christian-headshot.webp` |
| Project photos | `assets/projects/` |
| Résumé PDF | `assets/rejoice-christian-resume.pdf` |

Edit and commit to the `main` branch. GitHub Pages publishes from the repository root. No build command or package installation is required.

You can open `index.html` directly, or run a local server from this folder:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Add another project

1. Copy a page from `projects/` and give it a descriptive filename.
2. Update its title, description, project facts, images, narrative, and navigation links.
3. Place optimized project images in `assets/projects/`.
4. Copy a homepage `<article class="project-card">` and update its link, image, and summary.
5. Include descriptive alternative text for images and verify links on desktop and mobile.

All website paths are relative so they work under the GitHub Pages repository URL. Keep `../` prefixes for shared assets referenced from project pages.

## Content and media

The Catapult, iPhone, and Speaker pages draw on Rejoice Christian’s original Google Sites project writeups and photos. Each detail page links to its original project archive for additional material. The speaker components image is identified as kit documentation. The speaker project is described as a kit build.

The SAE contribution is described as team concept development. UL Solutions descriptions stay at a high level: do not add internal standards, test setups, data, pricing, or other confidential materials.

The ME 347 gear-ratio fidget page draws on the supplied course presentation, including sketches, an early CAD prototype, a photo of the printed build, and documented limitations. Its 15:1 ratio is described as a design target, not a measured result. Selected assets avoid the student identifier visible elsewhere in the deck.

Contact links and the résumé appear in the footer of each HTML page. Update all five pages if these links change.

The website uses no JavaScript, external fonts, or third-party embeds. Previously included license notices remain in `assets/`. Personal content and supplied assets remain their owners’ property.
