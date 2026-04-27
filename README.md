# 🪙 GoldTrack Pro

<div align="center">

![GoldTrack Pro](https://img.shields.io/badge/GoldTrack-Pro-F59E0B?style=for-the-badge&labelColor=0f0f0f)
[![Made for Bangladesh](https://img.shields.io/badge/Made%20for-Bangladesh%20🇧🇩-006A4E?style=flat-square)](https://github.com)
[![No Install Required](https://img.shields.io/badge/No%20Install-Required-10B981?style=flat-square)](#)
[![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-3B82F6?style=flat-square)](#getting-started)
[![Free API](https://img.shields.io/badge/API-Free%20Tier-F59E0B?style=flat-square)](https://goldapi.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-94A3B8?style=flat-square)](LICENSE)

**A Real-Time Gold & Silver Price Tracker with AI-Powered Buy/Sell Signals — built for traders in Bangladesh.**

[🚀 Getting Started](#getting-started) · [🔑 Get Free API Key](https://goldapi.io) · [🧠 How AI Works](#-how-the-ai-prediction-works) · [🐛 Report a Bug](../../issues)

</div>

---

##  What is GoldTrack Pro?

GoldTrack Pro is a free, open-source web dashboard designed specifically for gold and silver traders in Bangladesh. International precious metal prices change every minute. Buying or selling at the right moment is the difference between profit and loss.

This software helps you decide:

- 🟢 **When to BUY** — when the market signals an upward movement
- 🔴 **When to SELL** — when the market signals a downward movement
- 🟡 **When to HOLD** — when signals are mixed or confidence is low

All prices are displayed in **BDT (Bangladeshi Taka)** per gram and per tola, making it directly usable for local trading decisions.....................

---

## ✨ Features

| Feature | Description |
|---|---|
| 🟢🔴🟡 **BUY / SELL / HOLD Signal** | The most prominent element — AI-generated trading signal at a glance |
| 💰 **Real-Time Price in BDT** | Live gold & silver prices in Bangladeshi Taka per gram and per tola |
| 💱 **Live USD → BDT Rate** | Automatically fetched and updated currency conversion rate |
| 🧠 **AI Prediction Engine** | Uses RSI + SMA + ROC to forecast whether the next price move will go UP or DOWN |
| 📊 **Price History Chart** | Interactive line chart for Gold and Silver price trends over time |
| ⏱️ **Auto Refresh Every 60s** | Prices update automatically with a visible countdown timer |
| 📱 **Mobile + Desktop Ready** | Fully responsive — works beautifully on any screen size |
| 🌙 **Dark Mode UI** | Eye-friendly dark theme with gold and silver accent colors |
| 📈 **Daily High / Low** | Today's highest and lowest prices shown in BDT per gram |
| 🟢 **Market Open/Close Status** | Real-time global gold market session status based on UTC hours |

---

## 🖥️ Preview

```
┌──────────────────────────────────────────────────────────┐
│  🪙 GoldTrack Pro                         🟢 LIVE  20:45 │
├──────────────────────────────────────────────────────────┤
│  🟢 Open  │  USD→BDT: ৳110.50  │  Gold High: ৳12,450/g  │
├─────────────────────┬────────────────────────────────────┤
│  🥇 GOLD            │  🥈 SILVER                         │
│  🟢  BUY            │  🟡  HOLD                          │
│  HIGH CONFIDENCE    │  LOW CONFIDENCE                    │
├─────────────────────┼────────────────────────────────────┤
│  ৳ 11,845 /gram     │  ৳ 138 /gram                       │
│  Per Tola: ৳1,38,100│  Per Tola: ৳ 1,610                 │
│  USD/oz:  $3,290.00 │  USD/oz:  $38.42                   │
├─────────────────────┴────────────────────────────────────┤
│  🧠 AI Prediction — Gold                                  │
│  📈 PRICE LIKELY TO GO UP                                 │
│  RSI: 42.3 · SMA: Bullish (SMA3 > SMA7) · ROC: +0.21%   │
└──────────────────────────────────────────────────────────┘
```

---

## 🚀 Getting Started

### Step 1 — Download the File

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/goldtrack-pro.git

# Or simply download GoldTrack-Pro.html directly from this repository
```

### Step 2 — Get Your Free API Key (5 minutes)

GoldTrack Pro uses **GoldAPI.io** to fetch real-time gold and silver prices. The free tier provides 100 requests per month at no cost.

1. Go to 👉 [**goldapi.io**](https://goldapi.io)
2. Click **"Sign Up"** and create a free account
3. After logging in, find your **API Key** on the dashboard
4. Copy it — it will look like: `goldapi-xxxxxxxxxxxxxxxxxx`

### Step 3 — Open the App

```
1. Open GoldTrack-Pro.html in any modern browser
   (Chrome, Firefox, Edge — all supported)

2. Paste your API Key into the input box shown on screen

3. Click the Start button

4. The dashboard will load with live data ✅
```

> 💡 **Tip:** Your API key is saved in the browser automatically. You will not need to enter it again on the same device.

### Step 4 — Access from Your Phone (Same Wi-Fi)

**Option A — Local Network:**
```bash
# Find your PC's local IP address:

# Windows — open Command Prompt and run:
ipconfig
# Look for "IPv4 Address" (e.g., 192.168.1.5)

# Mac / Linux — run:
ifconfig
# Look for "inet" address

# Then open this URL on your phone's browser:
http://192.168.1.5/path/to/GoldTrack-Pro.html
```

**Option B — Simple File Share (Easier):**
```
Send GoldTrack-Pro.html to yourself via WhatsApp or Gmail
→ Download on your phone
→ Open with Chrome
→ Done ✅
```

---

## 🧠 How the AI Prediction Works

GoldTrack Pro uses three proven technical analysis indicators to generate predictions:

### 1. RSI — Relative Strength Index

Measures whether an asset is overbought or oversold.

```
RSI < 30  →  Oversold    →  Price likely to bounce UP    (Bullish signal)
RSI > 70  →  Overbought  →  Price likely to pull DOWN    (Bearish signal)
30 to 70  →  Normal zone →  Direction depends on other indicators
```

### 2. SMA — Simple Moving Average

Compares short-term and long-term average prices to detect trend direction.

```
SMA(3) > SMA(7)  →  Short-term trend is rising   →  Bullish
SMA(3) < SMA(7)  →  Short-term trend is falling  →  Bearish
```

### 3. ROC — Rate of Change (Momentum)

Measures the speed and direction of recent price movement.

```
ROC > +0.3%  →  Strong upward momentum
ROC > 0      →  Positive momentum
ROC < 0      →  Negative momentum
ROC < -0.3%  →  Strong downward momentum
```

### Final Signal Logic

```
All three indicators are scored and combined:

BUY  →  Direction UP   + Confidence MEDIUM or HIGH
SELL →  Direction DOWN + Confidence MEDIUM or HIGH
HOLD →  Mixed signals   OR Confidence LOW
```

> **Important:** Prediction accuracy improves over time. The app needs at least 3 data points to begin predicting, and reaches full accuracy after 7 or more points — approximately 7 minutes of runtime.

---

## 💱 How BDT Conversion Works

```
Step 1:  Fetch price in USD per Troy Ounce from GoldAPI.io
         Example: Gold = $3,290.00 / troy oz

Step 2:  Convert to USD per gram
         $3,290.00 / 31.1035 = $105.77 / gram

Step 3:  Convert to BDT per gram using the live exchange rate
         $105.77 x 110.50 = 11,687 BDT / gram

Step 4:  Convert to BDT per tola  (1 tola = 11.6638 grams)
         11,687 x 11.6638 = 1,36,305 BDT / tola
```

The live **USD to BDT** rate is fetched automatically from `open.er-api.com` on every refresh. If the exchange rate API is temporarily unavailable, a fallback rate of **110 BDT = 1 USD** is used until the connection is restored.

---

## 📁 Project Structure

```
goldtrack-pro/
│
├── GoldTrack-Pro.html     ← The entire application in one single file
└── README.md              ← This documentation file
```

The entire app — HTML, CSS, and JavaScript — lives inside a single self-contained file. No build tools, no package manager, and no dependencies to install.

**Internal structure of GoldTrack-Pro.html:**

```
GoldTrack-Pro.html
│
├── <style>                 Dark theme CSS and responsive grid layout
│
├── <body>                  Dashboard HTML structure
│   ├── Header              Logo, live clock, LIVE indicator
│   ├── API Setup Screen    Shown only on first visit
│   ├── Market Status Bar   Open/Close status, BDT rate, daily High/Low chips
│   ├── Signal Cards        BUY / SELL / HOLD for Gold and Silver
│   ├── Price Cards         BDT per gram, BDT per tola, USD per oz
│   ├── Prediction Cards    AI direction, RSI bar, SMA signal, ROC value
│   └── Chart Cards         Line charts for Gold and Silver price history
│
└── <script>                All application logic
    ├── fetchMetal()            Fetch price data from GoldAPI.io
    ├── fetchAllPrices()        Orchestrate all API calls and BDT rate fetch
    ├── runPrediction()         RSI + SMA + ROC calculation engine
    ├── updatePriceUI()         Render BDT prices to the DOM
    ├── updateChart()           Build and update Chart.js line charts
    ├── updateSignalCard()      Render the BUY / SELL / HOLD badge
    ├── appendHistory()         Save price data points to localStorage
    └── startCountdown()        Manage the 60-second auto-refresh timer
```

---

## 🔧 Technologies Used

| Technology | Purpose |
|---|---|
| **Vanilla HTML / CSS / JS** | Zero framework — runs directly in any browser without installation |
| **Chart.js v4** | Interactive and responsive price history line charts |
| **GoldAPI.io** | Real-time gold and silver price data source |
| **Open Exchange Rates API** | Live USD to BDT currency conversion rate |
| **localStorage** | Client-side price history storage — no backend or server needed |
| **Google Fonts** | Syne (display font) and DM Mono (number font) |

---

## ⚙️ Configuration

The following constants can be adjusted at the top of the `<script>` block inside `GoldTrack-Pro.html`:

| Constant | Default | Description |
|---|---|---|
| `REFRESH_SECS` | `60` | Auto-refresh interval in seconds |
| `MAX_HISTORY` | `20` | Maximum number of price history points stored |
| `usdToBdt` | `110` | Fallback BDT rate when exchange rate API is unavailable |
| `TOLA` | `11.6638` | Number of grams per tola |
| `TROY_OZ_TO_GRAM` | `31.1035` | Number of grams per troy ounce |

---

## ❓ Troubleshooting

<details>
<summary><b>Market data unavailable — retrying...</b></summary>

**Cause:** The API key is incorrect, or the free tier monthly limit of 100 requests has been reached.

**Fix:**
1. Visit [goldapi.io](https://goldapi.io) and log in to verify your API key is correct
2. If the monthly limit is exhausted, sign up with a different email for a new free account
3. Click the **Change Key** button in the app and enter the new key
</details>

<details>
<summary><b>Prediction shows "Not enough data"</b></summary>

**Cause:** The prediction engine requires at least 3 data points to run. One point is collected every 60 seconds.

**Fix:** Keep the app open. Predictions begin after approximately 3 minutes and reach full accuracy after 7 minutes.
</details>

<details>
<summary><b>Charts are not displaying</b></summary>

**Cause:** Fewer than 2 data points have been collected yet.

**Fix:** Wait 2 minutes with the app open. Charts appear automatically once enough data is available.
</details>

<details>
<summary><b>Cannot open the app on my phone</b></summary>

**Fix:** Send the `GoldTrack-Pro.html` file to yourself via WhatsApp or Gmail. Download it on your phone and open it with the Chrome browser.
</details>

<details>
<summary><b>The BDT rate looks incorrect</b></summary>

**Cause:** The exchange rate API is temporarily unreachable, so the fallback rate of 110 BDT per USD is being used.

**Fix:** Check your internet connection and click the Refresh button. The correct live rate will load automatically.
</details>

<details>
<summary><b>The app asks for the API key again after I close the browser</b></summary>

**Cause:** Some browser privacy settings clear localStorage data on exit.

**Fix:** Disable "Clear cookies and site data when you close all windows" in your browser settings. Avoid using Incognito or Private mode, as it does not retain localStorage data.
</details>

---

## 🗺️ Roadmap

- [ ] PWA support — install directly to phone home screen without a browser
- [ ] Price alerts — receive a notification when gold or silver hits a target price
- [ ] Extended history — 7-day and 30-day trend views
- [ ] Bangladesh Bank official BDT rate integration
- [ ] Export price history to Excel or CSV
- [ ] Language toggle between English and Bangla

---

## 🤝 Contributing

Contributions are welcome. If you have a feature idea, found a bug, or want to improve the prediction engine:

1. Fork this repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Commit your changes: `git commit -m "Add: description of your change"`
5. Push the branch: `git push origin feature/your-feature-name`
6. Open a Pull Request

---

## ⚠️ Disclaimer

The AI-generated predictions in GoldTrack Pro are for **informational and reference purposes only**. This software does **not** constitute certified financial advice. Precious metal markets can be influenced by geopolitical events, inflation, currency fluctuations, and other unpredictable factors that no algorithm can fully account for.

**Always apply your own judgment and consult a qualified financial advisor before making any trading decisions.**

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

## 🙏 Credits

| Resource | Purpose |
|---|---|
| [GoldAPI.io](https://goldapi.io) | Real-time gold and silver price data |
| [Open Exchange Rates](https://open.er-api.com) | Live USD to BDT conversion rate |
| [Chart.js](https://chartjs.org) | Price history charts |
| [Google Fonts](https://fonts.google.com) | Syne and DM Mono typefaces |

---

<div align="center">

**If GoldTrack Pro helped your business, please give it a star ⭐**

Made with ❤️ for Bangladesh's gold and silver traders 🇧🇩

</div>
