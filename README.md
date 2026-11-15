# وصلة — Wasla · Nebula Edition

واجهة تطبيق **وصلة** الاجتماعية (نموذج تفاعلي كامل) في ملف واحد: `index.html`.
تصميم داكن/فاتح RTL، عربي + English + Français، PWA قابل للتثبيت على الجوال.

## الروابط الحيّة

| المنصة | الرابط |
| --- | --- |
| Vercel (الإصدار الكامل السابق) | https://wasla-vercel.vercel.app |
| GitHub Pages (هذا المستودع) | https://moohameed111111111111-eng.github.io/-/ |

## الملفات

| الملف | الوصف |
| --- | --- |
| `index.html` | التطبيق كاملًا (HTML + CSS + JS مضمّنة، بدون أي اعتماد خارجي) |
| `manifest.webmanifest` | بيانات تطبيق الويب التقدمي (PWA) |
| `favicon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | الأيقونات |
| `vercel.json` | إعدادات النشر على Vercel |
| `.nojekyll` | تعطيل معالجة Jekyll على GitHub Pages |

## التشغيل محليًا

```bash
python3 -m http.server 8080
# ثم افتح http://localhost:8080
```

## النشر

- **GitHub Pages:** تلقائيًا من هذا الفرع عند كل `push` (Source: *Deploy from a branch*).
- **Vercel:** مشروع `wasla-vercel` موجود؛ ولنشر نسخة من هذا الريبو: `vercel --prod` أو اربط المستودع من لوحة Vercel.
- **أي منصة ثابتة أخرى** (Netlify / Cloudflare Pages / Surge): ارفع جذر المستودع كما هو — لا توجد خطوة بناء.

## ملاحظات

- الدخول وتسجيل الحساب في الواجهة **نموذجان تفاعليان فقط**؛ الربط الحقيقي بالخادم (Supabase/Google) لم يُفعّل بعد.
- الملف `index.html` نسخة من مصدر Wasla (v2) مع إزالة سكربت Cloudflare المُحقون وإضافة وسوم PWA/SEO.
