🎬 YouTube Wrapped

Your YouTube history, decoded. A privacy-first web application that turns your raw Google Takeout data into a cinematic "Spotify Wrapped" style experience. Discover your "Vibe Shifts," identify your "Ghost Subscriptions," and analyze your learning habits—all without your data ever leaving your device.

⚡ Features

YouTube Wrapped organizes your data into intuitive tabs for deep exploration:

📈 Overview Dashboard

Top Stats: Instant view of Total Videos, Unique Creators, and Estimated Watch Time.

History Heatmap: A 365-day graph showing your daily viewing intensity.

Activity Charts:

Monthly: Bar charts identifying your peak viewing months (Jan-Dec).

Daily: Analysis of your most active days of the week.

Hourly: 24-hour distribution charts revealing your daily rhythm (00:00 - 23:00).

👥 Creator & Video Deep Dives

Creator Leaderboard: A ranked list of your top channels by video count and estimated watch time.

Top 100 Videos: Your most re-watched videos complete with thumbnails and "usual play time" stats.

🔒 Privacy First (Zero Data Collection)

We take privacy seriously.

No Servers: There is no backend.

No Uploads: Your files are processed 100% locally within your web browser using JavaScript.

No API Keys: You do not need to log in or provide access to your Google account.

Open Source: The code is transparent and runs entirely in a single HTML file.

🚀 How to Use

Step 1: Get Your Data (Google Takeout)

You need to download your data from Google. It's free and takes a few minutes to prepare.

Go to Google Takeout.

Click "Deselect all".

Scroll down to "YouTube and YouTube Music" and check the box.

⚠️ CRITICAL STEP: Click the button that says "Multiple formats".

Change History from HTML to JSON.

Click OK.

Click "Next Step" -> "Create Export".

Wait for the email from Google (usually takes 5-10 minutes) and download the ZIP file.

Step 2: Analyze Your Data

You have two ways to use this tool:

Option A: Use the Live Website (Easiest)

Visit rahullvahull.github.io/youtube_insight.

Drag and drop your downloaded takeout-xxxx.zip file directly onto the page.

Watch your dashboard generate instantly!

Option B: Run Locally

Download this repository (click "Code" > "Download ZIP" or clone it).

Open index.html (or youtube_wrapped.html) in any modern browser (Chrome, Edge, Firefox).

Drag and drop your zip file onto the page running on your computer.

📄 License

This project is open source and available under the MIT License.