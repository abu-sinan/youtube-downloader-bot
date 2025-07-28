# 📺 YouTube Downloader Bot

A powerful, modern, and customizable YouTube downloader built with `yt-dlp`. Supports single videos, playlists, channels, audio-only mode, smart retries, logging, and multithreaded downloads — all with command-line control.

---

## 🚀 Clone This Repo

```bash
git clone https://github.com/abu-sinan/youtube-downloader-bot.git
cd youtube-downloader-bot
```

---

## ⚙️ Features

✅ Download videos, playlists, or entire channels
✅ MP3 audio-only mode (`--audio`)
✅ Multithreaded downloads (`--threads 4`)
✅ Skips already downloaded videos
✅ Smart retry with backoff
✅ Pre-download URL validation
✅ Auto-organizes downloads into folders
✅ Logs success and failures
✅ Auto-updates `yt-dlp` before running
✅ Supports input from file or manual entry

---

## 📦 Installation

```bash
pip install -r requirements.txt
```

> ⚠️ You also need `ffmpeg` installed and accessible via your system PATH.

---

## 🧪 Usage Examples

### ▶️ Download manually:

```bash
python bot.py
```

### 🎧 MP3 audio-only:

```bash
python bot.py --audio
```

### 📁 Download from a file:

```bash
python bot.py --file links.txt
```

### 🚀 With multithreading:

```bash
python bot.py --file links.txt --threads 4
```

### 💾 Custom output directory:

```bash
python bot.py --file links.txt --dir "my_downloads"
```

---

## 🔧 CLI Options

| Flag        | Description                          |
|-------------|--------------------------------------|
| `--file`    | Path to file with video URLs         |
| `--audio`   | Download audio-only (MP3)            |
| `--dir`     | Output folder                        |
| `--threads` | Number of concurrent downloads       |

---

## 📁 Project Structure

```
youtube-downloader-bot/
├── bot.py              # Main script to download YouTube videos
├── requirements.txt    # List of Python dependencies
├── README.md           # Project documentation
├── links.txt           # (Optional) File containing video/playlist URLs to download
├── downloaded.txt      # Log of successfully downloaded videos
├── failed.txt          # Log of failed download attempts
├── archive.txt         # Tracks downloaded videos to avoid duplicates
├── .gitignore          # Git ignore rules (e.g., __pycache__, .env)
└── downloads/          # Output folder where videos/audios are saved
```

---

## 🧑‍💻 Author

**Abu Sinan**

[![Upwork](https://img.shields.io/badge/Upwork-ffffff?style=flat&logo=upwork&logoColor=black)](https://www.upwork.com/freelancers/abusinan)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/abu-sinan)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.com/users/1155521589065027735)
[![X](https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white)](https://x.com/AbuSinan_)


---

## 📜 License

MIT License — use it freely and responsibly.