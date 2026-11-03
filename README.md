# T-Shirt Mockup

A lightweight, browser-based tool for previewing and exporting custom front-and-back T-shirt designs.

**Suggested GitHub repository description:**  
Create and customize front-and-back T-shirt mockups in your browser. Add artwork, change shirt and stripe colors, and export PNG previews.

## Features

- Preview the front and back of a shirt and customize shirt colors.
- Optionally add double sleeve stripes, with preset or custom colors.
- Add, upload, move, resize, and rotate artwork layers on either side.
- Try the built-in Alumni Texas artwork and sample front/back test images.
- Use a custom shirt photo for each side.
- Download a front PNG, back PNG, or combined front-and-back PNG.
- Choose from six interface themes; themes change the page appearance, not the shirt.

## Run locally

No build step or package installation is required.

1. Download or clone the project.
2. Open `index.html` in a modern web browser.
3. Use the **Shirt**, **Artwork**, and **Layers** tabs to customize the mockup.

The included shirt photos are in `images/`. You can also use your own image files with **Upload photo for this side** or **Upload from your computer**.

## Using image URLs

Relative image paths (for example, `images/logo.png`) work when the file is in the project folder or when the site is hosted. Online images need to allow cross-origin access (CORS) for PNG export. If an online image cannot be exported, download it and use the upload control instead.

## Export

Use **↓ Front**, **↓ Back**, or **↓ Both** to export PNG files. Enable **White bg** for a white background; otherwise, the export background is transparent.
