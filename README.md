<div align="center">
<img src="https://client.digitalvps.ir/templates/lagom2/assets/img/logo/logo_big.1066038415.png" width="300" />
</div>

<div align="center">

[![release](https://img.shields.io/badge/release-v1.2.2-%23006400)](#)
[![sponsor](https://img.shields.io/badge/sponsor-DigitalVPS.ir-%23FF0000)](https://digitalvps.ir)
[![license](https://img.shields.io/badge/license-MIT-%23006400)](#)

</div>

---

[English](README-en.md)

# 🚀 DigitalVPS ToolBox
### ابزار جامع بهینه‌سازی و مدیریت سرورهای Ubuntu / Debian

---

دستور اجرای اسکریپت:

```bash
https://raw.githubusercontent.com/Digitalvps-Ir/Digitalvps-Toolbox/main/script.sh
```

## 🌟 معرفی پروژه
**DigitalVPS ToolBox** یک اسکریپت قدرتمند و کاربرپسند برای بهینه‌سازی و تنظیم سرورهای لینوکسی است که کمک می‌کند با چند دستور ساده، بهترین عملکرد را از سرور خود بگیرید.

این پروژه شامل بخش‌های اصلی زیر می‌شود:

- ⚙️ تنظیمات شبکه پیشرفته (MTU و DNS)
- 📊 ابزارهای تست و بنچمارک
- 🗄️ مدیریت میرور و رپوهای APT

---

<details>
<summary>📌 نکات بسیار مهم</summary>

- اسکریپت برای **Ubuntu 18.04+** و **Debian 9+** و مشتقات آن طراحی شده است.
- اجرای بعضی بخش‌ها نیاز به دسترسی **sudo/root** دارد.
- قبل از تغییرات شبکه (مثل MTU/DNS/Mirror)، بهتر است یک دسترسی جایگزین (مثل کنسول دیتاسنتر) داشته باشید.
- قابلیت‌های APT شامل **Backup** و **Rollback** هستند تا اگر چیزی خراب شد، دنیا کاملاً تمام نشود.

</details>

---

<details>
<summary>✅ مشاهده توضیحات و آموزش استفاده</summary>

## ⚙️ بخش اول: تنظیمات شبکه پیشرفته
<details>
<summary>✅ مشاهده توضیحات و آموزش استفاده</summary>

### 🔧 مدیریت هوشمند MTU
- ✅ **تشخیص خودکار بهترین MTU** برای شبکه
- ✅ **تنظیم دستی MTU** (دائمی و پایدار بعد از ریبوت)
- ✅ **ماندگاری بعد از ریبوت**
- ✅ **رفع مشکلات اتصال** Mirror و Repo ها

### 🌐 مدیریت DNS با دو دسته‌بندی

**DNS های رسمی جهانی:**
```text
✓ Google DNS ( 8.8.8.8 / 8.8.4.4 )
✓ Cloudflare DNS ( 1.1.1.1 / 1.0.0.1 )
✓ Quad9 DNS ( 9.9.9.9 / 149.112.112.112 )
✓ Open DNS ( 208.67.222.222 / 208.67.220.220 )
```

**DNS های رفع تحریم (ویژه ایران):**
```text
✓ DIGITALVPS DNS ( VIP For Digitalvps.ir Users ) - دسترسی به سرویس‌های تحریم‌شده
✓ Shecan DNS - دسترسی به سرویس‌های تحریم‌شده
✓ 403 DNS - دسترسی به سرویس‌های تحریم‌شده
✓ DNS PRO - دسترسی به سرویس‌های تحریم‌شده
✓ Electro DNS - دسترسی به سرویس‌های تحریم‌شده
```

</details>

---

## 📊 بخش دوم: ابزارهای تست و بنچ‌مارک
<details>
<summary>✅ مشاهده توضیحات و آموزش استفاده</summary>

### ⚡ اسپید تست CLI
- 🚀 **Speedtest CLI** - تست سرعت اینترنت از خط فرمان
- 📈 **Bench.Sh** - بنچمارک کامل سرور ( CPU , RAM , Disk i/o , Network )
- 📊 **True Total Result** - گزارش جامع از عملکرد سرور

### 🎭 تست لایسنس سوشال مدیا V4 & V6
- ✅ تست دسترسی به **Instagram**
- ✅ تست دسترسی به **Spotify Music**
- ✅ تست دسترسی به **YouTube**
- ✅ تست دسترسی به **Netflix**
- ✅ بررسی محدودیت‌های منطقه‌ای

</details>

---

## 🗄️ بخش سوم: مدیریت میرور و رپو های APT
<details>
<summary>✅ مشاهده توضیحات و آموزش استفاده</summary>

### 🌍 میرورهای رسمی جهانی
```text
✓ Ubuntu Main Repository
✓ Ubuntu Security Updates
✓ De Ubuntu Security Updates
✓ Aeza Ubuntu Security Updates
✓ Debian Official Repository
✓ Debian Security Repository
```

### 🌍 میرور های سریع داخلی ایران
```text
✓ Ubuntu Digitalvps.ir Vip Mirror
✓ Ubuntu Arvancloud Mirror
✓ Ubuntu Iran Mirror
✓ Yazd.ac.ir Mirror
```

### ⭐ میرور اختصاصی Digitalvps.ir

**🎯 چرا میرور DigitalVPS را انتخاب کنیم ؟**
```text
🚀 سرعت دانلود و آپدیت تا چند برابر سریع‌تر
🔄 به‌روزرسانی مداوم و خودکار میرور و رپو
⚡ سرورهای قدرتمند با اتصال 10 گیگابیت
✅ پشتیبانی از تمام نسخه‌های Ubuntu
🌐 بهینه‌سازی شده برای کاربران ایرانی
```

**✨ نتایج واقعی**
```text
پیش از استفاده از میرور Digitalvps
apt update → 45 ثانیه

بعد از استفاده از میرور Digitalvps
apt update → 10 - 15 ثانیه
```

**✨ امکانات منحصر به‌فرد**
- ✅ **انتخاب خودکار سریع‌ترین میرور**
- ✅ **انتخاب میرور دستی**
- ✅ **تست سرعت قبل از تنظیم**
- ✅ **Rollback آسان**
- ✅ **Backup خودکار**

</details>

</details>

---

## 📸 تصاویر
<details>
<summary>مشاهده نمونه منو</summary>

```text
╔═══════════════════════════════════════╗
║     DigitalVPS ToolBox v1.2.1        ║
╚═══════════════════════════════════════╝

[1] ⚙️  تنظیم MTU (خودکار/دستی)
[2] 🌐 مدیریت DNS
[3] 🗄️  بهینه‌سازی میرور APT
[4] ⚡ اسپید تست و بنچمارک
[5] 🎭 تست لایسنس سوشال مدیا
[0] ❌ خروج

انتخاب شما:
```

</details>

---

## 🎯 موارد استفاده
<details>
<summary>✅ مشاهده سناریوها</summary>

### سناریو 1: بهبود سرعت به‌روزرسانی
(در این بخش می‌توانید خروجی واقعی خودتان را اضافه کنید.)

### سناریو 2: رفع مشکل دسترسی به Docker Hub
```bash
# تنظیم DNS رفع تحریم
$ sudo ./toolbox.sh
> انتخاب گزینه 2
> انتخاب DNS Shecan

✅ دسترسی کامل به Docker Hub بدون فیلتر
```

### سناریو 3: بهینه‌سازی شبکه
```bash
# تشخیص خودکار بهترین MTU
$ sudo ./toolbox.sh
> انتخاب گزینه 1
> تشخیص خودکار

✅ کاهش 46% در latency
✅ حذف packet loss
```

</details>

---

## ❓ سوالات متداول
<details>
<summary>مشاهده FAQ</summary>

**Q: آیا این ابزار رایگان است؟**  
A: بله، کاملاً رایگان و متن‌باز است.

**Q: روی چه سیستم‌عاملی کار می‌کند؟**  
A: Ubuntu 18.04+ و Debian 9+ و تمام مشتقات آن‌ها.

**Q: آیا نیاز به دانش فنی دارد؟**  
A: خیر، رابط کاربری بسیار ساده است.

**Q: آیا تنظیمات قابل بازگشت هستند؟**  
A: بله، همه تنظیمات قابل Rollback هستند.

**Q: میرور DigitalVPS چقدر سریع است؟**  
A: در تست‌های ما تا 10 برابر سریع‌تر از میرورهای عمومی بوده است.

</details>

---

## 🤝 مشارکت
مشارکت شما را با آغوش باز می‌پذیریم!

1. Fork کنید
2. تغییرات خود را اعمال کنید
3. Pull Request ارسال کنید

---

## 📞 پشتیبانی
<details>
<summary>راه های ارتباطی</summary>

- 🌐 **وب‌سایت:** https://digitalvps.ir  
- 💬 **تلگرام:** https://t.me/digitalvps_group  
- 📢 **کانال:** https://t.me/digital_vps  
- 📧 **ایمیل:** support@digitalvps.ir

</details>

---

## <img src="https://client.digitalvps.ir/templates/lagom2/assets/img/logo/logo_big.1066038415.png" width="34" /> 💎 خدمات DigitalVPS
### سرورهای بهینه‌شده با میرور اختصاصی

**چرا DigitalVPS؟**

```text
✅ میرور اختصاصی با سرعت 10Gbps
✅ DNS اختصاصی رفع تحریم
✅ پشتیبانی 24/7
✅ آپتایم 99.9%
✅ قیمت رقابتی
```

**پلن‌های ویژه:**

| پلن | CPU | RAM | SSD | قیمت |
|:---:|:---:|:---:|:---:|:---:|
| 🥉 پایه | 2 vCore | 4GB | 50GB | 150,000 تومان/ماه |
| 🥈 استاندارد | 4 vCore | 8GB | 100GB | 320,000 تومان/ماه |
| 🥇 حرفه‌ای | 8 vCore | 16GB | 200GB | 640,000 تومان/ماه |

**🎁 کد تخفیف ویژه:** `TOOLBOX2024` - 15% تخفیف

[🚀 سفارش الان](https://digitalvps.ir) | [💬 مشاوره رایگان](https://t.me/digitalvps_group)

---

## 📝 لایسنس پروژه
<details>
<summary>توضیحات</summary>
این پروژه تحت لایسنس MIT منتشر شده است.
</details>

---

<div align="center">

**ساخته شده با ❤️ توسط [DigitalVps.ir](https://digitalvps.ir)**

[![ستاره بدهید](https://img.shields.io/github/stars/Digitalvps-Ir/Digitalvps-ToolBox?style=social)](https://github.com/Digitalvps-Ir/ToolBox)

</div>
