<p align="center">
  <img src="assets/sitznotes-logo.jpg" alt="SitzNotes Logo" width="260">
</p>

<h1 align="center">SitzNotes</h1>

<p align="center">
  Gedanken in Sekunden festhalten, zuordnen, verknüpfen und wiederfinden –<br>
  für Windows und macOS (iPhone/iPad folgen).
</p>

<p align="center">
  Deine Daten bleiben lokal auf deinem Gerät. Kein Konto, kein Server.
</p>

<p align="center">
  <a href="https://github.com/Sitz9/sitznotes-releases/releases/latest"><b>⬇ Neueste Version herunterladen</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Sitz9/sitznotes-releases/releases">Alle Versionen &amp; Patchnotes</a>
  &nbsp;·&nbsp;
  <a href="https://djsitz.com">djsitz.com</a>
</p>

<p align="center">
  <img src="assets/screenshots/sitznotes-liste.png" alt="SitzNotes: Liste und Detailansicht" width="900">
</p>

---

## Was SitzNotes kann

- **Quick Capture von überall:** Ein Tastenkürzel öffnet ein kleines Eingabefenster über allen Programmen – tippen, Enter, fertig. Der Gedanke landet in der **Inbox**.
- **Karten** mit Titel und Text (Markdown: fett, Listen, Tabellen, Links …). Arten: Text, Link, Bild, Checkliste und **🐞 Fix**.
- **Zuordnen:** Spaces (Projekte/Themen mit Farbe und Icon), Tags (`#tag` im Text wird automatisch erkannt), Status von „Inbox" bis „Erledigt". SitzNotes schlägt passende Spaces vor („gehört wahrscheinlich zu …"). Eine Karte kann in mehreren Spaces liegen.
- **Verknüpfungen** zwischen Karten: gehört zu, inspiriert von, blockiert, Alternative zu, Teil von.
- **Fixes:** eigener Bereich für Fehler und Korrekturen – getrennt von den Ideen, nach Space filterbar.
- **Liste und Board** (Kanban nach Status mit Drag & Drop), Schalter **„Erledigte ausblenden"**.
- **Volltextsuche** (auch Wortanfänge, Umlaute egal), Filter nach Status/Space/Tag, **Schnellsuche mit Strg+K**.
- **Bilder** per Drag & Drop oder Einfügen (z. B. Bildschirmausschnitt).
- **Export & Import:** alles oder einzelne Spaces als `.sitznotes`-Datei (Import führt zusammen, nichts wird doppelt) und als **Markdown + Bilder** – ein Ordner je Space, lesbar in jedem Editor oder z. B. in Obsidian.
- **Automatische Sicherung** täglich (die letzten 10 Stände) und **vor jedem Update**.
- **Passt sich deinem Monitor an:** von Laptop bis 4K, mit jeder Windows-Skalierung und auf Retina-Displays.
- Dunkles Design, alle Links öffnen im Standard-Browser.

<p align="center">
  <img src="assets/screenshots/sitznotes-board.png" alt="SitzNotes: Board nach Status" width="900">
</p>

## Installation

Die Installer findest du unter [**Releases**](https://github.com/Sitz9/sitznotes-releases/releases/latest).
Mit `SHA256SUMS.txt` kannst du prüfen, ob der Download unverändert ist.

### Windows (10/11)

1. `SitzNotes_<version>_x64-setup.exe` herunterladen und starten (alternativ das `.msi`).
2. Die Installer sind noch nicht digital signiert. Erscheint **„Der Computer wurde durch Windows geschützt"** (SmartScreen): **„Weitere Informationen" → „Trotzdem ausführen"**.
3. SitzNotes startet; das Symbol erscheint im Infobereich der Taskleiste (Tray).

### macOS (ab macOS 12, Apple Silicon und Intel)

1. `SitzNotes_<version>_universal.dmg` öffnen und SitzNotes in den Ordner **Programme** ziehen.
2. Die App ist noch nicht von Apple beglaubigt. Beim ersten Start: **Systemeinstellungen → Datenschutz & Sicherheit → „Dennoch öffnen"**.
3. Für das globale Tastenkürzel kann macOS eine Freigabe unter **Datenschutz & Sicherheit → Bedienungshilfen** verlangen.

### Updates

**Neue Version einfach über die alte installieren – deine Daten bleiben erhalten.**
Vor jeder Umstellung der Datenbank legt SitzNotes automatisch eine Sicherung an
(`Sicherungen/vor-update-<version>-<datum>` im Datenordner, zusätzlich in deinem gewählten Sicherungsordner).
Geht dabei etwas schief, wird der alte Stand wiederhergestellt – SitzNotes läuft nie mit halb umgestellten Daten weiter.

### Deinstallation

Beim Deinstallieren unter Windows gibt es das Kästchen **„App-Daten löschen"** – es ist **standardmäßig aus**.
Lass es aus, wenn du deine Karten behalten möchtest. Nur wenn du es bewusst anhakst, werden der Datenordner
und die Sicherungen darin gelöscht.

## Tastenkürzel

| Kürzel | Wirkung |
|---|---|
| **Strg+Shift+Leertaste** (Windows) · **⌥⇧Leertaste** (macOS) | Quick Capture von überall (in den Einstellungen änderbar) |
| **Enter** / **Shift+Enter** / **Esc** | im Quick Capture: speichern / neue Zeile / schließen |
| **Strg+N** oder **N** | neue Karte |
| **Strg+K** | Schnellsuche über alle Karten |
| **↑ / ↓** (oder J / K) | durch die Liste bewegen |
| **S** / **T** | Space bzw. Tag zuordnen |
| **1 – 8** | Status setzen (Inbox … Verworfen) |
| **Enter** | Vorschlag „gehört wahrscheinlich zu …" annehmen |
| **Entf** | in den Papierkorb |
| **Strg+Enter** oder **Esc** | beim Bearbeiten: **Fertig** |
| **Esc** | Karte schließen |

Auf dem Mac jeweils **⌘** statt **Strg**.

## Tipps zur Nutzung

- **Erst festhalten, später sortieren.** Mit dem Quick-Capture-Kürzel schreibst du den Gedanken in Sekunden auf, ohne das aktuelle Programm zu verlassen. Die erste Zeile wird zum Titel, ein reiner Link wird zur Link-Karte.
- **Inbox-Routine:** Einmal am Tag die Inbox öffnen und mit der Tastatur durchgehen – **S** für den Space, **T** für Tags, **1–8** für den Status, **Enter** übernimmt den Vorschlag. Ziel: Inbox leer.
- **Spaces für Projekte, Tags für Querschnittsthemen.** Ein Space ist z. B. „Homelab" oder „Musik", ein Tag z. B. `#idee-für-später` oder `#kaufen` – Tags schreibst du einfach mit `#` in den Text.
- **Fehler gehören zu den Fixes.** Beginnt eine Quick-Capture-Notiz mit `fix:`, wird sie zur Fix-Karte 🐞. Im Bereich „Fixes" siehst du alle offenen Fehler, auf Wunsch nur die eines Space.
- **Board für den Überblick:** Karten per Drag & Drop in die nächste Spalte ziehen; „Erledigte ausblenden" hält das Board übersichtlich.
- **Verknüpfen statt kopieren:** Gehört eine Idee zu einer anderen, verknüpfe sie – in beiden Karten ist die Verbindung sichtbar.
- **Diktieren statt tippen:** Systemeigenes Diktieren funktioniert in jedem Textfeld von SitzNotes – **Windows: Win+H**, **macOS: Diktierfunktion** (z. B. zweimal **Fn** bzw. die **Globus-Taste**).
- **Sicherungsordner außerhalb des App-Datenordners wählen** (Einstellungen → Sicherungsordner), z. B. **Dokumente**, ein **NAS** oder ein Cloud-Ordner. Dann überstehen deine Sicherungen auch eine Deinstallation oder einen Rechnerwechsel.
- **Zwischen Geräten übertragen:** auf dem einen Gerät „Alles exportieren (.sitznotes)", auf dem anderen importieren – SitzNotes führt zusammen und behält jeweils die neueste Änderung.
- **Markdown-Export** (Einstellungen oder Space-Menü „⋯") für eine lesbare Kopie: ein Ordner je Space, Bilder im Unterordner `bilder`, Fixes im Unterordner `Fixes`.

## Datenschutz

- Alle Karten, Bilder und Einstellungen liegen **nur lokal** auf deinem Gerät (Windows: `%APPDATA%\de.sitzmedia.sitznotes`, macOS: `~/Library/Application Support/de.sitzmedia.sitznotes`).
- **Kein Konto, kein Server, keine Telemetrie.** SitzNotes funktioniert vollständig ohne Internet.
- Links öffnen immer in deinem Standard-Browser, nie in der App.

## Bekannte Einschränkungen

- Installer sind noch nicht digital signiert (Hinweise oben bei der Installation).
- Keine automatische Update-Prüfung – neue Versionen findest du unter [Releases](https://github.com/Sitz9/sitznotes-releases/releases).
- Noch nicht enthalten: iPhone/iPad, Sprachaufnahme, Zeichnen, Mindmap/Canvas, Wireframes, Termine und Erinnerungen – diese kommen in späteren Versionen.
- Kein automatischer Abgleich zwischen Geräten – Übertragung per Export/Import.

## Patchnotes

Was sich in jeder Version geändert hat, steht bei den [**Releases**](https://github.com/Sitz9/sitznotes-releases/releases).

## Fehler melden

Fehler und Wünsche gerne als [Issue](https://github.com/Sitz9/sitznotes-releases/issues) – bitte mit Version (Einstellungen → Info) und Betriebssystem.

---

<p align="center">
  <a href="https://djsitz.com">djsitz.com</a>
</p>

© 2026 Markus Sitzmann. Alle Rechte vorbehalten.
