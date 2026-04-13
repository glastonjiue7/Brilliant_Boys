# 🚀 Deployment Guide - Vercel

Your cricket tournament website is **100% complete** and ready to deploy!

## What's Included

✅ **Homepage** with tournament information  
✅ **Logo & Images** - Brilliant Boys Club logo, trophy display, beach venue, Instagram QR  
✅ **All 18 Tournament Rules** - In Marathi & English  
✅ **Prize Money Section** - With trophy photos  
✅ **Tournament Details** - Dates, venue, format, entry fee  
✅ **Contact Information** - 4 coordinators with phone numbers  
✅ **Social Media** - Instagram QR code & handle  
✅ **Registration Link** - Direct link to tournament portal  
✅ **51 Images** - All from your PowerPoint presentation  
✅ **Responsive Design** - Works on mobile, tablet, desktop  

---

## Deploy in 3 Simple Steps

### **Option 1: Vercel Drag & Drop (Easiest)**

1. Go to **https://vercel.com**
2. Click **"New Project"** → **"Other"**
3. Drag & drop the entire `cricket-tournament-website` folder
4. Click **"Deploy"**
5. ✅ Done! Your website goes live instantly

**Your URL will be something like**: `cricket-tournament-website-abc123.vercel.app`

---

### **Option 2: GitHub + Vercel (Recommended for teams)**

**Step 1: Push to GitHub**
```bash
cd /Users/glaston.jiue/Desktop/Personal\ Doc/Cricket/cricket-tournament-website

git init
git add .
git commit -m "Initial commit: Cricket tournament website"
git remote add origin https://github.com/YOUR_USERNAME/cricket-tournament-website.git
git push -u origin main
```

**Step 2: Connect to Vercel**
1. Go to https://vercel.com
2. Click "New Project"
3. Select your GitHub repository
4. Click "Deploy"

**Benefits**: 
- Auto-deploys when you push changes
- Easy to share with team members
- Version control included

---

### **Option 3: Vercel CLI (For developers)**

```bash
# Install Vercel CLI
npm install -g vercel

# Navigate to project
cd /Users/glaston.jiue/Desktop/Personal\ Doc/Cricket/cricket-tournament-website

# Deploy
vercel

# Follow prompts to complete deployment
```

---

## After Deployment

### 1. **Share Your Website**
Once deployed, you'll get a URL like:
```
https://cricket-tournament-website.vercel.app
```

Share this link with:
- Teams via WhatsApp/Email
- Social media posts
- Tournament registration portals
- Instagram @DEVTALAO_BOYS

### 2. **Update Tournament Details**
If you need to change anything:
- Edit `index.html`
- Update phone numbers, dates, or text
- Push to GitHub (if using GitHub) or re-upload to Vercel
- Changes go live in seconds!

### 3. **Monitor Performance**
- Vercel automatically provides analytics
- See visitor count, page views, traffic sources
- Monitor on Vercel dashboard

---

## Website Structure

### **Header**
- Brilliant Boys Club Logo
- Tournament Title & Season

### **Main Content**
1. **Tournament Details** - 24 Teams, 5 Overs, Dates, Fee
2. **Venue** - Uttanbandar Beach with photo
3. **Prize Money** - With trophy display image
4. **Special Awards** - 8 different awards
5. **Special Feature** - 3 Super Over matches
6. **Important Info** - Entry requirements
7. **Registration CTA** - Button to register
8. **Contact Info** - 4 coordinators with phones
9. **Social Media** - Instagram QR code
10. **Tournament Rules** - All 18 rules in Marathi & English
11. **Consent Declaration** - Legal agreement

### **Footer**
- Tournament name
- Organizer info
- Copyright

---

## Customization (Optional)

### Change Colors
Open `index.html` and find the `<style>` section:
- Primary Color: `#0a3d5c` (Navy Blue)
- Accent Color: `#ff6b35` (Orange)

Replace with your preferred colors.

### Update Contact Information
Search for phone numbers and update:
- Brijal: 9152303111
- Gleson: 8655861163
- Rowin: 8898223990
- Glaston: 9821709825

### Add More Images
1. Place new images in `/images/` folder
2. Reference in HTML: `<img src="images/imagename.png">`

### Change Tournament Details
- Dates: Search "June 2026"
- Entry Fee: Search "Rs. 7,000"
- Prize Money: Search "Rs. 75,000"
- Teams: Search "24"

---

## Troubleshooting

### Images not showing?
✓ Make sure `images/` folder is uploaded with all files  
✓ Check file paths in HTML match actual filenames  
✓ Use relative paths: `images/image1.png`

### Website looks different on mobile?
✓ This is normal - CSS is responsive  
✓ All content is accessible on all devices

### Need to make changes later?
✓ Edit HTML file locally
✓ Push to GitHub or re-upload to Vercel
✓ Website updates in seconds!

---

## Domain Setup (Optional)

To use your own domain (e.g., `cricketstournament.com`):

1. Buy a domain from Godaddy, Namecheap, etc.
2. In Vercel dashboard → Project Settings → Domains
3. Add your custom domain
4. Update domain's DNS settings (Vercel will guide you)
5. Website now live on your custom domain!

---

## File Size

| Item | Size |
|------|------|
| index.html | 29 KB |
| All Images | 2.1 MB |
| Config Files | < 1 KB |
| **Total** | **2.13 MB** |

✅ Well within Vercel's free tier limits

---

## Support

### Need Help?
- **Vercel Support**: https://vercel.com/support
- **HTML/CSS Questions**: https://www.w3schools.com
- **Domain Help**: Contact your domain registrar

### Share Feedback
- Update your website based on feedback
- Re-deploy with new changes
- Track analytics on Vercel dashboard

---

## Checklist Before Going Live

- [ ] Review all tournament details are correct
- [ ] Check contact phone numbers are accurate
- [ ] Verify dates are correct (June 2026)
- [ ] Test on mobile phone
- [ ] Test on tablet
- [ ] Test on desktop
- [ ] All images display correctly
- [ ] All links work (Registration link, etc.)
- [ ] Instagram QR code is clear
- [ ] Rules are complete and readable

---

## Go Live! 🎉

Your website is ready. **Deploy it now and start promoting the tournament!**

**Happy Cricket Tournament! 🏏**

---

*Created: April 2026*  
*Rainy Season Beach Cricket Tournament - Season 32*  
*Organized by DEVTALAO_BOYS*
