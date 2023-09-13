# Einleitung
## Problemstellung
## Ausgangssituation
## Ziele der Arbeit
## Geplante Durchführung

### Energieeinsparungsmaßnahmen
### PoC über eine statistische Versuchsplanung
    Testprogramm
    Via-Punkte identifiziert
    Freiheitsgrade definiert
    Versuchsplan über Gelenkwinkelvariation erstellt
    Datenanalyse → Gelenkwinkel Identifizierung

# Stand der Technik/ Literaturüberblick
  


# Mechanische Modellbildung
## Starrkörpermodell
### Vorwärtskinematik
### Geschwindigkeitskinematik 
## Inverse Dynamik


# Bahnplanung 

# Bahnoptimierung
## Problemstellung
## Optimierungsparameter
## Kostenfunktion
## Nebenbedingungen
#### Kollisionsvermeidung (inverse Kinematik → Gelenkwinkelgrenzen)
#### Nebenbedingung der linearen Endeffektor-Geschwindigkeit bzw. Lastgrenzen
## Auswahl des Optimierungsalgorithmus


# Laborversuch
## Messaufbau und Steuerungsarchitektur
Messeinrichtungen
Architektur RSI
## Validierung des Modells
## Validierung der Optimierers
## Optimierungsergebnisse 
## Messergebnisse


# Bewertung
## Bewertungsmatrix
    absolute Einsparung ggü. Initial-Bahn
    Verfahr-Zeit
    Aufwand/Nutzen
    Skalierbarkeit (Austauschen der Kostenfunktion für andere Ziele z. B. Verfahr-Zeit)
## Vergleich mit proprietären Werkzeugen 
    Process Simulate
    KUKA energy saving
    
# Ausblick
## Anwendung
### Potenzial-Bewertung
    gewichtete Entscheidungsmatrix
        Energieverbrauch 
        Lastspitzen (Bahn tracken) Lastspitzen einfärben
        Kollisionsgefahr/ Größe des kartesischen Optimierungsraums
        Generalisierungspotenzial (wie viele Roboter vom selben Typ, Häufigkeit der Programmnutzung)

## Ansätze zur Verbesserung
### Modell
#### Gewichtsausgleich berücksichtigen
#### Elektrische Komponenten modellieren
### Bahnplanung
#### Approximation der Bahn mithilfe von B-Splines Gleeson.2016
### Modellierung
#### Absicherung des feasible-Sets gegen Kollisionsgefahr
### Methode
#### Automatisierte Optimierung
    Bedingung Syntax/Programmnotation (ECS)
