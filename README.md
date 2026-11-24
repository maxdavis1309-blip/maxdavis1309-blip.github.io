# Max Davis | Portfolio

**Live site: https://maxdavis1309-blip.github.io/**

Portfolio of Max Davis, a mechanical engineering student at the University of Cincinnati (B.S. expected April 2027) focused on CNC machining, fixturing, inspection automation, and manufacturing software.

The site is built to be used, not just read. Each demo below runs in the browser, so a hiring manager can try the ideas in about a minute.

## What's on the site

| Section | What it shows |
| --- | --- |
| **Hero** | Click and drag across a part outline to cut a toolpath. |
| **From print to part** | A four-step walkthrough of the workflow: read the print, build the CMM program, inspect, and score the result. |
| **Cut-sequence optimizer** | Compares the order points were drawn in against a nearest-neighbour route and a 2-opt improvement. Drag any point and the routes re-solve. |
| **GD&T position zone** | Drag a measured hole centre and change the hole size to see pass or fail, and how the bonus tolerance grows under the MMC modifier. |
| **Quote sandbox** | Change material, feature count, tolerance, and quantity to see why a one-off costs far more per part than a batch of fifty. |
| **Experience** | Co-op and internship roles, in the Cincinnati–Dayton area. |

## About the data

- All demos use **invented parts, tolerances, measurements, and coefficients**. They show how a method works, not real customer data.
- Employer and customer work is not published here.

## How it's built

- One static `index.html` with plain HTML, CSS, and JavaScript. No framework and no build step on the server.
- Demos are drawn on HTML canvas.
- No analytics or tracking scripts, and no third-party script requests.
- Fonts are self-hosted from `fonts/`: [Inter](https://github.com/rsms/inter) and [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono), both under the SIL Open Font License 1.1 (license files included).
- Hosted on GitHub Pages from the `main` branch.

## Repo contents

```
index.html     the whole site
404.html       not-found page
fonts/         self-hosted fonts and their licenses
og-card.png    social preview image
robots.txt, sitemap.xml
```

## Contact

[LinkedIn](https://www.linkedin.com/in/max-davis1309/). My email is on the site's Contact section.
