## Aufgabe 1

erreiche im Spiel 10000 Paperclips: 

Manipuliere den Localstorage





## Aufgabe 2
Öffne die Datei fill_localstorage.html - welcher Fehler wird in der Konsole ausgegeben bei vollem Speicher.
Klicke so oft wie du kannst auf den Button bei unterschiedlichen Browsern gibt es unterschiedliche Speicherkapazitäten.

## Aufgabe 3
Eigene Programm mit Localstorage set...

In Angular gibt es eine app.component,clicker, game-window, in der dann der clicker und die power-bonus komopnent nagezeit wird. Außerdem gibt es eine shell/naviagtion bei der man zum game-window oder zur upgrade-list wechseln kann.Die Upgrade-list hat upgrade-list-item

- Localstorage -> Speichert aktuellen Klicker Count
    - Button - Konvertiere 100 Klicks zu Diamanten -> neuer Localstorage Eintrag
- Sessionstorage -> Bonus sobald man 1min online ist -> Klicker Count 2
    - Wenn 2min Online soll der Klicker Count auf 4 gehen

- Upgrades sind in der Indexed DB gespeichert
    - Zeige alle Upgrades in der Upgrade-list an
    - Admin Tab, erstellt neue Updates