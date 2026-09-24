# nikolaj

Personal site design tests for Nikolaj Saudella, inspired by the general style of dennissnellenberg.com
(greeting loader, giant name marquee, magnetic round buttons, floating work previews, curved dark footer)
mixed with the serif / minimal language of the earlier versions.

Open `index.html` to compare all directions.

Round 1:

| File | Direction |
| --- | --- |
| `studio.html` | Dark stage portrait, Inter Tight, blue accent — closest to the reference |
| `editorial.html` | Paper + Instrument Serif, B&W portrait with colour spotlight, Bologna-red accent |
| `kinetic.html` | Archivo Expanded, name that parts as the portrait grows full-screen, horizontal track record, lime accent |

Round 2 — explorations that start from Studio but leave the reference's signature devices behind:

| File | Direction |
| --- | --- |
| `darkroom.html` | The pointer is the key light; the portrait only shows where the light falls |
| `cinema.html` | The site as a short film: leader countdown, letterbox, subtitles, scenes, end credits |
| `chapters.html` | Sticky portrait that re-frames itself for each chapter of the story |
| `letters.html` | Portrait inside giant type; scroll through the I of NIKOLAJ |
| `card.html` | Holographic esports-style player card with achievements and a main quest |

Round 3 — built to a written brief:

| File | Direction |
| --- | --- |
| `minimal.html` | Italian, Snellenberg-style brief: grey hero with a cut-out portrait, GSAP + ScrollTrigger + SplitText, curved page transitions between Home and Chi sono |

Everything is static HTML/CSS/JS. Serve the folder locally (e.g. `npx serve .`) so the relative `assets/` paths resolve.
Smooth scrolling uses a vendored copy of [Lenis](https://github.com/darkroomengineering/lenis) (MIT) in `assets/lenis.min.js`;
the pages fall back to native scrolling without it. `minimal.html` also uses vendored GSAP 3.13 (ScrollTrigger, SplitText,
CustomEase) under GreenSock's standard no-charge license. `assets/nikolaj-cutout*.webp` is the portrait with the background removed.
