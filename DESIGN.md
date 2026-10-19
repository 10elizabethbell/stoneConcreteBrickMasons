---
name: Stone, Concrete, & Brick Masons LLC
description: A mason's pitch site laid like their own job site. Slate ground, mortar paper, rose granite, safety yellow, chalk blue, and wet concrete you finish with a trowel.
colors:
  slate-ground: "#23313a"
  slate-ground-raised: "#2c3d47"
  mortar-paper: "#e4e7e2"
  mortar-paper-shade: "#d9ddd7"
  field-fill: "#f3f5f1"
  joint-rule: "#c6cbc4"
  mortar-joint: "#9ea49d"
  ink: "#1d2830"
  ink-soft: "#46555c"
  on-dark: "#f1efe9"
  on-dark-soft: "#c4ccce"
  rose-granite: "#8a6b6a"
  rose-granite-light: "#b39089"
  safety-yellow: "#f2c230"
  safety-yellow-deep: "#d9a812"
  chalk-line: "#2a78c2"
  error-brick: "#a3261b"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, Helvetica, Arial, sans-serif"
    fontSize: "clamp(2.75rem, 12.6vw, 6rem)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, Helvetica, Arial, sans-serif"
    fontSize: "clamp(2rem, 9vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, Helvetica, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, Helvetica, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.45
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, Helvetica, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, Helvetica, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, Helvetica, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.55
  phone-number:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, Helvetica, Arial, sans-serif"
    fontSize: "clamp(30px, 9vw, 44px)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.01em"
    fontFeature: "\"tnum\""
rounded:
  tile: "8px"
  md: "10px"
  pill: "999px"
  round: "50%"
spacing:
  xs: "8px"
  sm: "12px"
  md: "22px"
  lg: "36px"
  gutter: "20px"
  gutter-desktop: "40px"
  column-gap: "64px"
  section: "64px"
  section-desktop: "96px"
  container: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.safety-yellow}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.safety-yellow-deep}"
    textColor: "{colors.ink}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-send:
    backgroundColor: "{colors.slate-ground}"
    textColor: "{colors.on-dark}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-send-hover:
    backgroundColor: "{colors.slate-ground-raised}"
    textColor: "{colors.on-dark}"
  service-row:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    height: "64px"
    padding: "8px 0"
  row-arrow:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.round}"
    size: "42px"
  row-arrow-hover:
    backgroundColor: "{colors.safety-yellow}"
    textColor: "{colors.ink}"
  input-field:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: "14px"
    height: "54px"
  chip:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.slate-ground}"
    textColor: "{colors.on-dark}"
  facebook-card:
    backgroundColor: "{colors.slate-ground}"
    textColor: "{colors.on-dark}"
    typography: "{typography.title}"
    rounded: "{rounded.md}"
    padding: "14px 18px"
    height: "64px"
  step-tile:
    backgroundColor: "{colors.rose-granite}"
    textColor: "#ffffff"
    rounded: "{rounded.tile}"
    size: "48px"
---

# Design System: Stone, Concrete, & Brick Masons LLC

## Overview

**Creative North Star: "The Job Site You Finish Yourself"**

The whole system is lifted from one photo the client posted: a fresh broom-finished concrete walk beside a rose-granite block retaining wall, wooden form boards, safety-yellow curb stops and a blue chalk line. Every surface maps to one of those materials. The dark slate ground is the night side of the site, the pale grey-green paper is the mortar, rose granite trims and numbers things, safety yellow marks the things you can act on, and chalk blue outlines only the form you fill in. Nothing is decorative that isn't one of those materials.

It is a phone-first, single-column page that reads top to bottom like a job: promise, what we build, who we are, how it goes, the estimate form, the close. Density is low and blunt; headings are heavy uppercase system type, body is plain sentence case. Two living elements carry the craft: a wet-concrete slab under the hero that a steel trowel finishes (on its own, or under your finger in any direction), and courses of granite coping between sections and on top of the work photo that nudge under the pointer and settle back. The page is otherwise still.

The owner's house style (Ellie's pitch-site rules) shapes the frame: system font stack, no sticky bars, the phone number in the top-right corner and only there on the first screen, at most two buttons under the headline, accents on hover rather than at rest, and the Facebook link sitting directly under the work photo where a visitor wants to see more.

**Key Characteristics:**
- Materials, not decoration: slate, mortar, rose granite, safety yellow, chalk blue, concrete, wood.
- Heavy uppercase system-font headings over plain sentence-case body.
- Two living canvases (wet slab + trowel, granite coping); everything else static.
- Safety yellow means "act here"; chalk blue means "you are filling in the form".
- Phone-first: one column, 56px pill buttons, 44px minimum touch targets, tel: and sms: links as the primary actions.

## Colors

