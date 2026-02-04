# 🚀 Deployment Guide

This guide will help you deploy your Bootstrap 5 project to GitHub Pages or Netlify.

## Prerequisites

- Git installed on your computer
- GitHub account
- Code editor (VS Code, Sublime, etc.)

---

## 📂 Method 1: GitHub Pages (Recommended for Beginners)

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Fill in the details:
   - **Repository name**: `bootstrap-internship-project` (or any name you prefer)
   - **Description**: "Bootstrap 5 responsive website - Internship Task"
   - **Public** or **Private**: Choose Public
   - **DO NOT** initialize with README (we already have one)
5. Click **"Create repository"**

### Step 2: Push Your Code to GitHub

Open your terminal/command prompt and navigate to your project folder:

```bash
cd bootstrap-internship-project
```

Initialize Git repository:

```bash
git init
```

Add all files to Git:

```bash
git add .
```

Commit your changes:

```bash
git commit -m "Initial commit - Bootstrap 5 Internship Project"
```

Add your GitHub repository as remote:

```bash
git remote add origin https://github.com/YOUR-USERNAME/bootstrap-internship-project.git
```

**Replace `YOUR-USERNAME` with your actual GitHub username!**

Push to GitHub:

```bash
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. Scroll down and click **"Pages"** in the left sidebar
4. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **"Save"**
6. Wait 1-2 minutes for deployment

### Step 4: Access Your Live Site

Your site will be available at:

```
https://YOUR-USERNAME.github.io/bootstrap-internship-project/
```

**Note**: It may take a few minutes for the site to go live.

---

## 🌐 Method 2: Netlify (Alternative Method)

### Step 1: Push to GitHub

Follow Steps 1-2 from the GitHub Pages method above.

### Step 2: Deploy on Netlify

1. Go to [netlify.com](https://www.netlify.com)
2. Sign up or log in (you can use your GitHub account)
3. Click **"Add new site"** → **"Import an existing project"**
4. Choose **"Deploy with GitHub"**
5. Authorize Netlify to access your GitHub repositories
6. Select your **bootstrap-internship-project** repository
7. Configure build settings:
   - **Branch to deploy**: main
   - **Build command**: (leave empty)
   - **Publish directory**: (leave empty or put `/`)
8. Click **"Deploy site"**

### Step 3: Access Your Live Site

Netlify will generate a random URL like:

```
https://random-name-12345.netlify.app
```

You can customize this URL:
1. Go to **Site settings**
2. Click **"Change site name"**
3. Enter your preferred name (e.g., `techinnovate-demo`)
4. Your new URL: `https://techinnovate-demo.netlify.app`

---

## 📋 Submission Checklist

Before submitting your project, ensure you have:

- [ ] All three HTML pages (index.html, about.html, contact.html)
- [ ] README.md with complete reflection
- [ ] Clean, well-indented code
- [ ] Responsive design tested on mobile, tablet, desktop
- [ ] Form validation working
- [ ] All navigation links working
- [ ] GitHub repository is public
- [ ] Live site is accessible

---

## 🔗 What to Submit

Prepare the following for submission:

1. **GitHub Repository URL**:
   ```
   https://github.com/YOUR-USERNAME/bootstrap-internship-project
   ```

2. **Live Website URL** (GitHub Pages):
   ```
   https://YOUR-USERNAME.github.io/bootstrap-internship-project/
   ```
   
   OR (Netlify):
   ```
   https://your-site-name.netlify.app
   ```

3. **Project Reflection**: Included in README.md

---

## 🐛 Troubleshooting

### GitHub Pages not working?

**Problem**: 404 error after deployment

**Solutions**:
- Wait 2-5 minutes after enabling Pages
- Check that index.html is in the root directory
- Verify branch is set to "main" in Pages settings
- Clear your browser cache

**Problem**: CSS/styling not loading

**Solutions**:
- Check Bootstrap CDN links are correct
- Ensure files are in the root directory
- Check browser console for errors

### Netlify deployment failed?

**Solutions**:
- Ensure your repository is public
- Check that all files are committed and pushed
- Verify index.html exists in the root
- Try reconnecting your GitHub account

### Git push not working?

**Solutions**:
- Make sure you've set your Git credentials:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```
- If authentication fails, use GitHub Personal Access Token instead of password

---

## 📱 Testing Before Submission

Test your deployed site on:

1. **Desktop browsers**: Chrome, Firefox, Safari, Edge
2. **Mobile devices**: iPhone, Android phone
3. **Different screen sizes**: Use browser DevTools (F12) to test responsive breakpoints

Check that:
- All pages load correctly
- Navigation works
- Images display
- Form validation works
- No console errors
- Design is responsive

---

## 🎉 After Deployment

Once deployed, you can:

1. Share the live URL with friends/colleagues
2. Add it to your portfolio
3. Include it on your resume
4. Continue improving the project
5. Add more features over time

---

## 💡 Pro Tips

1. **Custom Domain**: Both GitHub Pages and Netlify support custom domains if you have one
2. **HTTPS**: Both platforms provide free SSL certificates
3. **Updates**: To update your site, just push new commits to GitHub:
   ```bash
   git add .
   git commit -m "Update: [description of changes]"
   git push
   ```
4. **Branches**: Use branches for experimenting with new features
5. **Issues**: Use GitHub Issues to track bugs or improvements

---

## 📞 Need Help?

If you encounter issues:

1. Check the error messages carefully
2. Search Google for the specific error
3. Check GitHub Pages/Netlify documentation
4. Ask your instructor or mentor
5. Review this guide step by step

---

**Good luck with your deployment! 🚀**
