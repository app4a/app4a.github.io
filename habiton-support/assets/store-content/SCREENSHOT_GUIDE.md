# HabitOn - Screenshot Guide

## Required Screenshots

### iOS Requirements

**Sizes Needed:**
- **6.5" Display** (iPhone 14 Pro Max, 15 Pro Max): 1290 x 2796 pixels (Required)
- **5.5" Display** (iPhone 8 Plus): 1242 x 2208 pixels (Optional but recommended)

**Number**: Minimum 3, Maximum 10 (Recommended: 5-6)

### Android Requirements

**Sizes Needed:**
- **Phone**: 1080 x 1920 pixels minimum (Required)
- **7" Tablet**: 1080 x 1920 pixels (Optional)
- **10" Tablet**: 1920 x 1200 pixels (Optional)

**Number**: Minimum 2, Maximum 8 (Recommended: 5-6)

---

## Screenshot Sequence (Recommended Order)

### Screenshot 1: Home Screen with Habits
**What to show:**
- List of 5-6 diverse habits
- Mix of completed (green checkmarks) and incomplete habits
- Current date showing "Today"
- Visible streak numbers on habits
- Clean, organized interface

**Text Overlay:**
"Track Your Daily Habits"
"Simple. Focused. Effective."

### Screenshot 2: Habit Completion / Calendar View
**What to show:**
- A habit's completion calendar
- Visible streak (e.g., "🔥 12 day streak")
- Completion rate percentage
- Calendar with green dots showing completed days
- Clear progress visualization

**Text Overlay:**
"Build Streaks & Stay Motivated"
"Visual progress tracking"

### Screenshot 3: Add Habit Screen
**What to show:**
- "Add New Habit" screen
- Filled form showing:
  - Habit name: "Morning Exercise"
  - Category selected (Health)
  - Frequency: Daily
  - Reminder time: 7:00 AM
  - Custom icon/color selected

**Text Overlay:**
"Flexible Scheduling"
"Daily, Weekly, Monthly & Custom"

### Screenshot 4: Analytics/Stats Screen
**What to show:**
- Analytics dashboard
- Completion rate charts
- Multiple habits with their stats
- Streak overview
- Clean data visualization

**Text Overlay:**
"Insightful Analytics"
"Track your progress over time"

### Screenshot 5: Notifications Example
**What to show:**
- Mockup of notification appearing
- Or settings screen showing notification preferences
- Example: "Time to complete: Morning Exercise, Read 30 minutes"
- Clean notification design

**Text Overlay:**
"Smart Reminders"
"Never miss a habit"

### Screenshot 6 (Optional): Privacy/Features
**What to show:**
- Profile screen or a designed graphic
- Key features listed:
  - ✓ 100% Private
  - ✓ No Account Needed
  - ✓ Offline Always
  - ✓ No Ads

**Text Overlay:**
"Your Data, Your Device"
"Complete privacy guaranteed"

---

## Design Guidelines

### Text Overlays
- **Font**: Bold, sans-serif (SF Pro Display for iOS, Roboto for Android)
- **Color**: White text with dark semi-transparent background OR dark text with light background
- **Size**: Large enough to read in thumbnail view
- **Position**: Top or bottom third of screen (avoid covering important UI)

### Device Frames
- **Option 1**: No device frame (full bleed) - Modern, clean look
- **Option 2**: Device frame with shadow - More realistic
- **Recommendation**: No frame for app stores (cleaner)

### Background
- Keep actual app UI as background
- Optional: Subtle gradient overlay for text readability
- Avoid busy backgrounds that distract from content

### Colors to Use
- **Primary**: #4CAF50 (App green)
- **Accent**: #FF9800 (Orange for highlights)
- **Text**: White or #212121 (dark gray)

---

## Screenshot Creation Tools

### Option 1: Real Device Screenshots (Recommended)
1. Use Xcode Simulator (iOS) or Android Emulator
2. Set device to required resolution
3. Take screenshots of actual app
4. Add text overlays in design tool

**Tools for Overlays:**
- Figma (free, web-based)
- Canva (free tier available)
- Adobe Photoshop
- Sketch (Mac only)

### Option 2: Screenshot Design Services
- **App Screenshot Builder** (online tools)
- **Previewed** - previewed.app (paid)
- **AppLaunchpad** - app-launchpad.com (paid)
- **PlaceIt** - placeit.net (paid)

### Option 3: Mockup Generators
- **Shotbot** - shotbot.io
- **MockuPhone** - mockuphone.com (free)
- **Smart Mockups** - smartmockups.com

---

## Sample Data for Screenshots

### Habits to Show:
1. **Morning Exercise** (Health) - 🔥 12 day streak - Completed today
2. **Read 30 minutes** (Learning) - 🔥 5 day streak - Not completed
3. **Drink Water** (Health) - 🔥 24 day streak - Completed today
4. **Practice Guitar** (Hobbies) - 🔥 3 day streak - Not completed
5. **Meditate** (Wellness) - 🔥 18 day streak - Completed today
6. **Journal** (Productivity) - 🔥 7 day streak - Not completed

### Stats to Display:
- Overall completion rate: 78%
- Active habits: 6
- Longest streak: 24 days
- Date: Show current month

---

## Testing Checklist

Before submitting screenshots:

- [ ] All screenshots are correct resolution
- [ ] Text is readable in thumbnail size
- [ ] No personal/sensitive information visible
- [ ] App UI looks polished (no debug elements)
- [ ] Screenshots show key features
- [ ] Text overlays don't have typos
- [ ] Colors are consistent with brand
- [ ] Screenshots tell a story (logical sequence)
- [ ] All required sizes provided
- [ ] File names are descriptive (e.g., "habiton-ios-1-home.png")

---

## Quick Capture Commands

### iOS Simulator
```bash
# Launch simulator with specific device
xcrun simctl boot "iPhone 15 Pro Max"
open -a Simulator

# Take screenshot
xcrun simctl io booted screenshot ~/Desktop/screenshot.png
```

### Android Emulator
```bash
# Take screenshot
adb shell screencap /sdcard/screenshot.png
adb pull /sdcard/screenshot.png ~/Desktop/
```

---

## File Naming Convention

Use descriptive names:
- `habiton-ios-01-home-screen.png`
- `habiton-ios-02-habit-calendar.png`
- `habiton-ios-03-add-habit.png`
- `habiton-android-01-home-screen.png`
- etc.

---

## Pro Tips

1. **Use Real Data**: Real-looking habits are more convincing than generic ones
2. **Show Success**: Include completed habits with good streaks
3. **Keep It Clean**: Don't show too many habits at once (5-6 max)
4. **Highlight Key Features**: Each screenshot should showcase one main feature
5. **Test Thumbnails**: View screenshots at small size to ensure readability
6. **Consistent Time**: Use same time across all screenshots (e.g., 2:30 PM)
7. **Status Bar**: Keep it clean (full battery, good signal, no distracting notifications)

---

## Next Steps After Creating Screenshots

1. Export at exact required resolutions
2. Review all screenshots for quality and consistency
3. Add to App Store Connect / Google Play Console
4. A/B test different screenshot sequences if possible
5. Update screenshots with each major app update



