---
id: main
aliases: []
tags: []
---

Thema: You Are The Weapon

Brainstorming:

- Idle-Game: Waffe, die zwischen RUnden verbessert werden kann, aber von Randos getragen wird
- Decision-Making: Spieler steht vor der Wahl, einen Knopf zu drücken oder nicht
- Reflektion: Spieler findet erst heraus, dass er als Waffe missbraucht wurde
- Don't blow me up: Spieler ist eine Bombe, die versucht, nicht abgefeuer zu werden
- Biological: Spieler ist eine biologische Waffe, die sich weiter ausbreitet...
- Hacking: Spieler ist ein Programm/eine KI, die sich in etwas einhacken muss

Waffe als:
    - Wort -> Gegen Propaganda
    - Magie -> Gegen Schlangen/Krankheiten
    - Immunzellen -> Gegen Krankheit
    - Zensur -> Meinungsfreiheit


# Weaponized Incompetence

- Spieler bekommt Aufgaben, die er möglichst schlecht lösen muss
    - Aufgaben sollen möglichst einfach sein, Schwierigkeit besteht darin, sie nicht zu lösen

- Topdown-GBC-Style Spiel im Office
    - Möglichst viele Aufgaben nicht annehmen oder schlecht machen

- Aufgaben:
    - Akten sortieren
    - Stempel aufsetzen
    - Kaffee machen
    - Dinge von A nach B bringen
    - PC hochfahren

- Andere Idee:
    - PC-Oberfläche, aber vollkommen anders als erwartet
    - Einfache Aufgaben müssen erfüllt werden, gestalten sich aber als zunehmend schwieriger
        - Inhärente Logik, allerdings nicht offensichtlich

- Aufgaben
    - KI begleitet und gibt Anweisungen
    - PC hochfahren
    - Einloggen
        - Benutzername ist gegeben
        - Keyboard-Layout it Rot13
        - Einloggen-Button weicht aus
    - Während Ladescreen
        - "Waht are you doing?"
        - "You need to..."
        - Ladebalken muss manuell gezogen werden
            - Oder Ladeanimation manuell gedreht?
    - Desktop sieht wie alte Windows-Oberfläche aus
        - Icons weichen aus?
            - Müssen "angefüttert" werden
        - Icons keine gute Ikonographie
        - Sprache ist anders
        - Was passiert beim Drücken auf den Start-Button?
            - Nur Symbol, das Konfetti verteilt
        - Was passiert mit der Uhr?
            - Uhr zählt langsam einen Countdown herunter
        - Gibt es Tray-Programme?
    - Sprache ändern?
    - Tastaturlayout ändern?
    - Mailprogramm öffnen
        - Mails abrufen
        - Mail schreiben
        - Anhang herunterladen und speichern
        - Anhang wiederfinden
        - Mail verschicken
    - Programme wieder schließen
    - Einen Text kopieren und speichern
    - Eine Datei ausdrucken
    - Das Internet öffnen
    - Eine Datei löschen
    - Eine Datei kopieren
    - Archiv entpacken
    - Virenscan durchführen
    - Betriebssystem updaten
    - Sprache einstellen
    - PC ausschalten


# Zensurspiel

- Spieler erhält Artikel, in denen er bestimmte Informationen zensieren oder nicht zensieren kann
- Er erhält zunehmend schwierigere Aufgaben, bestimmte Informationen zu zensieren
- Die Art der Zensur hat Auswirkungen auf den weiteren Verlauf des Spieles
- Je nachdem, welche Informationen bei der Öffentlichkeit ankommen, wird Auswirkungen auf die Folgeartikel haben

Kategorien:
    - Krankheitesausbruch
    - Wissenschaftlicher Fortschritt
    - Andere Länder
    - Kunst
    - Bildung
    - Naturkatastrophen
    - Wirtschaftskatasrophen

Spielablauf:
    - Stapel von Artikeln auf der einen Seite
    - Einer kann durch Anklicken ausgewählt werden
    - Fenster mit Artikel öffnet sich
    - Spieler kann mit Maus Teile des Artikels zensieren
    - Zensuren lassen sich nicht rückgängig machen
    - Ist ein Wort zensiert, wird es herausgenommen
    - Suche nach Schlüsselworten ergibt Punktzahl sowie weiteres Vorgehen

Umsetzung:
    - Zunächst:
        - Wörter werden als einzelne Buttons/Label gedruckt, bei Klick auf sie werden sie zensiert
    - Ggf.:
        - Manuelle Zensur mit Image-Overlay über RichText möglich
        - Am Ende werden Wortposition relevanter Wörter aus Richtext ausgelesen
        - Die Positionen werdne mit Schwärzungen im Image verglichen
        - Ist ein Prozentsatz über dem Wort geschwärzt, gilt es als zensiert

Ende:
    - Zunehmende Katastrophen sowie ein totalitärer Staat
    - Fangen und Töten des Spielers
