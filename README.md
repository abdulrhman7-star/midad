<div align="center">

# مِداد | Midad

### AI Markdown → DOCX · PDF · Google Docs

**حوّل نصوص الذكاء الاصطناعي إلى مستندات احترافية منسقة بدقة**

[![Firebase](https://img.shields.io/badge/Firebase-Hosting-FFCA28?logo=firebase)](https://midadd.web.app)
[![Supabase](https://img.shields.io/badge/Supabase-Auth%20%26%20DB-3ECF8E?logo=supabase)](https://supabase.com)
[![PayPal](https://img.shields.io/badge/PayPal-Payments-003087?logo=paypal)](https://paypal.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

[🌐 الموقع الحي](https://midadd.web.app) · [🐛 الإبلاغ عن مشكلة](../../issues) · [💡 طلب ميزة](../../issues)

</div>

---

## 📖 نظرة عامة

**مِداد | Midad** منصة عربية مجانية تحوّل نصوص **Markdown** المولّدة من أدوات الذكاء الاصطناعي (ChatGPT, Claude, Gemini) إلى مستندات احترافية بصيغ **Word (DOCX)**, **PDF**, و**Google Docs**.

### 🎯 لماذا مِداد؟

- ✅ **دعم كامل للعربية** و RTL
- ✅ **معادلات LaTeX** بصيغة OMML الأصلية (قابلة للتعديل في Word)
- ✅ **جداول وأكواد برمجية** مع تلوين syntax
- ✅ **مزامنة سحابية** عبر Supabase
- ✅ **دفع آمن** عبر PayPal
- ✅ **مجاني** بدون تسجيل إجباري

---

## 🚀 الميزات الرئيسية

| الميزة | الوصف |
|---|---|
| 🎨 **محرر Markdown** | محرر مباشر مع معاينة فورية |
| 📄 **تصدير DOCX** | ملفات Word احترافية مع دعم LaTeX |
| 📕 **تصدير PDF** | تخطيط A4 للطباعة |
| 📋 **نسخ لـ Google Docs** | HTML غني جاهز للصق |
| 🔢 **دعم LaTeX** | معادلات رياضية قابلة للتعديل |
| 💻 **تلوين الأكواد** | أكثر من 20 لغة برمجية |
| 🌍 **9 لغات** | عربي، إنجليزي، إسباني، فرنسي، ألماني، روسي، صيني، ياباني، تركي |
| ☁️ **حفظ سحابي** | مزامنة تلقائية بين الأجهزة |
| 💳 **دفع آمن** | عبر PayPal مع شحن فوري |

---

## 🛠️ التقنيات المستخدمة

### Frontend
- **HTML5** + **Vanilla JavaScript**
- **Tailwind CSS** (CDN)
- **Marked.js** — تحويل Markdown
- **KaTeX** — معادلات رياضية
- **highlight.js** — تلوين الأكواد
- **docx** — إنشاء ملفات Word
- **Temml** — LaTeX → MathML → OMML

### Backend & Services
- **Firebase Hosting** — استضافة ثابتة
- **Supabase** — مصادقة + قاعدة بيانات PostgreSQL
- **PayPal NCP** — بوابة الدفع
- **Firebase Analytics** — تحليلات

---

## 📁 بنية المشروع
midad-app/
├── .github/
│ └── workflows/
│ ├── deploy.yml # نشر تلقائي على Firebase
│ └── lighthouse.yml # فحص الأداء
├── public/
│ ├── index.html # التطبيق الكامل (SPA)
│ ├── manifest.json # PWA manifest
│ ├── robots.txt # إعدادات محركات البحث
│ ├── sitemap.xml # خريطة الموقع
│ ├── ads.txt # إعدادات AdSense
│ └── 404.html # صفحة 404
├── .firebaserc
├── firebase.json
├── .gitignore
├── README.md
└── LICENSE
