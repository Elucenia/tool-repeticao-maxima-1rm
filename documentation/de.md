<!-- ELUCENIA technical documentation · repeticao-maxima-1rm · de · no clinical/professional/rights approval -->

# Geschätztes 1RM (Epley und Brzycki)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/repeticao-maxima-1rm)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Gehobenes Gewicht

`carga`

kg · Bereich: 1–500

### Vollständige Wiederholungen bis zum Muskelversagen

`reps`

Bereich: 1–15

## Fassung der Methode

Epley Last×(1+Wdh/30) und Brzycki 1993 Last×36/(37−Wdh); lokaler Mittelwert; 1 Wdh=Last

## Dokumentierte Formel

Epley: 1RM = Last × (1 + Wiederholungen/30).

Brzycki: 1RM = Last × 36 ÷ (37 − Wiederholungen).

Das Hauptergebnis ist der Mittelwert beider. Bei 1 Wiederholung ist die Last das 1RM.

## Grenzen und Population

Das 1RM ist eine Schätzung aus der Last in kg und vollständigen Wiederholungen bis zur Ermüdung, kein gemessenes Maximum. LeSuer 1997 untersuchte 67 untrainierte Studierende nach Eingewöhnung beim Bankdrücken, Kniebeugen und Kreuzheben mit Sätzen von höchstens 10 Wiederholungen. Die Oberfläche erlaubt bis zu 15, doch diese Studie stützt keine Extrapolation auf 11–15. Der Fehler variierte je nach Übung. Der Epley–Brzycki-Mittelwert ist eine lokale Entscheidung, keine in dieser Studie validierte kombinierte Gleichung; das Ergebnis garantiert keine sichere Maximallast.

## Referenzen

- [Brzycki M. Strength testing: predicting a one-rep max from reps-to-fatigue. J Phys Educ Recreat Dance, 1993.](https://doi.org/10.1080/07303084.1993.10606684)

- [LeSuer DA et al. The accuracy of prediction equations for estimating 1-RM performance in the bench press, squat, and deadlift. J Strength Cond Res, 1997.](https://doi.org/10.1519/00124278-199711000-00001)

- [LeSuer1997,JStrengthCondRes11(4):211–213](https://paulogentil.com/pdf/The%20Accuracy%20of%20Prediction%20Equations%20for%20Estimating%201-RM%20Performance%20in%20the%20Bench%20Press,%20Squat,%20and%20Deadlift.pdf)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
