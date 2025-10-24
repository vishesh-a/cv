# Vishesh Agarwal - Portfolio Website

Modern, responsive portfolio website with the **exact design** from the original - complete with animations, timeline, and all visual effects.

## 🚀 Deploy to GitHub Pages (Super Easy!)

### Step 1: Create GitHub Repository
1. Go to [GitHub](https://github.com) and sign in
2. Click **+** → **New repository**
3. Name it: `portfolio` (or any name you like)
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload All Files
1. Download and extract this ZIP file
2. In your GitHub repository, click **uploading an existing file**
3. **Drag ALL files and folders** from the extracted folder:
   - `index.html`
   - `static/` folder (with css and js inside)
   - `asset-manifest.json`
4. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to repository **Settings**
2. Click **Pages** in left sidebar
3. Under **Source**, select **main** branch
4. Click **Save**
5. Wait 1-2 minutes
6. **Your site is live!** 🎉

Your URL will be: `https://YOUR-USERNAME.github.io/portfolio/`

---

## 📁 What's Included

```
portfolio/
├── index.html              # Main HTML file
├── static/
│   ├── css/
│   │   └── main.*.css     # All styles (Tailwind + custom animations)
│   └── js/
│       └── main.*.js      # React app bundle
└── asset-manifest.json    # Asset references
```

**Important:** Keep the folder structure intact! The `static` folder must be uploaded alongside `index.html`.

---

## ✨ Features (Exact Match!)

✅ Modern dark theme (charcoal background)
✅ Electric cyan (#00d4ff) accent color
✅ Animated gradient orbs in hero section
✅ Typing effect animation
✅ Timeline with alternating cards (left/right)
✅ Smooth scroll navigation
✅ Hover effects on cards
✅ Project filter tabs
✅ Responsive design
✅ Fixed header with blur effect
✅ Scroll-to-top button
✅ Links to all companies & universities

---

## ✏️ How to Edit Your Information

Since this is a production build, editing requires rebuilding. Two options:

### Option 1: Quick Text Changes (Advanced)
1. Open `static/js/main.*.js` in a text editor
2. Search for your name, email, etc.
3. Replace with new values
4. Save and re-upload to GitHub

**Note:** This is tricky as the JS is minified.

### Option 2: Edit Source & Rebuild (Recommended)
If you need to make significant changes:
1. Request the source code version
2. Edit `frontend/src/data/mock.js`
3. Run `yarn build`
4. Upload new build folder to GitHub

---

## 🌐 Using Custom Domain (Optional)

1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. In your repository, create file: `CNAME`
3. Add one line: `www.yourname.com`
4. Configure DNS with your provider:
   ```
   Type: CNAME
   Host: www
   Value: YOUR-USERNAME.github.io
   ```
5. More info: [GitHub Docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

## 🔧 Testing Locally

### Option 1: Simple HTTP Server
```bash
# With Python
python -m http.server 8000

# With Node.js
npx serve
```

Then open: `http://localhost:8000`

### Option 2: VS Code Live Server
1. Open folder in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"

---

## 📱 Mobile Responsive

The site automatically adapts to:
- 📱 Mobile phones (320px+)
- 📲 Tablets (768px+)
- 💻 Laptops (1024px+)
- 🖥️ Desktops (1920px+)

---

## 🆘 Troubleshooting

### Site shows but styling is broken
**Problem:** Files uploaded incorrectly
**Solution:**
- Make sure `static` folder is in the same directory as `index.html`
- Check that folder structure is preserved
- Re-upload all files together

### 404 Error
**Problem:** GitHub Pages not enabled or wrong branch
**Solution:**
- Go to Settings → Pages
- Verify **main** branch is selected
- Wait 2-3 minutes for deployment

### Blank page
**Problem:** JavaScript error or incorrect path
**Solution:**
- Check browser console (F12) for errors
- Verify all files uploaded correctly
- Clear browser cache (Ctrl + Shift + R)

---

## 📊 File Size

- Total: ~85 KB (gzipped)
- HTML: 4 KB
- CSS: 11 KB
- JS: 70 KB

Fast loading on all connections! ⚡

---

## 🔄 Updating Content

When you need to update:
1. Delete all files in repository
2. Upload new build files
3. Commit changes
4. Site updates automatically in 1-2 minutes

---

## 📧 Support

Questions?
- Email: vishesh.agarwal@student.ie.edu
- LinkedIn: [linkedin.com/in/agarwal-v](https://www.linkedin.com/in/agarwal-v)

---

## 📄 Technical Details

- **Framework:** React 19
- **Styling:** Tailwind CSS + Custom CSS
- **UI Components:** Shadcn UI
- **Build Tool:** Create React App
- **Hosting:** GitHub Pages (static)

---

**This is the production-optimized version with the exact design and animations from the original!**
