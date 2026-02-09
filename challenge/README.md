# Challenge — CSS practice pages

This folder contains a small CSS challenge/demo used for practicing layout and styling techniques.

## Contents

- `index.html` — primary demo page.
- `index1.html` — alternate/demo variation.
- `style.css` — styles for `index.html`.
- `style1.css` — styles for `index1.html`.
- `images/` — image assets used by the pages.

## Overview

Both HTML files are self-contained examples that reference the CSS files in this folder and the images in the `images/` directory. They showcase responsive layout and styling concepts used while practicing.

## How to view

1. Open the files directly in your browser by double-clicking `index.html` or `index1.html`.
2. Or serve the project locally (recommended) and open the pages via HTTP:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000/challenge/index.html` or `http://localhost:8000/challenge/index1.html`.

## Notes

- CSS files are linked in the HTML head; edit those to change styles.
- Image paths are relative to the `images/` folder.
- Test resizing the browser to see responsive behaviors.

## Author / License

Created for personal CSS practice. Feel free to reuse or modify for learning.
