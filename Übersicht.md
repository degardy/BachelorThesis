Ge# Titel der Arbeit
Energieeffiziente Bahnoptimierung eines Industrieroboters
a-priori Identifikation von energetische optimierten Via-Punkten zur Anpassung der Bahnplanung eines KUKA KR210 R2700-2

# Einleitung
Worum geht es in der Arbeit? (Hinführung zum Thema)
Ausgangslage, Voraussetzung, Aufgabenstellung?
Wieso ist das Projekt bedeutend? (Relevanz des Themas)
Wie ist das Projekt in der wissenschaftlichen/technischen Diskussion zu verorten?
Was sind Ihre Methoden?
Welche Ergebnisse erwarten Sie?

# Forschungskreislauf
1. Forschungsfrage (um welches Problem geht es?)
2. Forschungsstand (welche Arbeiten gab es bisher zum Thema? | Stand der Technik/ Literatur)
3. Forschungslücke (Problem Beschreibung)/Abgrenzung/Verortung im wiss. Kontext/Bedeutung
4. Methoden (wie wird das Problem untersucht?| Ansatz, Gliederung, Aufbau, Quellen)
5. Ergebnisse der eigenen Forschungsarbeit (Zielsetzung, Fragestellung)
6. Diskussion/ Ausblick (wie sind die Ergebnisse einzuordnen, welche neuen Forschungsfragen gibt es?)

# Schluss 
(soll eigenständig lesbar sein und die gesamte Arbeit in Erinnerung rufen, aber nicht ins Detail gehen, Beantwortet der Schluss die Fragen der Einleitung?)
Ergebnisse vor dem Hintergrund des Forschungsstands zusammenfassen und reflektieren
Erkenntnisse ableiten
Anwendungen aufzeigen

### Erkentnisse aus der Optimierung
- geringerer Energieverbrauch bei der Validierung für die objective Torque an Stelle der mechanischen Energie
- für realeres Optimierungsergebnis inkl. Gewichtsausgleich optimieren
- eigenartige Feststellung: Variablen für Bewegung gegen und mit der Gravitation sind identisch 

### Ausblick
- Kollisionsvermeidung
- Sensitivitätsanalyse/ Systemidentifikation


### Aufbau der Optimierung
Aufruf der Trajektorienplanung und Simulation des Energieverbrauchs innerhalb der Optimierungsschleife


# Modellierung
### Kinematisches Modell


Änderungen (-645 zu 645)
Alpha 1 = -90 statt 90 


# Optimierung 
classification
formelle Beschreibung 
Optimalitätskriterien KKT
Konvexität (konvex oder nicht konvex)

1. Definition des Versuchs
- Validierung des Optimierungsansatzes an zwei Bewegungsabläufen
- Charakteristik - gegen die Gravitation, Mit der GRavitation:  


# Todos 
 - Listing RNEA dem Anhang hinzufügen
 - Vernachlässigungen begründen
 - Auswirkunden der Vernachlässigungen
 - Vernachlässigung des GEwichtsausgleichs auf Achse 2 beschreiben
 - Berechnugsergebnisse
 - Trägheitsensor <- Massenträgehitsmoment
 - Körper -> Verbindungsglied
-  Systemparameter Anhang
- setcounter Anhang

## Modell
- Matlab Prüfung rec, rae
- LaTex konstante Parameter und dazugehörige KSYS kennzeichnen
- LaTex Formelzeichen in Verzeichnis
- Vernachlässigungen Statorgewicht, Schlauchpaket, Rotor Drehmoment aus Massenträgheit
- Unterscheidugn joint vel. acc. und link vel. acc.
- Startbedingung Kaft und Drehmoment vom Endeffektor auf 6 

## Optimierer
## Trajektorie
Soll Bewegung zwischen Start und Zielpunkt mit Berücksichtigung des Via-Punkts
Bewegungsart PTP
Überschleifen

## Versuch
- Abbildung des Roboters 
- Testing auf der Office KRC5
