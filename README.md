[README.md](https://github.com/user-attachments/files/28807556/README.md)
# JEpage# Iron &amp; Infrastructure — Key Systems

The official web presence and brand collateral for **Iron &amp; Infrastructure LLC** and its **Key Systems** coaching program by **Jacob Emery**.

> **Simple Scales. Complex Fails.**

Coaching for business leaders who are done dreaming and ready to build a life by design — the roadmap Jacob used to go from $9 an hour to an 8-figure business owner.

---

## 📄 Pages

| File | What it is |
|------|------------|
| `Key Systems Website.html` | **Main landing page.** Hero, premise, the KEY SYSTEMS framework, the Highway to Success roadmap, proof, lead magnet, podcast, and story timeline. |
| `Key Systems Website (standalone).html` | Fully self-contained version of the landing page — all fonts, logos, and scripts inlined. Works offline with no server or internet connection. |
| `Key Systems Presentation.html` | 15-page print-ready presentation deck (landscape Letter). Open and `Cmd/Ctrl + P → Save as PDF`. |
| `How the Iron Built My Infrastructure.html` | Long-form speech, typeset as a readable editorial document. |

### Supporting files

| File | Purpose |
|------|---------|
| `assets/` | Brand logos (Iron &amp; Infrastructure emblem, JE mark) and image-slot photos. |
| `image-slot.js` | Drag-and-drop image placeholder component used on the site. |
| `tweaks-panel.jsx` | In-page control panel (accent color, texture) for the live site. |
| `*-print.html` | Print-optimized variants. |

---

## 🚀 Deploy on GitHub Pages

1. **Push this repository to GitHub.**

2. **Set the homepage.** GitHub Pages serves `index.html` by default, so make a copy of the main page:
   ```bash
   cp "Key Systems Website.html" index.html
   ```
   *(Or use the standalone build: `cp "Key Systems Website (standalone).html" index.html`.)*

3. **Enable Pages.** In your repo: **Settings → Pages → Build and deployment**
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` · **Folder:** `/ (root)`
   - Click **Save**.

4. **Visit your site** at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```
   It can take a minute or two to go live after the first push.

---

## 💻 Run locally

No build step — these are static HTML files. Just open `Key Systems Website.html` in a browser.

For the live version (so fonts and the logo load over `http://` instead of `file://`), serve the folder:

```bash
# Python 3
python3 -m http.server 8000

# or Node
npx serve .
```

Then open <http://localhost:8000/Key%20Systems%20Website.html>.

> 💡 The **standalone** file is the exception — it has everything inlined, so you can open it directly with no server.

---

## 🎨 Brand

| Token | Value |
|-------|-------|
| Forge Red | `#e01e26` |
| Ink / Black | `#0b0c0e` |
| Steel surfaces | `#101316` · `#171b1f` |
| Read text | `#e3e5e8` |
| Display type | Anton |
| UI / body type | Barlow &amp; Barlow Condensed |

---

© Iron &amp; Infrastructure LLC · Jacob Emery, Owner. All rights reserved.
