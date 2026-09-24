# charity: water student landing page

This beginner-friendly project turns the Canva hero mockup into a responsive one-page website using only HTML and CSS.

## Open the website

1. Open this folder in your Codespace or code editor.
2. Open `index.html` with Live Server, or double-click it to open it in a browser.
3. Edit `index.html` for words and links. Edit `styles.css` for colors, spacing, and layout.

## Background photo

The original Canva background is already included at `img/hero-photo.jpg`. The CSS uses a custom sunset illustration only as an automatic fallback if that file is moved or renamed.

To use a different photo later, put it in the `img` folder and name it exactly `hero-photo.jpg`, replacing the current file.

For the sharpest result, use a landscape JPG around 1600–2000 pixels wide and under about 500 KB. If the subject is cropped too far left or right, adjust the `background-position` values in the `.hero` rules in `styles.css`.

## Project structure

```text
charity-water-landing-page/
├── index.html
├── styles.css
├── README.md
└── img/
    ├── canva-reference.png
    ├── hero-background.svg
    └── hero-photo.jpg        ← original Canva background photo
```

## What is included

- A responsive hero closely matching the Canva design
- Desktop and mobile navigation
- Accessible keyboard focus, a skip link, and readable contrast
- About, student action, and final call-to-action sections
- Working links to charity: water's donation and login pages
- No framework, build step, or JavaScript

This is an independent student concept and is not an official charity: water website.
