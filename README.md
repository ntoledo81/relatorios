# Impacto Enriquecimento Language Dashboard

Interactive dashboards for analyzing language learning performance data with automatic GitHub Pages deployment.

## 📊 Dashboards

- **Main Dashboard** ([index.html](index.html)): Comprehensive analysis across 9 language volumes
- **Language Dashboard** ([Impacto Enriquecimento Language.html](Impacto%20Enriquecimento%20Language.html)): Enhanced performance metrics view  
- **Fun Quest & Angles** ([Impacto Enriquecimento Fun Quest e Angles.html](Impacto%20Enriquecimento%20Fun%20Quest%20e%20Angles.html)): Detailed analysis for specific collections

## ✨ Features

- 📈 Interactive charts (Bar and Line graphs) powered by Chart.js
- 📊 Performance metrics comparison (2024 vs 2025)
- 💾 Export charts as JPEG images
- 📱 Fully responsive design with modern UI
- 🎯 Navigation between multiple dashboard views
- 🚀 **Automatic deployment to GitHub Pages**

## 🌐 View Live

Visit: **https://ntoledo81.github.io/relatorios/**

## 🚀 Automatic Deployment Setup

This repository is configured for **automatic publishing** to GitHub Pages. Here's what's already set up:

### ✅ What's Included

1. **GitHub Actions Workflow** (`.github/workflows/deploy.yml`)
   - Automatically deploys on every push to `main` branch
   - Uses latest GitHub Pages actions for optimal performance
   - No manual intervention required

2. **Optimized File Structure**
   - All dependencies use CDN links for faster loading
   - Cross-navigation between all dashboard pages
   - Mobile-responsive design

3. **Ready-to-Deploy Configuration**
   - `.gitignore` for clean repository
   - Proper HTML structure for GitHub Pages
   - SEO-friendly navigation

### 🔧 Quick Setup Instructions

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial dashboard deployment"
   git push origin main
   ```

2. **Enable GitHub Pages (One-time setup):**
   - Go to your repository on GitHub.com
   - Navigate to **Settings** → **Pages**
   - Under **Source**, select **GitHub Actions**
   - The workflow will automatically trigger and deploy your site

3. **That's it!** Your site will be available at:
   `https://[your-username].github.io/relatorios/`

### 🔄 Automatic Updates

- Every time you push changes to the `main` branch, the site automatically updates
- No manual deployment needed
- Changes typically go live within 2-3 minutes

## 🛠 Technologies

- **Frontend:** HTML5, CSS3, JavaScript
- **Charts:** Chart.js for interactive visualizations
- **Fonts:** Google Fonts (Ubuntu)
- **Deployment:** GitHub Actions + GitHub Pages
- **CDN:** All dependencies served via CDN for optimal performance

## 📁 Project Structure

```
├── index.html                                    # Main dashboard
├── Impacto Enriquecimento Language.html         # Language-specific dashboard  
├── Impacto Enriquecimento Fun Quest e Angles.html # Detailed analysis dashboard
├── .github/workflows/deploy.yml                 # Auto-deployment configuration
├── .gitignore                                   # Repository cleanup
└── README.md                                    # This documentation
```

## 🎯 Dashboard Features

### Interactive Controls
- **View Switching:** Toggle between Activities, Scores, and Completions
- **Chart Types:** Switch between Bar and Line chart visualizations
- **Collection Filters:** Focus on specific learning collections (Angles, Fun Quest)
- **Export Functionality:** Save charts as high-quality JPEG images

### Performance Metrics
- **Comparative Analysis:** 2024 vs 2025 performance tracking
- **Statistical Insights:** Average variations and trend analysis
- **Real-time Updates:** Interactive data exploration with hover details

---

**🚀 Ready to deploy?** Just push your changes and watch your dashboard go live automatically!

