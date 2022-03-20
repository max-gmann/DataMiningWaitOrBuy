# Flugpreis Vorhersage - Kaufen oder Warten?
### Projektarbeit Data Mining WS 2021/22 - Gruppe G: Max Grundmann s0559326 
---
### Inhalte
- [Aufgabenstellung](#aufgabenstellung)
- [Verwendete Bibliotheken](#verwendete-bibliotheken)
- [Aufbau des Repositories](#aufbau-des-repositories)
- [Ergebnisse](#ergebnisse)
---
### Aufgabenstellung
> Worum geht es in Ihrem Problem? Wie würden Sie ein Modell einsetzen? Wie würden Sie grundsätzlich die Güte eines Modells messen? <br><br>
Deskriptive Analyse der Daten: Was beschreiben die Daten, was sind die Datentypen und Wertebereiche, fehlen Daten, gibt es falsche Werte, gibt es Korrelationen zwischen Merkmalen (Features, Spalten)? <br><br> Benutzen Sie Visualisierungen, wenn es sinnvoll erscheint. Was können wir aus dieser deskriptiven Analyse über das Problem lernen?
Definieren Sie geeignete Merkmale (Features) für die Klassifikation/Regression/Clustering. <br><br>
Jede*r in der Gruppe soll ein Verfahren für Klassifikation/Regression/Clustering anwenden (insgesamt mindestens zwei pro Gruppe). <br><br>
Im Fall von Regression/Klassifikation: Benutzen Sie Kreuzvalidierung, um die Hyperparameter zu optimieren und die Qualität der Modelle zu evaluieren (wählen Sie sinnvolle Maße für die Qualität)  <br><br>
Im Fall von Clustering: Optimieren Sie die Hyperparameter und evaluieren Sie die Qualität der Clusteringmodelle<br><br>
Vergleichen Sie die Ergebnisse der verschiedenen Verfahren
---
## Verwendete Bibliotheken
- pandas
- keras / tensorflow
- sklearn
- xgboost
- matplotlib
---
## Aufbau des Repositories

- Data: enthält die Ausgangsdaten und die bearbeiteten Daten
- Models: enthält die finalen Machine Learning Modelle
- Notebooks: enthält vier Notebooks für die Schritte EDA, Datenvorbereitung, Model Training und Auswertung.
- Predictions: enthält die Vorhersagen für den Testdatensatz als .csv Dateien.
- Ressources: enthält die Präsentationsunterlagen sowie Screenshots von verschiedenen Graphen
---
## Ergebnisse
Als Modelle wurden je ein Random Forest Classifier sowie ein Neuronales Netzwerk trainiert. Beide erreichen eine Test-Genaugkeit von 92-93%.
Darüber hinaus wurde ein monetäres Gütemaß angewendet:
- Ground Truth: 1.388.860.66€
- Random Forest v4: 1.279.392.33€
- Neural Net v5: 1.244.365.11€ <br>

Hierbei zeigt sich, dass der Random Forest Classifier leicht bessere Ergebnisse liefert.
