# 🚀 Submit to Base App

## How to Get Your Mini App on Base

### Step 1: Deploy Your App

```bash
# Deploy to Vercel (or any host with HTTPS)
vercel --prod

# Note your URL: https://your-app.vercel.app
```

### Step 2: Update Configuration

Edit these files with your deployed URL:

**mini-app.json:**
```json
{
  "icon": "https://your-app.vercel.app/icon-512.png",
  "startUrl": "https://your-app.vercel.app/minikit.html",
  "screenshots": [
    "https://your-app.vercel.app/screenshot-1.png"
  ]
}
```

### Step 3: Submit to Base Team

**Option A: Email**
Send to: `minapps@base.org`

**Option B: Base Builders Form**
Apply at: https://base.org/build

### Step 4: Include This Info

```
App Name: Viral Predictor
Category: Social / Games
Description: Prediction game for Base Social metrics

URL: https://your-app.vercel.app/minikit.html
Icon: https://your-app.vercel.app/icon-512.png

What it does:
Users guess the viral metrics (likes, recasts, comments, tips) 
of Base Social posts within 24 hours. Closest predictions win 
and climb the leaderboard.

Why Base users will love it:
- Gamifies social engagement
- Creates friendly competition
- Rewards prediction skills
- Native Base social integration

Developer:
- Name: fitiwins
- Twitter: @fitiwins
- Address: 0x7261...C0357
```

### Step 5: Wait for Review

Base team reviews submissions and responds within 1-2 weeks.

---

## 📱 What Users Will See

Once approved, your app appears in:

**Base App → Discover → Social**

Users tap it → Opens instantly inside Base App → No download needed!

---

## 🔧 Technical Requirements Met

✅ Mobile-optimized  
✅ Uses MiniKit SDK  
✅ HTTPS only  
✅ Fast loading (< 3s)  
✅ No intrusive permissions  
✅ Base/Farcaster compatible  

---

## 💡 Tips for Approval

1. **Test thoroughly** on mobile before submitting
2. **Include screenshots** showing the main flow
3. **Explain the value** - why will Base users love this?
4. **Be responsive** - reply quickly to Base team's questions
5. **Start simple** - you can add features after launch

---

Ready to submit? Deploy first, then email minapps@base.org! 🚀
