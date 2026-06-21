# Ahmed Hany — Portfolio

Personal portfolio website built with pure HTML & CSS. Hosted on GitHub Pages.

## 🚀 How to deploy on GitHub Pages

1. Create a new repository named: `yourusername.github.io`
2. Upload all files from this folder to the repo
3. Go to **Settings → Pages → Branch: main → Save**
4. Your site will be live at: `https://yourusername.github.io`

## 📁 Project structure

```
portfolio/
├── index.html         ← Main portfolio file
├── assets/            ← Create this folder for project logos
│   ├── project1.png
│   ├── project2.png
│   └── ...
└── README.md
```

## 🎨 How to add your projects

In `index.html`, find the section `id="projects"` and update each `.project-card`:

1. **Add your logo image** to the `assets/` folder
2. **Replace the placeholder** `<div class="project-logo-placeholder">` with:
   ```html
   <img src="assets/your-logo.png" class="project-logo-img" alt="Project name logo" />
   ```
3. **Update the project details**: name, description, tech tags, links

## 📝 Customization

- Update your LinkedIn and GitHub URLs in the contact section
- Change the stats numbers in the About section
- Add/remove skill tags as needed
