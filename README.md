# بوابة التعريف بالمرشح — GitHub Pages

موقع عربي RTL متجاوب مع الهاتف، باستخدام HTML وCSS وJavaScript فقط.

## قبل النشر
1. افتح `index.html`.
2. استبدل `اسم المرشح` باسمك.
3. راجع نص التعريف والأولويات لتطابق برنامجك الحقيقي.
4. راجع رابط واتساب في `index.html`، واستبدل الرقم إن لزم. اكتب الرقم بصيغة دولية من دون `+` أو مسافات.
5. يمكنك إبقاء مساحة الصورة كما هي، أو إضافة صورتك وفق الخطوات أدناه.

## إضافة صورة اختيارية
- أنشئ مجلداً اسمه `assets`.
- ارفع الصورة باسم `candidate.jpg`.
- في `index.html` ابحث عن `<div class="portrait-placeholder" id="portrait">` واستبدل كتلة `div` كاملة بـ:
  `<div class="portrait-placeholder"><img src="assets/candidate.jpg" alt="صورة المرشح" style="width:100%;height:300px;object-fit:cover;border-radius:13px"></div>`
- إن كانت الصورة طولية أو أفقية، عدّل `object-position` عند الحاجة.

## النشر مجاناً على GitHub Pages
1. سجّل الدخول إلى https://github.com أو أنشئ حساباً.
2. اضغط `+` ثم `New repository`.
3. اختر اسماً مثل `candidate-campaign` واجعل المستودع `Public`، ثم أنشئه.
4. اضغط `Add file` ثم `Upload files`، وارفع `index.html` و`style.css` و`script.js` و`README.md` (وأي مجلد `assets` أضفته).
5. اضغط `Commit changes`.
6. افتح `Settings` للمستودع، ثم `Pages`.
7. تحت `Build and deployment` اختر `Deploy from a branch`.
8. اختر الفرع `main` والمجلد `/(root)` ثم اضغط `Save`.
9. انتظر قليلاً، ثم ستجد رابط الموقع في صفحة `Pages`، غالباً بالشكل:
   `https://USERNAME.github.io/REPOSITORY/`
   استبدل `USERNAME` باسم حسابك و`REPOSITORY` باسم المستودع؛ الرابط الفعلي يظهر داخل إعدادات Pages.

## ملاحظات
- الموقع لا يجمع بيانات الزوار ولا يحتاج قاعدة بيانات.
- رابط واتساب يفتح محادثة مع الرقم المحدد في الصفحة.
- راجع المعلومات والصلاحيات والقواعد الانتخابية قبل النشر.
- خط Cairo يُحمّل من Google Fonts؛ إذا لم يتوفر اتصال بالإنترنت فسيستخدم المتصفح خطاً بديلاً.
