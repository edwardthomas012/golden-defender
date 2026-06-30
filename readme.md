# 🎮 GOLDEN DEFENDER WEBSITE - SETUP INSTRUCTIONS 🎮

## ✨ SUPER SIMPLE 3-STEP SETUP ✨

### STEP 1: Organize Your Photos

Put your photos in folders like this:

```
golden-defender-site/
├── index.html (already here)
├── bezel.html (already here)
├── images/
│   ├── bezel/
│   │   ├── bezel1.jpg
│   │   ├── bezel2.jpg
│   │   └── bezel3.jpg
│   ├── controls/
│   │   ├── controls1.jpg
│   │   ├── controls2.jpg
│   │   └── controls3.jpg
│   ├── marquee/
│   │   └── (your marquee photos)
│   ├── boards/
│   │   └── (your board photos)
│   ├── monitor/
│   │   └── (your monitor photos)
│   └── full-photos/
│       └── (all your full cabinet photos)
```

**EASY WAY:**
1. Create a folder called "images" next to the HTML files
2. Inside "images" create folders: bezel, controls, marquee, boards, monitor, full-photos
3. Copy your photos into the matching folders
4. Rename them to simple names like: bezel1.jpg, bezel2.jpg, etc.

---

### STEP 2: Tell Each Page About Your Photos

Open `bezel.html` in Notepad (or any text editor)

Find this part (around line 153):

```javascript
const photos = [
    'bezel1.jpg',
    'bezel2.jpg',
    'bezel3.jpg',
    // Add more photos here
];
```

**Just list your photo filenames!** Example:

```javascript
const photos = [
    'bezel1.jpg',
    'bezel2.jpg',
    'bezel3.jpg',
    'bezel4.jpg',
    'bezel5.jpg',
];
```

That's it! The page will automatically show all those photos.

**Repeat this for each page:**
- `controls.html` - list your control photos
- `marquee.html` - list your marquee photos
- `boards.html` - list your board photos
- `monitor.html` - list your monitor photos
- `full-photos.html` - list all your full cabinet photos

---

### STEP 3: Upload to Netlify

1. **Zip everything:**
   - Select the whole `golden-defender-site` folder
   - Right-click → "Compress" or "Send to → Compressed folder"
   - You'll get `golden-defender-site.zip`

2. **Upload to Netlify:**
   - Go to your Netlify site (where you uploaded before)
   - Click "Deploys" tab
   - Drag the ZIP file onto the page
   - Wait 30 seconds - Done!

---

## 🎯 THAT'S IT! 

Your website will now show all your photos in beautiful galleries!

---

## 💡 TIPS

**Photo Names:**
- Use simple names: photo1.jpg, photo2.jpg, photo3.jpg
- No spaces in names! Use dashes: my-photo.jpg ✅ NOT my photo.jpg ❌
- Lowercase is best: photo.jpg ✅ 

**File Types:**
- .jpg or .jpeg ✅
- .png ✅
- .gif ✅

**Need Help?**
The website works right now with placeholder images, so you can upload it first and add photos later!

---

## 📝 QUICK EXAMPLE

If you have 5 bezel photos named:
- IMG_001.jpg
- IMG_002.jpg  
- IMG_003.jpg
- IMG_004.jpg
- IMG_005.jpg

1. Copy them to `images/bezel/`
2. Open `bezel.html`
3. Change the photo list to:

```javascript
const photos = [
    'IMG_001.jpg',
    'IMG_002.jpg',
    'IMG_003.jpg',
    'IMG_004.jpg',
    'IMG_005.jpg',
];
```

4. Save the file
5. Zip and upload!

Done! 🎉