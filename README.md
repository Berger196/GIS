# EP 1
## Beispiel 1 Choroplethenkarten
Monitoring soziale Stadtentwicklung 

Choroplethenkarten (Flächendichtekarten) stellen statistische Werte flächenbezogen dar und machen räumliche Unterschiede auf einen Blick sichtbar. Die abgestufte Farbgebung ermöglicht das erkennen und Vergleichen von Gebieten mit ähnlichen Eigenschaften. Hier zeigt die Karte, wie unterschiedlich die soziale Situation innerhalb Berlins verteilt ist. 

Die Werte werden jeweils einer gesamten Fläche zugeordnet. Innerhalb eines Planungsraums können sich die sozialen Verhältnisse unterscheiden. Kleinräumige Unterschiede werden dadurch nicht sichtbar. Auch die Größe der Flächen hat Einfluss auf die visuelle Wirkung, das bedeutet: Große Planungsräume nehmen mehr Platz ein als kleine, obwohl sie nicht zwangsläufig mehr Einwohner umfassen.
![Monitoring soziale Stadtentwicklung](https://github.com/Berger196/GIS/blob/main/Karte%202025_L.%20Berger.png?raw=true)

Grundlage der Karte sind die Daten des Monitorings Soziale Stadtentwicklung Berlin 2025 der Senatsverwaltung für Stadtentwicklung, Bauen und Wohnen. Die Planungsräume wurden nach ihrer Statusklasse in vier Kategorien eingeteilt. Die insgesamt 535 Planungsräume verteilen sich auf 86 mit hohem, 356 mit mittlerem, 43 mit niedrigem und 50 mit sehr niedrigem Status.

# EP 02
## Beispiel 2 Choroplethenkarten
Lebensweltlich orientierte Räume

Choroplethenkarten hängen von der gewählten Bezugsgröße, sowie von der gewählten statistischen Klassifikationsmethode ab.
Quantile: Verteilen die Einheiten gleichmäßig auf die Klassen. Dadurch können kleine relative Unterschiede auffallen. Die räumliche Verteilung könnte etwas verzerrt wirken.
Gleiche Intervalle: Teilen den Wertebereich in gleich große Abschnitte. Dies hebt Extremwerte hervor aber führt bei einer ungleicher Datenverteilung dazu, dass viele Flächen in einer Farbklasse landen.
Jenks (Natural Breaks): Verteilt Klassen auf natürliche Gruppierungen innerhalb der Daten. Damit werden die Abweichungen innerhalb der Klassen minimiert und Unterschiede zwischen den Klassen maximiert.

![Lebensweltlich orientierte Räume](https://github.com/Berger196/GIS/blob/main/Berlin_LOR_bev19.png?raw=true)

Grundlage der Karte sind die Daten der Bevölkerungsstatistik des Amts für Statistik Berlin-Brandenburg (Stand: 01.01.2019) auf Ebene der Lebensweltlich orientierten Räume (LOR). Die Zusammenstellung vergleicht vier Karten mit einer einheitlichen fünf Kategorien zur Bevölkerungsverteilung in Berlin.
