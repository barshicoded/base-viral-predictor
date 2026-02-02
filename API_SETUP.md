# 🔌 Real Data Setup

By default, Viral Predictor runs in **demo mode** with sample posts.

To fetch **real Base/Farcaster posts**, you need a Neynar API key (it's free).

---

## Step 1: Get Free API Key

1. Go to **https://neynar.com**
2. Sign up for free account
3. Go to Dashboard → API Keys
4. Copy your API key

---

## Step 2: Add to App

### Option A: In-App (Easiest)
1. Open Viral Predictor
2. Click **[Add API Key]** link
3. Paste your Neynar API key
4. Done! Status changes to `[LIVE_DATA]`

### Option B: LocalStorage (Dev)
```javascript
localStorage.setItem('neynar_api_key', 'your-api-key-here');
location.reload();
```

---

## How It Works

### URL Parsing
The app automatically detects cast hashes from:
- `https://warpcast.com/username/0xabc123...`
- `https://base.org/post/0xabc123...`
- Any URL containing a Farcaster cast hash

### API Call
```javascript
GET https://api.neynar.com/v2/farcaster/cast?identifier={hash}&type=hash
Headers: { api_key: YOUR_KEY }
```

### Data Fetched
- ✅ Author username/display name
- ✅ Post content (text)
- ✅ Like count
- ✅ Recast count  
- ✅ Reply count
- ✅ Timestamp
- ✅ Warpcast URL

---

## Demo Mode

Without API key, the app:
- Shows realistic demo posts
- Cycles through 3 example casts
- Fully functional for testing

---

## Privacy

- API key stored in **your browser only** (localStorage)
- Never sent to our servers
- You can remove it anytime

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| "Could not parse cast hash" | Check URL format - needs 0x... hash |
| "API error" | Verify API key is valid |
| "CORS error" | Neynar should work client-side - contact us |

---

Get your free key at **neynar.com** 🚀
