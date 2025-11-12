# HabitOn - Icon & Graphics Specifications

## App Icon Requirements

### iOS App Icon

**Size**: 1024 x 1024 pixels  
**Format**: PNG (no transparency)  
**Color Space**: RGB  
**File Size**: Under 1MB

**Design Guidelines:**
- No transparency or alpha channels
- Must be square (no rounded corners - iOS handles that)
- Should be recognizable at small sizes (60x60)
- Avoid text (illegible at small sizes)
- Should work on light and dark backgrounds

### Android App Icon

**Adaptive Icon** (Required):
- **Foreground**: 1080 x 1080 pixels, PNG with transparency
- **Background**: 1080 x 1080 pixels, PNG (can be solid color)
- **Safe Zone**: Keep important elements within center 66% (720 x 720 px)

**Legacy Icon** (Fallback):
- **Size**: 512 x 512 pixels
- **Format**: PNG

**Design Guidelines:**
- Foreground should work on any background
- Background can be solid color or simple pattern
- Test with different mask shapes (circle, squircle, rounded square)

---

## Icon Design Concept for HabitOn

### Concept 1: Checkmark + Flame (Recommended)
**Design Elements:**
- Large checkmark (representing habit completion)
- Small flame emoji/icon in corner (representing streak)
- Green gradient background (#4CAF50 to #66BB6A)
- Clean, modern, minimal

**Why it works:**
- Instantly communicates "habit tracking"
- Checkmark is universal symbol for completion
- Flame represents streaks (familiar to users)
- Green = growth, progress, success

### Concept 2: Calendar + Check
**Design Elements:**
- Simplified calendar grid
- One day marked with checkmark
- Circular design
- Green and white color scheme

**Why it works:**
- Shows daily tracking concept
- Clear and simple
- Professional look

### Concept 3: Circular Progress
**Design Elements:**
- Circular progress indicator (75% filled)
- Checkmark in center
- Gradient ring
- Minimalist

**Why it works:**
- Shows progress/completion
- Modern design
- Stands out in app grid

---

## Color Palette

### Primary Colors (Use These)
- **Brand Green**: #4CAF50
- **Light Green**: #66BB6A
- **Dark Green**: #388E3C
- **Accent Orange**: #FF9800 (for flame/streak elements)

### Background Options
- Gradient: #4CAF50 → #66BB6A
- Solid: #4CAF50
- White (with colored icon)

---

## Feature Graphic (Android Only)

### Specifications
- **Size**: 1024 x 500 pixels
- **Format**: PNG or JPEG
- **File Size**: Under 1MB
- **Usage**: Google Play Store header

### Design Layout

```
[Left 40%]                    [Right 60%]
- App Icon                    - App Name: "HabitOn"
- Or Screenshot Preview       - Tagline: "Build Better Habits"
                              - Key Features (3-4 bullet points)
                              - Visual elements (checkmarks, stars)
```

### Feature Graphic Content

**Text to Include:**
- **Main Headline**: "HabitOn - Daily Habit Tracker"
- **Tagline**: "Build Better Habits, One Day at a Time"
- **Key Points**:
  - ✓ Track Daily Habits
  - ✓ Build Streaks
  - ✓ Smart Reminders
  - ✓ 100% Private

**Visual Elements:**
- App icon on left
- Screenshot collage or mockup
- Background gradient (green theme)
- Clean, professional typography

---

## Icon Design Tool Recommendations

### Free Tools
1. **Figma** - figma.com (Best option, web-based)
2. **Canva** - canva.com (Easy templates)
3. **GIMP** - gimp.org (Free Photoshop alternative)
4. **Inkscape** - inkscape.org (Vector graphics)

### Paid Tools
1. **Adobe Illustrator** (Industry standard)
2. **Sketch** (Mac only, popular)
3. **Affinity Designer** (One-time purchase)

### Icon Generation Services
1. **App Icon Generator** - appicon.co (Free, generates all sizes)
2. **MakeAppIcon** - makeappicon.com (Free)
3. **Icon Kitchen** (Android) - icon.kitchen
4. **Figma Icon Templates** (Search community files)

---

## Design Process

### Step 1: Create Master Icon (1024x1024)
1. Open design tool
2. Create 1024x1024 canvas
3. Design icon with elements in safe zone (920x920 center)
4. Use vector shapes when possible (scalability)
5. Export as PNG at 72 DPI minimum

### Step 2: Test at Different Sizes
Export and view at:
- 1024x1024 (App Store)
- 180x180 (iPhone app icon)
- 120x120 (iPhone smaller size)
- 60x60 (Settings)
- 40x40 (Spotlight)

Ensure icon is recognizable at all sizes.

### Step 3: Test on Different Backgrounds
- White background
- Black background
- Home screen wallpapers (light and dark)
- In grid with other apps

### Step 4: Generate All Required Sizes

**iOS** (Use tool to generate):
- 1024x1024 (App Store)
- 180x180 (@3x)
- 120x120 (@2x)
- 60x60 (@1x)
- Plus all iPad sizes

**Android** (Use tool to generate):
- xxxhdpi: 192x192
- xxhdpi: 144x144
- xhdpi: 96x96
- hdpi: 72x72
- mdpi: 48x48

---

## Simple DIY Icon Design (Figma)

### Quick Tutorial:

1. **Open Figma** (figma.com - free account)

2. **Create Frame**: 1024 x 1024 pixels

3. **Add Background**:
   - Draw rectangle, size 1024x1024
   - Fill with gradient: #4CAF50 → #66BB6A (top to bottom)

4. **Add Checkmark**:
   - Use plugins like "Iconify" or "Feather Icons"
   - Search for "check" icon
   - Size: ~600px, centered
   - Color: White
   - Optional: Add subtle shadow for depth

5. **Add Flame** (Optional):
   - Emoji: 🔥 or icon
   - Position in top-right corner
   - Size: ~250px
   - Optional: White circle background

6. **Polish**:
   - Adjust spacing
   - Ensure balance
   - Round corners slightly if desired (but no transparency)

7. **Export**:
   - File → Export
   - Format: PNG
   - Size: 1024x1024
   - No transparency

8. **Generate All Sizes**:
   - Use appicon.co to upload your 1024x1024
   - Download generated size pack
   - Add to Xcode/Android Studio project

---

## Feature Graphic Design (Figma)

### Quick Tutorial:

1. **Create Frame**: 1024 x 500 pixels

2. **Background**:
   - Gradient or solid #4CAF50
   - Or use screenshot as background (blurred)

3. **Left Side** (40%):
   - Add app icon (300x300)
   - Or phone mockup with screenshot

4. **Right Side** (60%):
   - Text: "HabitOn" (60-80pt, bold, white)
   - Tagline: "Build Better Habits" (24pt, white, 80% opacity)
   - Bullet points with checkmarks
   - Keep text readable (high contrast)

5. **Export**:
   - Format: PNG or JPEG
   - Size: 1024 x 500
   - Under 1MB

---

## Icon Testing Checklist

Before finalizing:

- [ ] Icon is 1024x1024 pixels (iOS) and has adaptive layers (Android)
- [ ] No transparency in iOS version
- [ ] Recognizable at 60x60 pixels
- [ ] Works on light backgrounds
- [ ] Works on dark backgrounds
- [ ] No text (or text is very large and readable)
- [ ] Follows platform guidelines
- [ ] Matches app brand colors
- [ ] Looks professional and polished
- [ ] Different from competitors
- [ ] Tested in app grid next to other icons
- [ ] All required sizes generated

---

## Asset Checklist for Submission

### iOS
- [ ] App Icon (1024x1024 PNG)
- [ ] 5-6 screenshots (1290 x 2796 for 6.5" display)
- [ ] Optional: Screenshots for 5.5" display
- [ ] Optional: App Preview video

### Android
- [ ] App Icon - Adaptive (foreground + background, 1080x1080 each)
- [ ] App Icon - Legacy (512x512 PNG)
- [ ] Feature Graphic (1024 x 500)
- [ ] 5-6 screenshots (1080 x 1920 minimum)
- [ ] Optional: Tablet screenshots
- [ ] Optional: Promo video

---

## Resources

### Stock Images & Assets
- **Unsplash** - unsplash.com (free photos)
- **Pexels** - pexels.com (free photos)
- **Flaticon** - flaticon.com (icons)
- **Feather Icons** - feathericons.com (minimal icons)

### Mockup Tools
- **Previewed** - previewed.app
- **Mockuphone** - mockuphone.com
- **Smartmockups** - smartmockups.com

### Icon Inspiration
- **Dribbble** - dribbble.com/tags/app_icon
- **Behance** - behance.net/search/projects/app%20icon
- **App Store** - Study successful app icons in Productivity category

---

## Pro Tips

1. **Keep It Simple**: Icon should be recognizable at a glance
2. **Test Everywhere**: View on actual devices, not just on computer
3. **Be Unique**: Stand out from other habit tracking apps
4. **Consistency**: Icon should match app's UI design language
5. **No Words**: Avoid text in icon (doesn't scale well)
6. **High Contrast**: Ensure icon pops on any background
7. **Version Control**: Save all versions/iterations
8. **Get Feedback**: Show to potential users before finalizing

---

Ready to create your icon? Start with Figma + the checkmark/flame concept for a professional look!



