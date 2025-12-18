# Portfolio Website

A minimal, clean portfolio with dark theme elements.

## Quick Start (Local Preview)

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Then open http://localhost:8000
```

## Deploy to GitHub Pages

### Option 1: User Site (djnicora.github.io)

1. **Create the repository** on GitHub:
   - Go to https://github.com/new
   - Name it exactly: `djnicora.github.io`
   - Make it Public

2. **Push the code**:
   ```bash
   cd D:/dev/portfolio
   git init
   git add -A
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/djnicora/djnicora.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings > Pages
   - Source: Deploy from a branch
   - Branch: main, / (root)
   - Save

4. **Your site will be live at**: `https://djnicora.github.io`

### Option 2: Project Site (djnicora.github.io/portfolio)

1. Create a repo named `portfolio`
2. Push the same way as above
3. URL will be: `https://djnicora.github.io/portfolio`

## Customization

### Edit Content
- `index.html` - All text content, project descriptions, links
- Update the LinkedIn URL and email in the contact section
- Adjust project descriptions based on your actual frameworks

### Edit Styling
- `style.css` - Colors in `:root` CSS variables
- Change `--accent` to customize the highlight color

### Add Your Photo (Optional)
1. Add your image to the folder
2. In `index.html`, add an `<img>` in the `.hero-visual` section

## Structure

```
portfolio/
├── index.html      # Main page
├── style.css       # Styling
└── README.md       # This file
```

## Tech Stack

- Pure HTML5 & CSS3
- No JavaScript required
- Google Fonts (Inter, JetBrains Mono)
- Fully responsive
- No build step needed
