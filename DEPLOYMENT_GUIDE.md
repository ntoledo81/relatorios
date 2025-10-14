# 🚀 GitHub Pages Deployment Guide

This guide will help you publish your Language Dashboard to the web automatically.

## ✅ Prerequisites

- A GitHub account
- Git installed on your computer
- Your dashboard files ready (already included in this folder)

## 📤 Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** button → **"New repository"**
3. Repository details:
   - **Name:** `relatorios` (or any name you prefer)
   - **Description:** "Language Learning Performance Dashboard"
   - **Visibility:** Public (required for free GitHub Pages)
   - **✅ Add a README file** (uncheck this - we already have one)
   - **✅ Add .gitignore** (uncheck this - we already have one)

4. Click **"Create repository"**

## 💻 Step 2: Upload Your Files

### Option A: Using Git Command Line

Open PowerShell in your project folder and run:

```powershell
# Initialize git repository
git init

# Add all files
git add .

# Make your first commit
git commit -m "Initial dashboard deployment"

# Connect to your GitHub repository (replace YOUR_USERNAME and YOUR_REPO)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

# Push to GitHub
git push -u origin main
```

### Option B: Using GitHub Desktop

1. Download and install [GitHub Desktop](https://desktop.github.com/)
2. Sign in with your GitHub account
3. Click **"Add an existing repository from your hard drive"**
4. Select your project folder
5. Click **"Publish repository"**
6. Choose your repository name and make sure it's **public**
7. Click **"Publish Repository"**

### Option C: Upload via Web Interface

1. Go to your empty repository on GitHub.com
2. Click **"uploading an existing file"**
3. Drag and drop all your project files
4. Add commit message: "Initial dashboard deployment"
5. Click **"Commit changes"**

## ⚙️ Step 3: Enable GitHub Pages

1. In your repository on GitHub.com, go to **Settings** tab
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**:
   - Select **"GitHub Actions"**
   - This will use our automated deployment workflow

4. Click **"Save"**

## 🎉 Step 4: Watch the Magic Happen!

1. Go to the **"Actions"** tab in your repository
2. You should see a workflow called **"Deploy to GitHub Pages"** running
3. Wait for it to complete (usually 2-3 minutes)
4. Once done, your site will be live at:
   ```
   https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/
   ```

## 🔄 Making Updates

Every time you want to update your dashboard:

1. **Edit your files** locally
2. **Commit and push** your changes:
   ```powershell
   git add .
   git commit -m "Update dashboard data"
   git push
   ```
3. **Wait 2-3 minutes** - your site automatically updates!

## 🆘 Troubleshooting

### Site not loading?
- Check the **Actions** tab for any failed workflows
- Ensure your repository is **public**
- Verify GitHub Pages is set to **"GitHub Actions"** in Settings

### Charts not showing?
- Check browser console for JavaScript errors
- Ensure internet connection (charts use CDN)
- Try hard refresh (Ctrl+F5)

### Need help?
- Check the **Issues** tab in your repository
- Review GitHub Pages [official documentation](https://docs.github.com/en/pages)

## 🌟 Success!

Your dashboard is now:
- ✅ **Live on the internet**
- ✅ **Automatically updating** when you push changes
- ✅ **Mobile-friendly** and responsive
- ✅ **Fast loading** with CDN dependencies
- ✅ **Professional navigation** between dashboard views

**Share your live URL with others and showcase your language learning analytics!**

---

**Next steps:** Consider adding custom domain, analytics tracking, or additional dashboard features as your project grows.