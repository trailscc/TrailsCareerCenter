# TRAILS Career Center Website

Official landing page for TRAILS Career Center - Transforming Lives Through AI & Robotics Technology Training

## 🌟 About

TRAILS Career Center is a public benefit non-profit organization based in Salem, Oregon, dedicated to creating pathways from challenge to professional careers in cutting-edge technology fields including AI, robotics, coding, augmented reality, and entrepreneurship.

## 📁 Project Structure

```
TrailsCareerCenter/
├── index.html          # Main landing page
├── styles.css          # Stylesheet with responsive design
├── script.js           # Interactive JavaScript features
├── trails-logo.png     # TRAILS logo
└── README.md           # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com)
2. Click the "+" icon in the top right → "New repository"
3. Name it: `TrailsCareerCenter`
4. Make it **Public**
5. Click "Create repository"

### Step 2: Upload Files

**Option A: Upload via Web Interface**
1. Click "uploading an existing file"
2. Drag and drop all files:
   - index.html
   - styles.css
   - script.js
   - trails-logo.png
   - README.md
3. Add commit message: "Initial TRAILS website launch"
4. Click "Commit changes"

**Option B: Upload via Git Command Line**
```bash
# Navigate to your project folder
cd /path/to/your/files

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial TRAILS website launch"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/TrailsCareerCenter.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (gear icon)
3. Scroll to "Pages" in the left sidebar
4. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click "Save"
6. Wait 1-2 minutes for deployment

### Step 4: Access Your Website

Your site will be available at:
```
https://YOUR-USERNAME.github.io/TrailsCareerCenter/
```

## 🎨 Customization Guide

### Updating Content

**To change text:**
- Open `index.html`
- Find the section you want to edit
- Modify the text between HTML tags
- Save and push changes to GitHub

**To update the timeline:**
- Locate the `<section class="timeline">` in `index.html`
- Edit dates and descriptions
- Add new timeline items by copying existing `<div class="timeline-item">` blocks

**To modify colors:**
- Open `styles.css`
- Edit the `:root` variables at the top:
  - `--primary-color`: Main accent color (currently green)
  - `--secondary-color`: Secondary accent (currently yellow)
  - `--dark-bg`: Dark background color

### Adding New Sections

1. Copy an existing section structure from `index.html`
2. Paste it where you want the new section
3. Update the content
4. Add corresponding styles in `styles.css` if needed

## 📧 Contact Information

- **Email**: TrailsCareerCenter@proton.me
- **Location**: Salem, Oregon

## 🗓️ Project Timeline

- **November 2025**: Non-profit incorporation & planning
- **November-December 2025**: Website development & funding
- **January 22, 2026**: Full website launch target

## 📄 License

© 2025 TRAILS Career Center - Public Benefit Non-Profit Corporation

## 🛠️ Technical Details

- **Framework**: Vanilla HTML/CSS/JavaScript
- **Responsive Design**: Mobile, tablet, and desktop optimized
- **Animations**: CSS animations and Intersection Observer API
- **Font**: Inter (Google Fonts)
- **Hosting**: GitHub Pages

## 🔧 Troubleshooting

**Site not showing up after enabling Pages?**
- Wait 5-10 minutes for initial deployment
- Check that `index.html` is in the root directory
- Verify the repository is public

**Logo not displaying?**
- Ensure `trails-logo.png` is in the same folder as `index.html`
- Check file name matches exactly (case-sensitive)

**Styles not loading?**
- Clear your browser cache (Ctrl+Shift+Delete / Cmd+Shift+Delete)
- Verify `styles.css` is in the root directory

## 📞 Support

For questions about this website or TRAILS Career Center, contact:
**TrailsCareerCenter@proton.me**

---

**Built with dedication for transforming lives through technology education** 🚀
