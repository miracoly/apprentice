# Apprentice Guide

## Katas

Katas sind Übungsaufgaben, die man alleine, zu zweit oder im Team löst, wobei der Lernerfolg aller Beteiligten im Vordergrund steht. Am Ende eine funktionierende, allgemeine Lösung zu haben, ist eher nebensächlich.

### Warum schreibst du Katas?

Worauf es beim Lösen der Katas ankommt:
- Es geht um den Prozess/die Methode und weniger darum schwierige Katas zu lösen
- TDD (Testdriven Development)
  - Incrementelles arbeiten (kleine Tests, schnelle Iterationen)
  - Katas oft wiederholen, ggf. mit anderem Pairing Partner, anderem Ansatz oder anderer Sprache
- Shortcuts/Umgang mit der IDE lernen
- 4 Rules of Simple Design (Kent Beck)
- Clean Code/Refactoring
	- Code ist lesbar, Variablen- und Methoden-Namen sind eindeutig und hilfreich
	- Code ist nicht zu aufgeblasen (kleine Teilprobleme kann man auch klein lösen)
	- Dublikate auslagern

Mit der Zeit verinnerlichen sich diese Punkte und werden automatisch. Der Apprentice braucht nicht mehr über die Ausführung nachdenken, sondern kann sich voll und ganz auf das eigentliche Problem konzentrieren.

### Deine ersten Katas

Für den Anfang mache folgende Katas in dieser Reihenfolge:
1. FizzBuzz
2. Tennis
3. Xmas Tree / Christmas Tree
4. PrimeFactors
5. RomanNumerals
6. MarsRover
7. GOL - Game of Life

[Weitere Katas](https://codewars.com) findest du auf codewars.


Mögliche Constraints sind:
	- nur Immutables verwenden
	- keine Schleifen
	- Methoden mit begrenzter Einrückungstiefe
	- keine Rekursion
	- Laufzeitbegrenzungen
	- keine Maus verwenden
	- IntelliJ im Presentation Mode verwenden (und dadurch mehr Shortcuts nutzen = schneller werden)
[mehr Constraints](https://gist.github.com/asierba/5028e63991ce787fe383)


### Wie schreibst du deine Katas

Schreibe immer zuerst einen Test. Implementiere danach nur so viel, dass dieser Test läuft. Nutze 'Fake it till you make it'.
Wenn dein Test läuft, und nur dann, kannst du deinen Code refactoren. Nutze dafür kleine, incrementelle Schritte. Verbessere nur eine Punkt und führe die Tests erneut aus. Sofern alle Tests laufen, kannst du den nächsten Punkt refactoren, bis du mit deinem Code zufrieden bist.

Schreibe nun den nächsten Test und wieder hole die beschriebenen Ablauf, bis alle Testfälle abgedeckt sind.

Beim Refactoring kannst du:
- Variablen extrahieren
- Methoden extrahieren
- aussagekräftige Namen vergeben
- komplexe Konzepte simpler herunterbrechen
- Klassen erstellen
- u.v.m.

Pairing kann so ablaufen:
	- Programmieren zu zweit (z.B. Peter und Lisa), Peter hat Maus und Tastatur (Driver), Lisa sagt ihm was er schreiben soll (Navigator)
		- Lisa beschreibt einen Test
		- Die Rollen tauschen (Lisa schreibt)
		- Peter beschreibt eine Implementierung, die diesen (und alle bisherigen) Tests löst
		- Falls nötig/gewünscht, schlägt Peter Refactorings vor
		- Peter beschreibt einen neuen Test
		- Die Rollen tauschen (Peter schreibt)
		- Lisa löst den Test (und alle bisherigen)
		- Lisa schlägt ggf. Refactorings vor
		- Wiederholung von vorne
	- eine Sequenz von Test lösen, ggf. refactoren, neuen Test schreiben sollte 2-3 Minuten gehen. Danach Wechsel der Rollen.
	- Die Anweisungen des Navigators passen zu den Fähigkeiten des Drivers
		- Wenn der Driver die Sprache gut kennt, reichen grobe Anweisungen "erstelle ein String Array der Größe 1 mit dem Eintrag foo"
		- Wenn nicht, können die Anweisungen auch ganz detailiert sein, z.B. "schreibe String eckige Klammern words gleich new String eckige Klammern geschwungene Klammern und in Anführungszeichen foo"



### Nach dem Kata

Nach dem du ein Kata geschrieben hast, schreibe es nochmal. Dass muss **nicht** sofort im Anschluss erfolgen und auch nicht am selben Tag. Es ist gewollt, ein Kata viele Male zu machen und jedesmal einen Aspekt zu verbessern. Das kann sein, mehr Shortcuts zu verwenden, bessere Tests zu schreiben oder das Kata unter 'Constains' zu schreiben.

### Review
Wenn du mit der Art und weise, wie du dein Kata geschrieben hast, zu frieden bist, tu folgendes: Schreibe es nochmal :), aber nimm es auf. Erstelle also einen Screencast davon. Hier sollten keine großen Pausen mehr entstehen. Zeige deinen Screencast deinem Introducer, Mentor oder einem anderen erfahrenen Entwickler. Bitte ihn respektvoll um Verbesserungsvorschläge und
