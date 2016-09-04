Struktur der DVD:

"> literature" : In der Diplomarbeit verwiesene Literatur.
"> latex" : Latexdateien der Diplomarbeit
"> data" : Kleiner Ausschnitt aus den Daten, für die Graphen in der Diplomarbeit verwendet
"> AgentConfiguration" : Konfigurationsprogramm für das AgentSimulator Programm
"> AgentSimulator" : Simulationsprogramm, wird vom Konfigurationsprogramm aufgerufen

Anzumerken ist, dass AgentConfiguration die Konfigurationsdateien im aktuellen Verzeichnis erstellt und eine Datei "AgentSimulator.jar" im Unterverzeichnis "dist" erwartet. Setzt man für AgentConfiguration das Arbeitsverzeichnis auf "\AgentSimulator", kann bequem die jeweils aktuelle Version von AgentSimulator gestartet werden. Ansonsten empfiehlt sich eine Änderung von joschka.java von AgentConfiguration (Zeile 133ff).

Für eine Übertragung zu JoSchKa muss nach "Package" das erstellte Verzeichnis auf den aifbceres Server geladen werden und anschliessend die erstellte joschka Batchdatei mittels des JoSchKa Job Managers hochgeladen werden. Damit kann man mit sehr wenigen Tastendrücken neue Jobs erstellen.

