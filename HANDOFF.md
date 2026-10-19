# Stone, Concrete, & Brick Masons LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/stoneConcreteBrickMasons/ · **Repo:** https://github.com/10elizabethbell/stoneConcreteBrickMasons · **Built:** 2026-10-19 from Muse brief of 2026-10-19 (NJ Construction Connection ad posts)

## What's built
- One page, phone first: header (wordmark + tap-to-call 347-684-4863 top right), hero "One standard. Done right." with two buttons (Get a free estimate → form; Text us a photo → `sms:`), services, story, how it goes, free-estimate form, close, footer.
- **World:** their own job site from the ad photo: slate-blue ground, grey-green mortar paper, rose-granite blocks, wooden form board, safety-yellow actions, chalk-line blue form outlines.
- **Signature (hero):** a slab of wet concrete (height field: lumps slump, the trowel levels, pushes a ridge ahead and leaves a smooth finish with trowel-edge lines). It trowels itself until touched; mouse or finger takes over in every direction (vertical drags don't scroll the page). Fresh concrete slowly creeps back (`REGROW`). Tunables at the top of the `slab` IIFE.
- **Carried through:** granite coping courses between sections and capping the work photo; blocks shift under pointer/finger and settle back (`coping` IIFE constants).
- **Contact:** every service row opens a text pre-filled with that service; the form composes name / projects / town / details into one text. No email anywhere (none exists).
- Verified: 360/390/430 phone in Chromium + WebKit (no sideways scroll, inputs 17px, tap targets ≥44px), touch sweep smooths the slab without scrolling, coping push + settle, form errors + text body, desktop 1440. Impeccable detector clean (3 suppressions in `.impeccable/config.json`: Roboto = system-stack fallback, the short uppercase line, small-text size steps).

## Assumptions I made
- **Voice "we"**: their captions say "Three JDs" and "we".
- **Hero promise** "Three law-school grads from a family of masons…" is my plain-language version of their hook "Three JDs are building your dream property." (Impeccable flagged "JDs" as jargon to homeowners). Swap back if the owner prefers "Three JDs".
- **Story copy** paragraph 2 ("you deal with us from the first look at your yard to the last joint we point… the care we'd want in front of our own") is mine, built on their "One contractor. One standard." and "locally owned". Owner should approve.
- **How it goes** step 2 ("We look it over and give you a straight price") assumes they look at the job before quoting; inferred.
- **Colors** sampled from the walkway/wall photo; yellow from the curb stops on that job.
- **Brand mark**: no logo exists; the favicon/icon and header mark are three granite blocks over a yellow course, drawn by me in the site's own colors.
- **Audience** not flagged as 40+, so the motion version was built. If Ellie or Muse judge their customers older, follow `older-audience.md` (still slab, no autoplay).
- **Facebook link** goes to John Lewandowski III's personal profile (the ads post from it); his relationship to the LLC is unconfirmed.

## Placeholders and gaps
- **Only one real photo.** The second ad photo (fbid 1666251301667073) is behind Facebook's login wall; the post previews only show the first. The one photo is cropped to remove storefront signs (a law office and a performance shop: they would locate the job), cars and caution tape.
- No service area or towns on the page (brief: do not publish a location).
- No hours, years in business, licence, insurance, reviews, prices, email, or logo — none on the page.

## Questions for the owner
- More job photos (patios, driveways, pools, stonework), ideally before/after pairs.
- Which towns/counties do you work in?
- Business Facebook or Instagram page to link instead of the personal profile?
- Licensed and insured? (Would add a trust line.)
- Is "Three JDs" a line you want front and center?
- Do you do pool decks/coping, or pools themselves?
- Email for the footer?

## Ideas not built (yours to pick)
- **Runner-up world:** "Lay the wall": the hero is a granite retaining wall that builds itself course by course, and the visitor drops blocks into place. Other candidates considered: mortar joints being pointed, a paver patio in herringbone, a chalk line snapped across a slab, sparks from a stone chisel.
- Before/after sliders once pairs exist (plain yellow divider).
- A "your project" photo upload step in the form (needs a backend; texting the photo already works).
- Desktop hero: the right half of the slate is empty; the slab could rise into a right column.
- Trowel ceiling: a blade bevel and handle posts, arc-swirl burnish that catches the light.
- Step tiles drawn from the coping-block sprite instead of flat granite squares.
- Replace the services' `sms:` rows with a desktop fallback (they do nothing on most desktops; the header number covers it).

## Not verified
- Real-device touch on iPhone/Android inside Facebook's in-app browser (headless CDP touch only).
- The SMS handoff opening the Messages app with the body on iOS and Android.
- Frame rate on older phones (the slab runs about 7k cells on phones; one shared canvas pass per frame, paused off screen).
- The Facebook link preview card (og.jpg is set; check with Facebook's Sharing Debugger).
