# Comic Style

The **Golden-Age comic-book look**: hand-inked, cel-shaded illustration with bold black
outlines and large fields of **flat solid color** — the look of early-1940s newsstand
comics (*Superman*, *Captain America*), extended into modern action-comic story panels.

> **The defining rule:** flat color, **no Ben-Day halftone dots**. If you see dots, it's
> the [pop-art style](pop-art-style.md), not this.

## Reference artwork

- [GreatestInvention.png](../images/GreatestInvention.png) — vintage **cover** mode: a young
  inventor soldering a robot arm, full newsstand cover furniture, starburst title
  "HER GREATEST INVENTION!"
- [RobotRiot.png](../images/RobotRiot.png) — vintage **cover** mode: four kids driving
  robots in an arena, starburst title "ROBOT RIOT!"
- [projects/HisMastersVoice/](../projects/HisMastersVoice/) — **story-panel** mode: a
  masthead banner ([Head.png](../projects/HisMastersVoice/Head.png)) plus sequential panels
  (`panel1`–`panel4`) telling a story with narration caption boxes.

The source prompt for the cover mode lives in
[Prompts/comic-book-cover.md](../Prompts/comic-book-cover.md).

## Two modes

This style ships in two layouts that share the same rendering rules:

### A. Vintage cover
A full newsstand comic-book cover — one heroic illustration framed by classic "cover
furniture" (see below). Used for hero images and posters. Examples: *Greatest Invention*,
*Robot Riot*.

### B. Story panels
Sequential interior panels (and a wide masthead banner) that tell a short story. More
dynamic, modern action-comic energy: dramatic poses, radiating speed/action lines, and
single-color background fields (a panel might be all yellow, the next all blue). Narration
is delivered in **caption boxes**, not cover furniture. Example: *His Master's Voice*.

## Rendering rules

**Linework**
- Bold, confident **black ink outlines** with varied weight.
- Clean cel art — shapes are drawn and filled, not painted.

**Color**
- Large, **unbroken fields of solid flat color**.
- Restricted four-color-press palette: roughly **5–7 ink colors total** — red, blue,
  yellow, **flesh tone**, black — over one or two flat background color zones.
- Flesh tones and warm browns (hair, skin, wood, robot metal) are allowed and expected —
  this palette is **wider and warmer** than pop-art's strict primaries.
- Background sits on a **warm aged-newsprint / cream** tone (cover mode) or a single
  saturated color field per panel (story mode).

**Shading**
- Shadows are **single flat black shapes**. No hatching, no cross-hatching, no gradients.

**Explicitly forbidden**
- ❌ Ben-Day dot halftones (this is the #1 difference from pop-art)
- ❌ cross-hatching, rendered gradients, fine line texture, airbrush
- ❌ photorealism, 3D/CGI, painterly brushwork

## Focus & detail

- Spend detail **only** on (1) the kid(s) and (2) the robot / invention they're working on.
- Everything else simplifies to flat color and bold outline — **no cluttered rooms**, no
  extra props, blank background surfaces.
- Stylize faces enough that they read as **illustrated comic characters**, not identifiable
  people.
- Keep robots **low-detail like the characters**, with physically plausible grippers,
  pushers, hooks, or arms.

## Cover furniture (cover mode only)

Compose as a full vintage newsstand cover with these elements:

- **Masthead**, three stacked lines, vintage hand-drawn logo type with heavy black drop
  shadow:
  - "THE LEAGUE OF" — top, smaller, yellow with black outline
  - "AMAZING" — center, largest, orange `#F47920` with black outline
  - "PROGRAMMERS" — bottom, medium, yellow with black outline
- **Lightning bolts** flanking "THE LEAGUE OF" — flat solid orange `#F47920`, upright, one
  each side (in place of stars).
- **Subhead strip** under the logo: "SMART MINDS · BOLD IDEAS · BRIGHT FUTURES".
- **Price corner box** (top left): "10¢".
- **Issue / date corner** (top right): "NO. 1 / JUNE".
- **Approval badge** (upper right): circular stamp built around the League robot logo, with
  "APPROVED BY" curving the inside top and "THE CREATORS CODE AUTHORITY" the inside bottom.
- **Callout box**: one small rectangular callout (e.g. "MEET A YOUNG INVENTOR!",
  "WHOSE ROBOT WILL PREVAIL?"), placed so it covers no face or robot.
- **Cover title**: large dramatic hand-lettered title in a **jagged starburst banner** in
  the lower third (e.g. "HER GREATEST INVENTION!", "ROBOT RIOT!").
- **Background**: flat yellow behind the characters, below the subhead.

## Captions & lettering (story-panel mode)

- **Narration caption boxes**: small rectangular boxes (often yellow with a black border),
  italic, set in a corner of the panel — third-person narration ("Valente had an idea…").
- Action emphasized with **radiating speed lines / impact lines** and motion streaks.
- Speech is sparse; if used, short.

## Text rules (both modes)

- Render **only** the specified text — exact wording, nothing else.
- Do **not** invent posters, signs, slogans, labels, or extra lettering. Background
  surfaces are blank.

## Mood

Heroic, optimistic, aspirational, exciting, competitive — kids proud of what they build
and command.

## Prompt skeleton

> Transform the attached photo into a **1940s Golden-Age comic-book illustration** in the
> style of early *Superman* / *Captain America* covers. Hand-drawn cel art: bold black ink
> outlines, large unbroken fields of **flat solid color**, a restricted 5–7-color press
> palette (red, blue, yellow, flesh, black) over a warm aged-newsprint background. Shadows
> are single flat black shapes. **No Ben-Day dots, no cross-hatching, no gradients, no
> photorealism.** Spend detail only on the child and the robot; simplify everything else to
> flat color. Render only this text: `[masthead + title + callout]`. Mood: heroic,
> optimistic, aspirational.

(For story panels, swap the cover furniture for a single saturated background field, a
narration caption box, and radiating action lines.)
