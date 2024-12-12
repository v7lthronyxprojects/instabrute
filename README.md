# InstaBrute - Advanced Instagram Security Testing Tool

**[English]** | [فارسی](#فارسی)

## Description
InstaBrute is a sophisticated cybersecurity educational tool that demonstrates the importance of strong password security. Built with advanced features including AI-powered analysis, proxy management, and Tor integration.

## Core Features
- **Advanced Rate Limiting**: Smart request throttling to avoid detection
- **Proxy Integration**: Support for HTTP/HTTPS/SOCKS proxies
- **Tor Network Support**: Built-in Tor functionality for enhanced anonymity
- **Multi-threaded Operations**: Parallel password testing
- **Progress Tracking**: Real-time attack progress monitoring
- **Smart Error Handling**: Automatic retry mechanisms

## Command Line Options
```bash
python instabrute.py [OPTIONS]

Options:
  --username TEXT          Target username
  --password-list FILE    Password list file path
  --timeout INT           Operation timeout (seconds)
  --use-tor              Enable Tor network routing
  --proxy-list FILE      Custom proxy list file
  --threads INT          Number of concurrent threads
  --min-delay FLOAT      Minimum delay between requests
  --max-delay FLOAT      Maximum delay between requests
```

## Installation
```bash
# Clone repository
git clone https://github.com/v7lthronyxprojects/instabrute.git
cd instabrute

# Install dependencies
pip install -r requirements.txt

# Install Tor (Optional)
sudo apt install tor         # Linux
brew install tor            # macOS
```

## Usage Examples
```bash
# Basic usage with password list
python instabrute.py --username target_user --password-list wordlist.txt

# Using Tor for anonymity
python instabrute.py --username target_user --password-list wordlist.txt --use-tor

# Multi-threaded with custom proxy list
python instabrute.py --username target_user --password-list wordlist.txt --proxy-list proxies.txt --threads 4

# Advanced configuration
python instabrute.py \
  --username target_user \
  --password-list wordlist.txt \
  --use-tor \
  --threads 8 \
  --timeout 7200 \
  --min-delay 2 \
  --max-delay 5
```

---

# فارسی

## توضیحات
InstaBrute یک ابزار آموزشی پیشرفته امنیت سایبری است که اهمیت امنیت رمز عبور قوی را نشان می‌دهد. این ابزار با ویژگی‌های پیشرفته‌ای از جمله تحلیل مبتنی بر هوش مصنوعی، مدیریت پروکسی و یکپارچه‌سازی Tor ساخته شده است.

## ویژگی‌های اصلی
- **محدودیت نرخ پیشرفته**: تنظیم هوشمند درخواست‌ها برای جلوگیری از شناسایی
- **یکپارچه‌سازی پروکسی**: پشتیبانی از پروکسی‌های HTTP/HTTPS/SOCKS
- **پشتیبانی از شبکه Tor**: قابلیت Tor داخلی برای افزایش ناشناس بودن
- **عملیات چند نخی**: تست رمز عبور به صورت موازی
- **پیگیری پیشرفت**: نظارت بر پیشرفت حمله در زمان واقعی
- **مدیریت خطای هوشمند**: مکانیزم‌های خودکار برای تلاش مجدد

## گزینه‌های خط فرمان
```bash
python instabrute.py [OPTIONS]

Options:
  --username TEXT          نام کاربری هدف
  --password-list FILE    مسیر فایل لیست رمز عبور
  --timeout INT           زمان انتظار عملیات (ثانیه)
  --use-tor              فعال‌سازی مسیریابی شبکه Tor
  --proxy-list FILE      فایل لیست پروکسی سفارشی
  --threads INT          تعداد نخ‌های همزمان
  --min-delay FLOAT      حداقل تأخیر بین درخواست‌ها
  --max-delay FLOAT      حداکثر تأخیر بین درخواست‌ها
```

## نصب
```bash
# کلون کردن مخزن
git clone https://github.com/v7lthronyxprojects/instabrute.git
cd instabrute

# نصب وابستگی‌ها
pip install -r requirements.txt

# نصب Tor (اختیاری)
sudo apt install tor         # لینوکس
brew install tor            # macOS
```

## مثال‌های استفاده
```bash
# استفاده پایه با لیست رمز عبور
python instabrute.py --username target_user --password-list wordlist.txt

# استفاده از Tor برای ناشناس بودن
python instabrute.py --username target_user --password-list wordlist.txt --use-tor

# چند نخی با لیست پروکسی سفارشی
python instabrute.py --username target_user --password-list wordlist.txt --proxy-list proxies.txt --threads 4

# پیکربندی پیشرفته
python instabrute.py \
  --username target_user \
  --password-list wordlist.txt \
  --use-tor \
  --threads 8 \
  --timeout 7200 \
  --min-delay 2 \
  --max-delay 5
```

---

## Disclaimer
**English:**
This tool is intended for **educational purposes only**. Any unauthorized use of this tool against accounts without explicit consent is illegal and may result in legal consequences. The developers of this tool are not responsible for any misuse. Always respect user privacy and act within legal and ethical boundaries.

**فارسی:**
این ابزار صرفاً برای **اهداف آموزشی** طراحی شده است. هرگونه استفاده غیرمجاز از این ابزار علیه حساب‌ها بدون اجازه صریح غیرقانونی بوده و ممکن است عواقب قانونی به همراه داشته باشد. توسعه‌دهندگان این ابزار هیچ مسئولیتی در قبال سوءاستفاده ندارند. همواره به حریم خصوصی کاربران احترام بگذارید و در چارچوب قانونی و اخلاقی عمل کنید.


