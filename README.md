# DIIM Lab - Student Project Page Template

This template creates a standalone project page that matches the DIIM Digital Twin main site.

## 📁 File Structure

```
your-project-name/
├── index.html          ← Your project page (edit this)
├── css/
│   ├── variables.css   ← Color/font variables (DO NOT EDIT)
│   └── project-styles.css  ← Page styles (DO NOT EDIT)
├── js/
│   └── main.js         ← Animations (DO NOT EDIT)
├── images/             ← Your images go here
│   ├── hero.png        ← Main featured image
│   ├── gallery-1.png   ← Gallery images
│   ├── gallery-2.png
│   └── gallery-3.png
└── README.md           ← This file
```

## 🚀 Quick Start

### Step 1: Edit `index.html`

Open `index.html` and update the sections marked with `<!-- STUDENT: Update ... -->`:

1. **Page Title & Meta** (lines 10-12)
   - Your project title
   - Brief description for search engines
   - Your name

2. **Hero Section** (around line 60)
   - Research category tag (e.g., "Smart Manufacturing", "Precision Agriculture")
   - Project title
   - Your name and publication venue

3. **Content Sections**
   - Overview: 2-3 paragraphs about your research
   - Key Findings: 3-5 bullet points
   - Method: How your approach works
   - Results: Performance metrics and comparisons
   - Gallery: 2-4 images (optional)
   - Video: YouTube embed (optional)
   - Publication: Link to your paper

### Step 2: Add Images

Place your images in the `images/` folder:

| Image | Recommended Size | Purpose |
|-------|------------------|---------|
| `hero.png` | 1600×900px | Main featured image |
| `gallery-1.png` | 800×600px | Gallery images |
| `gallery-2.png` | 800×600px | Gallery images |
| `gallery-3.png` | 800×600px | Gallery images |

### Step 3: Host on GitHub Pages

1. Create a new GitHub repository (e.g., `my-research-project`)
2. Upload all files from this folder
3. Go to **Settings** → **Pages**
4. Select **main** branch, **/ (root)** folder
5. Click **Save**
6. Your page will be live at: `https://YOUR_USERNAME.github.io/my-research-project/`

### Step 4: Share with Professor

Send your GitHub Pages URL to the professor so they can add it to the main Digital Twin site.

---

## ⚠️ Important Rules

### DO NOT MODIFY:
- `css/variables.css`
- `css/project-styles.css`
- `js/main.js`
- Navigation section in `index.html`
- Footer section in `index.html`

These files ensure your page looks consistent with other project pages.

### DO MODIFY:
- Content sections in `index.html`
- Images in `images/` folder
- Page title and meta description

---

## 📹 Adding a YouTube Video

1. Go to your YouTube video
2. Click **Share** → **Embed**
3. Copy the video ID from the URL (e.g., `dQw4w9WgXcQ`)
4. In `index.html`, uncomment the Video Demo section
5. Replace `YOUR_VIDEO_ID` with your video ID

---

## 🔗 Adding Your Paper Link

Replace `https://doi.org/YOUR_DOI` with:
- Your paper's DOI link (preferred)
- A direct PDF link
- ArXiv link
- Conference/journal page link

---

## ❓ Need Help?

Contact the lab at syang19@uoguelph.ca

---

© 2025 DIIM Lab, University of Guelph
