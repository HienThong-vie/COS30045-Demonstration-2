# COS30045 Demonstration 2 – Master repository

COS30045 Data Visualisation – Demonstration 2 (Week 7)
Chung Hien Thong (106212681), Swinburne University of Technology

**Live site (Mercury):** http://mercury.swin.edu.au/cos30045/s106212681/demo2/index.html

## What this is

All four Demonstration 2 exercises in one repository, with a landing page (`demo2`) that links to each of them. The pages share one navigation bar, so they work as one website on Mercury.

| Exercise | Folder | Live site (Mercury) |
|---|---|---|
| Landing page | `demo2` | http://mercury.swin.edu.au/cos30045/s106212681/demo2/index.html |
| 4.1 SVG house | `dv-03-svg-exercise` | http://mercury.swin.edu.au/cos30045/s106212681/dv-03-svg-exercise/index.html |
| 4.3–4.7 Website with bar chart | `dv-04-bar-chart-exercise` | http://mercury.swin.edu.au/cos30045/s106212681/dv-04-bar-chart-exercise/index.html |
| 5 Multi-chart page | `dv-05-multichart-webpage` | http://mercury.swin.edu.au/cos30045/s106212681/dv-05-multichart-webpage/index.html |
| 6 Interactivity | `dv-06-interactivity` | http://mercury.swin.edu.au/cos30045/s106212681/dv-06-interactivity/index.html |

## Individual repositories

Each exercise is also in its own repository:

| Exercise | Repository |
|---|---|
| 4.1 SVG house | COS30045-Exercise-4.1-SVG-house |
| 4.3–4.7 Website with bar chart | COS30045-Exercise-4.3-4.6-Website-with-bar-chart |
| 5 Multi-chart page | COS30045-Exercise-5-Multi-chart-page |
| 6 Interactivity | COS30045-Exercise-6-Interactivity |

## Files

```
demo2/                      landing page with a card for each exercise
dv-03-svg-exercise/         Exercise 4.1 (index.html, css, js, img)
dv-04-bar-chart-exercise/   Exercises 4.3–4.7 (index.html, css, js, data, img)
dv-05-multichart-webpage/   Exercise 5 (index.html, css, js, data, img)
dv-06-interactivity/        Exercise 6 (index.html, css, js, data, img)
```

Each exercise folder has its own README with its file list.

## Running locally

`d3.csv()` uses `fetch`, so the pages must be served over HTTP (opening the files directly with `file://` blocks the CSV).
Use the VS Code **Live Server** extension, or run `python -m http.server 8000` in the root of this repository and open http://localhost:8000/demo2/index.html.
Keep the five folders side by side, because the navigation bar uses relative links between them.
D3 v7 is loaded from `https://d3js.org/d3.v7.min.js`.

## References

- Dufour, A. M. & Meeks, E. (2024). *D3.js in Action* (3rd ed.). Manning Publications.
- COS30045 Week 4–6 exercise instructions (Canvas, 2026).
- Australian Government Energy Rating – television registration data (2026); Australian Energy Regulator – annual spot prices (1998–2024).
