# tjlandon.github.io

Personal academic website for Taylor Landon, served by GitHub Pages at
https://tjlandon.github.io

## Structure

- `index.html` — home page (photo, contact info, bio, CV link)
- `research.html` — publications, working papers, works in progress
- `style.css` — shared stylesheet (colors, fonts, layout)
- `images/profile.jpg` — headshot shown on the home page
- `files/` — optional: put PDFs here if you want them hosted on GitHub
  instead of Dropbox (e.g. `files/CV_academic.pdf`)
- `.nojekyll` — tells GitHub Pages to serve these files as-is, with no
  Jekyll build. Leave it in place.

## How to update

**Papers and CV (most common update):** the site links to your Dropbox share
links. Just overwrite the PDF in your Dropbox folder with the new version
(same filename, via "Replace" or by copying over it) — the share link stays
the same and the website updates automatically. No GitHub steps needed.

**Text changes (new paper listed, bio edit):** edit the HTML file
on github.com — open the file in the repo, click the pencil icon, edit, and
click "Commit changes". The live site updates in about a minute.

Or, if you use GitHub Desktop: edit the file locally in any text editor,
then Commit + Push in GitHub Desktop.

**Replacing the headshot:** overwrite `images/profile.jpg`. Resize it to
roughly 700px wide first so the page stays fast.
