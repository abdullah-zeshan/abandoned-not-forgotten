# Abandoned, not forgotten

**An interactive story about the machines NASA left behind on the Moon and Mars.**

Astronauts could only stay a few days. The machines they left were meant to keep going for years. This site follows three of them from launch to silence and shows where they are today.

**Live site:** [add your link here]

## The three stories

| Machine | Where | What the story covers |
|---|---|---|
| **ALSEP** (Apollo Lunar Surface Experiments Package) | The Moon | Nuclear-powered science stations that kept listening until they were switched off in 1977 |
| **Lunar Module descent stage** | The Moon, Ocean of Storms | The landing platform that became a launch pad, and what Apollo 12 learned about dust |
| **Sojourner** | Mars, Ares Vallis | The rover built to last a week that worked for 83 sols |

Ten smaller machines (Lunar Roving Vehicles, Surveyor, Spirit and Opportunity, Viking, Phoenix and InSight, Ingenuity, Dawn, NEAR Shoemaker, Pioneer, Kepler) are in the "More left behind" drawer, each linking to NASA.

## Experience

- **Real 3D Moon and Mars** built from NASA-derived surface maps, with relief and an atmosphere glow on Mars. The camera follows your scroll, and clicking a planet flies you to its story.
- **Scroll-driven storytelling:** loader, title, plot, a draggable row of machine cards, giant "still up there" numbers and a footer.
- **Full-screen story panels:** each card expands into a looping video background with the story in front of it (problem, machine, discoveries, ending, what remains) plus a timeline.
- **Interactive map:** pan across the real Moon and Mars surfaces and find each landing site. Positions are approximate.
- **Gallery** of mission photographs.
- **Original ambient score** generated live in the browser, with an optional "Enter silent" mode.
- **Responsive and accessible:** works on phones, keyboard navigable, labelled dialogs, skip link, reduced-motion support.

## Built with

- HTML, CSS and vanilla JavaScript in a single page, no build step
- [three.js](https://threejs.org/) (r128) for the planets
- Web Audio API for the music
- Montserrat and Newsreader via Google Fonts

## Run it locally

No install needed. Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Project structure

```
index.html     the whole site
vid/           background videos for the three stories
robots.txt
```

## Sources and credits

- Mission facts: NASA Space Science Data Coordinated Archive (NSSDCA), NASA mission pages, NASA SP-350, the ALSEP Termination Report and NASA's Lunar Reconnaissance Orbiter (LRO) pages.
- Photographs: NASA and NASA/JPL-Caltech.
- Planet textures: NASA-derived maps from the open-source [threex.planets](https://github.com/jeromeetienne/threex.planets) project.
- Video clips: [add the source and licence of your clips here].
- Music: original, generated in the browser.

## Disclaimer

This is an independent project. It is not affiliated with or endorsed by NASA. Map positions are approximate.

## Team

[add team names here]

## Licence

[add a licence here, for example MIT for the code]

---

Created for the NASA International Space Apps Challenge 2026, "Abandoned but Not Forgotten: Storytelling about NASA's Discarded Equipment on the Moon and Mars."
