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
- **Ein Gedanke kann alles enthalten:** Text, Überschriften, **Checklisten** (direkt abhakbar), Links, Tabellen, **Bilder** und **Formeln** gemischt in einem Inhalt (Markdown).
- **Einfügen-Leiste** über dem Text – Überschrift, Checkliste, Bild, Link, Fix, Formel, Tabelle, Code – oder einfach **„/" tippen** (z. B. `/checkliste`, `/formel`).
- **Formeln in LaTeX-Schreibweise:** `$E = mc^2$` im Text oder als eigener Block mit `$$ … $$`.
- **Zuordnen:** Spaces (Projekte/Themen mit Farbe und Icon), Tags (`#tag` im Text wird automatisch erkannt), Status von „Inbox" bis „Erledigt". SitzNotes schlägt passende Spaces vor („gehört wahrscheinlich zu …"). Eine Karte kann in mehreren Spaces liegen.
- **Verknüpfungen** zwischen Karten: gehört zu, inspiriert von, blockiert, Alternative zu, Teil von.
- **Fixes 🐞:** eigene Spalte im Board direkt nach der Inbox; Schalter **„Nur Fixes"** zeigt nur Fehler und Korrekturen.
- **Liste und Board** (Kanban nach Status mit Drag & Drop), **Spalten auf- und zuklappbar**, Schalter **„Erledigte ausblenden"**.
- **Projektarbeiten (Beta):** wissenschaftliche Arbeiten, Bachelorarbeiten und andere Dokumente in **LaTeX** schreiben – mit **PDF-Vorschau** daneben, die sich nach dem Tippen selbst erneuert, verständlicher **Fehleranzeige** (Klick springt zur Zeile), Vorlage **„Wissenschaftliche Arbeit (deutsch)"** (Titelseite, Verzeichnisse, Literatur, deutsche Silbentrennung), deinen Notizen zum Einfügen und Export als PDF oder ZIP. Bestehende LaTeX-Projekte lassen sich als Kopie importieren.
- **Volltextsuche** (auch Wortanfänge, Umlaute egal), Filter nach Status/Space/Tag, **Schnellsuche mit Strg+K**.
- **Bilder** per Drag & Drop oder Einfügen (z. B. Bildschirmausschnitt).
- **Export & Import:** alles oder einzelne Spaces als `.sitznotes`-Datei (Import führt zusammen, nichts wird doppelt) und als **Markdown + Bilder** – ein Ordner je Space, lesbar in jedem Editor oder z. B. in Obsidian.
- **Automatische Sicherung** täglich (die letzten 10 Stände) und **vor jedem Update**.
- **Updates direkt in SitzNotes:** Hinweis mit den Neuerungen, „Jetzt installieren" oder „Später" – nie ungefragt.
- **Papierkorb** mit „Endgültig löschen" und „Papierkorb leeren" (mit Sicherheitsabfrage), auf Wunsch automatisch nach einer gewählten Zahl von Tagen.
- **Passt sich deinem Monitor an:** von Laptop bis 4K, mit jeder Windows-Skalierung und auf Retina-Displays.
- Dunkles Design, alle Links öffnen im Standard-Browser.

<p align="center">
  <img src="assets/screenshots/sitznotes-board.png" alt="SitzNotes: Board nach Status mit Fixes-Spalte" width="900">
</p>

<p align="center">
  <img src="assets/screenshots/sitznotes-projektarbeit.png" alt="SitzNotes: Projektarbeit mit LaTeX-Editor und PDF-Vorschau (Beta)" width="900">
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

**Ab Version 0.3.0 kommen Updates direkt in SitzNotes:** Gibt es eine neue Version, erscheint oben ein dezenter Hinweis
mit Versionsnummer und Neuerungen – **„Jetzt installieren"** oder **„Später"**. Es wird nie ungefragt installiert.
Selbst suchen: **Einstellungen → Updates → „Nach Updates suchen"**; die automatische Suche (beim Start und alle 6 Stunden)
lässt sich dort abschalten. Updates sind digital signiert – SitzNotes installiert nur Updates, die wirklich von SitzNotes stammen.

Von Version 0.1.0 oder 0.2.0 aus installierst du 0.3.0 einmal von Hand: **einfach über die alte Version installieren – deine Daten bleiben erhalten**
und werden automatisch ins neue Format übernommen (Link-, Bild-, Checklisten- und Fix-Karten werden zu normalen Gedanken mit diesem Inhalt).
Nimm dafür **dasselbe Paket wie bei der ersten Installation** – wer mit dem `.msi` installiert hat, wieder das `.msi`, sonst die `setup.exe`.
In-App-Updates erkennen das selbst.

Vor jedem Update und jeder Umstellung der Datenbank legt SitzNotes automatisch eine Sicherung an
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
| **1 – 9** | Status setzen (Inbox, Fixes, Idee … Verworfen) |
| **Enter** | Vorschlag „gehört wahrscheinlich zu …" annehmen |
| **Entf** | in den Papierkorb |
| **Strg+Enter** oder **Esc** | beim Bearbeiten: **Fertig** |
| **/** | beim Bearbeiten: Baustein einfügen (Checkliste, Formel, Bild …) |
| **Strg+S** | in einer Projektarbeit: speichern und PDF sofort erzeugen |
| **Esc** | Karte schließen |

Auf dem Mac jeweils **⌘** statt **Strg**.

## Tipps zur Nutzung

- **Erst festhalten, später sortieren.** Mit dem Quick-Capture-Kürzel schreibst du den Gedanken in Sekunden auf, ohne das aktuelle Programm zu verlassen. Die erste Zeile wird zum Titel, der Rest zum Inhalt.
- **Inbox-Routine:** Einmal am Tag die Inbox öffnen und mit der Tastatur durchgehen – **S** für den Space, **T** für Tags, **1–9** für den Status, **Enter** übernimmt den Vorschlag. Ziel: Inbox leer.
- **Alles in einen Gedanken:** Notiz schreiben, mit **/checkliste** Aufgaben dazu, ein Bildschirmfoto mit **Strg+V** direkt an die Stelle, eine Formel mit **/formel** – in der Vorschau hakst du Aufgaben direkt ab.
- **Spaces für Projekte, Tags für Querschnittsthemen.** Ein Space ist z. B. „Homelab" oder „Musik", ein Tag z. B. `#idee-für-später` oder `#kaufen` – Tags schreibst du einfach mit `#` in den Text.
- **Fehler gehören zu den Fixes.** Beginnt eine Quick-Capture-Notiz mit `fix:`, landet sie in der Spalte „🐞 Fixes". Mit **„Nur Fixes"** in der Kopfzeile siehst du alle offenen Fehler, zusammen mit dem Space-Filter nur die eines Projekts.
- **Board für den Überblick:** Karten per Drag & Drop in die nächste Spalte ziehen; Spalten, die du gerade nicht brauchst, per Klick auf den Spaltenkopf zuklappen; „Erledigte ausblenden" hält das Board übersichtlich.
- **Projektarbeit neben den Notizen:** Ordne die Projektarbeit dem Space mit deinen Recherche-Notizen zu – unter „Notizen" stehen sie neben dem Editor und lassen sich per Klick als LaTeX einfügen. Bilder einfach in die Dateiliste oder den Editor ziehen.
- **Verknüpfen statt kopieren:** Gehört eine Idee zu einer anderen, verknüpfe sie – in beiden Karten ist die Verbindung sichtbar.
- **Diktieren statt tippen:** Systemeigenes Diktieren funktioniert in jedem Textfeld von SitzNotes – **Windows: Win+H**, **macOS: Diktierfunktion** (z. B. zweimal **Fn** bzw. die **Globus-Taste**).
- **Sicherungsordner außerhalb des App-Datenordners wählen** (Einstellungen → Sicherungsordner), z. B. **Dokumente**, ein **NAS** oder ein Cloud-Ordner. Dann überstehen deine Sicherungen auch eine Deinstallation oder einen Rechnerwechsel.
- **Zwischen Geräten übertragen:** auf dem einen Gerät „Alles exportieren (.sitznotes)", auf dem anderen importieren – SitzNotes führt zusammen und behält jeweils die neueste Änderung.
- **Markdown-Export** (Einstellungen oder Space-Menü „⋯") für eine lesbare Kopie: ein Ordner je Space, Bilder im Unterordner `bilder`, Fixes im Unterordner `Fixes`.
- **Papierkorb aufräumen:** Gelöschte Karten liegen im Papierkorb, bis du sie endgültig löschst („Papierkorb leeren"). Wer möchte, stellt in den Einstellungen „Automatisch leeren nach … Tagen" ein – standardmäßig ist das aus.

## Projektarbeiten (Beta) – LaTeX

- **Neue Projektarbeit:** Seitenleiste → **Projektarbeiten** → „Neue Projektarbeit", Vorlage **„Wissenschaftliche Arbeit (deutsch)"** oder **„Leer"** wählen.
- **LaTeX-Engine:** Ist **MiKTeX**, **TeX Live** oder **MacTeX** installiert, nutzt SitzNotes diese automatisch (inkl. BibTeX und Biber). Sonst kommt das mitgelieferte **Tectonic** zum Einsatz: Beim **ersten** Erzeugen eines PDFs lädt es die benötigten LaTeX-Pakete einmalig aus dem Internet (etwa 40 MB, 1–2 Minuten), danach funktioniert alles **offline**. Die Engine lässt sich je Projektarbeit umstellen.
- **Literaturverzeichnis:** Die Vorlage nutzt BibTeX (`literatur.bib`, `\cite{…}`) – das funktioniert mit allen Engines. biblatex/Biber geht mit einer installierten Distribution.
- **Import:** „Ordner importieren" bzw. „ZIP importieren" übernimmt ein bestehendes LaTeX-Projekt als **Kopie** – deine Originaldateien werden nie verändert.
- **Sicherung:** Projektarbeiten sind in den automatischen Sicherungen, den Sicherungen vor Updates und im `.sitznotes`-Export enthalten.
- Es ist eine **Beta**: Bitte bei wichtigen Arbeiten zusätzlich regelmäßig „Projekt als ZIP" exportieren und Fehler als Issue melden.

## Datenschutz

- Alle Karten, Bilder, Projektarbeiten und Einstellungen liegen **nur lokal** auf deinem Gerät (Windows: `%APPDATA%\de.sitzmedia.sitznotes`, macOS: `~/Library/Application Support/de.sitzmedia.sitznotes`).
- **Kein Konto, kein Server, keine Telemetrie.** SitzNotes funktioniert vollständig ohne Internet.
- Ins Internet geht SitzNotes nur für die **Update-Suche** (eine kleine Abfrage bei GitHub, abschaltbar) und – nur wenn du Projektarbeiten mit dem mitgelieferten Tectonic nutzt – zum einmaligen Laden von LaTeX-Paketen. Dabei werden keine Daten von dir übertragen.
- Links öffnen immer in deinem Standard-Browser, nie in der App.

## Bekannte Einschränkungen

- Installer sind noch nicht digital signiert (Hinweise oben bei der Installation); die Updates selbst sind signiert.
- Projektarbeiten sind eine **Beta**. Mit dem mitgelieferten Tectonic gibt es kein Biber (biblatex) – dafür BibTeX/natbib nutzen oder MiKTeX/TeX Live installieren.
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
