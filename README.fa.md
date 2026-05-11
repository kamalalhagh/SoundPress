# صداپرس — فشرده‌ساز فایل صوتی

<p align="center">
  <img src="https://img.shields.io/github/v/release/kamalalhagh/SoundPress?style=flat-square&color=6C63FF" alt="نسخه">
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-blue?style=flat-square" alt="پلتفرم">
  <img src="https://img.shields.io/badge/python-3.12-brightgreen?style=flat-square" alt="پایتون">
  <img src="https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square" alt="مجوز">
</p>

یک اپلیکیشن دسکتاپ دوزبانه (فارسی / انگلیسی) برای فشرده‌سازی هر فایل صوتی به MP3 سبک با استفاده از FFmpeg. سه پیش‌تنظیم از صدای مونوی بهینه‌شده تا استریوی با کیفیت کامل — بدون نیاز به خط فرمان یا تنظیمات اولیه.

**[دانلود آخرین نسخه](https://github.com/kamalalhagh/SoundPress/releases/latest)** | **[English README](README.md)**

---

## ویژگی‌ها

- سه سطح فشرده‌سازی — حداکثر، متوسط و کم با توضیحات کامل
- رابط کاربری فارسی / انگلیسی با نمایش صحیح RTL
- تم تاریک و روشن
- FFmpeg در فایل دانلودی جاسازی شده — بدون نیاز به هیچ تنظیمی
- نمایش آمار فشرده‌سازی: حجم خروجی و درصد کاهش پس از تبدیل
- پشتیبانی از MP3، M4A، WAV، FLAC، AAC، OGG، WMA، OPUS، AIFF و بیشتر

---

## دانلود

| پلتفرم | فایل |
|--------|------|
| ویندوز Intel / AMD | `SoundPress-windows-x64.exe` |
| ویندوز ARM64 | `SoundPress-windows-arm64.exe` |
| macOS Universal (پیشنهادی) | `SoundPress-macOS-universal` |
| macOS Apple Silicon | `SoundPress-macOS-arm64` |
| macOS Intel | `SoundPress-macOS-intel` |

در macOS، یک بار پس از دانلود این دستور را اجرا کنید:

```bash
chmod +x SoundPress-macOS-*
xattr -d com.apple.quarantine SoundPress-macOS-*
```

---

## پیش‌تنظیم‌های فشرده‌سازی

| سطح | کانال | نرخ نمونه | بیت‌ریت | مناسب برای |
|-----|-------|-----------|---------|------------|
| حداکثر | مونو | ۱۶ کیلوهرتز | ۱۶ کیلوبیت | صدا، پادکست |
| متوسط | مونو | ۲۲ کیلوهرتز | ۳۲ کیلوبیت | صدای عمومی |
| کم | استریو | ۴۴.۱ کیلوهرتز | ۱۲۸ کیلوبیت | موسیقی |

---

## اجرا از سورس‌کد

```bash
git clone https://github.com/kamalalhagh/SoundPress.git
cd SoundPress
pip install -r requirements.txt
python main.py
```

نیاز به Python نسخه ۳.۹ یا بالاتر دارد. FFmpeg باید در PATH باشد، یا برنامه در اولین اجرا نصب آن را پیشنهاد می‌دهد.

---

## نویسنده

**Kevin Haji** — [kevinhaji.com](https://kevinhaji.com) · [github.com/kamalalhagh](https://github.com/kamalalhagh)

---

## مجوز

MIT © [Kevin Haji](https://kevinhaji.com)
