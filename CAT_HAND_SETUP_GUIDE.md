# CAT HAND - Complete Setup Guide
## Memory Stitcher and Workshops

---

## 🎉 What You Have

Your brand new "Cat Hand" website with:

1. **index.html** - Main landing page with 6 categories:
   - 📸 Photo Embroidery
   - 🎂 Birthday & Celebrations  
   - 🎁 Custom Gifts
   - 🏠 Home & Family
   - 🎓 Graduation & Milestones
   - ✂️ Workshops

2. **photo-embroidery.html** - Example gallery page for photo embroidery

3. **workshops.html** - Complete workshops page with 6 different class offerings

---

## 🚀 Quick Start - Upload to GitHub Pages

### Step 1: Create GitHub Account (if you don't have one)
1. Go to **github.com**
2. Click "Sign up"
3. Create your account (it's free!)

### Step 2: Create Repository
1. Click the **"+"** icon (top right) → "New repository"
2. Name it: `yourusername.github.io`
   - ⚠️ Replace "yourusername" with YOUR GitHub username
   - Example: If you're "maria123", name it `maria123.github.io`
3. Make it **Public**
4. Check: "Add a README file"
5. Click "Create repository"

### Step 3: Upload Your Files
1. In your repository, click **"Add file"** → **"Upload files"**
2. Drag and drop:
   - `index.html`
   - `photo-embroidery.html`
   - `workshops.html`
   - ALL your photos (photo-embroidery-1.jpg, etc.)
3. Click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Click **"Settings"** in your repository
2. Left sidebar → Click **"Pages"**
3. Under "Source" → Select **"main"** branch
4. Click **"Save"**
5. Wait 2-3 minutes
6. Your site will be live at: `https://yourusername.github.io`

---

## 📝 Customization Guide

### A) Add Your Contact Information

In **ALL files** (index.html, photo-embroidery.html, workshops.html), find and replace:

**Telegram:**
```html
<a href="https://t.me/yourusername"
```
Replace `https://t.me/yourusername` with YOUR Telegram link

**Email:**
```html
<a href="mailto:your.email@example.com"
```
Replace `your.email@example.com` with YOUR email

**WhatsApp:**
```html
<a href="https://wa.me/1234567890"
```
Replace `1234567890` with YOUR WhatsApp number (include country code, no + or spaces)
Example: `https://wa.me/355671234567` for Albanian number

**Instagram (if you want to add):**
```html
<a href="https://instagram.com/yourusername"
```

---

### B) Add Your Photos

#### For Photo Embroidery Gallery (photo-embroidery.html):

Find this:
```html
<div class="placeholder-image" style="height: 300px;">
    Replace with<br>photo-embroidery-1.jpg
</div>
```

Replace the entire placeholder div with:
```html
<img src="photo-embroidery-1.jpg" alt="Family Portrait">
```

Do this for all 6 images in the gallery:
- photo-embroidery-1.jpg
- photo-embroidery-2.jpg
- photo-embroidery-3.jpg
- etc.

**Pro tip:** Name your photo files exactly as shown, or update the HTML to match your filenames

---

### C) Create More Gallery Pages

You have 6 categories but only 2 gallery pages created. To make more:

1. **Copy** `photo-embroidery.html`
2. **Rename** it to match your category:
   - `celebrations.html` (Birthday & Celebrations)
   - `custom-gifts.html` (Custom Gifts)
   - `home-family.html` (Home & Family)
   - `milestones.html` (Graduation & Milestones)
3. **Edit** each file:
   - Change the `<title>` tag
   - Change the `<h1>` heading
   - Update subtitle
   - Replace photos with relevant images

---

### D) Customize Workshop Offerings

In `workshops.html`, you can:

**Add more workshops:**
Copy a workshop card and modify:
```html
<div class="workshop-card">
    <span class="workshop-icon">🎨</span>
    <div class="workshop-title">Your Workshop Name</div>
    <div class="workshop-description">
        Description here
    </div>
    <div class="workshop-details">
        Duration: X hours<br>
        Any special notes
    </div>
</div>
```

**Remove workshops you don't offer:**
Delete the entire `<div class="workshop-card">...</div>` block

---

## 📂 File Organization

Your folder should look like:

```
📁 cat-hand-website/
├── index.html
├── photo-embroidery.html
├── celebrations.html          ← Create this
├── custom-gifts.html          ← Create this
├── home-family.html           ← Create this
├── milestones.html            ← Create this
├── workshops.html
├── photo-embroidery-1.jpg
├── photo-embroidery-2.jpg
├── celebrations-1.jpg
├── celebrations-2.jpg
├── custom-gifts-1.jpg
└── ... (all your photos)
```

---

## 🎨 Your Brand Identity

**Business Name:** Cat Hand  
**Tagline:** Memory Stitcher and Workshops  
**Logo:** Your funny cat design (add this later!)

**What You Offer:**
- Photo embroidery keepsakes
- Birthday crowns for toddlers
- Custom tote bags and gifts
- Family tablecloths and home decor
- Graduation commemorative pieces
- Hands-on embroidery workshops

---

## 📱 Creating Your QR Code

Once your site is live:

1. Copy your URL: `https://yourusername.github.io`
2. Go to **qr-code-generator.com** or **qrcode-monkey.com**
3. Paste your URL
4. Customize if you want (add cat logo, colors)
5. Download as **PNG** (at least 300 DPI for printing)
6. Add to your business cards!

**QR Code Size for Business Cards:**
- Minimum: 2cm x 2cm (0.8 inches)
- Recommended: 2.5cm x 2.5cm (1 inch)
- Add text: "Scan to see my work!"

---

## ✅ Testing Checklist

Before printing business cards:

- [ ] All pages load correctly
- [ ] All category links work
- [ ] Photos display properly (not broken images)
- [ ] Telegram/WhatsApp/Email links work
- [ ] Test QR code on YOUR phone
- [ ] Test QR code on a FRIEND's phone (iPhone AND Android)
- [ ] Site loads fast (under 3 seconds)
- [ ] Mobile-friendly (looks good on phones)
- [ ] No spelling errors
- [ ] Contact info is correct

---

## 🎯 Next Steps

### Immediately:
1. ✅ Upload files to GitHub Pages
2. ✅ Replace placeholder contact info
3. ✅ Add your photos to photo-embroidery.html

### Soon:
4. Create remaining gallery pages (celebrations, gifts, etc.)
5. Take professional photos of your work
6. Generate QR code
7. Design business cards with QR code

### Later:
8. Add more photos as you create new pieces
9. Update workshop schedules
10. Consider adding a custom domain (optional)

---

## 💡 Pro Tips

**Photo Tips:**
- Use natural lighting (near a window)
- Plain white or neutral background
- Take photos straight-on (not at angles)
- Show details in close-ups
- Image size: 1200px wide is perfect

**File Naming:**
- Use lowercase
- No spaces (use hyphens instead)
- Be descriptive
- ✅ `birthday-crown-pink.jpg`
- ❌ `IMG_2034.JPG`

**SEO (Search Engine Optimization):**
- Your site will appear in Google after a few weeks
- People can find you by searching "Cat Hand embroidery"
- The categories help people find specific services

---

## ❓ Common Questions

**Q: Do visitors need a GitHub account to view my site?**
A: NO! Only YOU need a GitHub account. Anyone can visit your site.

**Q: Can I use a custom domain like cathand.com?**
A: Yes! GitHub Pages supports custom domains (you'd need to buy the domain separately)

**Q: How do I update my site after it's live?**
A: Just upload new files to your GitHub repository, they'll update automatically

**Q: Can I add more pages later?**
A: Absolutely! Just create new HTML files and link to them

**Q: Is this really free forever?**
A: Yes! GitHub Pages is 100% free for public repositories

**Q: What if I want to add a blog or shop?**
A: You can add these later, or integrate with platforms like Shopify/Etsy

---

## 🆘 Need Help?

If you get stuck:
1. Check GitHub Pages documentation: docs.github.com/pages
2. YouTube: Search "GitHub Pages tutorial"
3. Ask on GitHub community forums

Remember: You don't need to be a coding expert! Just follow these steps and you'll have a beautiful professional website for Cat Hand! 🐱✨

---

**Good luck with Cat Hand! May your memories be forever stitched! 🧵💕**