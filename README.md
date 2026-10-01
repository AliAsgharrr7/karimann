# KARIMAN STUDIO – ساخت APK

## روش ۱: بدون نصب هیچ چیز (GitHub Actions)
1. یک مخزن جدید در GitHub بسازید و محتوای این پوشه را در آن آپلود کنید.
2. به تب Actions بروید و workflow با نام Build APK را اجرا کنید.
3. پس از چند دقیقه فایل `kariman-studio-apk` را از بخش Artifacts دانلود کنید (داخلش app-debug.apk است).

## روش ۲: روی کامپیوتر خودتان
نیازمندی‌ها: Node.js 18+، JDK 17، Android Studio (برای Android SDK)

    npm install
    npx cap add android
    npm run apk

خروجی: android/app/build/outputs/apk/debug/app-debug.apk

## نکته
فونت Vazirmatn از اینترنت بارگذاری می‌شود. برای کار کامل آفلاین، فایل فونت را در www قرار دهید و در CSS به آن اشاره کنید.
