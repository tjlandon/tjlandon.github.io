# tjlandon.github.io

Personal academic website for Taylor Landon, served by GitHub Pages at
https://tjlandon.github.io

## Structure

- `index.html` — home page (photo, contact info, bio, CV link)
- `research.html` — publications, working papers, works in progress
- `style.css` — shared stylesheet (colors, fonts, layout)
- `images/profile.jpg` — headshot shown on the home page
- `files/CV.pdf` — the CV, hosted here and linked from the home page
- `sitemap.xml`, `robots.txt` — tell search engines what to index
- `.nojekyll` — tells GitHub Pages to serve these files as-is, with no
  Jekyll build. Leave it in place.

## How to update

**The CV (most common update):** replace `files/CV.pdf` with the new
version, keeping the same filename. The link on the home page points at
that fixed path, so nothing else needs to change and any link anyone has
saved keeps working. On github.com: open `files/CV.pdf`, click the pencil
icon (or "Upload files" in the `files` folder), and commit.

Do not rename the file to include a date — the URL would change and old
links would break.

**Papers:** those still link to Dropbox and Google Drive share links. To
update one, overwrite the PDF in Dropbox with the new version (same
filename, via "Replace") — the share link stays the same and the website
updates automatically, with no GitHub steps.

**Text changes (new paper listed, bio edit):** edit the HTML file
on github.com — open the file in the repo, click the pencil icon, edit, and
click "Commit changes". The live site updates in about a minute.

Or, if you use GitHub Desktop: edit the file locally in any text editor,
then Commit + Push in GitHub Desktop.

**Replacing the headshot:** overwrite `images/profile.jpg`. Resize it to
roughly 700px wide first so the page stays fast.

**When you add or remove a page:** add or remove its entry in
`sitemap.xml` so search engines stay in sync.
