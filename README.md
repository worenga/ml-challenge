# ml-challenge
Einreichung für die it-talents.de/ZF IT Code-Competition September 2018 ("[Machine Leaning](https://www.it-talents.de/foerderung/code-competition/code-competition-09-2018)"). Ein Deep Neural Network Model zur Prädiktion der Unfallschwere

# Kurzbeschreibung
In Lösung wird versucht das beschriebene Problem mit einem Feed-Forward neuronalen Netz zu modellieren.
Wir untersuchen zunächst den bereitgestellten Datensatz und bereiten die Daten auf. 
Anschliessend extrahieren wir weitere Features durch die Gruppierung ähnlichen Zeilen.
Wir unterteilen die Trainingsdaten in das eigentliche Trainingsset und Validierungsset ein.
Zuletzt definieren und wir ein neuronales Netz mithilfe von pytorch und trainieren es auf den Trainingsdaten.

# Abgabeartefakte 
Die Lösung ist als [Jupyter Notebook](./FNN_Model.ipynb) verfasst (Python Kernel).

Die Klassifizierung der Testdaten ist [hier](./output/classified-testdata.csv) zu finden.


# Installationsvorraussetzungen

Falls das Jupyter Notebook local ausgeführt werden soll müssen die folgenden Softwarepakete installiert sein

 * jupyter notebook
 * pytorch
 * pandas
 * matplotlib
 * numpy
 * scikit-learn
 * [sklearn-pandas](https://github.com/scikit-learn-contrib/sklearn-pandas)
 * [pandas-summary](https://github.com/mouradmourafiq/pandas-summary)