A cool slate-and-mortar neutral field with one loud action color (safety yellow), one quiet functional color (chalk blue, form only), and rose granite as the warm material trim.

### Primary
- **Safety Yellow** (safety-yellow): the curb-stop yellow. Fills the primary button, fills a service row's arrow or the Facebook card's arrow on hover/focus, the global keyboard focus ring, text selection, and the hover color for the header and closing phone numbers. **Safety Yellow Deep** (safety-yellow-deep) is its pressed/hover fill on the primary button only.

### Secondary
- **Chalk Line Blue** (chalk-line): the mason's chalk line. Outlines text fields and chips on hover, draws their focus ring (as a 3px ring at 25% alpha), sets the text caret, and outlines the send button on hover and focus. It lives inside the estimate form and nowhere else.

### Tertiary
- **Rose Granite** (rose-granite): the retaining-wall stone. Fills the numbered step tiles and forms the base hue of the coping blocks and the logo mark. **Rose Granite Light** (rose-granite-light) is the paler block in the logo mark and favicon.

### Neutral
- **Slate Ground** (slate-ground): the dark ground. Hero, story section, closing section, the Facebook card, the selected chip and the send button. Also the browser theme color. **Slate Ground Raised** (slate-ground-raised) is the send button's hover fill.
- **Mortar Paper** (mortar-paper): the default page background for light sections. **Mortar Paper Shade** (mortar-paper-shade) is the alternate light band (How it goes) and the photo frame's placeholder fill.
- **Field Fill** (field-fill): the slightly lighter fill inside text fields and unselected chips, so they read as recessed panels on the paper.
- **Joint Rule** (joint-rule): 1px dividers between service rows, the resting 2px border of fields, chips and row arrows.
- **Mortar Joint** (mortar-joint): the mortar bed behind the coping blocks on the divider canvases.
- **Ink** (ink) and **Ink Soft** (ink-soft): text on light grounds; soft is for ledes, step descriptions, helper text and notes.
- **On Dark** (on-dark) and **On Dark Soft** (on-dark-soft): text on slate; soft carries the promise line, story paragraphs and footer text, with bold phrases lifted back to full on-dark.
- **Error Brick** (error-brick): validation message text and the invalid field's border.

### Named Rules
**The Curb-Stop Rule.** Safety yellow is a fill for primary actions and a response to hover or focus. Cues such as arrows sit neutral at rest and turn yellow only when the pointer or focus reaches them.

**The Chalk-Line Rule.** Chalk blue belongs to the form. Every control inside the form (fields, chips, the send button) shows a chalk-blue outline on hover and focus; nothing outside the form uses it.

## Typography

**Display Font:** system UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif)
**Body Font:** the same stack

**Character:** One family at two extremes: 900-weight uppercase headings set tight (line-height 1, -0.02em) like stencilled site signage, against calm 400-weight sentence-case body. The system stack is the owner's house mandate for these pitch sites (fast, familiar in Facebook's in-app browser), not a placeholder.

### Hierarchy
- **Display** (900, clamp(2.75rem, 12.6vw, 6rem), line-height 1, uppercase): the hero headline only, capped at 11ch so it breaks into two short lines.
- **Headline** (900, clamp(2rem, 9vw, 3.6rem), line-height 1, uppercase): every section heading; balanced wrapping, capped at 13 to 14ch on dark sections.
- **Title** (800 to 900, 20px): service row labels and the Facebook card label (800, sentence case); step headings (900, uppercase, -0.01em).
- **Lead** (400, clamp(17px, 4.6vw, 20px), line-height 1.45): the hero promise line, about 34ch. Story paragraphs use the same voice slightly larger (clamp(18px, 4.8vw, 21px), 1.55, 36ch).
- **Body** (400, 17px, line-height 1.55): default text, ledes capped near 40ch.
- **Label** (800, 17px): buttons and form labels; chip text is 700.
- **Small** (400 to 700, 15px): row note, validation errors (700), after-send status, footer.
- **Phone Number** (900, clamp(30px, 9vw, 44px), tabular numerals): the big closing number. The header number is 900 at 17px (16px under 380px, 20px from 640px), also tabular.
- **Brand lockup** (900, 12.5px, 14px from 640px, uppercase, two lines): the company name beside the brick logo mark.

### Named Rules
**The Signage Rule.** Headings are 900-weight uppercase with tight leading; body never goes uppercase and never goes above 21px.

## Layout

Phone-first single column inside a 1180px container with 20px gutters (40px from 1024px). Light and dark bands alternate: slate hero, coping, mortar services, slate story, coping, shaded steps, mortar form, slate close, darker footer. Section padding is 56 to 72px on phones and 96 to 100px on desktop.

