ضربان شو - ساخت APK اندروید
سازنده: کیان قادرزاده

ساختار: www/index.html بازی است و capacitor.config.json تنظیمات اپ است.

مراحل ساخت APK (روی کامپیوتر خودتان با نصب Node.js و Android Studio):
۱. این پوشه را از حالت فشرده خارج کنید.
۲. در ترمینال داخل پوشه اجرا کنید:
     npm install
     npx cap add android
     npx cap sync android
۳. دستور زیر Android Studio را باز می‌کند:
     npx cap open android
۴. در Android Studio از منوی Build گزینهٔ Build Bundle(s) / APK(s) > Build APK(s) را بزنید.
۵. فایل APK در مسیر app/build/outputs/apk/debug/ ساخته می‌شود و قابل نصب روی گوشی است.
۶. برای نسخهٔ منتشرشده در Google Play از Build > Generate Signed Bundle / APK استفاده کنید.

نکته: برای تغییر بازی، فقط فایل www/index.html را ویرایش کنید و دوباره npx cap sync android را اجرا کنید.
