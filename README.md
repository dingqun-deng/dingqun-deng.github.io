# dingqun-deng.github.io

Personal academic homepage of Dingqun Deng, served by GitHub Pages at
<https://dingqun-deng.github.io>.

## Files

| File            | Purpose                                             |
| --------------- | --------------------------------------------------- |
| `index.html`    | Home — affiliation, contact, positions and education |
| `research.html` | Research interests, publications, preprints, thesis  |
| `teaching.html` | Courses taught                                       |
| `talks.html`    | Conference, workshop and seminar talks               |
| `style.css`     | Shared stylesheet for all four pages                 |
| `.nojekyll`     | Tells GitHub Pages to serve the files as-is          |

Plain HTML and CSS — no build step, no dependencies. Edit a file, commit,
push, and the live site updates within about a minute.

## How to edit

**Adding a publication.** Open `research.html`, copy an existing `<li>` block
inside `<ol class="pubs" reversed>`, and paste it at the *top* of the list.
The numbering is automatic — `reversed` counts down from the number of
entries, so a new entry at the top becomes the highest number by itself.

**Adding a talk or course.** Same idea: copy the nearest `<li>` in
`talks.html` or `teaching.html` and edit the text.

**Adding a photo.** Put a square image named `photo.jpg` next to
`index.html`, then uncomment the `<img class="portrait" ...>` line near the
top of the `<div class="intro">` block.

**Adding a CV.** Drop `cv.pdf` into this folder and add a link wherever you
want it, e.g. in the contact line on `index.html`:

```html
<p class="contact">
  Email: <a href="mailto:dingqun.deng@gmail.com">dingqun.deng@gmail.com</a>
  &middot; <a href="cv.pdf">CV</a>
</p>
```

## Enabling GitHub Pages

Repository → Settings → Pages → Source: *Deploy from a branch* → Branch:
`main`, folder `/ (root)` → Save.
