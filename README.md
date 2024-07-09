Hallo, dies sind einige Sachen, die ich programmiert habe.
Für meine C#-Projekte ist eine ausführbare Datei im Projektordner.


Hier werde ich nun die Dateien kurz beschreiben:

-Whitenoise:
Whitenoise ist ein Programm welches auf einem Fenster zufällig gefärbte Rechtecke mit 5*5 Pixel Größe platziert.
Es ist ein Vorgänger für einen geplanten zufälligen Bildgenerator inspiriert von KI basierter Bildgeneration.

-TESTPROJ:
Ein Test, um zu sehen, in wie fern ich fähig bin in Winforms ein Spiel zu programmieren.
Der Code ist verbesserungsbedürftig und enthält noch keine Kommentierung.
Den Meisten Code habe ich in meiner Freizeit während der Schule geschrieben.
Das Spielfeld nimmt Inspiration aus den Schachbrettern in meinen Webanwendungen.
Prinzip des Spiels ist es möglichst viele Level zu schaffen und seinen Score zu erhöhen, indem man alle Gegner auf dem Spielfeld besiegt.
Normale Gegner bewegen sich zufällig in eine der vier Richtungen.
Jede fünf Level kommt ein Boss, welcher den Spieler verfolgt, mehrere Leben hat und auch schießen kann.
Die Level werden immer schwieriger mit erhöhter Geschwindigkeit, mehr Gegnern und stärkeren Bossen.
Der Spieler, welcher oben links erscheint, hat eine Vielzahl von Steuerungsmöglichkeiten:
Pfeiltasten: Lassen den Spieler in die entsprechende Richtung laufen.
Taste Q: Schießt ein Projektil, welches bei dem Aufprall mit einem Gegner diesem Schaden zufügt. Die Projektile sind auf 3 begrenzt und werden mit der Zeit nachgeladen. Diese Projektile erhöhen den Score um 30, wenn sie einen normalen Gegner vernichten. 
Taste W: Ein Durchschuss-Projektil, welches nicht mit dem Aufprall gelöscht wird. Von diesen Projektilen kann nur eins gleichzeitig auf dem Fenster sein und wird mit dem erzeugen eines neuen gelöscht. Bei Treffer erhöht sich der Score um 10 plus die Anzahl an vorher getroffener Gegner mit dem gleichen Projektil. Projektile werden immer aus der Richtung geschossen, in die der Spieler Schaut.
Taste E: Eine temporäre Unverwundbarkeit (zu sehen durch die hellblaue Farbe) gefolgt von einer Abklingzeit (zu sehen durch die gelbe Farbe). Während der Unverwundbarkeit kann einen der Boss noch mit Kontakt angreifen.
Taste R: Vier pinke Rechtecke erscheinen um den Spieler, welche Gegner treffen und nach kurzer Zeit wieder verschwinden. Pro Gegner wird der Score um 15 erhöht.
Taste TAB und T: Drehen den Spieler entweder im oder gegen den Uhrzeigersinn.
Dieses Projekt gab mir einen guten Eindruck, wozu ich fähig bin. In Zukunft möchte ich mir das Programmieren in Unity aneignen.

-8damenproblem:
Diese Webanwendung repräsentiert das Damenproblem (https://de.wikipedia.org/wiki/Damenproblem). Es gilt 8 Damen auf ein Schachbrett zu platzieren, ohne dass diese sich gegenseitig in den weg der jeweiligen Laufbahnen kommen.
Oben gibt es einen Knopf zum Neustarten, wenn man etwas falsch platziert hat. Sobald 8 Damen in einer der richtigen Weisen auf dem Spielbrett platziert wurden, wird eine Siegesnachricht erzeug.
Fast alles auf der Seite wird programmatisch erzeugt. Dies war eine Zusatzaufgabe meiner Lehrkraft im Unterricht Internetanwendungen während der Mittelstufe.

-Schach:
Eine Webanwendung, auf der sich Schach spielen lässt. Geschrieben habe ich den Code während eines Vierwöchigen Praktikums. Der Code ist schon etwas älter und wurde fortwährend verbessert. Bekannte Fehlerquellen sind auf der Seite gelistet. Ansonsten ist das Spiel vollkommen funktionstüchtig. Ich konnte hier auf viele kreative Wege lernen logische Dinge in JavaScript umzusetzen.
