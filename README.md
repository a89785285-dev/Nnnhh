# ioslauncher

لانشر أندرويد بواجهة iOS: شاشة رئيسية بشبكة تطبيقات، Dock، شريط حالة، Control Center، Notification Center، وشاشة قفل.

## البنية
- `HomeActivity`: نقطة الدخول كـ HOME launcher.
- `LockScreenActivity`: شاشة القفل.
- `apps/`: تطبيقات أساسية (حالياً placeholders).
- `ui/`: مكونات Jetpack Compose.

## المتطلبات
- JDK 17
- Android minSdk 26

## التشغيل
1. توليد الـ wrapper مرة واحدة (يحتاج Gradle مثبت محلياً):
   `gradle wrapper --gradle-version 8.9`
2. بناء الـ APK:
   `./gradlew assembleDebug`
3. استبدال `app/src/main/res/mipmap/ic_launcher.png` بأيقونة حقيقية.
