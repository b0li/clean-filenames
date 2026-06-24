# Clean Filenames

Dateien per Drag & Drop reinziehen und SEO-konform sauber benannt wieder herunterladen. Läuft komplett im Browser, kein Upload.

**Live:** https://b0li.github.io/clean-filenames/

## Features

- Drag & Drop oder Klick, mehrere Dateien gleichzeitig, beliebige Typen
- Live-Vorschau: Original → bereinigter Name
- Transliteration (ä→ae, é→e, ß→ss …), Spaces/Underscores/Punkte → Hyphen, lowercase, Mehrfach-Hyphen kollabiert
- Toggles: Kleinschreibung, Umlaute ausschreiben (ä→ae vs. ä→a)
- Einzel-Download (umbenannt) + Batch als ZIP
- Single `index.html`, Vanilla JS, kein Build-Step (nur JSZip via CDN)
