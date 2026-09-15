# Hassanpreet Dhaliwal — Air Quality Portfolio

This is a static GitHub Pages portfolio. No build step is required.

## 1. The fastest way to publish

1. Create a GitHub repository named exactly:
   `YOURUSERNAME.github.io`
2. Upload **everything inside this folder** to the repository root.
3. In GitHub go to **Settings → Pages**.
4. Under "Build and deployment", choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
5. Save.
6. Your site should appear at `https://YOURUSERNAME.github.io`.

## 2. Exactly where to add your images

All images live here:

`assets/images/`

The easiest method is to export your figure as PNG/JPG/WebP and give it the SAME NAME
as the placeholder you are replacing. You then do not need to edit HTML.

### Hero image
Replace:
`assets/images/hero-visual.svg`

Suggested content:
A high-impact AOD map, satellite composite, or elegant regional geospatial visualization.

### Project images

Project 1 — VIIRS/AERONET satellite validation
Replace:
`assets/images/project-viirs.svg`

Suggested:
A redesigned satellite-vs-AERONET scatterplot, station map, or a clean 2-panel validation graphic.

Project 2 — AOD / PM2.5 / boundary-layer events
Replace:
`assets/images/project-aod-pm.svg`

Suggested:
Your strongest time series combining AOD, PM2.5, boundary-layer height, or meteorology.

Project 3 — long-term land-atmosphere observational analysis
Replace:
`assets/images/project-land-atmosphere.svg`

Suggested:
Station map, seasonal heatmap, SM–T plot, VPD-regime figure, or rainfall composite.

Project 4 — data pipeline / reproducible analytics
Replace:
`assets/images/project-pipeline.svg`

Suggested:
A workflow diagram, pipeline graphic, or screenshot of a polished geospatial/data-processing product.

### Visualization gallery

Replace these six files:
- `gallery-map.svg`
- `gallery-timeseries.svg`
- `gallery-scatter.svg`
- `gallery-heatmap.svg`
- `gallery-profile.svg`
- `gallery-workflow.svg`

Use:
1. a map
2. a time series
3. a scatter/validation plot
4. a heatmap or categorical/regime comparison
5. a vertical profile/lidar plot
6. a workflow/data-pipeline visual

### Image format
You may replace an SVG with a PNG, but then edit the filename in `index.html`.

Example:
Change:
`src="assets/images/project-viirs.svg"`

to:
`src="assets/images/project-viirs.png"`

Recommended image export:
- 1600–2200 px wide for project figures
- PNG or WebP
- crop excess white journal margins
- increase axis/legend font sizes before exporting

## 3. Add your CV

Put your CV here:

`assets/docs/Hassanpreet_Dhaliwal_CV.pdf`

The "Download CV" button already points to that file.

## 4. Add your personal links

Open `index.html` in any text editor.

Search for:
`REPLACE THESE THREE # VALUES`

Immediately below it, replace the `#` in each link with:
- email: `mailto:your@email.com`
- LinkedIn URL
- Google Scholar URL
- GitHub URL

## 5. Add publication links

In `index.html`, search for:
`Add paper link`

Replace the `href="#"` with the DOI, publisher page, or Google Scholar link.

## 6. Change any text

Nearly all editable text is in:
`index.html`

Styling is in:
`style.css`

You can edit the HTML directly in GitHub by clicking the pencil icon.

## 7. Positioning strategy used in this website

Primary identity:
**Air Quality Scientist**

Differentiators:
- Satellite remote sensing
- Spatial and temporal data analysis
- Large observational datasets
- Satellite + surface data integration
- Environmental data visualization
- Python / geospatial analytics
- Instrument and QA/QC literacy

This is deliberate: it keeps you credible for air-quality research/policy roles while
also making you legible to geospatial-data-science employers.

## 8. Do not overload the site

Recommended:
- 4 flagship projects
- 6 excellent visualizations
- 2–4 selected publications
- CV + Google Scholar for everything else

The portfolio should show what you can *do*, not duplicate your academic CV.
