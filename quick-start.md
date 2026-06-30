# 🚀 QUICK START GUIDE 🚀

## Your Website is Ready! Here's What to Do:

### METHOD 1: Test Locally First (Recommended)

1. **Open the folder** you downloaded
2. **Double-click `index.html`** - it opens in your web browser
3. **You'll see the website!** (Photos will show placeholder images for now)
4. **Click around** to test navigation

### METHOD 2: Upload Right Away

1. **Zip the entire folder**
2. **Go to Netlify.com** → Your project → Deploys
3. **Drag the ZIP file** onto the page
4. **Done!** Your site is live

---

## Adding Your Photos - The EASIEST Way:

### Option A: Add Photos One Folder at a Time

**Start with Bezel photos:**

1. Open the `images/bezel/` folder
2. Copy all your bezel photos there
3. Rename them simply: `photo1.jpg`, `photo2.jpg`, `photo3.jpg`, etc.
4. Open `bezel.html` in Notepad
5. Find the photos list (line 153)
6. Type your filenames:
   ```javascript
   const photos = [
       'photo1.jpg',
       'photo2.jpg',
       'photo3.jpg',
   ];
   ```
7. Save and upload!

**Repeat for other folders** (controls, marquee, etc.)

---

### Option B: Use Your Original Photo Names

**Don't want to rename?** No problem!

If your photos are named:
- `IMG_20240115_143522.jpg`
- `IMG_20240115_143655.jpg`
- `IMG_20240115_143821.jpg`

Just type them exactly:
```javascript
const photos = [
    'IMG_20240115_143522.jpg',
    'IMG_20240115_143655.jpg',
    'IMG_20240115_143821.jpg',
];
```

---

## 📁 Folder Structure You'll Have:

```
golden-defender-site/
│
├── index.html          ← Main page
├── bezel.html          ← Bezel gallery
├── controls.html       ← Controls gallery
├── marquee.html        ← Marquee gallery
├── boards.html         ← Boards gallery
├── monitor.html        ← Monitor gallery
├── full-photos.html    ← All photos gallery
├── README.md           ← Full instructions
│
└── images/
    ├── bezel/          ← Put bezel photos here
    ├── controls/       ← Put controls photos here
    ├── marquee/        ← Put marquee photos here
    ├── boards/         ← Put boards photos here
    ├── monitor/        ← Put monitor photos here
    └── full-photos/    ← Put full cabinet photos here
```

---

## ⚡ FASTEST WAY TO GET STARTED:

1. **Start with just ONE folder** (like "bezel")
2. **Add 3-5 photos** to test
3. **Update the bezel.html** file with those photo names
4. **Zip and upload** to Netlify
5. **See it working!**
6. **Then add more** photos and folders

---

## 🆘 Troubleshooting:

**Photos not showing?**
- Check the photo is in the right folder
- Check the filename matches EXACTLY (including .jpg or .png)
- Check for spaces in filenames (use dashes instead)

**Page looks broken?**
- Make sure you uploaded the WHOLE folder as a ZIP
- Make sure `index.html` is at the root (not inside another folder)

---

## 💪 You Got This!

The hardest part is done - the website is built and beautiful!  
Now you just need to:
1. Copy photos into folders
2. List the photo names in the HTML files
3. Upload

Each folder/page is independent, so do them one at a time!

---

Need help? The website works right now with placeholders,  
so you can upload it and see it live before adding ANY photos!