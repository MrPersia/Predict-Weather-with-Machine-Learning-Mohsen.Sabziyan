# Global Temperature Prediction

Dieses Projekt beschäftigt sich mit der Vorhersage der globalen Durchschnittstemperatur unter Verwendung von maschinellem Lernen. Es verwendet historische Temperaturdaten, um Modelle zu trainieren und Vorhersagen über zukünftige Temperaturen zu treffen.

## Daten

Die Daten stammen aus der Datei `GlobalTemperatures.csv`, die historische Temperaturmessungen enthält. Der Datensatz enthält die folgenden Spalten:

- `dt`: Datum
- `LandAverageTemperature`: Durchschnittstemperatur auf Landebene
- `LandMaxTemperature`: Maximaltemperatur auf Landebene
- `LandMinTemperature`: Minimaltemperatur auf Landebene
- `LandAndOceanAverageTemperature`: Durchschnittstemperatur auf Land- und Ozeanebene

## Vorverarbeitung

Die Daten werden vor dem Training der Modelle vorverarbeitet, indem fehlende Werte behandelt und die Temperaturskala von Celsius in Fahrenheit umgerechnet wird.

## Modelle

Es werden drei verschiedene Modelle für die Vorhersage verwendet:

1. **RandomForestRegressor**: Ein Ensemble-Modell basierend auf Entscheidungsbäumen.
2. **LinearRegression**: Ein lineares Regressionsmodell.
3. **SVR (Support Vector Regressor)**: Ein Regressionsmodell basierend auf Support-Vektoren.

## Dateien im Repository

- `GlobalTemperatures.csv`: Die Rohdaten.
- `temperature_prediction.ipynb`: Ein Jupyter Notebook, das den Code zur Vorverarbeitung der Daten und zum Training der Modelle enthält.
- `README.md`: Diese Datei, die eine Beschreibung des Projekts enthält.
