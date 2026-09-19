# Rejoice Christian — Engineering Portfolio

A static portfolio built with HTML and CSS. About Me and the portrait lead the homepage. Every project opens in the same browser tab, with its narrative, images, results, and available videos contained on its own page.

**Live site:** [Rejoice Christian’s portfolio](https://rejoicechr14.github.io/-Rejoice-Christian-Mechanical-Engineering-Portfolio/)

## Project order

The gallery leads with mechanical design, analysis, and physical prototyping, followed by laboratory documentation, electronics, and business support:

1. Traffic mast-arm design — `projects/mast-arm.html`
2. 15:1 gear-ratio fidget — `projects/gear-fidget.html`
3. Catapult — `projects/catapult.html`
4. Formula SAE push bar — `projects/sae-push-bar.html`
5. Test reference guides — `projects/test-reference-guides.html`
6. Bluetooth speaker — `projects/speaker.html`
7. iPhone repairs — `projects/iphone.html`
8. Department pricing initiative — `projects/pricing-initiative.html`

## Editing

| What to change | Location |
| --- | --- |
| Introduction, ordered project cards, contact details | `index.html` |
| Complete project stories | The matching page in `projects/` |
| Colors, spacing, typography, responsive layout | `styles.css` |
| Project images and inline videos | `assets/projects/` |
| Portrait | `assets/rejoice-christian-headshot.webp` |
| Résumé | `assets/rejoice-christian-resume.pdf` |

Commit to `main` to publish through GitHub Pages. No build tool or dependency installation is required. For a local preview, run `python3 -m http.server 8000` in the repository root and open `http://localhost:8000`.

To add a project, copy an existing project page and its homepage card. Update the previous/next navigation to match the gallery order. Keep asset paths relative, using `../assets/` from project pages. Update contact links in all nine HTML pages when they change.

## Content conventions

Keep the full project explanation on its page. Include relevant figures, photos, tables, and local video players directly. Do not redirect visitors to Google Sites, slide decks, or separate reports to understand the project. Videos use native controls and do not autoplay.

Distinguish measured tests from design targets and simulation results. The mast-arm figures and comparison values come from the ME 347 Project 2 report dated April 30, 2026. The catapult table reproduces the original trials; row means are calculated from those values. The gear ratio is a design target. The speaker is a kit build with supplied component ratings.

Selected gear-project media avoid the student identifier visible elsewhere in the source presentation. SAE work remains described as concept development. UL Solutions pages use only high-level information already approved for this portfolio; exclude internal test details, documents, pricing, and company data.

The site uses no JavaScript, external fonts, or third-party embeds. Previously included license notices remain in `assets/`. Personal content and supplied assets remain their owners’ property.
