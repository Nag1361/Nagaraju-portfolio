# ⚡ QUICK DEPLOYMENT GUIDE

## Your exact portfolio is ready to deploy on GitHub Pages!

### 🎯 3 Simple Steps

---

## **STEP 1: Create GitHub Repository** (2 minutes)

1. Go to **[github.com](https://github.com)** → Login
2. Click **"+"** → **"New repository"**
3. Repository name: `portfolio`
4. Choose **Public**
5. Click **"Create repository"**

---

## **STEP 2: Upload Code to GitHub** (2 minutes)

Copy and paste these commands in your terminal/command prompt:

```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

**⚠️ Important:** Replace `YOUR_USERNAME` with your actual GitHub username

Example:
```bash
git remote add origin https://github.com/nagaraju/portfolio.git
```

---

## **STEP 3: Enable GitHub Pages** (1 minute)

1. Go to your repository on GitHub
2. Click **Settings** (top navigation)
3. Click **Pages** (left sidebar)
4. Under "Source":
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Click **Save**

---

## ✅ **COMPLETE!**

Your site is now live at:

### 🌐 **`https://YOUR_USERNAME.github.io/portfolio/`**

**Wait 1-2 minutes for it to appear.**

---

## 🔄 **Update Your Portfolio Later**

Every time you make changes:

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

That's it! GitHub Pages auto-deploys. ✨

---

## 🆘 **Need Help?**

### Site not showing?
- Wait 5 minutes
- Refresh page (Ctrl+F5)
- Check Settings → Pages

### Don't have Git?
Download from: https://git-scm.com/

### First time with Git?
That's OK! Follow the commands exactly as shown above.

---

## 📋 **What's Included**

✅ `index.html` - Your complete portfolio (HTML + CSS + JS)  
✅ `README.md` - Full documentation  
✅ `DEPLOY_GUIDE.md` - This file  
✅ `.gitignore` - Git configuration  

---

## 💡 **Optional: Update EmailJS**

Your contact form uses EmailJS. To update credentials:

1. Open `index.html`
2. Find this line (around line 752):
   ```javascript
   emailjs.init("bm3Ye8daBswxqbahI");
   ```
3. Get your own EmailJS key from: https://www.emailjs.com/
4. Replace with your key

---

**That's all! Your portfolio is on GitHub Pages! 🎉**
