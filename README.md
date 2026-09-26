# My research website

Built from two free HTML5 UP templates:
- **Dimension** → the space front page and pop-up tabs (`index.html`)
- **Multiverse** → the photo gallery (`gallery.html`)

## What to edit

| What | Where |
|---|---|
| Your name, one-line tagline | `index.html` → top section (search for `Your Name`) |
| About, Research, CV, Community, Contact tabs | `index.html` → each `<article>` block |
| Space background | replace `images/bg.jpg` (keep the same name) |
| Intro picture | replace `images/intro.jpg`, or delete that line in `index.html` |
| CV PDF | replace `files/cv.pdf` (keep the same name) |
| Photos | `images/gallery/fulls/` (big) and `images/gallery/thumbs/` (small), then `gallery.html` |

Tip: in any editor, search for `EDIT` and `Your Name` to find every placeholder.

### Adding a photo
1. Put `10.jpg` in `images/gallery/fulls/` and a smaller copy in `images/gallery/thumbs/` (same name).
2. In `gallery.html`, copy one `<article class="thumb"> … </article>` block, change `09` to `10`, and edit the title and caption.

### Contact form
GitHub Pages can't send email by itself. Sign up free at formspree.io, create a form, and replace
`YOUR_FORM_ID` in `index.html` with your ID. (Or delete the `<form> … </form>` block and keep just the email link.)

## Putting it online with GitHub Pages
1. Create a GitHub account, then a **new public repository** named `yourusername.github.io`.
2. On the repo page click **Add file → Upload files**, drag in *everything inside this folder*
   (so `index.html` sits at the top level, not inside a sub-folder), then **Commit changes**.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, Save.
4. After a minute or two the site is live at `https://yourusername.github.io`.

To update later, upload the changed files again (same names overwrite the old ones), or edit them
directly on GitHub with the pencil icon.

## Credits
Design: [HTML5 UP](https://html5up.net) (CCA 3.0 license — keep the "Design: HTML5 UP" credit in the footers).
