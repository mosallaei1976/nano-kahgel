# نانو کاهگل قزوین — نسخه بهینه‌شده موبایل + بخش شبکه‌های اجتماعی

## 📦 محتویات این بسته

```
nano-kahgel-final.zip
├── index.html                          فایل اصلی HTML بهینه‌شده
├── images/                             پوشه تصاویر (10 فایل webp)
│   ├── hero-craftsman-trowel.webp
│   ├── transformation-before-after.webp
│   ├── renovation-heritage-sidebyside.webp
│   ├── exterior-ecolodge-details.webp
│   ├── interior-luxury-terracotta-living.webp
│   ├── interior-rustic-ecolodge-bedroom.webp
│   ├── courtyard-terracotta-patio.webp
│   ├── exterior-santafe-house-1.webp
│   ├── exterior-santafe-house-2.webp
│   └── palette-tools-swatches.webp
├── final_screenshots/                   اسکرین‌شات کامل صفحه سایت
│   ├── fullpage-mobile.png              کل صفحه در موبایل (390x844)
│   ├── fullpage-tablet.png              کل صفحه در تبلت (768x1024)
│   └── fullpage-desktop.png             کل صفحه در دسکتاپ (1440x900)
└── README.md                            این فایل
```

## ✨ بهبودهای نسخه بهینه‌شده

### 📱 بهینه‌سازی موبایل
1. **منوی همبرگری + Drawer** — دسترسی کامل به ناوبری روی موبایل
2. **جدول مقایسه به کارت تبدیل شد** — به جای اسکرول افقی مزاحم
3. **هدر فشرده و چسبان** — از 80px به 60px کاهش یافت
4. **دکمه‌های هیرو ستونی** — full-width و قابل لمس (حداقل 52px)
5. **کاهش padding و فاصله‌ها** — بخش‌ها از 100px به 50px
6. **touch targets استاندارد** — حداقل 44px (Apple HIG)
7. **گالری بهینه** — captionها همیشه نمایش داده میشن
8. **Accessibility** — aria-expanded, aria-hidden, prefers-reduced-motion

### 🌐 بخش شبکه‌های اجتماعی (جدید)
بخش اختصاصی با کارت‌های زیبا برای ۵ پلتفرم:

| پلتفرم | آیدی | رنگ برند |
|---|---|---|
| 📺 یوتیوب | @mosallaei.architect | قرمز #ff0000 |
| 🎬 آپارات | mohamad_mosallaei | صورتی #ed1450 |
| ✈️ تلگرام | @msli1976 | آبی #2aabee |
| 💼 لینکدین | mohamad-mosallaei | آبی #0a66c2 |
| 📷 اینستاگرام | @qazvin_kahgel_nano | صورتی #e1306c |

**سه نقطه دسترسی:**
- بخش اختصاصی social-section قبل از CTA
- آیکون‌های دایره‌ای پایین drawer موبایل
- آیکون‌های دایره‌ای در فوتر با hover effect

## 🚀 نحوه Deploy روی GitHub Pages

1. این ZIP رو extract کنید
2. به ریپوی GitHub برید: `mosallaei1976/nano-kahgel`
3. فایل `index.html` فعلی رو با نسخه جدید جایگزین کنید:
   - روی `Upload files` کلیک کنید
   - فایل `index.html` رو drag کنید
   - پیام commit بدید و `Commit changes` رو بزنید
4. پوشه `images/` از قبل در ریپو هست — نیازی به آپلود مجدد نیست
5. صبر کنید ۱-۲ دقیقه تا GitHub Pages rebuild بشه
6. سایت رو چک کنید: https://mosallaei1976.github.io/nano-kahgel/

## 📊 مشخصات فنی

- **حجم فایل HTML:** 121 KB
- **تعداد تصاویر:** 10 (همگی webp)
- **حجم کل تصاویر:** 2.6 MB
- **فونت:** Vazirmatn (Google Fonts)
- ** breakpointها:**
  - `1024px` — تبلت/لپ‌تاپ
  - `768px` — موبایل بزرگ
  - `380px` — موبایل کوچک
- **Browser Support:** تمام مرورگرهای مدرن (Chrome, Firefox, Safari, Edge)
- **No external dependencies** جز فونت Vazirmatn از Google Fonts

## 📸 اسکرین‌شات‌ها

سه اسکرین‌شات full-page در پوشه `final_screenshots/`:
- **fullpage-mobile.png** — نمایش کامل صفحه در موبایل
- **fullpage-tablet.png** — نمایش کامل صفحه در تبلت
- **fullpage-desktop.png** — نمایش کامل صفحه در دسکتاپ

## ❓ سوالات متداول

**سوال: آیا باید تصاویر رو هم دوباره آپلود کنم؟**
خیر. پوشه `images/` از قبل در ریپو هست و تصاویر بدون تغییر باقی مونده‌ان. فقط فایل `index.html` رو جایگزین کنید.

**سوال: اگر خواستم چیزی تغییر بدم چیکار کنم؟**
فایل `index.html` رو با ویرایشگر متن باز کنید. تمام CSS در تگ `<style>` داخل `<head>` هست. JavaScript در انتهای فایل قبل از `</body>`.

**سوال: منوی موبایل کار نمیکنه!**
چک کنید که JavaScript فعال باشه. مرورگر باید JavaScript رو اجازه اجرا کنه.

---

ساخته‌شده توسط Super Z (Z.ai)
