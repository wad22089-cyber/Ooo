# دليل بناء ملف APK لتطبيق: نظام القيمة الجمركية - وليد الراشد

تحتوي هذه الحزمة على مشروع Android Capacitor الجاهز والمتصل مباشرة بتطبيقك، بالإضافة إلى أيقونة التطبيق المخصصة الخاصة بك.

## الطريقة الأسرع (بدون برامج على جهازك - عبر GitHub Actions):
1. ارفع محتويات هذا المجلد إلى مستودع جديد في GitHub.
2. افتح تبويب **Actions** ثم اختر **Build Android APK** واضغط **Run workflow**.
3. خلال دقيقتين سيظهر ملف **Customs-Valuation-Walid-APK** جاهزاً للتحميل بصيغة `.apk` وتثبيته على أي هاتف أندرويد.

## الطريقة المباشرة من المتصفح (PWABuilder):
1. انسخ رابط التطبيق المباشر: `https://ais-pre-f5i5rnxt2vur7dfmtdgo5m-972325761340.europe-west2.run.app`
2. أو افتح الرابط الجاهز مباشرة: `https://www.pwabuilder.com/reportcard?site=https%3A%2F%2Fais-pre-f5i5rnxt2vur7dfmtdgo5m-972325761340.europe-west2.run.app`
3. اختر **Package For Stores -> Android -> Generate Package** لتحميل ملف APK موقّع وجاهز فوراً.

## البناء المحلي (Android Studio):
```bash
npm install
npx cap add android
npx cap sync android
cd android && ./gradlew assembleDebug
```
ستجد الملف النهائي في: `android/app/build/outputs/apk/debug/app-debug.apk`
