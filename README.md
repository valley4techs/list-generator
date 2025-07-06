# 🎯 أداة توليد القوائم التفاعلية

أداة ويب متقدمة لإنشاء قوائم HTML/CSS مخصصة وتفاعلية بتصميم عصري وواجهة سهلة الاستخدام.

## 🌟 الميزات الرئيسية

### 🎨 تخصيص متقدم
- **أنواع القوائم**: نقطية (Bulleted) أو رقمية (Numbered)
- **4 أنماط تصميم**: عصري، كلاسيكي، مبسط، ومتدرج
- **تحكم كامل في الألوان**: أداة انتقاء الألوان + ألوان محددة مسبقاً
- **أيقونات مخصصة**: مجموعة من الأيقونات الجاهزة أو بدون أيقونات
- **تحكم في المسافات**: مضغوط، عادي، أو واسع

### ✨ تأثيرات بصرية
- **تأثيرات الحوم**: تفاعل بصري عند تمرير المؤشر
- **حركات متقدمة**: انتقالات سلسة ومتدرجة
- **ظلال ثلاثية الأبعاد**: لإضافة عمق بصري
- **حواف مدورة**: لمظهر عصري وناعم

### 🔧 سهولة الاستخدام
- **معاينة مباشرة**: رؤية التغييرات فورياً
- **نسخ بنقرة واحدة**: نسخ الكود المولد إلى الحافظة
- **تصميم متجاوب**: يعمل على جميع الأجهزة
- **واجهة باللغة العربية**: دعم كامل للغة العربية

## 🚀 العرض الحي

