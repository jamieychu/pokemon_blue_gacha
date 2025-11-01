# 🚀 GitHub Pages Deployment Guide

## Complete Step-by-Step Instructions for Publishing Your Pokémon Blue Gacha Prototype

---

## 📋 Prerequisites

Before you begin, make sure you have:
- A GitHub account (create one at https://github.com if you don't have one)
- All project files downloaded from this folder

---

## 📁 Project Files

Your project contains:
- `index.html` - Main showcase page (renamed from pokemon_showcase_scaled.html)
- `trainer_recruitment_scaled.html` - Game Boy prototype (iframe content)
- `README.md` - Project documentation
- `.gitignore` - Files to exclude from Git

---

## 🎯 Method 1: Upload via GitHub Website (Easiest for Beginners)

### Step 1: Create a New Repository

1. Go to https://github.com
2. Log in to your account
3. Click the **"+"** icon in the top-right corner
4. Select **"New repository"**

### Step 2: Configure Repository Settings

1. **Repository name**: Choose a name (e.g., `pokemon-blue-gacha` or `trainer-recruitment-prototype`)
   - This will be part of your URL: `username.github.io/repository-name`
2. **Description** (optional): "Interactive Game Boy prototype for Pokémon Blue trainer recruitment feature"
3. **Public/Private**: Select **Public** (required for free GitHub Pages)
4. **Initialize repository**: 
   - ✅ Check "Add a README file" (or you'll upload yours)
   - Don't add .gitignore or license yet
5. Click **"Create repository"**

### Step 3: Upload Your Files

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL files from your project folder:
   - `index.html`
   - `trainer_recruitment_scaled.html`
   - `README.md`
   - `.gitignore`
3. Scroll down to the commit section
4. Write a commit message (e.g., "Initial commit - Add Pokemon Blue Gacha prototype")
5. Click **"Commit changes"**

### Step 4: Enable GitHub Pages

1. In your repository, click **"Settings"** (tab at the top)
2. Scroll down and click **"Pages"** in the left sidebar
3. Under **"Source"**:
   - Select **"Deploy from a branch"**
   - Choose **"main"** branch (or "master" if that's what you see)
   - Select **"/ (root)"** folder
4. Click **"Save"**

### Step 5: Wait for Deployment

1. GitHub will now build your site (this takes 1-3 minutes)
2. Refresh the Settings → Pages page
3. You'll see a green banner with your live URL:
   ```
   Your site is live at https://username.github.io/repository-name/
   ```
4. Click the link or visit the URL to see your live site!

---

## 🎯 Method 2: Using GitHub Desktop (Recommended for Ongoing Updates)

### Step 1: Install GitHub Desktop

1. Download from https://desktop.github.com
2. Install and sign in with your GitHub account

### Step 2: Create Repository via GitHub Desktop

1. Open GitHub Desktop
2. Click **"File"** → **"New repository"**
3. Fill in:
   - **Name**: `pokemon-blue-gacha`
   - **Description**: "Pokémon Blue trainer recruitment prototype"
   - **Local path**: Choose where to create the folder
   - ✅ Check "Initialize this repository with a README"
   - **Git ignore**: None
   - **License**: None
4. Click **"Create repository"**

### Step 3: Add Your Files

1. Click **"Show in Explorer"** (Windows) or **"Show in Finder"** (Mac)
2. Copy all your project files into this folder:
   - `index.html`
   - `trainer_recruitment_scaled.html`
   - `README.md` (replace existing)
   - `.gitignore`
3. Return to GitHub Desktop

### Step 4: Commit and Push

1. You'll see all files listed in the left panel
2. In the bottom-left:
   - **Summary**: "Initial commit - Add prototype files"
   - **Description** (optional): "Added main page and Game Boy prototype"
3. Click **"Commit to main"**
4. Click **"Publish repository"** button at the top
5. Make sure **"Keep this code private"** is UNCHECKED (for free GitHub Pages)
6. Click **"Publish repository"**

### Step 5: Enable GitHub Pages

Follow **Step 4** from Method 1 above.

---

## 🎯 Method 3: Using Git Command Line (For Advanced Users)

### Prerequisites
- Git installed on your computer
- Terminal/Command Prompt access

### Commands

```bash
# Navigate to your project folder
cd path/to/your/project/folder

# Initialize Git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Add Pokemon Blue Gacha prototype"

# Create repository on GitHub first, then:
# Add remote origin (replace with your URL)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then follow **Step 4** from Method 1 to enable GitHub Pages.

---

## ✅ Verification Checklist

After deployment, verify:
- [ ] Main page loads at `https://username.github.io/repository-name/`
- [ ] Game Boy prototype is visible and interactive
- [ ] Buttons on Game Boy work (A, B, SELECT, START, D-Pad)
- [ ] Page is responsive on mobile (use browser dev tools to test)
- [ ] No console errors (press F12 to check)

---

## 🔧 Troubleshooting

### Problem: Page shows 404 error
**Solution**: 
- Wait 2-3 minutes for GitHub to build the site
- Check that GitHub Pages is enabled in Settings → Pages
- Verify your repository is public

### Problem: Game Boy prototype not showing
**Solution**:
- Check that `trainer_recruitment_scaled.html` is in the same folder as `index.html`
- Verify the filename matches exactly (case-sensitive)
- Check browser console (F12) for errors

### Problem: Files not updating
**Solution**:
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Wait a few minutes for GitHub Pages to rebuild
- Check your commit was pushed successfully

### Problem: Images or styles not loading
**Solution**:
- All resources are embedded in the HTML, so this shouldn't happen
- If you added external files, make sure paths are relative (not absolute)

---

## 🔄 Updating Your Site

### Via GitHub Website:
1. Navigate to the file you want to edit
2. Click the pencil icon (Edit)
3. Make changes
4. Scroll down and commit changes
5. Wait 1-2 minutes for site to rebuild

### Via GitHub Desktop:
1. Edit files locally
2. Open GitHub Desktop
3. Review changes in left panel
4. Write commit message
5. Click "Commit to main"
6. Click "Push origin"
7. Wait 1-2 minutes for site to rebuild

---

## 🎨 Customization Tips

### Update the README:
1. Add your actual GitHub Pages URL to the "Live Demo" section
2. Add screenshots
3. Update author information

### Add a Custom Domain (Optional):
1. Purchase a domain name
2. Go to Settings → Pages
3. Enter custom domain
4. Follow GitHub's DNS setup instructions

---

## 📱 Sharing Your Site

Once deployed, share your prototype:
- Direct link: `https://username.github.io/repository-name/`
- Add to your portfolio
- Share on social media
- Include in your resume/CV

---

## 🆘 Need Help?

- **GitHub Pages Docs**: https://docs.github.com/en/pages
- **GitHub Community**: https://github.community
- **GitHub Support**: https://support.github.com

---

## 🎉 Success!

Congratulations! Your Pokémon Blue Gacha prototype is now live on the internet!

Remember to:
- ⭐ Star your own repository
- 📝 Keep the README updated
- 🔄 Push updates regularly
- 🎨 Continue improving the prototype

**Your site URL will be:**
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

---

*Last updated: October 31, 2025*
