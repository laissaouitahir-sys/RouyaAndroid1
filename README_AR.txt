مشروع تطبيق رؤية (Rouya) لنظام Android

هذا مجلد مشروع Android Studio جاهز للبناء، وليس ملف APK جاهزاً للتثبيت.

طريقة إنشاء APK:
1) افتح المجلد RouyaAndroid باستخدام Android Studio.
2) انتظر انتهاء Gradle Sync وتثبيت Android SDK Platform 35 عند الطلب.
3) من القائمة Build اختر Build Bundle(s) / APK(s) ثم Build APK(s).
4) ستجد الملف عادةً في: app/build/outputs/apk/debug/app-debug.apk

ملاحظات مهمة:
- التطبيق يعرض نسخة HTML المرفقة داخل التطبيق عبر WebView.
- تم تضمين أيقونة رؤية وملفات الواجهة.
- مكتبة Chart.js في صفحة الويب محمّلة من CDN، لذلك يلزم اتصال بالإنترنت لظهور الرسوم البيانية.
- لم يتم نشر الموقع على الإنترنت.
