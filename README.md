# Medicare - Patient-Centered Healthcare

صفحة ويب مطابقة للتصميم (Pixel-Perfect) باستخدام HTML و CSS فقط.

## الملفات

- **index.html** — هيكل الصفحة الكامل (الهيدر، الهيرو، الكاروسيل، الأقسام)
- **styles.css** — كل التنسيقات والألوان والتصميم المتجاوب
- **README.md** — شرح التشغيل

## الخطوط

يتم استخدام **Google Fonts - Inter** (بدون تثبيت إضافي):

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
```

## كيفية تشغيل الموقع

### الطريقة 1: فتح الملف مباشرة
1. افتح مجلد المشروع `DOCTOR`
2. انقر نقراً مزدوجاً على ملف **index.html**
3. سيفتح الموقع في المتصفح الافتراضي

### الطريقة 2: باستخدام Live Server (في VS Code / Cursor)
1. ثبّت إضافة **Live Server**
2. انقر بزر الماوس الأيمن على `index.html` → **Open with Live Server**
3. ستفتح الصفحة مع تحديث تلقائي عند حفظ التعديلات

### الطريقة 3: من الطرفية (Terminal)
إذا كان لديك Python:
```bash
cd "c:\Users\Med Saief Allah\Desktop\DOCTOR"
python -m http.server 8080
```
ثم افتح في المتصفح: `http://localhost:8080`

## التصميم المتجاوب

- **كمبيوتر:** عرض كامل مع كل الأقسام
- **تابلت:** تكيّف الهيدر والكاروسيل والشبكات
- **موبايل:** قائمة تنقل تحت اللوجو، أزرار وحجم نصوص مناسبة

## ملاحظات

- الصور في الكاروسيل وبروفايل الأطباق حالياً **placeholders** (خلفيات ملونة). لاستبدالها بصور حقيقية، أضف عناصر `<img>` داخل `.carousel-image` و `.profile-avatar` و `.doctor-img-placeholder` وحدّث المسارات في الـ HTML.
- التبديل (Toggle) في الهيدر للشكل فقط؛ لا يغيّر الثيم لأن المشروع CSS فقط.
