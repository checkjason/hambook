# Alexander Hamilton: A Reader (14+ edition)

A 14-chapter reading app plus printable PDFs. Plain HTML, no build step, works offline after the first visit.

- `index.html` is the reader (chapters, notes, text size, dark mode, saves her place).
- `downloads/` has the reading-copy PDF and the legal-size booklet.
- `graphic-novel/` is the earlier graphic novel and workbook, linked from the home page.

## Put it on GitHub Pages
1. Create a repository (for example `hamilton`) and upload everything in this folder, including the hidden `.nojekyll` file.
2. Settings > Pages > Deploy from a branch > `main` > folder `/ (root)` > Save.
3. After a minute it is live at `https://YOUR-USERNAME.github.io/hamilton/`. If you upload this folder as a subfolder of an existing repo (such as `hamilton-site`), the address ends with that folder name, for example `https://checkjason.github.io/hamilton/hamilton-site/`.

## Add it to the iPad
Open the link in Safari, tap Share > Add to Home Screen. Open it once on Wi-Fi so it saves for offline use.

## Print the booklet
Open `downloads/Hamilton_Booklet_LEGAL_print.pdf`. Print on legal paper, landscape, scale 100% (Actual size), double-sided, flip on the short edge. Fold the stack in half.

## Updating
Replace files and change `hamilton-book-v1` in `sw.js` to `-v2` so devices refresh.
