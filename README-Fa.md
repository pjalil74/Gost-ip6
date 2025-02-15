# اسکریپت Gost IP6
[English](README.md) | [فارسی](README-Fa.md)

اسکریپت Gost IP6 یک اسکریپت Bash است که برای ساده‌تر کردن راه‌اندازی تونل‌های Gost برای هر دو IPv4 و IPv6 طراحی شده است. این اسکریپت یک رابط کاربری آسان برای پیکربندی Gost با گزینه‌های مختلف فراهم می‌کند، که به کاربران این امکان را می‌دهد تا تونل‌های امنی برای نیازهای شبکه خود ایجاد کنند.

## ویژگی‌ها

- ایجاد تانل Gost برای هر دو آی پی  IPv4 و IPv6.
- پیکربندی‌های سفارشی‌سازی‌پذیر برای پورت بصورت تکی،بصورت مولتی پورت.
- انتخاب انعطاف‌پذیر پروتکل با گزینه‌های TCP و Grcp.
- گزینه حذف برای حذف آسان.

## نصب

![ScreenShot_2024-01-29_02-22-04](https://github.com/masoudgb/Gost-ip6/assets/87688187/54ca010b-cc39-4edb-be8a-6d42b2300d9f)





1. مطمئن شوید که دسترسی root را قبل از اجرای اسکریپت دارید.

   ```bash
   bash <(curl -Ls https://github.com/masoudgb/Gost-ip6/raw/main/Gost.sh)
از بین گزینه‌های موجود، از جمله ایجاد تونل، پیکربندی پورت و انتخاب پروتکل، انتخاب کنید.

دستورهای مورد نیاز برای ورود IP مقصد، پورت‌ها و ترجیحات پروتکل را دنبال کنید.

اسکریپت بر اساس انتخاب‌های شما Gost را نصب و پیکربندی می‌کند.

## آموزش پروژه

[![آموزش یوتیوب](https://img.youtube.com/vi/AHzhI7TUJSI/0.jpg)](https://youtu.be/AHzhI7TUJSI)

حمایت از سازنده محترم ودیو: [کانال تلگرام](https://t.me/+2S96GjBZJ1cxYzVk)

## حذف نصب

برای حذف Gost، گزینه حذف را انتخاب کنید و اسکریپت Gost را همراه با سرویس systemd آن حذف خواهد کرد.

اعتبارات
ساخته شده توسط MasoudGB با تشکر ویژه از Mr.HamidRouter.

نسخه
اسکریپت Gost IP6 v0.6
