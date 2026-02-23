# Visual Sitemap Tool

A browser-based tool for building and exporting visual website sitemaps. Enter a list of pages using indentation to define hierarchy, then generate and export a clean box-and-line diagram as a JPG.

## Features

- **Indented text input** — define page hierarchy with spaces or tabs
- **Box-and-line diagram** — clean tree layout with elbow, straight, or curved connectors
- **Level-based color coding** — distinct colors for root, top-level, sub-pages, and deeper nesting
- **Customizable appearance** — box style (rounded, sharp, pill), dimensions, spacing, font, and per-level colors
- **Export as JPG** — download the sitemap at full resolution
- **Zoom controls** — zoom in/out or fit the diagram to the window
- **Live preview** — settings update the diagram in real time

## Usage

1. Open `index.html` in any modern browser — no build step or server required
2. Enter your pages in the text area, one per line, indented to indicate nesting:
   ```
   Home
     About
       Team
       History
     Products
       Product A
     Contact
   ```
3. Adjust appearance settings in the sidebar
4. Click **Generate Sitemap**
5. Click **Export as JPG** to download

## Input Format

- One page per line
- Use **2 spaces**, **4 spaces**, or **tabs** per indent level
- The first non-indented line becomes the root node
- Multiple root-level lines are wrapped under a virtual "Site" root automatically
