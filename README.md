# esimgo-app

Aplikacja mobilna Android dla esimgo.is z WebView

## Funkcjonalności

✅ WebView wyświetlający https://esimgo.is
✅ Przycisk "Powrót" do nawigacji wstecz
✅ Menu ze strony (automatyczne)
✅ Wszystkie produkty ze strony
✅ Responsywny design

## Wymagania

- Android Studio (wersja 2021.1 lub wyższa)
- Android SDK 21+
- Java 11+

## Instalacja

1. Sklonuj repozytorium:
```bash
git clone https://github.com/pakozlowski/esimgo-app.git
cd esimgo-app
```

2. Otwórz projekt w Android Studio

3. Czekaj na sync Gradle

4. Kliknij Run (lub Shift + F10)

## Użycie

Aplikacja automatycznie załaduje stronę https://esimgo.is. Możesz:
- 🍔 Korzystać z menu ze strony
- ⬅️ Kliknąć przycisk "Powrót" lub użyć przycisku back urządzenia
- 📦 Przeglądać wszystkie produkty
- 📱 Wszystko działa na responsywnym designie

## Struktura projektu

```
esimgo-app/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/esimgo/app/
│   │   │   │   └── MainActivity.java
│   │   │   ├── res/
│   │   │   │   └── layout/
│   │   │   │       └── activity_main.xml
│   │   │   └── AndroidManifest.xml
│   │   └── build.gradle
├── build.gradle
└── README.md
```

## Autor

pakozlowski

## Licencja

MIT
