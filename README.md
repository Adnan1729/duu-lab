# Decisions Under Uncertainty Lab

Source for the website of the Decisions Under Uncertainty Lab, School of Mathematics, University of Edinburgh.

The site is a static website built with plain HTML and CSS. It has no build step or dependencies and is served directly by GitHub Pages.

## Structure

```
duu-lab/
├── index.html          Home
├── research.html       Research areas
├── people.html         Members
├── publications.html   Publications
├── contact.html        Contact details
├── style.css           Shared styles
├── images/             Member portraits
└── README.md
```

## Portraits

Member portraits are stored in `images/` as black-and-white JPEGs, one per member, named to match the references in `people.html`. Images are displayed at a 4:5 ratio and cropped to fill; a grayscale filter is applied in CSS for visual consistency.

## Local development

Open `index.html` in a browser to preview the site. For live reloading during editing, use a local static server such as the Live Server extension for Visual Studio Code.

## Deployment

The site is deployed with GitHub Pages from the `main` branch, root directory. Changes pushed to `main` are published automatically.

## License

© Decisions Under Uncertainty Lab, University of Edinburgh. All rights reserved.
