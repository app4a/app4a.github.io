Localization structure for store content

Place localized files under per-locale folders:

- en/
  - APP_DESCRIPTION.txt
  - KEYWORDS.txt
  - PRIVACY_POLICY.html
  - TERMS_OF_SERVICE.html
- ko/
  - APP_DESCRIPTION.txt
  - KEYWORDS.txt
  - PRIVACY_POLICY.html
  - TERMS_OF_SERVICE.html

All filenames must exist for each locale. Add new locales by creating a folder and mirroring filenames.

# App Store Submission Content

All content required for Apple App Store and Google Play Store submission has been prepared and is ready to use.

## 📝 What's Included

### Text Content (Ready to Use)
1. **APP_DESCRIPTION.txt** - Complete app store listings
   - Full description (2,200 chars, under 4,000 limit)
   - Short description for Android (72 chars)
   - Promotional text for iOS (167 chars)
   - All optimized for App Store Optimization (ASO)

2. **KEYWORDS.txt** - SEO and discoverability
   - iOS keywords (99 chars, under 100 limit)
   - Android category tags
   - Keyword strategy and recommendations

### Legal Documents (Ready to Host)
3. **PRIVACY_POLICY.html** - Complete privacy policy
   - Fully styled, professional HTML
   - Emphasizes local-only data storage
   - No data collection = simplified compliance
   - Ready to upload to GitHub Pages or web host

4. **TERMS_OF_SERVICE.html** - Complete terms of service
   - Fully styled, professional HTML
   - Standard terms for mobile apps
   - Covers liability, usage rights, disclaimers
   - Ready to upload to GitHub Pages or web host

### Guides (For Creating Assets)
5. **SCREENSHOT_GUIDE.md** - Complete screenshot instructions
   - Required sizes for iOS and Android
   - 6 screenshot concepts with descriptions
   - Text overlay suggestions
   - Design guidelines and best practices
   - Tools and commands for capture
   - Testing checklist

6. **ICON_AND_GRAPHICS_SPECS.md** - Icon design specifications
   - iOS app icon specs (1024x1024)
   - Android adaptive icon specs (foreground + background)
   - Feature graphic specs for Google Play
   - 3 design concepts (recommended: checkmark + flame)
   - Step-by-step Figma tutorial
   - Design tool recommendations
   - Testing checklist

7. **SUPPORT_CONTACT_SETUP.md** - Support infrastructure guide
   - Email setup instructions
   - Auto-reply templates
   - Response templates for common issues
   - FAQ content (ready to use)
   - Simple GitHub Pages website setup
   - Management and monitoring tips

---

## ✅ Next Steps (In Order)

### 1. Host Legal Documents (15 minutes)
**Option A: GitHub Pages (Free, Recommended)**
```bash
# Create repository
gh repo create habiton-support --public
cd habiton-support

# Copy files
cp assets/store-content/PRIVACY_POLICY.html privacy.html
cp assets/store-content/TERMS_OF_SERVICE.html terms.html

# Push and enable GitHub Pages
git add .
git commit -m "Add legal documents"
git push

# Enable in Settings → Pages → Source: main branch
```

**URLs will be:**
- Privacy Policy: `https://yourusername.github.io/habiton-support/privacy.html`
- Terms of Service: `https://yourusername.github.io/habiton-support/terms.html`

**Option B: Netlify/Vercel (Also Free)**
- Just drag and drop the HTML files
- Get instant URLs

### 2. Set Up Support Email (15 minutes)
1. Create `support@habiton.app` or `habiton.support@gmail.com`
2. Set up auto-reply from `SUPPORT_CONTACT_SETUP.md`
3. Save email templates as Gmail canned responses
4. Test by sending yourself an email

### 3. Create App Icon (1-2 hours)
Follow `ICON_AND_GRAPHICS_SPECS.md`:
1. Open Figma (free account)
2. Use the "Checkmark + Flame" design concept
3. Export 1024x1024 PNG
4. Use appicon.co to generate all sizes
5. Replace files in `/assets/` folder

### 4. Take Screenshots (2-3 hours)
Follow `SCREENSHOT_GUIDE.md`:
1. Run app on simulator/emulator
2. Add 5-6 sample habits with good streaks
3. Capture 5-6 screens at required resolutions
4. Add text overlays in Figma/Canva
5. Test readability at thumbnail size

### 5. Copy Content to App Stores

#### Apple App Store Connect
1. **App Information**
   - Name: HabitOn
   - Subtitle: Daily Habit Tracker (or similar)
   - Privacy Policy URL: [Your GitHub Pages URL]/privacy.html
   
2. **App Store Information**
   - Promotional Text: (from `APP_DESCRIPTION.txt`)
   - Description: (from `APP_DESCRIPTION.txt`)
   - Keywords: (from `KEYWORDS.txt`)
   - Support URL: [Your GitHub Pages URL] or mailto:support@habiton.app
   - Marketing URL: (optional)

