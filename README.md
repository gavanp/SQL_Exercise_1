Ausgangslage:
-	In der Tabelle dbo.MissingDates sind Daten (Spalten CalDate und WasMissing) vom 1.1.2020 bis zum 31.12.2025.
-	Leider gibt es Lücken. Wieviele fehlen?
Aufgaben:
-	Die Lücken müssen aufgefüllt werden.
-	Nun sind Samstage und Sonntage nicht von Bedeutung und müssen gelöscht werden.
-	TSQL-Scripts/Statements zeigen.

Hinweis:
-	In der SQL 2022 Version (16.x) gibt es eine Table Valued Function (TVF) GENERATE_SERIES. Die vorliegende Version auf dem ABSBE4058 ist aber eine 19er (15.x).
 
Ich habe in der DB eine entsprechende Funktion dbo.GetNums abgelegt, die funktioniert gleich.
-	Spielplatz ist hier also der Server ABSBE4058, die Instanz SQLEXPRESS und die DB SQLTests.
