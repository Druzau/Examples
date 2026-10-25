# Кулинарный дневник

Сборка APK локально (нужны Node 18+, JDK 17 и Android SDK):

    npm install
    npx cap add android
    npx cap sync android
    cd android && ./gradlew assembleDebug

Готовый файл: android/app/build/outputs/apk/debug/app-debug.apk

Сборка без установки чего-либо: загрузить проект в репозиторий GitHub,
вкладка Actions, workflow build-apk, внутри запуска скачать app-debug.

Интерфейс лежит в www/index.html, его можно открыть в браузере.
