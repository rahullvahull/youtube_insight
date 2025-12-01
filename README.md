# 🎬 YouTube Wrapped

> Your YouTube history, decoded. A privacy-first web application that turns your raw Google Takeout data into a cinematic "Spotify Wrapped" style experience.

Discover your **"Vibe Shifts,"** identify your **"Ghost Subscriptions,"** and analyze your learning habits—all without your data ever leaving your device.

---

## ⚡ Features

YouTube Wrapped organizes your data into intuitive tabs for deep exploration:

### 📈 Overview Dashboard

**Top Stats Cards**
- 📊 Total Videos Watched
- 👥 Unique Creators  
- ⏱️ Estimated Watch Time (hours + minutes)

**365-Day History Heatmap**
- GitHub-style contribution graph showing daily viewing intensity
- Color-coded patterns reveal your watching habits over the year

**Activity Charts**
- **Monthly Analysis**: Bar charts identifying peak viewing months (Jan-Dec)
- **Weekly Patterns**: Your most active days of the week
- **Hourly Distribution**: 24-hour viewing rhythm (00:00 - 23:00)

---

### 👥 Creator & Video Deep Dives

**Creator Leaderboard**
- Ranked list of your top channels
- Video count and estimated watch time per creator
- Full sortable table of all creators you've watched

**Top 100 Videos**
- Your most re-watched videos with thumbnails
- Play counts and "usual play time" statistics
- Estimated total time spent on each video

---

## 🔒 Privacy First (Zero Data Collection)

We take privacy seriously. Here's our guarantee:

| Feature | Status |
|---------|--------|
| **No Servers** | ✅ There is no backend |
| **No Uploads** | ✅ Files processed 100% locally in your browser |
| **No API Keys** | ✅ No login or Google account access required |
| **Open Source** | ✅ Transparent code in a single HTML file |

**Your data never leaves your device. Period.**

---

## 🚀 How to Use

### Step 1: Get Your Data (Google Takeout)

You need to download your data from Google. It's free and takes a few minutes to prepare.

1. Go to **[Google Takeout](https://takeout.google.com/)**
2. Click **"Deselect all"**
3. Scroll down to **"YouTube and YouTube Music"** and check the box
4. ⚠️ **CRITICAL STEP**: Click the button that says **"Multiple formats"**
   - Change **History** from `HTML` to `JSON`
   - Click **OK**
5. Click **"Next Step"** → **"Create Export"**
6. Wait for the email from Google (usually 5-10 minutes)
7. Download the ZIP file

---

### Step 2: Analyze Your Data

You have two ways to use this tool:

#### Option A: Use the Live Website (Easiest)

1. Visit **[rahullvahull.github.io/youtube_insight](https://rahullvahull.github.io/youtube_insight)**
2. Drag and drop your downloaded `takeout-xxxx.zip` file onto the page
3. Watch your dashboard generate instantly! 🎉

#### Option B: Run Locally

1. Download this repository
   - Click **"Code"** → **"Download ZIP"** or clone it
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox)
3. Drag and drop your zip file onto the page

---

## 🛠️ Tech Stack

Built with modern web technologies for maximum performance:

- **HTML5** - Single-file application architecture
- **Tailwind CSS** - Modern, responsive dark theme styling
- **Chart.js** - Beautiful, interactive data visualizations
- **JSZip** - Client-side ZIP file processing
- **Vanilla JavaScript** - No frameworks, pure performance

---

## 📊 What We Analyze

### Metrics Displayed:
- ✅ Total videos watched & unique creators
- ✅ Estimated watch time (hours + minutes)
- ✅ 365-day viewing heatmap
- ✅ Monthly, weekly, and hourly activity patterns
- ✅ Top creators with watch time breakdown
- ✅ Top 100 most-watched videos with thumbnails
- ✅ Peak viewing times for each video

### What We DON'T Have Access To:
- ❌ Actual video durations (not in Google Takeout)
- ❌ Video categories or genres
- ❌ Watch completion percentages
- ❌ Likes, comments, or engagement data

---

## 📄 License

This project is open source and available under the **MIT License**.

Feel free to use, modify, and share!

---

## ⭐ Acknowledgments

Inspired by **Spotify Wrapped's** engaging year-in-review experience.

---

<div align="center">

**Made with ❤️ for YouTube data nerds**

[View Demo](https://rahullvahull.github.io/youtube_insight) • [Report Bug](https://github.com/rahullvahull/youtube_insight/issues) • [Request Feature](https://github.com/rahullvahull/youtube_insight/issues)

</div>