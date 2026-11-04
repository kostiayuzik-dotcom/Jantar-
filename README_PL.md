# Kadry Online — aplikacja Android

Prosta aplikacja typu WebView otwierająca portal Kadry Online.

## Wymagania
- Android Studio (aktualna wersja)
- JDK 17
- Android SDK Platform 36

## Budowanie APK
1. Rozpakuj archiwum.
2. Otwórz folder `KadryOnlineAndroid` w Android Studio.
3. Poczekaj, aż Gradle pobierze wymagane komponenty.
4. Wybierz **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. APK znajdziesz w `app/build/outputs/apk/debug/app-debug.apk`.

## Ważne
- Aplikacja nie przechowuje ani nie odczytuje hasła. Logowanie odbywa się na stronie portalu.
- Sesja może być zapamiętana przez ciasteczka WebView, zależnie od ustawień portalu.
- Portal i jego poddomeny `jantar.eu.com` otwierają się wewnątrz aplikacji. Inne adresy HTTPS otwierają się w przeglądarce.
- Aplikacja wymaga połączenia z internetem.
- To projekt źródłowy; APK trzeba zbudować w Android Studio.
