# HabitOn - Support Contact Setup

## Required Contact Information

Both Apple App Store and Google Play Store require you to provide support contact information. This is **mandatory** for app submission.

---

## Options for Support Contact

### Option 1: Email (Recommended)
**Pros:**
- Simple and professional
- Easy to manage
- No website needed
- Direct communication

**Setup:**
1. Create dedicated email: `support@habiton.app` or `hello@habiton.app`
2. Or use personal email if domain not available: `habiton.support@gmail.com`
3. Set up auto-reply for immediate acknowledgment
4. Create email template for common questions

**Recommended Services:**
- **Gmail** (free, reliable)
- **ProtonMail** (privacy-focused)
- **Zoho Mail** (professional, free tier)
- **Custom Domain Email** (if you have habiton.app domain)

### Option 2: Support Website
**Pros:**
- More professional
- Can include FAQ
- Better for scaling

**Setup:**
1. Create simple static website with FAQ
2. Host on:
   - **GitHub Pages** (free)
   - **Netlify** (free)
   - **Vercel** (free)
3. Include contact form or email link

### Option 3: Both (Best for Launch)
- Support website with FAQ
- Email for direct contact
- Links to social media (optional)

---

## Recommended: Simple Support Setup

### Create Gmail Account
1. Go to gmail.com
2. Create account: `habiton.support@gmail.com`
3. Set professional name: "HabitOn Support"
4. Add profile picture (app icon)

### Create Auto-Reply Template
```
Subject: We received your message - HabitOn Support

Thank you for contacting HabitOn Support!

We've received your message and will respond within 24-48 hours.

In the meantime, you might find these resources helpful:

Common Questions:
• How do I backup my data? 
  Use your device's backup feature (iCloud/Google Backup)

• Can I sync across devices? 
  Not currently - all data is stored locally for privacy

• How do I restore a deleted habit? 
  Unfortunately, deleted habits cannot be recovered

• How do streaks work? 
  Complete your habit on scheduled days to maintain your streak

For immediate assistance, check our FAQ: [Link when available]

Best regards,
HabitOn Team

---
This is an automated response. A human will reply to your specific question soon.
```

### Create Response Templates

**Template 1: Feature Request**
```
Thank you for your suggestion about [FEATURE]!

We appreciate user feedback and are always looking to improve HabitOn. 
I've added your request to our feature consideration list.

While I can't promise when or if this will be implemented, knowing what 
users want helps us prioritize development.

Best regards,
HabitOn Support
```

**Template 2: Bug Report**
```
Thank you for reporting this issue with [ISSUE].

To help us investigate:
• What device are you using? (iPhone 14, Samsung Galaxy S23, etc.)
• What iOS/Android version?
• What exactly were you doing when this happened?
• Can you reproduce it consistently?

Your feedback helps us improve the app for everyone!

Best regards,
HabitOn Support
```

**Template 3: Data Loss**
```
I'm sorry to hear you've lost your habit data.

Unfortunately, HabitOn stores all data locally on your device for privacy. 
This means if the app is deleted or the device is reset, data cannot be 
recovered from our end (we don't have access to it).

For the future, I recommend:
• iOS: Enable iCloud Backup (Settings → [Your Name] → iCloud → iCloud Backup)
• Android: Enable Google Backup (Settings → System → Backup)

These will include HabitOn data in your device backups.

I understand this is frustrating, and I'm sorry we can't recover your data.

Best regards,
HabitOn Support
```

---

## FAQ Page Content

Create a simple FAQ page to reduce support emails:

### FAQ Content

**Q: Is my data private?**
A: Yes! All your data stays on your device. We don't collect or store any personal information on servers. See our Privacy Policy for details.

**Q: Can I sync my habits across devices?**
A: Not currently. HabitOn stores data locally for privacy. We may add optional cloud sync in a future version.

**Q: How do I backup my data?**
A: Use your device's built-in backup:
- iOS: Settings → [Your Name] → iCloud → iCloud Backup
- Android: Settings → System → Backup
Your HabitOn data will be included in device backups.

**Q: How do streaks work?**
A: Complete your habit on its scheduled days to build a streak. Missing a scheduled day resets your current streak (but your longest streak is saved!).

**Q: Can I edit or delete a habit?**
A: Yes! Tap the habit to see details, then use the Edit or Delete buttons.

**Q: How do I change notification times?**
A: Edit the habit and update the reminder time. New time will apply going forward.

**Q: What frequency options are available?**
A: Daily, Weekdays, Weekends, Weekly (specific day), Bi-weekly, Monthly, or Custom schedules.

**Q: Can I undo a habit completion?**
A: Yes! Just tap the checkmark again to uncheck it.

