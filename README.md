# 🇩🇪 تعلم الألمانية — Das Alphabet

تطبيق تفاعلي لتعلم الأبجدية الألمانية للمستوى A1

🔗 **الرابط المباشر:** `https://YOUR_USERNAME.github.io/german-alphabet`

---

## ✨ المميزات

- 🔤 **الحروف الأساسية** — 26 حرف + الحروف الخاصة (Ä Ö Ü ß) مع الصوت
- 🎵 **قواعد النطق** — 17 قاعدة تفصيلية مع أمثلة صوتية
- 📖 **مترجم ذكي** — قاموس محلي + MyMemory API للكلمات الجديدة
- ❓ **اختبار تفاعلي** — 3 أنواع أسئلة
- 💾 **حفظ التقدم** — داخل الملف نفسه
- 📝 **ملاحظات** — على كل حرف

---

## 🚀 رفع على GitHub Pages

### الطريقة السريعة:

1. **اصنع repository جديد** على GitHub اسمه `german-alphabet`
2. **ارفع الملفات:**
   ```bash
   git init
   git add .
   git commit -m "first commit"
   git branch -M main
   git remote add origin https://github.com/USERNAME/german-alphabet.git
   git push -u origin main
   ```
3. **فعّل GitHub Pages:**
   - Settings → Pages → Source: `main` branch → `/root`
   - Save ✅

4. **موقعك جاهز** على: `https://USERNAME.github.io/german-alphabet`

---

## 📁 الملفات

```
german-alphabet/
├── index.html   ← التطبيق الكامل
└── README.md    ← هذا الملف
```

---

## 🔧 التقنيات

- HTML / CSS / JavaScript (Vanilla)
- Web Speech API للصوت
- MyMemory Translation API
- localStorage + File System Access API للحفظ
