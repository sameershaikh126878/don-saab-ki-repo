# 📦 PW All-in-One Leech Bot

A Telegram bot built using **Pyrogram** to download and upload lectures (videos, PDFs, ZIPs) from **PhysicsWallah**, **Classplus**, and other direct sources with token support.

---

## 🔧 Features
- ✅ Supports PW `.m3u8` / `.mpd` token-based video downloads
- ✅ Leech & upload PDFs, ZIPs, images, lectures
- ✅ Asks user for VID ID, Batch Name, Token, Quality etc.
- ✅ Auto uploads to your Telegram **channel** with stylish captions
- ✅ Progress bar & size stats during downloads

---

## 📁 Folder Structure
```
.
├── main.py               # Main Telegram bot logic
├── vars.py               # All environment vars and constants
├── utils.py              # File handling, cleaner, path helpers
├── utils_progress.py     # Stylish progress bar and ETA
├── downloads/            # Temp storage for downloaded files
└── README.md             # This file
```

---

## ⚙️ Requirements
- Python 3.10+
- `yt-dlp`, `pyrogram`, `tgcrypto`, `requests`

### 🔌 Install
```bash
pip install -r requirements.txt
```

**Or manually:**
```bash
pip install pyrogram tgcrypto requests yt-dlp
```

---

## 🌐 Environment Variables
Set them in your shell or `.env`:
```
API_ID=your_api_id
API_HASH=your_api_hash
BOT_TOKEN=your_bot_token
CHANNEL_ID=-100XXXXXXXXXX
```

---

## 🚀 Run
```bash
python3 main.py
```

---

## 🧠 Usage in Telegram
Type:
```
/leech
```
Then reply step-by-step with:
1. VID ID
2. Batch name
3. Downloaded By
4. Quality
5. Token (for PW)
6. Video/PDF link or file

Bot will download & auto upload to your channel with this caption:

```
◆➤ VID_ID: 003
📜 Title: PW_Lecture_003.mp4
🗂️ Batch: Yakeen NEET 2025
📺 Quality: 720p
📥 Downloaded by: @yourname
✯ ━━━━━━ ✿ SAMEER BHYYA ✿ ━━━━━━ ✯
```

---

## 🔒 Made with ❤️ by @CHAT_WITH_SAMEER_BOT
Feel free to fork & modify!
