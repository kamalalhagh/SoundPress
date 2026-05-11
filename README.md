# SoundPress — Audio Compressor

<p align="center">
  <img src="https://img.shields.io/github/v/release/kamalalhagh/SoundPress?style=flat-square&color=6C63FF" alt="Release">
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-blue?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/python-3.12-brightgreen?style=flat-square" alt="Python">
  <img src="https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/author-Kevin%20Haji-6C63FF?style=flat-square" alt="Author">
</p>

A bilingual (English / Persian) desktop app that compresses any audio file to a lightweight MP3 using FFmpeg. Three presets range from voice-optimised mono to full-quality stereo — no command line, no setup.

**[Download latest release](https://github.com/kamalalhagh/SoundPress/releases/latest)** | **[README فارسی](README.fa.md)**

---

## Features

- Three compression presets — Maximum, Medium, and Low with clear descriptions
- English / Persian UI with correct RTL rendering
- Dark and light theme
- FFmpeg is bundled — works out of the box on every supported platform
- Compression stats showing output size and percentage saved after conversion
- Accepts MP3, M4A, WAV, FLAC, AAC, OGG, WMA, OPUS, AIFF and more

---

## Download

| Platform | File |
|----------|------|
| Windows Intel / AMD | `SoundPress-windows-x64.exe` |
| Windows ARM64 | `SoundPress-windows-arm64.exe` |
| macOS Universal (recommended) | `SoundPress-macOS-universal` |
| macOS Apple Silicon | `SoundPress-macOS-arm64` |
| macOS Intel | `SoundPress-macOS-intel` |

On macOS, run this once after downloading:

```bash
chmod +x SoundPress-macOS-*
xattr -d com.apple.quarantine SoundPress-macOS-*
```

---

## Compression Presets

| Level | Channels | Sample Rate | Bitrate | Best for |
|-------|----------|-------------|---------|----------|
| Maximum | Mono | 16 kHz | 16 kbps | Voice, podcasts |
| Medium | Mono | 22 kHz | 32 kbps | General audio |
| Low | Stereo | 44.1 kHz | 128 kbps | Music |

---

## Running from Source

```bash
git clone https://github.com/kamalalhagh/SoundPress.git
cd SoundPress
pip install -r requirements.txt
python main.py
```

Python 3.9 or later required. FFmpeg must be in PATH, or the app will offer to install it on first launch.

---

## Author

**Kevin Haji** — [kevinhaji.com](https://kevinhaji.com) · [github.com/kamalalhagh](https://github.com/kamalalhagh)

---

## License

MIT © [Kevin Haji](https://kevinhaji.com)
