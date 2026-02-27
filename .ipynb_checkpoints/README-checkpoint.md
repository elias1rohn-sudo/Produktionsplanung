# Produktionsplanung-Lineare-Programmierung

Dieses Mini-Projekt modelliert ein Produktionsplanungsproblem als MILP.
Ziel ist die Bestimmung optimaler Produktionsmengen unter begrenzten Ressourcen. (Implementierung in Python mit PuLP)

Problem
Ein Unternehmen produziert mehrere Produkte mit begrenzten Ressourcen:
- Maschinenkapazität
- Material
- Arbeitszeit
Gesucht wird der Produktionsplan mit maximalem Gewinn.


Modell
Entscheidungsvariablen:
- Produktionsmengen xᵢ
- Binäre Startvariablen yᵢ (für die Fixkosten)

Zielfunktion:
Maximierung des Gewinns unter Berücksichtigung von Fixkosten.

Nebenbedingungen:
- Kapazitätsrestriktionen
- Ganzzahligkeit der Produktion
- Big-M-Kopplung zwischen xᵢ und yᵢ


Erweiterung
- MILP in Abhängigkeit der Maschinenkapazität
- Grafische Auswertung (Matplotlib)