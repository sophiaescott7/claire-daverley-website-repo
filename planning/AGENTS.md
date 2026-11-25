# Project brief for the coding agent

## What this is
A redesign of Claire Daverley's author website, for women aged 18-35 who read
literary fiction and contemporary romance (fans of Claire Daverley and of
comparable authors such as Sally Rooney, Alice Winn and Gabrielle Zevin).
Its goal is to be the central hub where readers discover her two books
(*Talking at Night* and *People in Love*), buy them easily from retailers,
find and RSVP to her events, and follow her on Substack and Instagram.

## Source of truth
All planning documents are in /planning. Read /planning/README.md first.
- Pages and navigation: follow /planning/site-map.md exactly.
- Page text and links: use only /planning/content/. Do not invent copy,
  reviews, events, or URLs. Mark gaps with an HTML comment and report them.
- Goals, audience, and brand: /planning/design-brief.md
- Page-by-page requirements: /planning/requirements.md
- Colors, fonts, buttons, tone: /planning/style-guide.md
- Layout: the wireframes in /planning/wireframes/ and the user flow in
  /planning/ux-flow-diagram.png
- Do not look at or copy any existing website. Design only from /planning.
- Do not edit anything in /planning unless I ask.
- If something is missing, unclear, or contradictory, ask me instead of guessing.

## Technical rules
- Static site only: plain HTML, CSS, and a little vanilla JavaScript.
  No frameworks, no backend, no build step.
- One shared stylesheet: /css/styles.css
- The home page is index.html at the root of the repo. One HTML file per page.
- Hosted on GitHub Pages in a subfolder: use relative links only
  (never links starting with "/").
- Images go in /images/. Source images are in /planning/images/; copy them,
  using the alt text in /planning/content/_content-notes.md.
- Mobile-first and responsive. Mobile and tablet share one layout: hamburger
  menu, single column. Desktop gets the horizontal nav.
- Accessible (WCAG 2.1 AA): semantic HTML, alt text on every image, keyboard-
  navigable menus, visible focus states, and sufficient color contrast.
  If a color pairing from the style guide fails contrast, flag it and propose
  an accessible alternative instead of using it silently.
- Fast: no large unoptimized images, no unnecessary scripts.
- Credit every image per /planning/image-credits.md.

## Style
Colors: vivid pink #FC3C71, pastel blue #A6B8D9, orange #FB481D,
green/brown #72630C. Fonts: Montserrat Bold for headings, Lora for body text.
Tone: friendly yet factual, mirroring the tone of the author's writing.
Buttons: white background, rectangular with rounded corners, black text.

## Decisions (edit these as I decide)
- Navigation: Home, Talking at Night, People in Love, Events, About, Contact.
  There is no separate Books page. Make the two book links stand out in a
  bright background color to guide visitors to buy.
- Hamburger menu: top left on mobile and tablet.
- Substack and Instagram: link out with buttons and a Substack subscribe
  button. Do not try to pull their feeds dynamically.
- Out of scope for now: unlock codes for book owners, "Reader Postcards" wall.
- Do not build the character quiz or time-aware background art until I ask.
- Open questions (ask me, do not guess): the date of the Books Are Magic event
  (Feb 25 vs Feb 27, 2027) and the US release date of *People in Love*
  (January 2027 vs February 2, 2027).

## How to work with me
Propose a plan before writing code. Build one page at a time.
When you finish a page, explain what you changed in plain language, list
every file you created, and list anything you had to assume.
Never ask me for, or put into the repo, passwords, API keys, or other people's personal data.