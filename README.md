# عالم العلوم | Science World

تطبيق Flutter (Android) تعليمي لطلاب المنهاج السوري.

## تشغيل المشروع

```bash
flutter pub get
flutter run
```

## فحص

```bash
dart format .
flutter analyze
flutter test
```

## ملاحظة بيئة العمل

هذه المرحلة (الهيكل البرمجي + شاشات أولية) منفذة ككود Flutter. لم يتم تشغيل `flutter pub get` / `flutter analyze` / `flutter test` في بيئة العمل الحالية لعدم توفر Flutter SDK في الـ sandbox (Alpine Linux، Node فقط). يُرجى تشغيلها على جهاز/محاكي Android.