# Song Guess v5.0.33
762 Songs. UI-, Wiedergabe- und Spielfluss-Update mit 762 Songs.

Neu u. a.:
- gleiche Frage + gleicher Song für alle, nacheinander oder gleichzeitig
- Antwortfelder / „ich sage es laut“ / Passen
- Reveal nur wenn alle geantwortet haben und der aktuelle Song tatsächlich gestartet wurde
- Reveal stoppt den Song nicht
- Bonusrunden: +3 Punkte bei perfekter Antwort
- Shuffle-Bag für Fragen (keine 3x gleiche Kategorie)
- Undo der letzten Wertung
- Spiel fortsetzen nach Reload
- Spiel-Menü, Passen vs. anderer Song
- kuratierte, musikbezogene Avatare + Farben
- Jahrzehntfilter und kuratierter Shuffle
- Eurovision, Indie 2003–2013, Alternative/Art Pop und Metal/Heavy
- Pool-Tags beim Reveal
- Favoritenpool
- kompakter A/B-Reveal
- Soundtrack der Partie + kopierbare Playlist-Liste



## Referenzpool-Update
- Bibliothek gesamt: **762 Songs**.


## v4.2 Pool work
- 📼 80s: 90 spielbare Songs aus 1980–1989.
- Älter/Jünger: dritte Antwort **GLEICHES JAHR**.



## Public Release


## v5 Änderungen
- 3-Sekunden-Challenge: Titel + Interpret nach den ersten drei Sekunden.
- Reveal wird erst nach Eingabe, Teilantwort, „Ich sage es laut“ oder „Passen“ aktiv.
- Teilantworten sind erlaubt; besonders Bonusrunden führen nicht mehr in eine Sackgasse.
- Passen wird automatisch mit 0 Punkten als vollständig gewertet.
- Perfekte Bonusrunden erhalten +3 Zusatzpunkte.
- Nach Reveal und Punktevergabe bleibt die Runde stehen. Erst „Nächste Runde“ stoppt den alten Song und erzeugt die nächste Runde.
- Endscreen-Soundtrack hat ein stabiles zweispaltiges Layout.
- Cover-Metadaten ergänzt und kleine Musikpools erweitert.

- v5 last-test: Nerdwissen ist nach jedem Reveal verfügbar; Best-of-, 50s- und Schlager-Lücken erweitert.

- v5.0.5: automatisch erzeugte Pseudo-Nerdfakten (nur Jahr/Genre/Album-Wiederholungen) entfernt. Nerdwissen zeigt nur noch kuratierte Zusatzinfos; sonst einen klaren Leerhinweis.

- v5.0.6: Versionsnummer wird auf der Startseite sichtbar angezeigt, damit ein erfolgreicher Deployment-Upload sofort erkennbar ist.

- v5.0.12: Versionsschema vereinheitlicht; ZIP-Dateiname und sichtbare Startseitenversion sind identisch.

- v5.0.17: Vollaudit: CSS-Klammer bereinigt, echte 3-Sekunden-Challenge, Resume ohne Rundensprung, Spieloptionen beim Resume erhalten und Überraschungsmix-UI synchronisiert.


## v5.0.33
- Setup: Songanzahl und Ratetimer als kompakte Auswahlfelder statt Dropdown/Freifeld.
- Rundenkopf und Typografie ruhiger; Kategorienlabel über der Frage entfernt.
- Play/Pause direkt über die Schallplatte; im A/B-Vergleich über die jeweilige Songkarte.
- Spielerkarte mit klarerem Header, Status und besseren Abständen.
- Mehr kuratierte Musik-Avatare; Fuchs bleibt enthalten.
- Reveal ist an den tatsächlich gestarteten Song der Runde gebunden.
- Nach der Wertung kann ein laufender Song gestoppt und derselbe Song weitergehört werden; bei beendetem Song verschwindet die Transportaktion.
- Cover-Fragen zeigen das Original sofort in der Lösung.
- High Hopes: Album auf Pray for the Wicked korrigiert.
- Startseite: zwei exakt gespiegelte große Discokugeln und mehrfarbige Lichtreflexe.
- Debug: Restart merkt sich im A/B-Vergleich den zuletzt aktiven Song.
- Manuelle Punktewahl zeigt nur tatsächlich mögliche Werte je Fragetyp (z. B. Interpret 0/2).
- Vergleichsrunden zeigen bei gesperrtem Reveal konkret, welcher Song noch gehört werden muss.


## v5.0.33
- Layout-Hierarchie überarbeitet: kompakter Score, klare Kopfzeile, Reveal als Hauptaktion.
- Vergleichsmodus mit zwei anklickbaren Mini-Vinyls.
- Passen funktioniert auch in Vergleichsfragen sauber; wenn alle passen, ist Anhören keine Voraussetzung.
- Jahreswertung zeigt die Punktestufen direkt an.
- Vinyl-Label: als Single markierte Releases 45 RPM, Albumtracks 33⅓ RPM; Animation bleibt bewusst langsam.
- Zusätzliche lokale Anti-Wiederholungs-Historie; übersprungene Songs werden im laufenden Spiel nicht wieder freigegeben.
- Datenkorrekturen und Konsistenzprüfung, u. a. Uptown Funk, Djadja, Royals und Sprachangaben.
