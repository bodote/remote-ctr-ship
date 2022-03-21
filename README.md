# Status
- enthält bereits eine Loesung aus dem Buch `Test-Driven Java Development
Second Edition`
- Allerdings ist das Projekt umgebaut auf 
  - maven statt gradle
  - lombok ergänzt
  - slf4j-api und slf4j-simple ergänzt
  - weitere dependencies ergänzt (AssertJ, Mockito,..)

# Mögliche Zusatzaufgabe:
- finde Luecken in der Testabdeckung
- verwendet dazu pitest.org
  - baue pitest - maven plugin in die pom.xml ein 
  - lasse pitest laufen und finde die Stellen die laut pitest trotz pitests mutation keine "roten" test ergeben
  - schließe die Lue~~~~cken