# مشروع تطبيق NOVA AI لنظام أندرويد الأصلي (Android Native)
تطوير: **Derraz**

هذا المجلد يحتوي على كامل هيكلية مشروع **Android Studio** الرسمي والجاهز للفتح المباشر وبناء الـ APK.

## 📂 هيكل المجلدات:
- `app/src/main/java/com/derraz/novaai/MainActivity.kt`: كود الواجهة الكاملة بنظام Jetpack Compose والربط بالسيرفر.
- `app/src/main/java/com/derraz/novaai/NetworkModels.kt`: طبقة الاتصال بشبكة الإنترنت ومحرك الذكاء الاصطناعي عبر Retrofit.
- `app/src/main/AndroidManifest.xml`: صلاحيات الوصول للإنترنت وإعدادات التطبيق.
- `app/build.gradle.kts`: مكتبات Compose و Retrofit و OkHttp.
- `settings.gradle.kts` & `build.gradle.kts`: إعدادات بيئة Gradle المعتمدة.

## 🚀 كيفية فتح المشروع في Android Studio:
1. افتح برنامج **Android Studio**.
2. اختر **Open** ثم حدد مجلد `android_project`.
3. انتظر ثوانٍ ليكتمل الـ Gradle Sync.
4. اضغط من القائمة العلوية: **Build ➔ Build Bundle(s) / APK(s) ➔ Build APK(s)**.
5. سيخرج لك ملف `app-debug.apk` الأصلي لتثبيته فوراً على الهاتف!
