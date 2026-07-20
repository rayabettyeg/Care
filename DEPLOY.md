# 🚀 دليل النشر على GitHub Pages

## الخطوة 1: إنشاء Repository على GitHub

1. اذهب إلى [github.com/new](https://github.com/new)
2. اكتب اسم المستودع: `rayabetty`
3. اختر **Public**
4. اضغط **Create repository**

## الخطوة 2: رفع الملفات

```bash
# فك الضغط (إذا لم تفعل)
cd rayabetty

# تهيئة Git
git init
git add .
git commit -m "Initial commit - RayaBetty Home Nursing Egypt"

# ربط بالـ remote
git remote add origin https://github.com/YOUR_USERNAME/rayabetty.git
git branch -M main
git push -u origin main
```

## الخطوة 3: تفعيل GitHub Pages

1. في المستودع، اذهب إلى **Settings**
2. اذهب إلى **Pages** من القائمة اليسرى
3. في **Source**، اختر **Deploy from a branch**
4. اختر **main** و **/(root)**
5. اضغط **Save**
6. انتظر 2-5 دقائق، ثم زر: `https://YOUR_USERNAME.github.io/rayabetty`

## الخطوة 4: ربط دومين مخصص (اختياري)

1. في **Settings → Pages**
2. في **Custom domain**، اكتب: `rayabetty.com`
3. اضغط **Save**
4. في إعدادات DNS لدى مزود الدومين، أضف:
   - `A` records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - أو `CNAME`: `YOUR_USERNAME.github.io`

## الخطوة 5: التحقق من SSL

GitHub Pages يوفر SSL تلقائياً. تأكد من:
- ✅ **Enforce HTTPS** في Settings → Pages

## 🎯 بعد النشر - خطوات مهمة

### 1. Google Search Console
- اذهب إلى: https://search.google.com/search-console
- أضف موقعك وتحقق من الملكية
- أرسل `sitemap.xml`

### 2. Google Analytics
- أنشئ حساب في: https://analytics.google.com
- احصل على Measurement ID
- استبدل `GA_MEASUREMENT_ID` في `index.html`

### 3. Google Business Profile
- أنشئ ملف عمل: https://business.google.com
- أضف الصور والعنوان والهاتف

## 🔄 التحديثات المستقبلية

```bash
cd rayabetty
# عدل الملفات
git add .
git commit -m "Update: description of changes"
git push origin main
```

GitHub Pages سيتم تحديث الموقع تلقائياً خلال دقيقتين.

## 📞 دعم فني

إذا واجهت أي مشكلة، تواصل معنا:
- 📧 rayabettyeg@gmail.com
- 📱 01030313959
