# Bin Locator - FREE GitHub Pages Hosting Guide 🚀

## What You Get
- ✅ **Python Desktop App** (bin_locator.py) - Capacity: 24 per bin
- ✅ **Web Version** (index.html) - Works in any browser, capacity: 24 per bin
- ✅ **FREE hosting** on GitHub Pages

## How to Host on GitHub Pages (FREE!)

### Step 1: Create GitHub Account
Go to https://github.com and sign up (it's free!)

### Step 2: Create New Repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `bin-locator` (or any name you want)
3. Make it **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 3: Upload the Web File
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop **index.html** (the web version)
3. Scroll down and click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to repository **Settings** (tab at top)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **"Deploy from a branch"**
4. Under **Branch**, select **main** and **/root**
5. Click **Save**

### Step 5: Get Your FREE Website! 🎉
Wait 1-2 minutes, then visit:
```
https://YOUR-USERNAME.github.io/bin-locator/
```

Replace `YOUR-USERNAME` with your actual GitHub username!

## Features

### Both Versions Include:
- ✅ Bin selection via dropdowns (A-F, 1-7) or manual input
- ✅ Code validation (2 letters + 4 digits, e.g., SM2002)
- ✅ Capacity: **24 items per bin**
- ✅ Pending list before commit
- ✅ Search and inspect bins
- ✅ Visual location diagram
- ✅ Export/Import JSON data
- ✅ Status bar (no annoying popups!)

### Web Version Extras:
- 📱 Works on phones/tablets
- 💾 Auto-saves to browser (localStorage)
- 🌐 Access from anywhere
- 🆓 Completely free hosting

## Python Desktop Version

### Run it:
```bash
python bin_locator.py
```

### Build Windows .exe:
```bash
pip install pyinstaller
pyinstaller --onefile --windowed bin_locator.py
```

The .exe will be in the `dist` folder!

## Need Help?
- The web version stores data in your browser (localStorage)
- Use Export/Import to backup or move data between devices
- Works offline once loaded!

---

**Author:** ChatGPT (GPT-5 Thinking)  
**Updated:** 2024 - Now with 24 capacity and web version!
