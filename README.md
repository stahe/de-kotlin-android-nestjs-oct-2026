# Ein Client-Server-Beispiel - Kotlin Android / NestJS (2026)

Dieses Repository gehört zum Kurs **„Ein Client-Server-Beispiel - Kotlin Android / NestJS (2026)“**, veröffentlicht unter:

**https://stahe.github.io/de-kotlin-android-nestjs-oct-2026/**

## Überblick

Dieses Dokument überträgt die Lehranwendung **RdvMedecins** (Terminplanung in einer Arztpraxis), die bereits in den Kursen zu Angular, React, Vue.js und Flutter behandelt wurde, in eine native Android-App. Hier wird eine **Android**-Version vorgestellt: ein in **Kotlin** mit **Jetpack Compose** (Material 3) geschriebener Client, der auf einem **NestJS**-Server (TypeScript) aufsetzt, der eine durch JWT-Authentifizierung geschützte JSON-API (Rollen ADMIN / USER) bereitstellt.

Dieses Dokument bietet eine Schritt-für-Schritt-Anleitung entlang der Progression des Kurses [Ein Client-Server-Beispiel - Flutter / NestJS (2026)](https://stahe.github.io/de-flutter-nestjs-sept-2026/), von dem es den Server, die Datenbank und die Client-Architektur übernimmt: Jedes Jetpack-Compose-Konzept wird mit seinem Flutter-Pendant verknüpft. Die Grundlagen der Sprache Kotlin werden im [Kotlin-Kurs](https://stahe.github.io/de-kotlin-oct-2026/) behandelt.

Der Kurs behandelt:

- die Einrichtung der Entwicklungsumgebung (Android Studio, Android SDK, Gradle, Anlegen eines Compose-Projekts, Emulator und Android-Smartphone);
- die Installation und den Start des NestJS-Servers der Anwendung (MySQL-Datenbank, Konfiguration, Tests mit einem Browser und mit Postman);
- eine Einführung in Android und Jetpack Compose (Activities, `@Composable`-Funktionen, Zustand und Recomposition, `CompositionLocal`, Coroutinen, Lebenszyklus und `ViewModel`);
- einen ausführlichen Durchgang durch den Kotlin-Client der Anwendung RdvMedecins, Datei für Datei (OkHttp, kotlinx.serialization, SharedPreferences, Material 3);
- das Ausführen der App auf einem Emulator und auf einem Smartphone, wobei die mobilspezifischen Stolperfallen behandelt werden (Serveradresse, `adb reverse`, unverschlüsselter HTTP-Verkehr, Bildschirmdrehung, schmale Bildschirme), das Erstellen einer APK und einen Überblick über Kotlin Multiplatform;
- ein Fazit zum Erreichten und Anregungen für die weitere Beschäftigung.

## Autoren

- **Hauptautor:** KI Claude (Anthropic)
- **Prüfer:** [Serge Tahé](https://stahe.github.io)
