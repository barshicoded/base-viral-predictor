# 🎯 Viral Predictor

**Guess Base Social metrics. Win bragging rights.**

A mobile-first prediction game for Base social posts.

## 🎮 How It Works

1. **Paste a Base social post URL** (Base App or Warpcast)
2. **Predict 24-hour metrics**: Likes, Recasts, Comments, Tips
3. **Submit your prediction** (free to play)
4. **Check back in 24h** - closest guesses win!

## 📱 Mobile Installation

### Option 1: PWA (Install as App)
1. Open the site in mobile browser (Safari/Chrome)
2. Tap "Share" → "Add to Home Screen"
3. Works like a native app!

### Option 2: Native iOS/Android App
```bash
# Install dependencies
npm install

# Build iOS app
npm run build:ios

# Build Android app  
npm run build:android
```

## 🚀 Deploy

### Web (PWA)
```bash
vercel --prod
```

### Native Apps
Requires Xcode (iOS) or Android Studio (Android).

## 🛠️ Tech Stack

- **Frontend**: HTML + Tailwind CSS (mobile-first)
- **PWA**: Service Worker + Manifest
- **Native**: Capacitor (iOS/Android wrapper)
- **Storage**: localStorage (predictions)

## 🔮 Future Features

- [ ] Real Farcaster API integration
- [ ] Wallet connection
- [ ] On-chain predictions with small stakes
- [ ] Push notifications for results
- [ ] Friend leaderboards

---

Built by @fitiwins for the Base ecosystem.
