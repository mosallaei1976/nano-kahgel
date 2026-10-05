# نانو کاهگل — سایت معرفی کاهگل صنعتی

یک صفحه فرودی (Landing Page) تک‌فایلی، فارسی و راست‌چین برای خدمات کاهگل صنعتی نانو در قزوین.

- **تماس:** محمد مصلایی — [09122810702](tel:09122810702)
- **تکنولوژی:** HTML خالص + CSS داخلی (بدون فریم‌ورک)، فونت وزیرمتن از CDN گوگل (آفلاین با فونت جایگزین کار می‌کند)، بدون جاوااسکریپت.
- **موبایل‌فرست:** دکمه تماس شناور در موبایل — با یک لمس تماس گرفته می‌شود.

## ساختار فایل‌ها

```
nano-kahgel-site/
├── index.html
├── README.md
└── images/
    ├── logo-grid-1.webp
    ├── logo-grid-2.webp
    ├── logo-grid-3.webp
    └── reference-layout.webp  (مرجع، در صفحه استفاده نشده)
```

## انتشار روی GitHub Pages

1. در گیت‌هاب یک مخزن جدید بسازید (مثلاً `nano-kahgel-site`).
2. محتویات پوشه `nano-kahgel-site` را آپلود یا پوش کنید (فایل `index.html` باید در ریشه مخزن باشد):
   ```bash
   cd nano-kahgel-site
   git init
   git add .
   git commit -m "سایت نانو کاهگل"
   git branch -M main
   git remote add origin https://github.com/USERNAME/nano-kahgel-site.git
   git push -u origin main
   ```
3. در مخزن به **Settings → Pages** بروید.
4. در بخش **Source** گزینه **Deploy from a branch** و شاخه `main` / پوشه `/ (root)` را انتخاب کنید و **Save** بزنید.
5. بعد از یک تا دو دقیقه سایت در این آدرس در دسترس است:
   `https://USERNAME.github.io/nano-kahgel-site/`

## افزودن عکس‌های جدید

عکس را (ترجیحاً WebP) در پوشه `images/` بگذارید، سپس در `index.html` داخل بخش گالری خط کامنت‌شده را از کامنت خارج و نام فایل را جایگزین کنید.
