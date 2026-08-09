# LBSD website

Static GitHub Pages website for the Laboratory of Biomolecular Structure & Dynamics (LBSD), Department of Biotechnology, JIIT Noida.

Modeled on the information architecture of a typical academic lab site (e.g. Dhanjal Lab): Home with latest updates and contact, plus People, Research, Publications, Teaching, Opportunities, News, and Contact.

## Pages

| File | Purpose |
|------|---------|
| `index.html` | Welcome, latest updates, contact teaser, research themes |
| `people.html` | PI profile, students, alumni |
| `research.html` | Research themes |
| `publications.html` | Year-wise publications |
| `teaching.html` | Courses |
| `opportunities.html` | PhD / Master's / internship interest |
| `news.html` | Lab news, media coverage, and outreach videos |
| `contact.html` | Address, email, office hours |
| `about.html` | Short mission (not in main nav; kept for bookmarks) |

## Edit later

- Main wording: the `.html` files
- Colors / layout: `assets/style.css`
- PI image: `assets/images/vipul-kumar.jpg`
- Replace placeholder office / institutional email when finalized
- Add course titles on `teaching.html` when assigned

## Publish on GitHub Pages

1. Create a new public GitHub repository (for example `lbsd-lab`).
2. Upload all files and folders from this package to the repository root.
3. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.

## Local preview

Open `index.html` in a browser, or from this folder run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
