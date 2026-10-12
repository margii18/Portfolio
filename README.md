# Margi Patel — Portfolio Website

A responsive single-page portfolio with **Home**, **About**, and **Resume** sections.

## Files

```
margi-portfolio/
├── index.html
├── README.md
└── assets/
    ├── margi-portrait.jpg
    └── margi-resume.jpg
```

## Preview locally

Open `index.html` in a web browser. An internet connection is used to load the Google Fonts; the site still works without them.

## Publish using GitHub Pages

1. Create a new public GitHub repository (for example, `margi-portfolio`).
2. Upload **index.html** and the **assets** folder to the repository root (or push the entire contents of this folder).
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose **main** and **/(root)**, then click **Save**.
6. After GitHub publishes the site, open the URL shown in the Pages settings. It will generally have the format `https://YOUR-USERNAME.github.io/margi-portfolio/`.

## Customization

- Edit the text, contact email, and social links inside `index.html`.
- Replace the files in `assets/` with new images while keeping their file names.
- Edit the colors in the CSS `:root` variables near the top of `index.html`.

The resume in the provided image is embedded as an image, not as accessible selectable text. Consider adding a text-based HTML or PDF resume later for better accessibility and searchability.
