<div align="center">

# ❄️ SubZero

**Privater Konto-, Fixkosten- & Abo-Tracker im modernen Liquid-Glass-Design.**  
*100 % lokal. 0 % Tracking. Eine einzige HTML-Datei.*

[![Single File](https://img.shields.io/badge/Architecture-Single%20File%20HTML-38bdf8?style=for-the-badge&logo=html5&logoColor=white)](#)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20LocalStorage-34d399?style=for-the-badge&logo=shield&logoColor=white)](#)
[![Zero Backend](https://img.shields.io/badge/Backend-None%20Required-a1a1aa?style=for-the-badge)](#)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages%20Ready-c084fc?style=for-the-badge&logo=github&logoColor=white)](#)

<br />

> **Live-Demo:** `[https://<dein-benutzername>.github.io/<dein-repo-name>/](https://marlii77.github.io/SubZero/)`  
> *(Passe den Link oben nach dem Aktivieren von GitHub Pages an.)*

</div>

---

## ✨ Warum SubZero?

Laufende Abos, vergessene Kündigungsfristen und verstreute Kontostände kosten jeden Monat unnötig Geld – aber Finanzdaten gehören nicht in fremde Clouds.

**SubZero** bringt volle Kostenkontrolle direkt in deinen Browser: als sofort lauffähige **Single-File-Web-App** (`index.html`) ohne Build-Prozess, ohne Account-Zwang und mit einem reaktiven **Hyper-Glass-Interface**, das sich auf Desktop und Smartphone gleichermaßen flüssig anfühlt.

---

## 🚀 Features

### 💳 Konten- & Vermögensübersicht
- Verwalte **Girokonten, Sparkonten, Kreditkarten, Depots und Bargeld** an einem Ort.
- Automatische Berechnung des **Gesamtvermögens** inklusive prozentualer Verteilung.
- **Schnellbuchung (`+/-`)** für blitzschnelle Kontostands-Updates.

### 🔁 Abo- & Fixkosten-Manager
- Erfasse laufende Verträge mit Kategorie, Betrag, Intervall (**monatlich / vierteljährlich / jährlich**), nächstem Abbuchungsdatum und individueller Kündigungsfrist.
- Automatische Umrechnung aller Kosten auf eine einheitliche **Monats- und Jahresbelastung**.
- Visuelle **Kostenverteilung nach Kategorien**, Echtzeit-Suche, Kategorie-Filter und Sortierung nach Dringlichkeit oder Betrag.

### 🔔 Kündigungs-Wecker
- Intelligente Berechnung des exakten Kündigungs-Stichtags (in Tagen oder Monaten).
- **Visuelle Warnstufen:**
  - 🟡 **Amber-Glow:** Kündigungsfrist oder Verlängerung innerhalb der nächsten **30 Tage**.
  - 🔴 **Red-Pulse:** Kritische Frist (**≤ 7 Tage**) oder bereits abgelaufen.

### 📊 Wechsel- & Spar-Rechner
- Vergleiche bestehende Verträge direkt mit günstigeren Alternativen (inkl. Alt-vs.-Neu-Balkenvergleich).
- Sofortige Kalkulation der Ersparnis auf **1 Monat, 1 Jahr und 3 Jahre**.
- **1-Klick-Übernahme:** Aktualisiere den bestehenden Vertrag direkt aus dem Rechner auf den neuen Tarif.

### 🎯 Sparziele (Buckets)
- Behalte Rücklagen wie *Notgroschen*, *Setup-Upgrade* oder *Führerschein* mit animierten **Progress-Rings** und **Shimmer-Balken** im Blick.
- Ein- und Auszahlungen über praktische Schnell-Buttons (`+25 €`, `+50 €`, `+100 €`, `-50 €`).

### 🎨 5 Liquid-Glass-Designs & Effekt-Engine
Über **Design & Profil** lässt sich SubZero jederzeit personalisieren:
- **5 Themes mit Live-Vorschau:** `SubZero Ice` · `Arctic Aurora` · `Cyber Violet` · `Ember Noir` · `Titanium Mono`
- **Persönliches Profil:** Eigener Benutzername mit tageszeitabhängiger Begrüßung.
- **Hyper-Glass-Effekte:** 60fps Cryo-Partikel-Netz & Licht-Bursts, 3D-Karten-Neigung (Tilt), mausverfolgender Specular-Spotlight, rotierende Conic Border Beams, Liquid Click-Ripples und Sliding-Pill-Navigation *(Effekt-Intensität, Tilt und Partikel einzeln umschaltbar)*.

---

## 🔒 Datenschutz & Datensicherung

- **100 % Lokal:** Alle Eingaben, Einstellungen und Verträge bleiben ausschließlich im `localStorage` deines Browsers. Es werden keinerlei Finanzdaten an einen Server übertragen.
- **JSON-Export & Import:** Sichere deine kompletten Daten mit einem Klick als `.json`-Datei und stelle sie beim Gerätewechsel nahtlos wieder her.
- **Schnellstart:** Beim allerersten Start sind realistische Beispieldaten vorgeladen, die du direkt anpassen oder per Klick komplett leeren kannst.

---

## 🛠️ Schnellstart & Deployment

### Option 1: Direkt lokal nutzen
1. Repository klonen oder die `index.html` herunterladen.
2. `index.html` per Doppelklick im Browser öffnen – fertig.

### Option 2: Kostenlos über GitHub Pages hosten (empfohlen)
1. Lade die `index.html` in dein GitHub-Repository hoch.
2. Öffne im Repository **Settings → Pages**.
3. Wähle unter **Build and deployment** den Branch `main` und den Ordner `/ (root)` aus und speichere.
4. Nach wenigen Sekunden ist deine private Instanz weltweit erreichbar.

### 📱 Als App auf dem Smartphone installieren
- **iOS (Safari):** Seite öffnen → *Teilen-Symbol* → **„Zum Home-Bildschirm“**.
- **Android (Chrome):** Seite öffnen → *Menü (`⋮`)* → **„Zum Startbildschirm hinzufügen“**.

---

## 🧱 Tech-Stack

| Bereich | Umsetzung |
| :--- | :--- |
| **Struktur** | Single-File HTML5 (`index.html`), keine Build-Tools |
| **Styling** | Tailwind CSS (CDN) + Custom Liquid-Glass CSS (`backdrop-filter`, `@property`, Spring-Transitions) |
| **Logik & FX** | Reines Vanilla JavaScript (ES6+) + HTML5 Canvas 2D Partikel-Engine |
| **Icons** | Saubere, monochrome Inline-SVGs (Lucide-Style) |
| **Persistenz** | Browser `localStorage` + JSON Backup Export/Import |

---

## 📸 Screenshots

> *Tipp: Erstelle 1–2 Screenshots von deinem Lieblings-Theme (z. B. `SubZero Ice` und `Cyber Violet`) und lege sie in einen `/screenshots`-Ordner, um sie hier einzubinden:*
>
> ```markdown
> ![SubZero Dashboard](screenshots/dashboard.png)
> ```

---

## 📄 Lizenz

Dieses Projekt steht unter der **MIT-Lizenz** – frei nutzbar, anpassbar und erweiterbar für deine eigenen Finanz-Workflows.