3. **Media**
   - App Icon: Upload 1024x1024 PNG
   - Screenshots: Upload 5-6 for 6.5" display
   - App Preview: (optional)

#### Google Play Console
1. **Store Listing**
   - App name: HabitOn
   - Short description: (from `APP_DESCRIPTION.txt`)
   - Full description: (from `APP_DESCRIPTION.txt`)
   
2. **Graphics**
   - App icon: 512x512 PNG
   - Feature graphic: 1024x500 (follow guide)
   - Screenshots: 5-6 at 1080x1920

3. **Contact Details**
   - Email: support@habiton.app
   - Website: [Your GitHub Pages URL]
   - Privacy Policy: [Your GitHub Pages URL]/privacy.html

4. **Categorization**
   - Category: Productivity
   - Tags: (from `KEYWORDS.txt`)
   - Content rating: Complete questionnaire (likely Everyone)

### 6. Build & Submit
```bash
# Install EAS CLI (if not already)
npm install -g eas-cli

# Login to Expo
eas login

# Build for iOS
eas build --platform ios --profile production

# Build for Android
eas build --platform android --profile production

# Submit to stores (when builds complete)
eas submit --platform ios
eas submit --platform android
```

---

## 📋 Submission Checklist

### Before Submitting
- [ ] Privacy Policy hosted and accessible
- [ ] Terms of Service hosted and accessible
- [ ] Support email created and tested
- [ ] App icon created (1024x1024)
- [ ] 5-6 screenshots created (all required sizes)
- [ ] Feature graphic created (Android)
- [ ] App description proofread
- [ ] Keywords optimized
- [ ] Age rating questionnaire completed
- [ ] App tested on physical devices
- [ ] All permissions justified and explained

### Apple App Store
- [ ] Apple Developer account ($99/year)
- [ ] App Store Connect listing complete
- [ ] Build uploaded via EAS or Xcode
- [ ] TestFlight testing recommended
- [ ] All required fields filled
- [ ] Screenshots uploaded for all devices
- [ ] App Review information provided
- [ ] Export compliance answered

### Google Play Store
- [ ] Google Play Developer account ($25 one-time)
- [ ] Play Console listing complete
- [ ] AAB uploaded via EAS or Android Studio
- [ ] Internal testing track recommended
- [ ] Data safety form completed
- [ ] Content rating completed
- [ ] Target API 34+ confirmed
- [ ] All store listing content added

---

## 🎯 Content Quality Summary

### ✅ Ready to Use As-Is
- App descriptions (optimized for ASO)
- Privacy Policy (complete, professional)
- Terms of Service (complete, standard)
- Keywords (researched, optimized)

### 📝 Customize Before Using
- Support email (replace `support@habiton.app` with yours if different)
- URLs in legal documents (add your actual website/support URL)
- Contact section in Terms/Privacy (add your jurisdiction if needed)

### 🎨 Create Based on Guides
- App icon (follow specs, use provided concepts)
- Screenshots (follow guide, use suggested sequence)
- Feature graphic (follow specs for Android)
- FAQ website (optional, template provided)

---

## 📊 Estimated Time to Launch

| Task | Time | Can Parallelize? |
|------|------|-----------------|
| Host legal docs | 15 min | - |
| Set up support email | 15 min | ✅ |
| Create app icon | 1-2 hrs | ✅ |
| Take screenshots | 2-3 hrs | ✅ |
| Fill store listings | 1 hr | - |
| Complete ratings | 30 min | ✅ |
| Build with EAS | 1 hr | - |
| Submit to stores | 1 hr | - |

**Sequential Total**: ~8-10 hours  
**With Parallelization**: ~5-6 hours

---

## 💡 Pro Tips

1. **Start with legal docs** - They take 15 minutes and are required
2. **Create icon first** - You'll need it for screenshots and can reuse it
3. **Take extra screenshots** - Easier to have options than to recreate later
4. **Test on real devices** - Especially notifications (don't work fully in simulators)
5. **Use TestFlight/Internal Testing** - Catch issues before public launch
6. **Respond to reviews** - Especially negative ones, shows you care
7. **Monitor first week** - Check for crash reports or common complaints
8. **Plan v1.0.1** - You'll likely find small bugs to fix post-launch

---

## 📞 Need Help?

All content has been created with best practices in mind, but feel free to customize:
- Adjust descriptions to your preference
- Change wording in legal docs (while maintaining intent)
- Use different icon design concepts
- Customize screenshot sequence

The content is production-ready but also flexible for your brand voice!

---

**You're 90% done with productionization! Just assets and execution remaining. Good luck with your launch! 🚀**



