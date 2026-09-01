# jiwoooda.github.io

Personal portfolio site for Jiwoo Won, served via GitHub Pages at
<https://jiwoooda.github.io>.

## Structure

```
/
├─ index.html          # Home page
├─ ddalangoo.html      # Ddalangoo engineering case study
├─ assets/
│  ├─ profile/         # Profile photo
│  ├─ ddalangoo/       # Ddalangoo case-study images
│  ├─ research/        # Research / other-project images
│  └─ common/          # Shared images
└─ docs/               # PDF slide decks and papers
```

Static HTML/CSS only — no build step. All asset paths are relative to the
repository root so the site works identically on GitHub Pages and when served
locally (e.g. `python -m http.server`).
