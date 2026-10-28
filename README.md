# Google Maps Lead Collector

**A bilingual Python desktop application for collecting and organizing business information.**

A desktop tool built with Python, Tkinter, Playwright, and SQLite. It provides Persian and English interfaces for searching businesses on Google Maps, collecting available details, and exporting results.

## Features

- Search businesses by keyword and location
- Collect business names, phone numbers, addresses, and websites
- Optional email extraction from business websites
- Collect categories, ratings, reviews, and opening hours when available
- Retrieve Google Maps links and geographic coordinates when available
- Store results in a local SQLite database
- Avoid duplicate records
- Export data to CSV, JSON, Excel, and TXT
- Select which fields to collect
- Stop an active search
- Clear the database to start a fresh collection
- Persian and English interfaces

## Requirements

- Python 3.10 or newer
- Playwright
- openpyxl

## Installation

Install the required packages:

```bash
python -m pip install playwright openpyxl
python -m playwright install chromium
```

## Run the Application

### English Version

```bash
python maps_lead_collector_english.py
```

### Persian Version

```bash
python maps_lead_collector_persian.py
```

## Data Storage

Collected data is stored locally in `maps_leads.sqlite3`.

Do not upload your database if it contains private or sensitive information.

## Responsible Use

Use this project responsibly. Review applicable laws, privacy requirements, and Google Maps' terms before collecting, storing, or redistributing data. Users are responsible for their use of this software.

---

# گردآورنده اطلاعات کسب‌وکارهای Google Maps

**یک برنامه دسکتاپ پایتون با رابط کاربری فارسی و انگلیسی برای جمع‌آوری و سازمان‌دهی اطلاعات کسب‌وکارها.**

این ابزار با استفاده از Python، Tkinter، Playwright و SQLite ساخته شده است و امکان جست‌وجوی کسب‌وکارها در Google Maps، استخراج اطلاعات قابل‌دسترسی و خروجی گرفتن از نتایج را فراهم می‌کند.

## امکانات

- جست‌وجوی کسب‌وکار بر اساس عبارت و موقعیت مکانی
- جمع‌آوری نام، شماره تلفن، آدرس و وب‌سایت
- استخراج اختیاری ایمیل از وب‌سایت کسب‌وکارها
- دریافت دسته‌بندی، امتیاز، تعداد نظرات و ساعات کاری در صورت دسترس بودن
- دریافت لینک Google Maps و مختصات جغرافیایی در صورت دسترس بودن
- ذخیره اطلاعات در دیتابیس محلی SQLite
- جلوگیری از ثبت رکوردهای تکراری
- خروجی CSV، JSON، Excel و TXT
- انتخاب فیلدهای موردنیاز برای جمع‌آوری
- توقف عملیات جست‌وجو
- پاک‌کردن دیتابیس برای شروع یک جمع‌آوری جدید
- رابط کاربری فارسی و انگلیسی

## پیش‌نیازها

- Python نسخه 3.10 یا بالاتر
- کتابخانه Playwright
- کتابخانه openpyxl

## نصب

دستورهای زیر را در CMD یا ترمینال اجرا کنید:

```bash
python -m pip install playwright openpyxl
python -m playwright install chromium
```

## اجرای برنامه

### نسخه انگلیسی

```bash
python maps_lead_collector_english.py
```

### نسخه فارسی

```bash
python maps_lead_collector_persian.py
```

## ذخیره‌سازی اطلاعات

اطلاعات جمع‌آوری‌شده به‌صورت محلی در فایل `maps_leads.sqlite3` ذخیره می‌شوند.

اگر دیتابیس حاوی اطلاعات خصوصی یا حساس است، آن را در GitHub منتشر نکنید.

## استفاده مسئولانه
 
از این پروژه مسئولانه استفاده کنید. پیش از جمع‌آوری، ذخیره یا بازنشر اطلاعات، قوانین مربوطه، الزامات حریم خصوصی و شرایط استفاده Google Maps را بررسی کنید. مسئولیت نحوه استفاده از این نرم‌افزار بر عهده کاربر است.
