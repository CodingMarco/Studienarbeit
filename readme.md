# Studienarbeit Marco von Rosenberg
Titel: Spatio-Temporal Predictions am Beispiel von Geschwindigkeitskontrollen

## Beispielvorhersage
![Beispielvorhersage](/content/images/Gefahrenstufen.png?raw=true "Beispielvorhersage")

![Precision-Recall-Kurve](/content/images/prc_ugs.jpeg?raw=true "Precision-Recall-Kurve")

## Abstract
Spatio-temporal predictions have gained more and more popularity over the last few years.
Spatio-temporal neural networks have been used for many different applications,
including precipation forecasting, traffic forecasting or crime prediction.
In this work, the spatio-temporal model ConvLSTM is applied to the prediction of speed camera locations.
The model is trained and tested on a dataset covering seven years of reported speed camera locations in Germany.
To be able to apply ConvLSTM, the raw locations are rasterized and a heatmap is generated for each day.
The model then predicts, based on the preceeding 16 days, the heatmap of the following day.
It is concluded that spatio-temporal neuronal networks are indeed applicable to the prediciton of speed camera locations, since the resulting predictions largely match the ground truth.
Since the predictions match the actual ground truth significantly better than another random day of the same day of week, it can also be concluded that the data contains certain patterns by which the speed camera locations on a given day depend on those of the preceeding 16 days.
Moreover it is confirmed that the model is able to learn these patterns.

## Kurzfassung
Räumlich-zeitliche Vorhersagen haben in den letzten Jahren deutlich an Popularität zugenommen.
Räumlich-zeitliche neuronale Netze wurden in der Vergangenheit erfolgreich auf verschiedene räumlich-zeitliche Aufgabenstellungen angewendet, wie z. B. die Vorhersage von Niederschlägen, Verkehrsaufkommen oder Verbrechen.
In dieser Arbeit wird das räumlich-zeitliche Modell ConvLSTM auf die Vorhersage von mobilen Radarkontrollen angewendet.
Das Modell wird mit einem Datensatz trainiert und evaluiert, der die in einer App gemeldeten Standorte von mobilen Radarkontrollen der letzten sieben Jahre in ganz Deutschland enthält.
Um ConvLSTM auf den Datensatz anwenden zu können, werden die Standorte zunächst rasterisiert und somit wird eine Heatmap für jeden Tag erstellt.
Das Modell sagt dann anhand von 16 Tagen als Eingabe die Heatmap des 17. Tages voraus.
Es ist festzustellen, dass räumlich-zeitliche neuronale Netze tatsächlich auf die Vorhersage von mobilen Radarkontrollen anwendbar ist, da die Vorhersagen größtenteils mit der Grundwahrheit übereinstimmen.
Da die Vorhersagen deutlich besser mit der Grundwahrheit des tatsächlichen Zieltages übereinstimmen als mit der eines zufälligen anderen Tages vom selben Wochentag, kann auch festgestellt werden, dass die Daten bestimmte Muster enthalten, durch die die Standorte von mobilen Radarkontrollen an einem bestimmten Tag von denen der letzten 16 Tage abhängen.
Zudem ist bestätigt, dass das vorgestellte Modell diese Muster erlernen kann.
