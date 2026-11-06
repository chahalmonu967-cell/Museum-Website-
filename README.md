# Museo Sans — Responsive Museum Website

A responsive HTML and CSS recreation of the museum website shown in the assignment references.

## Run locally
1. Extract the ZIP file.
2. Open the `Museum-Website` folder in VS Code.
3. Open `index.html` with the VS Code **Live Server** extension, or open it directly in a browser.
4. Keep an internet connection active so Google Fonts and the original artwork images can load.

## Project structure
- `index.html` — semantic page structure and mobile navigation behaviour
- `css/style.css` — layout, styles, hover animations, and responsive breakpoints
- `images/ASSET-SOURCES.md` — original artwork source and licensing links

## Responsive behaviour
- **Desktop (above 1050px):** large city card on the left; wide bread card and two lower cards on the right.
- **Tablet and phone (1050px and below):** city and bread cards stack; portrait and vintage cards sit side-by-side.
- **Small screens:** compact header with a working Menu toggle and smaller card typography.

## Included requirements
- Semantic HTML5 elements and descriptive image alternative text
- Inter imported from Google Fonts and used for all page text
- Responsive media queries for desktop, tablet, and phone
- Hover effects on navigation, artwork images, and Get Started links
- Button scale and colour transition on hover
- Organized project folders

## Artwork image note
The artwork is no longer cropped out of your screenshots. The page uses the original hosted artwork images, with their source pages listed in `images/ASSET-SOURCES.md`. Internet access is required to load those image URLs. For a fully offline copy, save the original artwork files in `images/` and replace their remote URLs in `index.html` with local file paths.
