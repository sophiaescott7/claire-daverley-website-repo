# Content notes (read before building)

Source: WordPress export, 2026-11-25. This folder contains copy, links and alt text only. Layout and visual design are intentionally NOT included: design the site from design-brief.md, requirements.md, style-guide.md and the wireframes.

## Images used on the WordPress site (download from Media Library into `planning/images/`)
| File | Use | Alt text |
|---|---|---|
| fullpage.do_.jpeg | Talking at Night cover (home + product page) | Cover of Talking at Night by Claire Daverley, showing two people sitting on a hillside beneath a large cloud. |
| 9780593653517_p0.jpg.webp | People in Love cover (home + product page) | Cover of People in Love by Claire Daverley, showing two people lying together on a couch. |
| images-11-2.jpeg | Events page photo | Claire Daverley smiling in front of a bookstore holding up a copy of People in Love. |
| images-10-2.jpeg | Events page photo | Claire Daverley in conversation with another author at an event for People in Love. |
| images-9-2.jpeg | Events page photo | Claire Daverley smiling in front of a bookstore holding up a copy of People in Love. |
| Submitted+-+ClaireAndClive-30+3.jpeg | Likely the About page featured author photo (confirm) | (none in export) |

## Embeds
- Home page media: two Spotify podcast episodes (URLs in `home.md`)
- Substack: https://clairedaverley.substack.com ("Desk by the Ocean")
- Instagram: https://www.instagram.com/clairedaverley

## Known inconsistencies in the source content (resolve, don't guess)
1. **Event dates differ:** the home page lists Books Are Magic on Feb 25, 2027; the Events page lists it on Feb 27, 2027.
2. **US release date of People in Love:** About page says "January 2027"; the product page says "February 2, 2027".
3. **Placeholder text on About page:** "(link to book product page)" and "(link to “Contact” page)" are notes to self, not final copy. They should be real links to /talking-at-night, /people-in-love and /contact.
4. **No "Books" page exists** in WordPress. The nav is Home, People in Love, Talking at Night, About, Events, Contact.
5. **Pre-order buttons:** the People in Love page uses "Pre-Order" wording, which must change after the Feb 2, 2027 release.
6. **Internal page links** were converted to relative names (e.g. `events.html`) and image references now point to `planning/images/<filename>`. External links (retailers, venues, Substack, Instagram, Spotify) are unchanged.
7. **Tracking junk in some retailer URLs** (utm_, gclid, srsltid, ref=). Safe to strip; keep the product path.
8. **Missing from the content vs. the requirements doc:** event guest names, the embedded Instagram feed, and an embedded Substack article module. Events show no guest field.
9. **About page includes a Freelancing Services section** that is not in the requirements doc. Keep or cut.
10. **Trashed duplicate page** "People in Love__trashed" in the export was ignored.
