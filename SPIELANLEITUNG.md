# SONG GUESS v3.2 — Spielanleitung & How-to

## Was ist Song Guess?
Song Guess ist ein privates, browserbasiertes Musikquiz, das Spotify als Player nutzt. Es ist für iPhone, iPad und Desktop gestaltet. Die Musik bleibt bis zum Reveal anonym; danach werden Songdaten und optional Nerdwissen angezeigt.

## Schnellstart
1. Song Guess im Browser öffnen.
2. Einmal „Mit Spotify verbinden“ wählen.
3. „Neues Spiel“ öffnen.
4. Spieler:innen eintragen.
5. Einen oder mehrere Songpools wählen.
6. Fragen auswählen.
7. Antwortmodus, Songanzahl und Standard-Ausschnitt festlegen.
8. Spiel starten.

## Songpools
Pools können kombiniert werden. Ein Song, der in mehreren Pools vorkommt, landet trotzdem nur einmal im Lostopf.

- Meine Mischung — quer durch die Jahrzehnte, Schwerpunkt ab den 1950ern.
- Guilty Pleasures DE / NL / FR — kuratierte, von regionalen Guilty-Pleasures-Ausgaben inspirierte Auswahl.
- Film & TV — Songs mit Film-/Serienbezug.
- Rock.
- Urban / Hip-Hop.
- Französisch.
- Deutschsprachig.

Die Datenstruktur ist offen für weitere Pools.

## Fragen
- Jahr: exakt = 3 Punkte, ±1 Jahr = 2, ±3 Jahre = 1.
- Jahrzehnt.
- Interpret / Act.
- Titel.
- Herkunft des Acts.
- Film / Serie — nur wenn für den Song eine passende Information vorhanden ist.
- Älter / Jünger — zwei anonyme Songs werden verglichen.

„Eine zufällige“ zieht pro Song eine Frage aus dem gewählten Fragenpool.
„Alle ausgewählten“ fragt mehrere Kategorien zum selben Song ab.
„Pro Runde“ erlaubt, den Fragenpool vor jeder Runde neu festzulegen.

## Antwortmodus
Nacheinander: Eine Person ist pro Runde dran.
Alle gleichzeitig: Alle raten denselben Song und werden nach dem Reveal einzeln gewertet.

Es gibt bewusst kein Texteingabefeld: Antworten werden laut gesagt oder für sich notiert. Nach dem Reveal wird nur die Punktezahl angetippt.

## Musiksteuerung
Bei jeder Runde kann spontan gewechselt werden:
- Ganz — Song ab Anfang.
- 30 s Start — 30 Sekunden ab Beginn.
- 30 s Zufall — zufälliger 30-Sekunden-Ausschnitt.

Play/Pause funktioniert auch im A/B-Vergleich. Wird B gestartet, stoppt A. „Restart“ spielt denselben Ausschnitt erneut; „Überspringen“ zieht ohne Wertung einen anderen Song.

## Reveal
Der Reveal zeigt Titel, Interpret, Jahr, Herkunft, Jahrzehnt, Genre und — sofern vorhanden — Album, Sprache und Film-/Serienbezug.

„In Spotify öffnen“ führt direkt zum Song.

### 🧠 Mehr zum Song
Der aufklappbare Nerdbereich kann enthalten:
- Entstehungs- oder Popkultur-Fact.
- Cover → Original mit Spotify-Link.
- Sample → Samplequelle mit Spotify-Link.
- „Wurde gesampelt in …“.
- musikalische Verwandtschaft / Inspiration.

Nicht jeder Song hat schon alle Nerdfelder; die Bibliothek kann schrittweise angereichert werden.

## Favoriten
Nach dem Reveal kann ein Song lokal als Favorit markiert werden. Favoriten werden ausschließlich im Browser des jeweiligen Geräts gespeichert.

## Historie & Scores
Beides ist im Setup separat abschaltbar.

Spielhistorie speichert lokal: Datum, Spieler:innen, Pools, Kategorien, Songanzahl und Endstand.
Dauerhafte Scores speichern lokal: Spiele, Siege und Gesamtpunkte pro Name.

Diese Daten werden nicht zu GitHub oder Spotify hochgeladen. Andere Geräte sehen sie nicht.

Optional können Songs aus den letzten drei gespeicherten Spielen vermieden werden.

## Überraschungsmix
„Überraschungsmix“ bereitet ein schnelles Spiel mit gemischten Fragen vor. Namen kurz prüfen und losspielen.

## Datenschutz
Die GitHub-Seite ist öffentlich. Deshalb enthält der Quellcode keine privaten Spielernamen mehr. Die Spotify Client-ID ist eine öffentliche App-Kennung und kein Passwort. Ein Spotify Client Secret gehört niemals in die Website.

Spielernamen, Historie, Favoriten und Scores liegen lokal im Browser (localStorage).

## Geräte
Das Layout ist touchfreundlich und responsive:
- iPhone: einspaltige Spielansicht und große Touchflächen.
- iPad: breitere Zwei-Spalten-Ansicht, wenn Platz vorhanden ist.
- Desktop: ebenfalls spielbar.

Wenn der Browser es unterstützt, versucht Song Guess während einer Partie den Bildschirm wach zu halten.

## Songbibliothek
Version 3.2 enthält 281 Songs. Der Schwerpunkt liegt von den 1950ern bis heute, mit einigen älteren Klassikern. Die Bibliothek ist als kuratierter Start gedacht und kann auf mehrere hundert Songs wachsen.

## Wichtig zu Spotify
Song Guess nutzt Spotify für die Wiedergabe. Die App steht derzeit im Spotify Development Mode. Daher können nicht automatisch beliebige Spotify-Accounts die App autorisieren; freigegebene Testnutzer:innen funktionieren.

## Gute erste Partie
Für drei Personen:
- Pool: Meine Mischung
- Fragen: Jahr + Interpret + Herkunft + Titel + Älter/Jünger
- Fragen je Song: Eine zufällige
- Antwortmodus: Alle gleichzeitig
- 15 Songs
- Ausschnitt: 30 s Zufall

Danach Nerdwissen aufklappen, wenn ein Song interessant ist. Das Spiel darf ausdrücklich beim Musikwissen-Abbiegen entgleisen. :)


## Anleitung im Frontend
Die vollständige Kurz-Spielanleitung ist jetzt direkt über den `?`-Button oben in Song Guess erreichbar.
