# Max Davis | Portfolio

**Live site: https://maxdavis1309-blip.github.io/**
**Resume (PDF): https://maxdavis1309-blip.github.io/Max_Davis_Resume.pdf**

Portfolio of Max Davis, a mechanical engineering student at the University of Cincinnati (B.S. expected April 2027) focused on CNC machining, fixturing, inspection automation, and manufacturing software.

## What's on the site

| Section | What it shows |
| --- | --- |
| **What I built** | The internal manufacturing platform I built and run at a precision quartz machining shop: quoting from the print, first-article (FAIR) packages, CMM programs, waterjet programs, live shop-floor data, and the testing and review that make it trustworthy. |
| **Beyond the platform** | Vacuum-plate fixturing work and my current senior design project, a lights-out CNC machining pilot. |
| **Demos** | Three interactive demos on invented data. See below. |
| **Experience** | Roles at Quality Quartz Engineering, General Tool Company, Avid Manufacturing, and Specialty Manufacturing Solutions. |
| **Resume** | A PDF copy of my resume, linked from the header, Experience, and Contact. |

### Interactive demos

| Demo | What it does |
| --- | --- |
| **From print to part** | A four-step walkthrough of the workflow: read the print, build the CMM program, inspect, and score the result. |
| **Cut-sequence optimizer** | Compares the order points were drawn in against a nearest-neighbour route and a 2-opt improvement. Drag any point and the routes re-solve. |
| **Quote sandbox** | Change material, feature count, tolerance, and quantity to see why a one-off costs far more per part than a batch of fifty. |

## About the data

- All demos use **invented parts, tolerances, measurements, and coefficients**. They show how a method works, not real customer data.
- Employer and customer work is described in general terms only. No customer names or internal data are published here.

## How it's built

- One static `index.html` with plain HTML, CSS, and JavaScript. No framework and no build step on the server.
- Demos are drawn on HTML canvas.
- No analytics or tracking scripts, and no third-party script requests.
- Fonts are self-hosted from `fonts/`: [Inter](https://github.com/rsms/inter) and [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono), both under the SIL Open Font License 1.1 (license files included).
- Hosted on GitHub Pages from the `main` branch.

## Repo contents

```
index.html            the whole site
Max_Davis_Resume.pdf  resume
404.html              not-found page
fonts/                self-hosted fonts and their licenses
og-card.png           social preview image
robots.txt, sitemap.xml
```

## Contact

[LinkedIn](https://www.linkedin.com/in/max-davis1309/). My email is on the site's Contact section.
