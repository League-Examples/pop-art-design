# League of Amazing Programmers — Visual Styles

This project produces promotional artwork for **The League of Amazing Programmers**
and its **League Labs** robotics program. The artwork uses **two distinct illustration
styles**. They look related — both are bold, ink-outlined, retro, and robot-focused —
but they are **not the same style**, and going forward we keep them **separate**.

These docs exist so we (and other agents / image models) can describe, request, and
judge each style precisely instead of blending them.

| | **Comic Style** | **Pop-Art Style** |
|---|---|---|
| **Era / lineage** | 1940s Golden-Age comics (Superman, Captain America) + modern action-comic panels | 1960s gallery pop art (Roy Lichtenstein) |
| **The one-glance tell** | **Flat solid color, NO halftone dots** | **Ben-Day dots everywhere** |
| **Palette** | Warm 4-color newsprint: red, blue, yellow, **flesh + browns**, black, aged-paper cream | Strict primaries: **red, yellow, blue, black, white** |
| **Shading** | Single flat black shadow shapes (cel shading) | Dot-density gradients (Ben-Day) + flat color |
| **Format** | Full comic **cover** w/ masthead furniture, or sequential **story panels** w/ caption boxes | Single dramatic **poster/panel**, big faces, starburst balloons |
| **Lettering** | Vintage cover logo, starburst title banner, narration caption boxes | Burst speech balloons + one big sound effect (`WHAM!`) |
| **Reference files** | [GreatestInvention](../images/GreatestInvention.png), [RobotRiot](../images/RobotRiot.png), [His Master's Voice](../projects/HisMastersVoice/) | [robot-arena](../images/robot-arena.png), [boy-mecha](../images/boy-mecha.png), [Robots-2kids-table](../images/Robots-2kids-table.png), [BringHomeTheFuture](../images/BringHomeTheFuture.png), [ThatWasFun](../images/ThatWasFun.png) |

## The single deciding question

> **Are there Ben-Day halftone dots?**
> Dots → **Pop-Art**. Flat color, no dots → **Comic**.

Everything else (palette breadth, cover furniture vs. caption boxes, flesh tones vs.
strict primaries) follows from that.

## Style docs

- [comic-style.md](comic-style.md) — the Golden-Age comic look (covers + story panels)
- [pop-art-style.md](pop-art-style.md) — the Lichtenstein pop-art look

## Shared ground (true of both styles)

Both styles share the brand and subject matter, so these rules hold either way:

- **Real student robots, rendered faithfully.** Robots are compact, classroom-built
  educational machines (Micro:bit-style controller boards, two-wheel-drive chassis,
  visible batteries, exposed wiring, small servos, plastic beam structures, simple
  grabbers / forks / paddles / scoops). They are **stylized into the art style** but
  keep the real proportions and engineering. They are **not** battlebots, mechs,
  humanoid robots, race cars, or sci-fi machines. (The lone exception is the
  intentionally heroic giant robot in [boy-mecha](../images/boy-mecha.png).)
- **Kids are the heroes.** Children are expressive, proud, focused, excited —
  inventors and competitors, never passive.
- **Celebrate ingenuity** — engineering, creativity, teamwork, competition, discovery.
- **No outside branding or wall text.** No logos, posters, slogans, or floating
  typography except the lettering the style itself calls for. Any code appears **only**
  on a laptop screen facing the viewer.
- **No** Funko Pop / vinyl-toy proportions, chibi, oversized heads, Pixar, anime-cartoon,
  3D/CGI, or photorealism.

## Source photos

The `IMG_*.png` files in [images/](../images/) and reference shots are **source
photographs** (the garage, the playfield, the actual robots and controllers) — the raw
input that gets transformed into either style. They are not finished artwork.
