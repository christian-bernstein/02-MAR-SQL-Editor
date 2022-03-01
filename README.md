# 02-MAR-SQL-Editor

In dieser Stunde soll der SQL-Editor getestet werden. Link zum Editor [hier](www.christian-bernstein.de). Der SQL-Editor ist eine Website, auf der man seine eigenen Datenbanken erstellen und verwalten kann. Ziel der Stunde ist es, den Editor zu testen und mir ein Feedback zu den einzelnen Funktionen zu geben. 

## Aufgabenüberblick
1. Erstelle ein Benutzerkonto
2. Melde dich danach im Editor an
3. Erstelle ein neues, leeres Projekt
4. Schreibe SQL (Optionale Aufgabenstellung unter Punkt *SQL Aufgabe*)
5. **Feedback:** Mach dir Notizen zur Benutzbarkeit und Funktionalität des SQL-Editors. Schreibe dir auch auf, welche Fehler du gefunden hast.
6. **Verbesserung:** Überlege dir welche Funktion/en du dir für den SQL-Editor noch wünschen würdest. *(Es dürfen auch gerne größere Dinge sein)*. Notiere dir am besten, wie die Funktionen funktionieren sollten und mache, wenn möglich, eine kleine Skizze. 

## SQL Aufgabe
Du möchtest für ein Autohaus eine Datenbank anlegen, mit der die Mitarbeiter einen besseren Überblick über die Autos bekommen, die zurzeit verkauft werden. Es soll durch deine Datenbank für die Verkäufer einfacher werden, die Autos zu finden, die den Wünschen der Kunden entsprechen *(zb. nur dunkelgraue Autos, Kilometerstand nicht über 10.000 Kilometer, mindestens 75 PS und Erstzulassung nach 2020)*.

1. Überlege dir, welche Attribute eine Tabelle haben sollte, die die Autos des Autohauses speichert. (Siehe *Kunde sucht Auto*)
2. Erstelle deine Tabelle in der Datenbank, indem du ein passendes **SQL-Kommando** schreibst und ausführst.
3. Überlege dir mindestens 7 Beispielautos, und speierere diese in die Tabelle
4. Stelle dir vor, ein Kunde sucht ein Auto. Schau, ob sich für den Kunden ein Auto in deiner Tabelle mit Beispielautos bedindet. (Siehe *Kunde sucht Auto*). Schreibe dazu mit den gegeben Kriterien **SQL-Abfragen**

## Kunde sucht Auto
6 verschiedene Kunden suchen jeweils ein Auto, jeder Kunde hat verschiedene Vorstellungen & Wünsche, hier eine Auflistung der Vorstellungen eines jeden Kunden.
1. `Nur dunkelgraue Autos`, `Kilometerstand nicht über 10.000 Kilometer`, `mindestens 75 PS` und `Erstzulassung nach 2020`
2. `Nur Autos von BMW oder Volkswagen`, `Kilometerstand nicht über 25.000 Kilometer`, `mindestens 100 PS` und `Erstzulassung nach 2018`
3. `Preis bis 12.000 EU`, `4 Türen`, `4 Sitzplätze` und `Schaltgetriebe`
4. `Nur Dieselbetrieben`, `mindestens 100 PS`, `Preis bis 13.500 EU` und `nur Automatik`
5. `Schadstoffklasse Euro6` und `Kilometerstand nicht über 50.000 Kilometer`
6. `Schadstoffklasse ab Euro5` und `Verbrauch (kombiniert) nicht über 4,6l/100km`

## SQL in a nutshell
https://www.w3schools.com/sql/
