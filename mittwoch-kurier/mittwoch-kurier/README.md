# Der Mittwoch-Kurier 🗞️⚽

Statische Website für das AH-Training des VfB Neckarrems, Hummelberg.

## Deployment auf GitHub Pages

1. Neues Repository auf GitHub erstellen (z.B. `mittwoch-kurier`)
2. Inhalt dieses Ordners hineinladen (nur `index.html` reicht)
3. In den Repository-Einstellungen → **Pages** → Branch `main` auswählen
4. Fertig – die Seite ist unter `https://DEIN-USERNAME.github.io/mittwoch-kurier` erreichbar

## Neuen Artikel hinzufügen

Nach jedem Mittwoch-Training einfach in `index.html` im `ARTICLES`-Array
einen neuen Eintrag **oben** einfügen (damit er als Featured erscheint).

Vorlage für einen neuen Artikel – in Claude eingeben:

> „Heute haben Weiß X : Y Rot gewonnen / verloren. Füge den neuen Artikel ein."

Claude generiert dann den kompletten Artikel-Eintrag zum Einfügen.

## Struktur

```
mittwoch-kurier/
└── index.html   ← alles in einer Datei, kein Build-Step nötig
```
