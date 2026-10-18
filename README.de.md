# ⚡ PicoResize

[日本語](README.md) | [English](README.en.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md)

---

**PicoResize** ist eine hochleistungsfähige Windows-Desktop-Anwendung zur Stapelverarbeitung von Bildern (JPG, PNG, WebP, BMP, TIFF) und PDF-Dokumenten mit **automatischer Randbeschneidung**, **intelligenter Seitenverhältnisanpassung** und **Zielgrößenkomprimierung (MB)** in einer 100 % sicheren, lokalen Offline-Umgebung.

---

## 🌟 Hauptfunktionen

1. **Automatische Randbeschneidung (Auto Trim)**
   - Erkennt und entfernt automatisch unerwünschte weiße Ränder und Rahmen von Fotos, gescannten Bildern und PDF-Seiten.
2. **Ausrichtungserkennende intelligente Größenanpassung (Seitenverhältnis beibehalten)**
   - Passt Bilder in die angegebene Begrenzungsbox ein (z. B. `[ 640 ] × [ 480 ]`):
     - **Horizontale Bilder (Breite ≥ Höhe)**: Passt in Breite × Höhe = `640 × 480` unter Beibehaltung des Seitenverhältnisses.
     - **Vertikale Bilder (Höhe > Breite)**: Passt in Höhe × Breite = `640 × 480` (Breite 480 × Höhe 640) mit automatischer Ausrichtungsdrehung.
3. **Ziel-Dateigrößenkomprimierung (MB)**
   - Passt die Komprimierungsqualität mittels binärer Suche automatisch an, um sicherzustellen, dass Dateien unter der Zielgröße (z. B. `0,5` MB) bleiben – bei minimalem Qualitätsverlust.
4. **Automatische Umbenennung bei Duplikaten**
   - Falls im Zielordner bereits eine Datei mit demselben Namen existiert, wird automatisch `(2)`, `(3)` usw. angehängt, um versehentliches Überschreiben zu verhindern.
5. **Nahtlose Stapelverarbeitung von Bildern & PDFs**
   - Ziehen Sie PDF-Dateien (erste Seite gerastert bei 300 DPI) und verschiedene Bildformate per Drag & Drop in dieselbe Warteschlange.
6. **Extrem geringer Speicherverbrauch (stabil bei 10–20 MB)**
   - Verwendet Win32-Working-Set-Trimming, UI-Virtualisierung und Idle-Speicherfreigabe für einen winzigen Speicher-Footprint von nur ~10 MB.
7. **Vollständige Lokalisierung in 8 Sprachen**
   - 🌐 Unterstützt Japanisch, Englisch, vereinfachtes Chinesisch, traditionelles Chinesisch, Koreanisch, Spanisch, Deutsch und Französisch mit sofortiger Echtzeit-Umschaltung.
8. **Automatische Velopack-Updates**
   - Integriert mit Velopack für nahtlose Differenz-Updates mit einem Klick.

---

## 🖥️ Systemanforderungen
- **Betriebssystem**: Windows 10 (Version 2004 oder höher) / Windows 11 (x64)
- **Laufzeitumgebung**: Eigenständig / Self-contained (keine externe .NET-Installation erforderlich)

---

## 🚀 Erste Schritte
1. Geben Sie die gewünschten Abmessungen (`Breite × Höhe`), die Zielgröße in MB und das Ausgabeformat (`JPEG / PNG / WebP`) ein.
2. Ziehen Sie Ihre Bild- oder PDF-Dateien in den Drop-Bereich (oder nutzen Sie die Schaltfläche „Dateien hinzufügen“).
3. Klicken Sie auf „🚀 Ändern & Speichern“ und wählen Sie den Zielordner aus.
4. Nach Abschluss des Vorgangs erscheint ein Bestätigungsdialog mit der Option, den Zielordner direkt zu öffnen.

---

## 📄 Lizenz
MIT-Lizenz
