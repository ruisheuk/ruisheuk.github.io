# Rui She — Personal Webpage

Live site: **https://&lt;your-github-username&gt;.github.io**

---

## 🚀 How to Deploy

1. Create a GitHub repository named exactly: `<your-github-username>.github.io`
2. Upload the following files:
   - `index.html`
   - `uploads/` folder (all 7 images inside)
3. Go to **Settings → Pages → Deploy from branch → main → / (root)**
4. Wait ~1 minute. Your site is live!

---

## 📁 File Structure

```
your-repo/
├── index.html                        ← Main webpage (edit this)
├── README.md                         ← This file
└── uploads/
    ├── id.png                        ← Your profile photo
    ├── Huawei.png                    ← Huawei logo
    ├── genetec.png                   ← Genetec logo
    ├── deppon.png                    ← Deppon logo
    ├── bayes.jpg                     ← Bayes Business School logo
    ├── university-of-birmingham.png  ← University of Birmingham logo
    └── acca.png                      ← ACCA logo
```

---

## ✏️ How to Edit Content

All content lives in `index.html`. Open it in any text editor (VS Code recommended).

### Change your name / title
Search for `hero-name` or `hero-title` and edit the text directly.

### Update the summary paragraph
Search for `hero-summary` — edit the `<p>` tag content.

### Update the 3 highlight bullets
Search for `hero-highlights` — edit the 3 `<div class="hero-hi">` blocks.

### Change contact details
- **Email:** Search for `ruisheuk@gmail.com` — replace both occurrences
- **LinkedIn:** Search for `linkedin.com/in/rui-she` — replace both occurrences

### Edit experience bullet points
Search for the company name (e.g. `Huawei Technologies`) — the `<ul class="exp-bullets">` below it contains the bullet points.

### Edit education details
Search for `edu-grid` — the three `<div class="edu-card">` blocks contain degree, school, modules and year.

### Replace your photo
Swap out `uploads/id.png` with a new photo file. Keep the filename `id.png` or update the reference in `index.html`:
```html
<img class="hero-photo" src="uploads/id.png" alt="Rui She" />
```

### Replace a company logo
Swap out the relevant file in `uploads/` keeping the same filename, e.g. replace `uploads/Huawei.png`.

---

## 🎨 How to Change Colours

At the top of `index.html`, inside `<style>`, find the `:root` block:

```css
:root {
  --bg: #f7f6f3;           /* Page background */
  --navy: #0d1b2a;         /* Dark headings & nav */
  --accent: oklch(58% 0.19 218);  /* Blue accent colour */
  --border: #e4e2dc;       /* Card borders */
  --muted: #6b7a8d;        /* Muted text */
}
```

Change `--accent` to any colour to update buttons, chips, dates, and highlights across the whole page.

---

## 📌 Things to Update Later

- [ ] Add your **GitHub username** to the live URL in this README
- [ ] Update **profile photo** when you have a more formal headshot
- [ ] Add **new role** if you change jobs — copy an existing `exp-card2` block and edit
- [ ] Update **ACCA status** from "Part-Qualified" to "Qualified" when complete
- [ ] Consider adding a **downloadable CV link** — upload your CV PDF to `uploads/` and add a button in the hero:
  ```html
  <a href="uploads/RuiShe_CV.pdf" download class="btn-secondary">⬇ Download CV</a>
  ```
- [ ] Consider adding a **languages / tools** section if applying for roles requiring SQL or Tableau
- [ ] Keep the **hero stats** (5+, 10%, 4) updated as your experience grows

---

## 🛠 Recommended Tools

- **VS Code** — free code editor: https://code.visualstudio.com
- **GitHub Desktop** — easy way to push changes: https://desktop.github.com
- **Squoosh** — compress images before uploading: https://squoosh.app

---

*Built with HTML, CSS and ♥ — no frameworks, no dependencies. One file, deploy anywhere.*