**Q: Is there a free trial or subscription?**
A: HabitOn is free with no subscriptions. All features are included.

**Q: Where can I request features?**
A: Email us at support@habiton.app - we love hearing from users!

---

## Simple FAQ Website Template

### Using GitHub Pages (Free)

1. **Create Repository**:
   - Name: `habiton-support`
   - Public repository

2. **Create `index.html`**:
```html
<!DOCTYPE html>
<html>
<head>
    <title>HabitOn Support</title>
    <style>
        body { 
            font-family: -apple-system, system-ui, sans-serif; 
            max-width: 800px; 
            margin: 40px auto; 
            padding: 0 20px;
            line-height: 1.6;
        }
        h1 { color: #4CAF50; }
        h2 { color: #333; margin-top: 30px; }
        .contact { 
            background: #f0f9f0; 
            padding: 20px; 
            border-radius: 8px; 
            margin: 30px 0;
        }
    </style>
</head>
<body>
    <h1>HabitOn Support</h1>
    <p>Welcome! How can we help you?</p>
    
    <div class="contact">
        <strong>Contact Us:</strong><br>
        Email: support@habiton.app<br>
        Response time: 24-48 hours
    </div>
    
    <h2>Frequently Asked Questions</h2>
    
    [Paste FAQ content here]
    
</body>
</html>
```

3. **Enable GitHub Pages**:
   - Settings → Pages
   - Source: main branch
   - URL will be: `yourusername.github.io/habiton-support`

4. **Use this URL** in app store listings

---

## App Store Listing Details

### Apple App Store
**Support URL**: Required
- Enter: `https://yourusername.github.io/habiton-support`
- Or: `mailto:support@habiton.app`

**Marketing URL**: Optional
- Can be same as support URL or separate website

### Google Play Store
**Email**: Required
- Enter: `support@habiton.app`

**Website**: Optional but recommended
- Enter: `https://yourusername.github.io/habiton-support`

**Privacy Policy**: Required (separate, already created)
- Upload PRIVACY_POLICY.html to GitHub Pages
- URL: `https://yourusername.github.io/habiton-support/privacy.html`

---

## Response Time Expectations

### Recommended SLA (Service Level Agreement)
- **Acknowledgment**: Within 24 hours (automated)
- **Response**: Within 24-48 hours
- **Resolution**: Depends on issue complexity

### Managing Volume
**Low Volume** (Expected at launch):
- Check email 1-2 times daily
- Respond personally to each
- Most emails at launch: feature requests, minor bugs

**Medium Volume** (If app grows):
- Set up email filters/labels
- Use templates for common questions
- Consider help desk software (Zendesk, Freshdesk)

---

## Monitoring & Tools

### Email Management
- **Gmail Labels**: Organize by type (bug, feature, question)
- **Filters**: Auto-label common subjects
- **Canned Responses**: Gmail feature for templates

### Optional Tools (For Growth)
- **Help Scout** - Simple, email-based support
- **Intercom** - In-app chat + email
- **Zendesk** - Full help desk (probably overkill initially)

---

## Pre-Launch Checklist

- [ ] Create support email (support@habiton.app)
- [ ] Set up auto-reply
- [ ] Create response templates
- [ ] Create FAQ page (optional but recommended)
- [ ] Host FAQ on GitHub Pages or similar
- [ ] Test email delivery (send to yourself)
- [ ] Add support URL to App Store listing
- [ ] Add support email to Google Play listing
- [ ] Include support email in app (Profile → Support)
- [ ] Set calendar reminder to check email daily

---

## In-App Support Link

Make sure your app's Support screen links to your support resources:

**In ProfileScreen.tsx → SupportScreen.tsx**:
- Email: support@habiton.app
- Website: https://yourusername.github.io/habiton-support
- Or open email compose: `Linking.openURL('mailto:support@habiton.app')`

---

## Pro Tips

1. **Respond Quickly**: Even "I'm looking into this" is better than silence
2. **Be Friendly**: Users are reaching out for help, be patient
3. **Track Common Issues**: If multiple users report same bug, prioritize fix
4. **Learn from Support**: Common questions might indicate UX issues
5. **Say Thank You**: To bug reporters and feature requesters
6. **Update FAQ**: Add new Q&As based on support emails
7. **Consider Users' Time Zones**: If many users in specific region, adjust response times

---

## Quick Setup (15 Minutes)

1. **Create Gmail**: `habiton.support@gmail.com` (5 min)
2. **Set Auto-Reply**: Use template above (2 min)
3. **Create Templates**: Save 3-4 canned responses (5 min)
4. **Add to App Store**: Enter email in store listings (3 min)

Done! You're ready for support.

---

**Ready to launch? Users appreciate responsive support! 🎉**



