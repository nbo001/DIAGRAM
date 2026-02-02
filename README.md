# Be My Valentine 💕

A beautiful, interactive Valentine's Day website to ask that special someone to be your Valentine!

## Features ✨

- 💖 Beautiful gradient background with floating hearts
- 🏃 "No" button that runs away when you try to hover over it
- 🎉 Celebration animation with confetti when "Yes" is clicked
- 📱 Fully responsive for mobile and desktop
- 🎨 Romantic animations and effects

## How to Deploy to GitHub Pages 🚀

Follow these simple steps to deploy your website:

### 1. Authenticate with GitHub
```bash
gh auth login
```
Follow the prompts to log in to your GitHub account.

### 2. Create and Push to GitHub Repository
```bash
cd /Users/webcode/Desktop/valentin
gh repo create valentin --public --source=. --remote=origin --push
```

### 3. Enable GitHub Pages
```bash
gh repo edit --enable-pages --pages-branch=master
```

Or manually:
1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "master" branch
5. Click "Save"

### 4. Share the Link! 💌

Your website will be live at:
```
https://YOUR_GITHUB_USERNAME.github.io/valentin/
```

Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username.

## Alternative: Quick Manual Deploy

If you prefer to do it manually:

1. Go to [GitHub](https://github.com) and create a new repository called "valentin"
2. Run these commands:
```bash
cd /Users/webcode/Desktop/valentin
git remote add origin https://github.com/YOUR_USERNAME/valentin.git
git branch -M main
git push -u origin main
```
3. Enable GitHub Pages in repository settings (Settings → Pages → Select main branch)

## Local Testing 🧪

To test locally, simply open `index.html` in your web browser!

---

Made with ❤️ for Valentine's Day 2026