- **Hero:** fills up to the viewport (min(100svh, 940px)). Header row with brand left and phone number right (44px tap height), then headline, promise, and a CTA grid (stacked on phones, two equal columns from 640px, max 560px), then the wet slab taking the remaining height (min clamp(240px, 30svh, 340px) phone, clamp(300px, 36svh, 420px) desktop).
- **Services + work:** one column on phones (rows, then photo, then Facebook card); from 1024px a 1fr / 1.15fr split with 64px gap, the photo column dropped 58px so it starts beside the rows.
- **Story, form, close:** two-column splits from 1024px (1fr 1fr, 1fr 1.4fr, 1.2fr 1fr) with 48 to 64px gaps; the close aligns to the bottom.
- **Steps:** a stacked list with 22px gaps on phones; three equal columns with 40px gaps on desktop.
- **Rhythm:** 22px is the house vertical step (heading-to-content, form field gap, step gap); 12px between stacked buttons; 8px label-to-control.
- **Breakpoints:** 380px (small-phone type trims), 640px, 1024px.

**The Thumb Rule.** Every interactive target is at least 44px tall; buttons are 56px, rows 64px, chips 46px, fields 54px.

## Elevation & Depth

Interface surfaces are flat; depth comes from the materials. Bands of slate and mortar do the layering. The one UI shadow is a soft, slate-tinted drop under the work photo. Inside the canvases the materials cast their own shadows: the trowel blade throws a soft blurred shadow onto the concrete, the form board shades the slab edge, and each coping block sits on a slight dark offset that reads as the stone resting on its mortar bed.

### Shadow Vocabulary
- **Photo lift** (`box-shadow: 0 12px 26px -14px rgba(35,49,58,.55)`): under the framed work photo only.
- **Chalk focus ring** (`box-shadow: 0 0 0 3px rgba(42,120,194,.25)`): form fields and chips on focus, paired with a chalk-blue border.
- **Keyboard focus** (`outline: 3px solid` safety yellow, offset 3px): every other focusable element; the send button uses a chalk-blue outline instead.

**The Material Shadow Rule.** Shadows belong to things with weight (a photo, a trowel, a stone block) and are tinted with slate, never black. Cards, buttons, and rows stay flat.

## Shapes

Soft, worked corners: 10px on fields, the Facebook card, and the photo frame's lower corners (its top edge is covered by the coping cap); 8px on the step number tiles; full pills on buttons and chips; full circles on the arrow cues and the Facebook badge. Borders are 2px on every control (field, chip, button, arrow) and 1px on row dividers. The coping blocks are the one irregular shape: split-face outlines with jittered corners, 24px tall, 44 to 96px long, 4px joints.

## Components

### Buttons
Tactile pills, all the same 56px height and 2px border so pairs match.
- **Shape:** full pill (999px), 0 24px padding, 800 weight 17px, optional 20px leading icon at a 10px gap.
- **Primary:** safety yellow fill with ink text; hover deepens to safety yellow deep.
- **Secondary (on slate):** transparent with a safety-yellow 2px border and on-dark text; hover adds a 14% yellow wash. Used once, as "Text us a photo" beside the primary.
- **Send (form):** slate fill and border with on-dark text; hover lifts to slate raised with a chalk-blue border; focus is a chalk-blue outline.
- **Press:** every button drops 1px on active.
- At most two buttons sit under the hero headline; there is never a Call button there.

### Service Rows
Full-width sms: links, one per service, each composing a text that names the service.
- **Style:** 64px rows, 800 20px label, 1px joint-rule dividers above and below the list.
- **Arrow cue:** 42px circle with a 2px joint-rule border and an 18px right arrow.
- **Hover / Focus:** only the arrow changes: it fills with safety yellow (and gets the yellow focus outline for keyboard). The row itself never takes a background, outline, or shadow.

### Chips
- **Style:** 46px pills, field-fill background, 2px joint-rule border, 700 weight; the checkbox is visually hidden behind the label.
- **Hover / Focus:** chalk-blue border; keyboard focus adds the chalk focus ring.
- **Selected:** slate fill and border with on-dark text; hovering a selected chip still shows the chalk-blue border.

### Inputs / Fields
- **Style:** field-fill background, 2px joint-rule border, 10px radius, 14px padding, 54px minimum (textarea 110px, vertical resize only), chalk-blue caret.
- **Hover:** chalk-blue border. **Focus:** chalk-blue border plus the chalk focus ring, no outline.
- **Error:** error-brick border and a 15px bold error line below; errors clear as soon as the field is fixed.
- **Labels:** 800 weight above the control; optional fields carry a 400 "(optional)" note in ink soft.

### Facebook Card
Sits directly under the work photo: "Click to see more of our work."
- **Style:** slate card, 10px radius, 14px 18px padding, 64px tall, 800 20px on-dark label.
- **Badge:** 36px circle in Facebook's own brand blue with the white f mark (a brand asset, not a palette color).
- **Go cue:** 36px circle on the right with a translucent on-dark border; hover/focus fills it safety yellow with ink arrow. The card body does not change.
- The footer repeats a plain Facebook text link.

