# Nagaraju Salendra - Portfolio Website

A modern, professional portfolio website built with vanilla HTML, CSS, and JavaScript featuring smooth animations, glassmorphism design, and responsive layouts.

## 🚀 Live Demo

Your portfolio is currently deployed at: **https://nagaraju-portfolio.netlify.app/**

Now you can deploy it to **GitHub Pages** for free and own your distribution!

## ✨ Features

- 🎨 Modern dark theme with cyan and purple accents
- 💅 Glassmorphism design with blur effects
- ✨ Smooth scroll animations and fade-in effects
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎯 Sticky navigation bar with active section tracking
- 🔄 Scroll progress indicator
- ⚡ Smooth transitions and hover effects
- 📧 EmailJS contact form integration
- 🎬 Loading screen and scroll wheel indicator
- 🌙 Professional dark mode throughout

## 📦 What's Included

- **index.html** - Complete portfolio with all HTML, CSS, and JavaScript
- **.gitignore** - Git ignore rules
- **README.md** - Documentation
- **DEPLOY_GUIDE.md** - Quick deployment guide

## 🛠️ Setup Instructions

### Local Development (Testing)

1. **Clone the repository** (after you create it):
```bash
git clone https://github.com/YOUR_USERNAME/portfolio.git
cd portfolio
```

2. **Open in browser**:
   - Simply open `index.html` in your browser, OR
   - Use a local server for best results:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js
npx http-server
```

Then visit: `http://localhost:8000`

### Note on EmailJS
Your portfolio uses **EmailJS** for contact form submissions. The configuration is already embedded in the code with your EmailJS credentials. When you fork/copy this, you may want to update the EmailJS service ID, template ID, and public key to your own account.

**Update in index.html** (around line 752):
```javascript
emailjs.init("YOUR_PUBLIC_KEY");
// And update the send parameters:
emailjs.send('YOUR_SERVICE_ID','YOUR_TEMPLATE_ID',{...})
```

[Get your own EmailJS account here](https://www.emailjs.com/)

---

## 🚀 DEPLOYMENT TO GITHUB PAGES

### Step 1️⃣: Create a GitHub Repository

1. Go to **[github.com](https://github.com)**
2. Click **"+"** in top right → **"New repository"**
3. Name it: **`portfolio`** (or any name)
4. Choose **Public**
5. Do NOT initialize with README, .gitignore, or license
6. Click **"Create repository"**

### Step 2️⃣: Push Your Code to GitHub

Open Terminal/Command Prompt in your portfolio folder and run:

```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

**⚠️ Replace `YOUR_USERNAME` with your actual GitHub username**

### Step 3️⃣: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Click **Pages** in left sidebar
4. Under "Source":
   - Select Branch: **`main`**
   - Select Folder: **`/ (root)`**
5. Click **Save**

### ✅ Done!

Your site will be live at: **`https://YOUR_USERNAME.github.io/portfolio/`**

⏳ It may take 1-2 minutes to appear.

---

## 📝 Making Updates

Every time you make changes:

```bash
# Make your changes in index.html

# Stage and commit
git add .
git commit -m "Update portfolio content"

# Push to GitHub
git push origin main
```

**GitHub Pages automatically rebuilds and deploys your site!** 🎉

Your changes will be live within 1-2 minutes.

---

## 🎨 Customization

### Change Your Information
Edit `index.html` and update:
- Your name and tagline
- About section content
- Project descriptions
- Social media links
- Contact information

### Update Profile Picture
In the HTML, find the profile image section and update the image URL or replace with your own image path.

### Modify Colors
The color scheme uses CSS variables at the top of the `<style>` section:
```css
:root{
  --bg:#0d1117;           /* Background color */
  --fg:#e8edf5;           /* Text color */
  --primary:hsl(190,95%,55%);    /* Cyan accent */
  --accent:hsl(270,80%,65%);     /* Purple accent */
  /* ... more colors ... */
}
```

### Add Projects
Duplicate a project card in the Projects section and update:
- Project title
- Description
- Features
- Technologies
- Demo and GitHub links

---

## 🔗 Custom Domain (Optional)

If you have your own domain:

1. In repository **Settings** → **Pages**
2. Under "Custom domain", enter your domain
3. Click **Save**
4. Follow the DNS configuration instructions

[Learn more about custom domains](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

## 🆘 Troubleshooting

### Site not showing up?
- ✅ Wait 5 minutes for GitHub Pages to build
- ✅ Check Settings → Pages
- ✅ Verify branch is set to `main`
- ✅ Make sure repository is **Public**
- ✅ Clear browser cache (Ctrl+Shift+Del)

### Changes not appearing?
- ✅ Hard refresh browser (Ctrl+F5 on Windows, Cmd+Shift+R on Mac)
- ✅ Wait 1-2 minutes for deployment
- ✅ Check if there are any build errors in repository Settings → Pages

### Contact form not working?
- ✅ Update your EmailJS credentials in index.html
- ✅ Make sure EmailJS service is active
- ✅ Check browser console for errors (F12)

### Mobile menu not working?
- ✅ This is intentional - mobile menu is fully functional
- ✅ Check that JavaScript is enabled in browser

---

## 📚 Resources

- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [Git Basics](https://git-scm.com/book/en/v2)
- [EmailJS Docs](https://www.emailjs.com/docs/)
- [MDN Web Docs](https://developer.mozilla.org/)

---

## 📄 License

This project is open source and available for personal use.

## 👤 Author

**Nagaraju Salendra**
- Portfolio: [nagaraju-portfolio.netlify.app](https://nagaraju-portfolio.netlify.app)
- Twitter: [@Naga5635](https://x.com/Naga5635)
- Reddit: [NAGA_0808](https://www.reddit.com/u/NAGA_0808/)

---

## 🤝 Support

If you find this helpful, please star this repository! ⭐

**Questions or issues?** Feel free to open an issue or contact me through the portfolio.

---

**Happy Coding & Good Luck with Your Portfolio! 🚀**
