# Durwas Khot — Portfolio

A single-file static site (`index.html`, no build step needed).

## Add your CV
Drop your CV file into `assets/documents/` and name it exactly:

    assets/documents/Durwas_Khot_CV.pdf

The "Download CV" buttons in the nav bar, hero, and contact section already point to this path — as soon as the file is there, the buttons work. If your file is a `.docx` instead of `.pdf`, either convert it to PDF or update the three `href="assets/documents/Durwas_Khot_CV.pdf"` references in `index.html` to match your filename.

## Add a profile photo (optional)
The current design uses a "waveform" panel instead of a photo, matching the NVH/engineering theme. If you'd rather add a headshot, I can swap that panel for an image — just say the word and send the photo.

## Deploy on GitHub Pages
1. Create a new GitHub repo, e.g. `durwas-portfolio`.
2. Upload `index.html`, the `assets/` folder, and this README to it.
3. In the repo, go to **Settings → Pages**, set source to the `main` branch and `/ (root)`, save.
4. Your site will be live at `https://<your-username>.github.io/durwas-portfolio/` within a minute or two.

## Editing content later
Everything is in `index.html` — sections are marked with comments-like `<!-- ... -->` structure via `id`s (`about`, `skills`, `work`, `experience`, `contact`). Text can be edited directly in that file; no other tooling required.
