КАЗАНЬ 88: ФЕНОМЕН — Android-проект (WebView-обёртка над index.html)

КАК ПОЛУЧИТЬ APK
1) Установи Android Studio (бесплатно): https://developer.android.com/studio
2) File > Open > выбери папку Kazan88 (где лежит этот файл) и дождись синхронизации Gradle.
3) Меню Build > Build Bundle(s) / APK(s) > Build APK(s).
4) Готовый файл: app/build/outputs/apk/debug/app-debug.apk — скинь на телефон и установи
   (в настройках Android разреши установку из неизвестных источников).

Игра лежит в app/src/main/assets/index.html (можно заменить на новую версию и пересобрать).
Сохранения хранятся в памяти приложения (localStorage). Кнопка «Назад» открывает меню паузы.
ВАЖНО: проект собран без проверки сборки на реальном Android Studio — если Gradle предложит
обновить версии плагина, соглашайся.
