# 🎤 YouTubeOke Ads Server

This repository contains the ad configuration for **YouTubeOke** - YouTube Karaoke with Scoring System.

## 📋 Files

| File | Description |
|------|-------------|
| `ads.json` | Ad configuration (banner + popup ads) |

## 🔧 How It Works

1. YouTubeOke app fetches `ads.json` from this repo
2. App displays banner ads in sidebar
3. App shows popup ads after scoring
4. Update `ads.json` here = All users get new ads automatically!

## 📱 Ad Types

### Banner Ads
- Location: Left sidebar (below Top 10)
- Refresh: Every 5 minutes
- Always visible

### Popup Ads
- Trigger: After score is shown
- Skip: After 3 seconds
- Non-intrusive (never during singing!)

## ⚙️ Settings

```json
{
  "banner_refresh_minutes": 5,
  "popup_interval_minutes": 60,
  "show_popup_after_score": true
}
```

## 📞 Contact

- **App:** YouTubeOke
- **Developer:** Avydel

---

© 2024 YouTubeOke. All rights reserved.
