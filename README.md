# OFUQ Academy — Landing Page

نسخة Landing Page جاهزة للنشر كـ Static Website، RTL، Responsive، ومتوافقة مع هوية أكاديمية أفق.

## الموجود في النسخة
- لوجو أفق الحقيقي من ملف الهوية.
- Hero ثلاثي الأبعاد بصور حقيقية وعناصر تعليمية عائمة.
- زر **تواصل معنا عبر واتساب** في الـHero والأقسام الرئيسية والـFooter.
- رسالة واتساب جاهزة: «مرحبًا، أريد معرفة تفاصيل الحجز في أكاديمية أفق.»
- زر WhatsApp عائم على الموبايل.
- تم حذف خانة صور وأسماء المدرسين بناءً على طلبك.
- قسم «مدرسون مصريون أونلاين لطلاب الخليج» مع الإمارات والسعودية وقطر والكويت وعُمان والبحرين.
- SEO وOpen Graph / Social Preview وFavicon.
- Responsive للموبايل والـTablet والـDesktop.
- Google Analytics 4 وMeta Pixel جاهزان، لكن غير مفعلين حتى تضعي الـIDs الحقيقية.
- `.nojekyll` جاهز لـGitHub Pages.
- إضافة Instagram وFacebook بروابط الصفحات الرسمية المرسلة.
- إضافة أيقونات تعليمية 3D عائمة بحركة رأسية مع تفاعل خفيف مع تمرير الصفحة، مع الالتزام بألوان الهوية.
- إصلاح استخدام اللوجو في أعلى وأسفل الموقع عبر نسخة نظيفة من الشعار بدون الجزء المقطوع أسفل الصورة.
- تعديل الخطوة الثانية في «رحلة تعليمية بسيطة» إلى «تواصل معنا».

## قبل الإطلاق
1. راجعي المحتوى النهائي والروابط قبل الإطلاق.
2. راجعي البريد `info@ofuqacademy.com` والدومين الموجودين في meta tags.
3. إذا كان لديك Domain فعلي، ضعيه بدل `www.ofuqacademy.com` في `canonical` وOG/Twitter URLs.
4. لإعلانات Meta: ضعي Meta Pixel ID داخل `CONFIG.metaPixelId`.
5. لـGoogle Analytics: ضعي GA4 Measurement ID داخل `CONFIG.googleAnalyticsId`.

## النشر المجاني

### GitHub Pages
1. أنشئي Repository جديدًا على GitHub.
2. ارفعي محتويات مجلد `ofuq_site` إلى الفرع `main`.
3. من `Settings → Pages` اختاري `Deploy from a branch` ثم `main / root`.
4. سيظهر الموقع على رابط GitHub Pages مجاني من نوع `https://USERNAME.github.io/REPOSITORY/`.

### الدومين
- الاستضافة على GitHub Pages مجانية.
- للحصول على دومين مخصص مثل `ofuqacademy.com` يلزم امتلاك/شراء الدومين، ثم ربطه من إعدادات GitHub Pages.
- لا تضعي ملف `CNAME` إلا بعد تحديد الدومين النهائي.

