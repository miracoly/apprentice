# Become a better Programmer
## Prinzipien
- Felder wenn möglich immer final
- nie StringBuilder und StringBuffer
- typisierte Parameter verwenden: anstatt int oder String -> z.B. Obj. Pos übergeben bzw. von funktion zurückgeben
- Unterscheidung: Daten-Objekte, statische funktionale Klassen
- Vererbung
    - Nie verwenden, stattdessen Composition (feld mit entsprechendem Objekt)
    - wenn doch, dann nur eine Ebene tief und nur aus sehr guten Gründen
- Mutation von Listen
    - list.add nur auf einer Ebene -> nie liste in weitere funktion übergeben und dann verändern
    - stattdessen liste aus mehreren teillisten zusammensetzen
        - so können auf mehrere kleine funktionen verwendet werden
- Lombok um Code kürzer zu machen
    - @EqualsAndHashCode verwenden
    -@AllArgsConstructor(access = AccessLevel.PRIVATE) verwenden
- Daten-Objekte: z.B. Point mit feldern x und y
    - Felder
        - immer final
        - können public sein, da sie eh final sind
    - Objekt wird einmal erzeugt und nicht mehr geändert
- Funktionale Klassen
    - sollten statisch und final sein
    - Construktor private -> keine Instanziierung
    - alle Methoden statisch und funktional
- Construktor
    - sollte private sein
    - sollte nie mehr machen als automatisch generierter Construktor / Standard-Construktor
    - für alles andere statische Faktory Methoden verwenden
        - diese haben beschreibenden Namen
        - geben ein erzeugtes Objekt zurück
        - 'from' im Namen macht Sinn

## Programmiersprachen
### Für mindestens einen Tag anschauen und die Vorteile erkennen
- [x] lisp
- [ ] prolog
- [ ] rlang
- [ ] python
- [ ] lua
- [ ] haskel
- [ ] elm
- [ ] skala
- [ ] bootstrap

## Libraries
- VAVR: functional library


