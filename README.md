# Rejoice Christian — Engineering Portfolio

A static portfolio built with HTML and CSS. About Me and the portrait lead the homepage. Five selected projects have complete pages containing their narratives, images, results, and available videos. Smaller team and industry contributions appear in expandable rows on the homepage.

**Live site:** [Rejoice Christian’s portfolio](https://rejoicechr14.github.io/-Rejoice-Christian-Mechanical-Engineering-Portfolio/)

## Selected projects

The gallery leads with mechanical design, analysis, and physical prototyping, followed by electronics and repair:

1. Traffic mast-arm design (ME 347 Project 2) — `projects/mast-arm.html`
2. 15:1 gear-ratio fidget — `projects/gear-fidget.html`
3. Catapult — `projects/catapult.html`
4. Bluetooth speaker — `projects/speaker.html`
5. iPhone repairs — `projects/iphone.html`

## Additional projects

The “Team & industry projects” section follows the gallery. Its three compact rows expand in place:

- Formula SAE push bar — `index.html#sae-push-bar`
- UL Solutions test reference guides — `index.html#test-reference-guides`
- UL Solutions pricing initiative — `index.html#pricing-initiative`

The former standalone URLs for these three projects redirect to the corresponding homepage rows so existing links continue to work.

## Editing

| What to change | Location |
| --- | --- |
| Introduction, ordered project cards, additional projects, contact details | `index.html` |
| Complete selected-project stories | The matching page in `projects/` |
| Colors, spacing, typography, responsive layout | `styles.css` |
| Project images and inline videos | `assets/projects/` |
| Portrait | `assets/rejoice-christian-headshot.webp` |
| Résumé | `assets/rejoice-christian-resume.pdf` |

Commit to `main` to publish through GitHub Pages. No build tool or dependency installation is required. For a local preview, run `python3 -m http.server 8000` in the repository root and open `http://localhost:8000`.

To add a selected project, copy an existing full project page and its homepage card. Update the previous/next navigation to match the gallery order. The final selected project links to the additional-project section. Keep asset paths relative, using `../assets/` from project pages. Update contact links on the homepage and the five full project pages when they change.

## Content conventions

Keep the full selected-project explanation on its page, with relevant figures, photos, tables, and local video players. Keep additional-project summaries within their homepage accordion rows. Visitors should not need Google Sites, slide decks, or separate reports to understand a project. Videos use native controls and do not autoplay.

Distinguish measured tests from design targets and simulation results. The mast-arm figures and comparison values come from the ME 347 Project 2 report dated April 30, 2026. The catapult table reproduces the original trials; row means are calculated from those values. The gear ratio is a design target. The speaker is a kit build with supplied component ratings.

Selected gear-project media avoid the student identifier visible elsewhere in the source presentation. SAE work remains described as concept development. UL Solutions summaries use only high-level information already provided for this portfolio; exclude internal test details, documents, pricing, and company data.

The site uses no JavaScript, external fonts, or third-party embeds. Previously included license notices remain in `assets/`. Personal content and supplied assets remain their owners’ property.