يمكنك تجربة الأداة مباشرة من خلال الرابط التالي:
[https://www.valley4techs.com/p/list-generator.html](https://www.valley4techs.com/p/list-generator.html)

## 📸 لقطات الشاشة

### الواجهة الرئيسية
![الواجهة الرئيسية](2025-07-06 (1).png)

### المعاينة المباشرة
![المعاينة المباشرة](https://via.placeholder.com/800x400/f0fdf7/13b981?text=Live+Preview)

## 🛠️ كيفية الاستخدام

### الخطوة 1: اختيار الإعدادات
1. حدد نوع القائمة (نقطية أو رقمية)
2. اختر النمط المطلوب (عصري، كلاسيكي، مبسط، أو متدرج)
3. حدد الأيقونة المناسبة أو اتركها فارغة
4. اختر اللون المطلوب باستخدام أداة الألوان

### الخطوة 2: إدخال المحتوى
- أدخل عناصر القائمة في منطقة النص (كل عنصر في سطر منفصل)

### الخطوة 3: تخصيص التأثيرات
- فعل أو أوقف تأثيرات الحوم
- اختر الحركات المتقدمة
- أضف الظلال والحواف المدورة

### الخطوة 4: توليد الكود
1. اضغط على زر "توليد الكود"
2. اضغط على المربع المحتوي على الكود لنسخه
3. الصق الكود في موقعك أو مشروعك

## 📁 هيكل الملفات

```
List Generator/
├── index.html          # الملف الرئيسي
├── README.md          # هذا الملف
└── assets/            # مجلد الأصول (في حالة الإضافة لاحقاً)
    ├── images/        # الصور
    └── docs/          # الوثائق الإضافية
```

## 🎯 أمثلة على الاستخدام

### قائمة نقطية عصرية
```html
<style>
.custom-list-xyz li {
  background: #f0fdf7;
  border-right: 3px solid #13b981;
  padding: 12px 15px;
  margin-bottom: 10px;
  border-radius: 12px;
  transition: all 0.3s ease;
}
</style>

<ul class="custom-list-xyz">
  <li>المهمة الأولى</li>
  <li>المهمة الثانية</li>
  <li>المهمة الثالثة</li>
</ul>
```

### قائمة رقمية كلاسيكية
```html
<style>
.custom-list-abc li {
  counter-increment: custom-counter;
  background: #ffffff;
  border: 1px solid #13b981;
  padding: 12px 15px;
  position: relative;
}
.custom-list-abc li::before {
  content: counter(custom-counter);
  position: absolute;
  right: 0.8rem;
  background: #13b981;
  color: white;
  border-radius: 50%;
  width: 1.8rem;
  height: 1.8rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>

<ol class="custom-list-abc">
  <li>الخطوة الأولى</li>
  <li>الخطوة الثانية</li>
  <li>الخطوة الثالثة</li>
</ol>
```

## 🔧 التخصيص المتقدم

### إضافة ألوان مخصصة
يمكنك إضافة ألوان جديدة عبر تعديل المتغيرات في CSS:

```css
:root {
  --primary-color: #13b981;
  --secondary-color: #f0fdf7;
  --accent-color: #059669;
}
```

### إضافة أيقونات جديدة
لإضافة أيقونات إضافية، عدل قسم `iconPicker` في HTML:

```html
<option value="🔥">🔥 نار</option>
<option value="⚡">⚡ برق</option>
<option value="🎨">🎨 فن</option>
```

## 🌍 دعم المتصفحات

الأداة تدعم جميع المتصفحات الحديثة:
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+

## 📱 التوافق مع الأجهزة

- 📱 **الهواتف الذكية**: تصميم متجاوب كامل
- 📟 **الأجهزة اللوحية**: تجربة محسنة
- 💻 **أجهزة الكمبيوتر**: تجربة كاملة

## 🛡️ الأمان والخصوصية

- **لا توجد بيانات مرسلة**: جميع العمليات تتم محلياً في المتصفح
- **لا توجد ملفات تعريف ارتباط**: لا نتتبع أي بيانات شخصية
- **مفتوح المصدر**: الكود مفتوح للمراجعة والتطوير

## 🤝 المساهمة

نرحب بالمساهمات من المطورين! إليك كيفية المساهمة:

1. **Fork** المشروع
2. أنشئ **branch** جديد للميزة (`git checkout -b feature/AmazingFeature`)
3. **Commit** تغييراتك (`git commit -m 'Add some AmazingFeature'`)
4. **Push** إلى الـ Branch (`git push origin feature/AmazingFeature`)
5. افتح **Pull Request**

### أفكار للتطوير
- [ ] إضافة أنماط تصميم جديدة
- [ ] دعم تصدير القوائم كصور
- [ ] إضافة قوالب جاهزة
- [ ] دعم الرسوم المتحركة المخصصة
- [ ] إضافة وضع الليل/النهار

## 🐛 الإبلاغ عن الأخطاء

إذا واجهت أي مشاكل أو أخطاء، يرجى:
1. التأكد من أن المشكلة لم يتم الإبلاغ عنها مسبقاً
2. فتح **Issue** جديد مع وصف مفصل للمشكلة
3. إرفاق لقطات شاشة إن أمكن

## 📧 التواصل

للأسئلة أو الاستفسارات:
- **الموقع**: [Valley4Techs](https://www.valley4techs.com)
- **البريد الإلكتروني**: [info@valley4techs.com](mailto:info@valley4techs.com)

## 📄 الترخيص

هذا المشروع مرخص تحت رخصة MIT - راجع ملف [LICENSE](LICENSE) للتفاصيل.

## 🙏 شكر وتقدير

- شكر خاص لمجتمع المطورين العرب
- Font Awesome لتوفير الأيقونات الرائعة
- جميع المساهمين في تطوير هذا المشروع

## 📊 إحصائيات

![GitHub stars](https://img.shields.io/github/stars/yourusername/list-generator?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/list-generator?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/list-generator)
![GitHub license](https://img.shields.io/github/license/yourusername/list-generator)

---

<div align="center">
صنع بـ ❤️ من قبل <a href="https://www.valley4techs.com">وادي التكنولوجيا</a>
</div>