### Step Tiles
- **Style:** 48px rose-granite square at 8px radius, white 900 22px counter, spanning the heading and its description in a 48px / 1fr grid.

### Header
- Brand lockup left (38px brick logo mark: three courses of rose-granite blocks over a safety-yellow course), phone number right as a tel: link, on-dark, safety yellow on hover. Not sticky.

### Wet Concrete Slab (signature, hero)
A height field of fresh concrete under a wooden form board, finished by a steel trowel. Lumps slump when steeper than the talus angle; the blade levels what it covers, plows a little material ahead of its leading edge, leaves a smoother, darker, slightly shiny finish and faint arc marks from its trailing edge, and the slab slowly creeps back to fresh. Idle, the trowel works the slab on its own along a looping path; mouse (hover) or finger (drag, any direction) takes over and the cursor is hidden over the slab. Touch-action is disabled on the slab so drags never scroll.
- **Grid:** 4px cells on phones, 5px on desktop; canvas DPR capped at 1.5.
- **Trowel:** 112 x 38px blade (86% on phones under 640px), blade leads its stroke at 90 degrees minus 0.45 rad, turning 0.12 per step.
- **Physics:** TALUS 0.05, SLUMP 0.22 (two slump passes per frame), FLATTEN 0.5, PLOW 0.015, SMOOTH_RATE 0.3, REGROW 0.0028 per frame (smoothness fades at 1.4x that).
- **Autopilot:** resumes 3500ms after the last input, AUTO_SPEED 0.55.
- **Light and color:** light vector (-0.45, -0.65, 0.62), rough concrete rgb(132,137,132), troweled rgb(104,112,112); sand and aggregate grain drawn once and masked away where smooth.
- **Form board:** 16px wood strip along the top edge with grain lines and a shadow onto the slab.
- **Reduced motion:** a single still frame with one finished arc; the slab only responds while being dragged. Pauses offscreen.

### Granite Coping (signature, dividers and photo cap)
Courses of split-face rose-granite blocks on a mortar bed. Full-width dividers (58px tall, two courses, the second offset by a part block) sit after the hero and after the story. A single-course cap (30px tall, transparent bed) overhangs the top of the work photo by 8px each side and 18px up, framing the photo in the wall's own stone. Blocks within 80px of the pointer or finger get shoved away from it, picking up some of its velocity and a slight rotation, then spring back with a small wobble.
- **Blocks:** ROW_H 24px, JOINT 4px, MIN_W 44px, MAX_W 96px; seeded per canvas so each wall is stable across reloads; rose base hue varied per block with split-face patches, biotite and feldspar grain, and a top lip highlight.
- **Push:** PUSH_R 80px, PUSH 0.9, MAX_OFF 9px horizontal (4.5px vertical), rotation clamped to 0.08 rad.
- **Spring:** K 38, DAMP 6.5; pointer velocity decays 0.85 per frame.
- **Reduced motion:** blocks are drawn but never pushed. Offscreen walls do not update.

**The Living Material Rule.** Motion only ever lives inside the materials (concrete, stone). Text, buttons and cards never animate beyond color transitions (0.15 to 0.2s) and the 1px press.

## Do's and Don'ts

### Do:
- **Do** take every new color from the job-site materials: slate, mortar, rose granite, safety yellow, chalk blue, concrete grey, form-board wood.
- **Do** keep safety yellow for primary fills and hover/focus responses; cues sit neutral at rest (The Curb-Stop Rule).
- **Do** outline every form control in chalk blue on hover and focus, and keep chalk blue inside the form (The Chalk-Line Rule).
- **Do** make service lists whole-row sms: links with one arrow cue each; only the arrow fills on hover.
- **Do** frame client photos in the world's own material, as the granite cap does on the work photo, and put the Facebook link directly under the work.
- **Do** keep every target at least 44px tall and match paired buttons in height and border.
- **Do** honor prefers-reduced-motion by freezing the living elements to a finished still.

### Don't:
- **Don't** add a sticky bottom bar, or a Call button under the hero headline; the phone number lives top-right in the header on the first screen.
- **Don't** put more than two buttons under the hero headline.
- **Don't** tint, outline or shadow a service row on hover.
- **Don't** use chalk blue outside the form, or yellow as the form's focus color.
- **Don't** add thin decorative highlight lines or hairline glints; depth comes from shading and slate-tinted soft shadows.
- **Don't** let either canvas run behind text; the slab sits below the hero copy and the coping sits between sections.
- **Don't** give UI cards or buttons drop shadows; only the photo, the trowel and the stone blocks cast them.
