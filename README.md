# Floating-Dashboard-Download
# The ultimate desktop productivity overlay.
<div align="center">
  
# 🚀 Floating Dashboard 
**The Ultimate AI-Powered Desktop Productivity Overlay**

[![Download Latest Release](https://img.shields.io/badge/Download-v1.0.0-success?style=for-the-badge&logo=windows)](https://github.com/henrymendis/Floating-Dashboard-App/releases)
[![License: Trial](https://img.shields.io/badge/License-30_Day_Trial-orange?style=for-the-badge)](https://github.com/henrymendis/Floating-Dashboard-App/releases)

*Never miss a meeting, lose a thought, or break your workflow ever again.*

</div>

---

## ✨ What is it?
**Floating Dashboard** is a beautifully designed, always-on-top desktop overlay that lives at the corner of your screen. It seamlessly blends into your workflow, automatically capturing your clipboard, scheduling your meetings, and keeping your productivity metrics right where you can see them—all without opening a single calendar app.

---

## 🔥 Groundbreaking Features

### 🧠 AI Smart-Clipboard Parsing
Forget manually typing out calendar events. Simply highlight any email, message, or text block and press **`Ctrl + Alt + A`**. The dashboard's built-in AI engine will automatically:
* Identify if it's an email, message, or raw text.
* Extract meeting links (Zoom, Google Meet, Teams, Webex).
* Pull out critical business keywords.
* Detect quantities and "Counts".
* Schedule the event instantly with zero manual data entry!

### ⏰ Intelligent Audio & Visual Alarms
* **Quarterly & Hourly Chimes**: Gentle, customizable ambient chimes keep you tethered to reality during deep-focus work.
* **Smart Active Hours**: Configure your chime schedule (e.g., `09:00 to 18:00`) so the app stays completely silent while you sleep.
* **Auto-Launch Meetings**: Alarms don't just beep; they automatically open your Zoom or Google Meet links in your browser precisely when the meeting starts.

### 💻 Live System Telemetry
Keep an eye on your machine's health without opening Task Manager. The dashboard natively streams real-time **CPU and RAM** usage directly to your screen.

### 🎨 Fully Customizable UI
* **Adjustable Opacity**: Make it completely solid or highly transparent so it never blocks your work.
* **Dynamic Marquee**: A beautifully animated scrolling marquee that constantly counts down to your next upcoming event.
* **Fluid Layout**: Expand the dashboard to view your saved items and search history, or collapse it into a tiny, unobtrusive widget.
* **Run on Startup**: Automatically launch the dashboard silently in the background every time you turn on your PC.

---

## ⚡ How to Install

1. Navigate to the **Releases** tab on the right side of this page.
2. Download the `floating_main.exe` file.
3. Move the `.exe` to your Desktop (or anywhere you prefer) and double-click to run!

---

## ⚙️ Power User Configuration

Once you run the dashboard for the first time, it will generate a few folders and files in the same directory as the `.exe`. You can use these to supercharge your dashboard:

### 📅 How to Sync your Apple/Google Calendars (iCal)
To have the dashboard automatically read your existing calendars:
1. Open the newly generated **`cal_urls.json`** file in Notepad.
2. Paste your secret `.ics` or `iCal` URLs into the list. For example:
   ```json
   [
     "https://calendar.google.com/calendar/ical/your_email/private-key/basic.ics",
     "https://p01-calendars.icloud.com/published/2/your_apple_key"
   ]
