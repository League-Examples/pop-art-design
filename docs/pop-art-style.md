# Pop-Art Style

The **1960s gallery pop-art look**: an authentic **Roy Lichtenstein**-inspired painting —
bold black contours, **precise Ben-Day dot patterns throughout**, and flat primary colors.
The target is "a lost 1960s Lichtenstein museum canvas," not a modern illustration.

> **The defining rule:** **Ben-Day halftone dots everywhere** — in skin, skies, shadows,
> and background fields. If the color is flat with no dots, it's the
> [comic style](comic-style.md), not this.

## Reference artwork

- [robot-arena.png](../images/robot-arena.png) — robots colliding in an arena, kids reacting
  around the perimeter, "WHAM!" sound effect, foam balls and cubes. The canonical example.
- [boy-mecha.png](../images/boy-mecha.png) — a young inventor in a homemade superhero costume,
  akimbo beside the giant robot he built; yellow dot-field background, laptop with code.
- [Robots-2kids-table.png](../images/Robots-2kids-table.png) — extreme close-up of two kids'
  faces as their robot comes to life.
- [BringHomeTheFuture.png](../images/BringHomeTheFuture.png) — two kids + robot, burst speech
  balloon "LET'S BRING HOME THE FUTURE!", marketing caption strip.
- [ThatWasFun.png](../images/ThatWasFun.png) — two delighted kids + robot, balloon "THAT WAS
  FUN! LET'S DO IT AGAIN!", marketing caption strip.

The source prompts live in [Prompts/image_prompts.md](../Prompts/image_prompts.md).

## Rendering rules

**Linework**
- **Bold black contour lines**, crisp and graphic.
- Clean, hard-edged shapes; high contrast.

**Color**
- **Flat primary colors only**: strong **red, yellow, blue, black, white**. This palette is
  **narrower and cooler** than comic style — no soft flesh/brown blends; skin is rendered in
  dot-shaded primaries.
- Backgrounds are simple flat or dotted color fields, **minimal detail**.

**Halftone**
- **Precise Ben-Day dot patterns throughout** — the signature element. Used for skin tones,
  background fields, skies, and shading gradients (dot density = value).

**Composition**
- Dramatic, graphic, high-contrast. Often **extreme close-up** with big, emotionally intense
  faces, or a **low-angle field-level** action viewpoint for arena scenes.
- Strong sense of speed: **motion lines**, flying game pieces, near-collisions, mechanical
  precision, competitive tension. ("Formula One + hockey + middle-school robotics tournament
  in one frame.")
- A recurring motif: an **open laptop**, screen facing the viewer, showing simple readable
  code. **Code appears only on that screen.**

## Lettering

- **Burst / starburst speech balloons** containing one short, punchy line:
  "LET'S BRING HOME THE FUTURE!", "THAT WAS FUN! LET'S DO IT AGAIN!".
- **One** comic-book sound effect, integrated into the action: `WHAM!`, `CLASH!`, `ZOOM!`,
  or `BAM!` — at most one per image.
- Optional thin **caption strip** along the bottom for a marketing line + the small League
  logo (e.g. "Your Kids, Our Robots. Host a Tech club.").
- No other text, labels, or wall lettering.

## Subjects

- **Kids:** big, expressive, emotionally dramatic faces in classic comic fashion —
  cheering, reacting, strategizing, concentrating. In arena scenes, **all children are
  outside the playfield**, around the perimeter as drivers/spectators; no child is inside.
- **Robots:** rendered **faithfully to the real student-built robots** (Micro:bit-style
  boards, two-wheel-drive chassis, visible batteries, exposed wiring, servos, plastic beams,
  simple grabbers/forks/paddles/scoops) — stylized into pop-art but keeping real proportions
  and classroom-built character. Not battlebots, mechs, humanoids, or race cars.
- **Game pieces:** bright foam balls, colored cubes, scoring objects — matching real
  competition elements; everything on the field belongs to the game.
- **Controllers (when shown):** the real Micro:bit joystick controllers, shown **from the
  rear** as held during play (battery compartment, bracket, screws, red-and-blue side grips
  visible; the Micro:bit display faces the child, away from the viewer). Never draw them as
  video-game gamepads, and never invent extra buttons/triggers/thumbsticks.

## Explicitly forbidden

- ❌ No Funko Pop, vinyl-toy proportions, chibi, oversized heads
- ❌ No Pixar, anime, mascot characters, cartoon-merchandising look
- ❌ No CGI, 3D render, photorealism, painterly brushwork, modern digital-illustration style
- ❌ No logos, branding, motivational posters, wall text, floating typography, slogans
- ❌ No weapons, lasers, explosions, or military imagery (the action is strategic, not violent)
- ❌ No text/code/screens on walls, furniture, robot parts, tools, clothing, or monitor backs
  — code lives only on the front-facing laptop screen

## Mood

Celebratory and electric — ingenuity, engineering, competition, teamwork, and the thrill of
educational robotics, captured at the moment of maximum excitement.

## Prompt skeleton

> **Authentic Roy Lichtenstein-inspired 1960s pop-art painting** of `[scene]`. Bold black
> contour lines. **Precise Ben-Day dot patterns throughout.** Flat primary colors — strong
> red, yellow, blue, black, and white. Crisp graphic shapes, high contrast, minimal
> background. Should resemble a lost 1960s Lichtenstein museum canvas, not a modern
> illustration. Big expressive comic-book faces; [optional: low-angle, motion lines, speed].
> Robots rendered faithfully to the uploaded student-built robots. One burst speech balloon:
> `[short line]`; at most one sound effect (`WHAM!`). No Funko Pop / Pixar / anime / CGI /
> photorealism. No wall text or logos; any code only on the laptop screen.
