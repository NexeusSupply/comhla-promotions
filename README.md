# Comhla Vet promotions page

The monthly clinic promotions page. GitHub Pages publishes it at
**https://nexeussupply.github.io/comhla-promotions/**, and the Comhla Vet Rocketspark site
shows it through a Code block (see `rocketspark-code-block.html`). Any change saved here
appears on the website within a minute or two. Nobody needs to touch Rocketspark again.

## What to edit

| To change | Edit |
|---|---|
| Offer wording, dates, clinics, add or remove an offer | `data.js` (the `D.offers` list) |
| A download button's file or link | `data.js` (the `FILES` list) |
| A poster, form or brief | upload it into the `files/` folder |
| Look and layout | `index.html` (rarely needed) |

Edit in the browser: open the file on GitHub, click the pencil icon, make the change,
then click **Commit changes**.

## Adding a file

1. Rename it to a short name with no spaces, e.g. `Cobaltsure-WCV.pdf`.
2. Open the `files` folder on GitHub, click **Add file > Upload files**, drop it in, commit.
3. Make sure the matching line in `FILES` in `data.js` says `"files/Cobaltsure-WCV.pdf"`.

A button whose file isn't uploaded yet shows as a yellow "coming soon" note, never a broken link.
Max 25MB per file when uploading through the browser.

### Files expected for December 2026

| `FILES` key | File name in `files/` |
|---|---|
| bh-wd-vetsouth | BlackHawk-WorkingDog-VetSouth.pdf |
| bh-wd-wcv | BlackHawk-WorkingDog-WCV.pdf |
| bh-wd-srv | BlackHawk-WorkingDog-SRV.pdf |
| bh-wd-vcm | BlackHawk-WorkingDog-VCM.pdf |
| vax-vetsouth | CA-Vax-Collateral-VetSouth.zip |
| vax-wcv | CA-Vax-Collateral-WCV.zip |
| campy-poster | CampyVax-Poster-A3.pdf |
| campy-prize | CampyVax-Prize-Poster-A3.pdf |
| campy-paddock | CampyVax-Paddock-Poster-A3.pdf |
| campy-paddock-dig | CampyVax-Paddock-Poster-Digital.png |
| campy-entry | CampyVax-Entry-Form-A4.pdf |
| selekt-readme | SELEKT-Summer-Read-Me-First.pdf |
| selekt-brief | SELEKT-Summer-Staff-Brief.pdf |
| selekt-tent | SELEKT-Summer-Tent-Card.pdf |
| selekt-poster | SELEKT-Chilly-Bin-Poster.pdf |
| cobalt-vetsouth | Cobaltsure-VetSouth.pdf |
| cobalt-wcv | Cobaltsure-WCV.pdf |
| calf-vetsouth | Calf-Care-VetSouth.pdf |
| calf-wcv | Calf-Care-WCV.pdf |

Still to come: Delicate Care poster, Calmex and Cyrex buy-in forms, Royal Canin FAQ,
CampyVax online survey link and order form.

## Giving someone edit access

Repository **Settings > Collaborators > Add people**, enter their GitHub username or email.
They need a free GitHub account and must accept the email invite.

## Privacy

This repository and everything in `files/` is public. Anyone with the link can see it,
the same as an unlisted Rocketspark page. Search engines are asked not to index the page.
