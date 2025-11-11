# Marek Markon - Senior iOS & macOS Developer

Herzlich willkommen in meinem Entwickler-Portfolio. Ich bin ein auf Apple-Plattformen spezialisierter Softwareentwickler mit einem Fokus auf **SwiftUI, SwiftData und der sicheren, resilienten Integration von KI-Diensten**.

Ich baue nicht nur Apps – ich konzipiere und entwickle die **gesamte Full-Stack-Architektur** dahinter, von der nativen SwiftData-Datenbank auf dem Gerät bis hin zum sicheren, serverseitigen API-Management.

---

## Featured Project: Venueflux (KI-Lern-App)

Mein Hauptprojekt ist **Venueflux**, eine KI-gestützte Lernanwendung, die ich von Grund auf konzipiert, entwickelt und im Apple App Store veröffentlicht habe.

* **Website:** [https://www.venueflux.com](https://www.venueflux.com)
* **Plattformen:** iOS, iPadOS & macOS (eine native, Multi-Plattform SwiftUI-App)
* **Technologien:**
    * **UI:** 100% SwiftUI
    * **Daten:** SwiftData
    * **KI:** Integration der OpenAI API
    * **Monetarisierung:** StoreKit (In-App Subscriptions)
    * **Backend:** Eigener, sicherer PHP-Proxy für API-Key-Management (siehe unten)

---

## Featured Code Samples (Fallstudien)

Um meine technischen Fähigkeiten zu demonstrieren, habe ich zwei Kernkomponenten aus meinen Projekten als separate Fallstudien isoliert.

### 1. Fallstudie: Secure AI Proxy (Full-Stack / Backend)

**[➡️ zum Repository: `secure-openai-proxy-php`](https://github.com/VenueMare/secure-openai-proxy-php)**

Ein produktionsreifer, serverseitiger PHP-Proxy. Er sitzt zwischen der App und der OpenAI-API, um API-Keys zu schützen und Business-Logik hinzuzufügen.

* **Sicherheit:** Schützt API-Keys vor der Offenlegung im App-Client.
* **Resilienz:** Implementiert eine automatische **Fallback-Logik** (z.B. von `gpt-4o` zu `gpt-4o-mini` bei einem API-Fehler), um die App-Funktionalität zu gewährleisten.
* **Management:** Nutzt eine serverseitige Allow-List und Aliase, um KI-Modelle zu verwalten, ohne die App aktualisieren zu müssen.

### 2. Fallstudie: Komplexe SwiftUI Settings View (Frontend / App)

**[➡️ zum Repository: `ios-swiftui-settingsview`](https://github.com/VenueMare/ios-swiftui-settingsview)**

Ein einzelner, realer Code-Ausschnitt (`SettingsView.swift`), der eine komplexe Einstellungs-Ansicht aus einer SwiftUI-App zeigt.

* **SwiftUI:** Demonstriert komplexe `Form`-Strukturen und State Management (`@EnvironmentObject`, `@State`, `@FocusState`).
* **StoreKit:** Zeigt die Integration eines `SubscriptionManager` und die UI-Logik zum Anzeigen einer Paywall und zur Wiederherstellung von Käufen.
* **Sicherheit:** Integriert einen `KeychainService` und `SecureField` für die sichere Eingabe und Speicherung von API-Schlüsseln durch den Benutzer.

---

## 🛠️ Meine Kernkompetenzen

* **Sprachen:** Swift (Expert), PHP (Profi)
* **Apple Frameworks:** SwiftUI, SwiftData, StoreKit (In-App Purchases), CoreData, NotificationService
* **Architektur:** MVVM, State Management, Separation of Concerns
* **Backend & API:** Sicheres API-Design, REST-APIs, JSON, cURL
* **Sicherheit:** Keychain-Management, Serverseitiges Key-Hashing, API-Proxy-Entwicklung
* **Tools:** Xcode, GitHub, App Store Connect

---

## 💬 Kontakt

Ich suche aktiv nach neuen Freelance-Herausforderungen. Wenn Sie einen Entwickler benötigen, der nicht nur Code schreibt, sondern sichere und robuste Architekturen für moderne Apps entwirft, freue ich mich auf Ihre Nachricht.

* **Website:** [https://www.venueflux.com](https://www.venueflux.com)
* **LinkedIn:** *[Hier deinen LinkedIn-Profil-Link einfügen, sobald du einen hast]*
