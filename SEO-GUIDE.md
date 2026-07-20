# 🔍 دليل SEO لموقع رعاية بيتي

## Google Search Console

### 1. التسجيل
- اذهب إلى: https://search.google.com/search-console
- سجّل الدخول بحساب Google
- أضف موقعك: `https://rayabetty.com`

### 2. التحقق من الملكية
اختر طريقة "HTML tag" وانسخ الكود إلى ملف `index.html`:
```html
<meta name="google-site-verification" content="YOUR_CODE" />
```

### 3. إرسال Sitemap
- اذهب إلى Sitemaps
- أدخل: `sitemap.xml`
- اضغط Submit

### 4. فهرسة الصفحات
- اذهب إلى URL Inspection
- أدخل كل URL واضغط "Request Indexing"

## Google Analytics 4

### 1. إنشاء حساب
- اذهب إلى: https://analytics.google.com
- أنشئ property جديد
- احصل على Measurement ID (مثال: G-XXXXXXXXXX)

### 2. التفعيل
استبدل `GA_MEASUREMENT_ID` في `index.html` بـ ID الخاص بك:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'G-XXXXXXXXXX');
</script>
```

## Bing Webmaster Tools

### 1. التسجيل
- اذهب إلى: https://www.bing.com/webmasters
- أضف موقعك وتحقق من الملكية
- أرسل sitemap.xml

## نصائح SEO إضافية

### الكلمات المفتاحية الرئيسية:
- تمريض منزلي
- ممرضة منزلية
- رعاية كبار السن
- رعاية منزلية
- تمريض منزلي مصر
- ممرضة منزلية القاهرة
- رعاية صحية منزلية
- علاج طبيعي منزلي
- رعاية المواليد
- عناية مركزة بالمنزل

### التحسينات المستقبلية:
1. إضافة صور حقيقية مع alt text
2. إنشاء محتوى جديد أسبوعياً
3. بناء backlinks من مواقع طبية مصرية
4. إنشاء صفحة Google Business Profile
5. التسجيل في دليل الأعمال المصري
