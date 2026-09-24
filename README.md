# nikolaj

Personal site design tests for Nikolaj Saudella, inspired by the general style of dennissnellenberg.com
(greeting loader, giant name marquee, magnetic round buttons, floating work previews, curved dark footer)
mixed with the serif / minimal language of the earlier versions.

Open `index.html` to compare the three directions:

| File | Direction |
| --- | --- |
| `studio.html` | Dark stage portrait, Inter Tight, blue accent — closest to the reference |
| `editorial.html` | Paper + Instrument Serif, B&W portrait with colour spotlight, Bologna-red accent |
| `kinetic.html` | Archivo Expanded, name that parts as the portrait grows full-screen, horizontal track record, lime accent |

Everything is static HTML/CSS/JS. Serve the folder locally (e.g. `npx serve .`) so the relative `assets/` paths resolve.
Smooth scrolling uses a vendored copy of [Lenis](https://github.com/darkroomengineering/lenis) (MIT) in `assets/lenis.min.js`;
the pages fall back to native scrolling without it.
