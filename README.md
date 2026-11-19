# Rassismuskritische Soziale Arbeit

Interaktives Skript zur Lehrveranstaltung „3.02.2 Rassismuskritische Soziale Arbeit: Theorie und Praxis“ von Prof. Dr. Mehmet Kart, Soziale Arbeit (B. A.), OTH Regensburg (WiSe 2026/27).

## Was wo liegt

```
welcome.qmd              Willkommensseite
index.qmd                Seminarüberblick (Startseite der Webseite)
grundlagen/              Grundbegriffe zum Aufklappen
sitzungen/               Sitzungen 1–13 nach dem Seminarplan WiSe 2026/27
03-lernspiele.qmd        Lernspiele (Memory, Aussagen zuordnen)
04-lernkontrolle.qmd     Lernkontrolle
interactions/            die drei Lernspiele als HTML-Dateien
images/                  Abbildungen
fonts/                   Schrift Outfit (OTH), lokal eingebunden
include/                 Technik: Höhe der Lernspiele, aufklappbare Theorien
_quarto.yml              Einstellungen (Titel, Navigation links, Fußzeile)
styles.scss              Layout im OTH-Design
apa.csl                  Zitierstil
docs/                    fertige Webseite (wird automatisch erzeugt, nicht von Hand ändern)
```

Welche Seiten gebaut werden, steht in `_quarto.yml` unter `render:`.

## Neue Seite hinzufügen

Neue `.qmd`-Datei anlegen (z. B. `grundlagen/02-....qmd`) und in `_quarto.yml` unter `sidebar: contents:` an der gewünschten Stelle eintragen.

## Lernspiele ändern

In jeder Datei unter `interactions/` steht oben ein Block `DATEN`. Nur dort Begriffe, Aussagen oder Fragen ändern; der Rest ist Technik.

## Webseite aktualisieren

1. `.qmd`-Datei in RStudio bearbeiten und speichern.
2. Im Reiter *Terminal*: `quarto render`
3. In GitHub Desktop: kurze Notiz eintragen, **Commit to main**, dann **Push origin**.

Nach ein bis zwei Minuten ist die Webseite aktualisiert (im Browser mit Strg+F5 neu laden).
