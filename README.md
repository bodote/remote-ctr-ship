# Status
- enthält bereits eine Loesung zur Aufgabe des Kapitels 4 aus dem Buch `Test-Driven Java Development
Second Edition`
- Allerdings ist das Projekt umgebaut auf 
  - maven statt gradle
  - lombok ergänzt
  - slf4j-api und slf4j-simple ergänzt
  - weitere dependencies ergänzt (AssertJ, Mockito,..)
  - versionsmäßig insgesamt auf neuerem Stand 

# Mögliche Zusatzaufgabe:
- finde mind. eine Luecke in der Testabdeckung
- verwendet dazu pitest.org
  - baue pitest - maven plugin in die pom.xml ein 
  - lasse `pitest` laufen und finde die Stellen, die laut pitest trotz pitests mutationen keine "roten" test ergeben. 
    - Hinweis: Besonders verdächtig sind die Stellen die in Verbindung mit Fallunterscheidungen stehen!
  - schließe die Lücke(n)
  - beachte, dass das pitest-plugin für maven auch noch das pitest-junit5-plugin in version 0.14 benötigt wird.
