<div align="center">

<img src="https://raw.githubusercontent.com/AghaBanafshi-2/Reponew/refs/heads/main/file_0000000095f08210bd7aec2e59f00378.png" alt="Purple Panel Logo" width="150"/>

# 🟣 Purple Panel

**پنل مدیریتی ساخت کانفیگ پرسرعت V2ray**

با یک داشبورد ساده و زیبا، کانفیگ‌های V2ray خودت رو بساز و مدیریت کن!

[![GitHub](https://img.shields.io/badge/GitHub-TheAghaBanafshi-181717?style=for-the-badge&logo=github)](https://github.com/TheAghaBanafshi/Purple-Panel)
[![Railway](https://img.shields.io/badge/Deploy-Railway-0B0D0E?style=for-the-badge&logo=railway)](https://railway.app)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python)](https://python.org)

</div>

---

## ✨ معرفی

**Purple Panel** یک پنل مدیریتی سبک و کاربرپسند برای ساخت و مدیریت کانفیگ‌های **V2ray** است. با استفاده از این پروژه می‌توانید تنها با چند کلیک، پنل شخصی خود را روی [Railway](https://railway.app) راه‌اندازی کنید و از داشبورد مدیریتی آن لذت ببرید.

> 💡 نیازی به دانش برنامه‌نویسی ندارید — فقط مراحل زیر را قدم به قدم دنبال کنید!

---

## 🚀 راه‌اندازی سریع (Deploy در ۵ دقیقه)

### 📌 قدم اول — ثبت‌نام در GitHub

اگر هنوز حساب کاربری ندارید، در سایت [github.com](https://github.com) با ایمیل خود ثبت‌نام کنید.

### 📌 قدم دوم — ثبت‌نام در Railway

به سایت [railway.app](https://railway.app) بروید و با همان اکانت GitHub ثبت‌نام کنید.

### 📌 قدم سوم — Deploy پروژه

۱. در صفحه اصلی Railway روی گزینه **Deploy** کلیک کنید.
۲. گزینه **Github Repository** را انتخاب کنید.
۳. روی **Install Github App** بزنید.
۴. در پنجره باز شده، دسترسی **All Repository** را بدهید و روی **Install & Authorize** کلیک کنید.
۵. به صفحه اصلی Railway برگردید و دوباره مسیر **Deploy → Github Repository** را طی کنید.
۶. در کادر بالا، آدرس زیر را وارد کنید:

```
https://github.com/TheAghaBanafshi/Purple-Panel
```

۷. روی **Deploy Repo** کلیک کنید تا پنل نصب شود.

### 📌 قدم چهارم — تنظیم دامنه

۱. روی آیکون پروژه (شبیه عکس پایین) کلیک کنید.
۲. روی دکمه **Settings** بزنید.
۳. روی دکمه **Generate Domain** کلیک کنید.
۴. اگر شماره‌ای خواست، عدد **8080** را وارد کنید.

پس از این مرحله، لینکی به شما داده می‌شود، مثلاً:

```
https://purple-panel-production-a45r.up.railway.app/
```

> ⚠️ **توجه:** ابتدا باید پنل به حالت **Online** برود، سپس وارد شوید.

### 📌 قدم پنجم — ورود به پنل

در انتهای آدرس، عبارت `/login` را اضافه کنید:

```
https://purple-panel-production-a45r.up.railway.app/login
```

سپس **رمز پیش‌فرض** را وارد کنید.

🎉 **تبریک!** شما الان یک پنل شخصی ساخت کانفیگ دارید.

---

## 💾 ذخیره تنظیمات (Saves All Settings)

اگر می‌خواهید بعد از آپدیت‌های پنل، کانفیگ‌های شما **ذخیره بمانند** و کار کنند، مراحل زیر را انجام دهید:

۱. روی پروژه در Railway **کلیک راست** کنید.
۲. روی گزینه **Attach Volume** کلیک کنید.
۳. در کادر بالا عبارت `/data` را وارد کنید.
۴. کلید **Enter** را بزنید و صبر کنید تا فرآیند Deploy تمام شود.

✅ از این به بعد تنظیمات شما پایدار خواهند ماند!

---

## 📁 ساختار پروژه

| فایل | توضیحات |
|------|---------|
| `main.py` | فایل اصلی اجرای برنامه |
| `pages.py` | مدیریت صفحات و رابط کاربری |
| `relay_vless.py` | مدیریت کانفیگ‌های VLESS |
| `telegram_bot.py` | ربات تلگرام |
| `speed_limit.py` | مدیریت محدودیت سرعت |
| `xhttp_siz10.py` | پشتیبانی از پروتکل XHTTP |
| `requirements.txt` | وابستگی‌های پایتون |
| `screenshots.md` | تصاویر پروژه |

---

## 🖼️ تصاویر

برای مشاهده اسکرین‌شات‌های پروژه، فایل [`screenshots.md`](./screenshots.md) را بررسی کنید.

---

## 🧩 ویژگی‌ها

- ✅ رابط کاربری ساده و زیبا
- ✅ ساخت و مدیریت کانفیگ‌های V2ray
- ✅ پشتیبانی از VLESS
- ✅ ربات تلگرام
- ✅ مدیریت محدودیت سرعت
- ✅ نصب آسان روی Railway
- ✅ پایداری تنظیمات با Volume

---

## 🤝 مشارکت

اگر ایده، پیشنهاد یا باگی دارید، خوشحال می‌شویم در [بخش Issues](https://github.com/TheAghaBanafshi/Purple-Panel/issues) مطرح کنید.

---

<div align="center">

<img src="https://raw.githubusercontent.com/AghaBanafshi-2/Reponew/refs/heads/main/file_0000000095f08210bd7aec2e59f00378.png" alt="Purple Panel Logo" width="80"/>

**⭐ اگر این پروژه برایتان مفید بود، یک ستاره به آن بدهید!**

ساخته شده با 💜 توسط [TheAghaBanafshi](https://github.com/TheAghaBanafshi)

</div>
