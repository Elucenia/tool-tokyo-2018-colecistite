<!-- ELUCENIA technical documentation · tokyo-2018-colecistite · de · no clinical/professional/rights approval -->

# Schweregrad der akuten Cholezystitis (Tokyo 2018)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/tokyo-2018-colecistite)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Grad III · Kardiovaskulär: Hypotonie mit Dopamin ≥ 5 µg/kg/min oder Noradrenalin in beliebiger Dosis

`cardio`

### Grad III · Neurologisch: verminderte Bewusstseinslage

`neuro`

### Grad III · Respiratorisch: PaO₂/FiO₂ \< 300

`resp`

### Grad III · Renal: Oligurie oder Kreatinin \> 2,0 mg/dL

`renal`

### Grad III · Hepatisch: INR \> 1,5

`hepat`

### Grad III · Hämatologisch: Thrombozyten \< 100.000/mm³

`hemato`

### Grad II · Leukozyten \> 18.000/mm³

`leuco`

### Grad II · Tastbare druckschmerzhafte Raumforderung im rechten Oberbauch

`massa`

### Grad II · Symptome seit mehr als 72 Stunden

`tempo`

### Grad II · Ausgeprägte lokale Entzündung (Gangrän, pericholezystischer oder hepatischer Abszess, biliäre Peritonitis, emphysematöse Cholezystitis)

`local`

## Fassung der Methode

Tokyo Guidelines 2018/Yokoe (TG13-Kriterien beibehalten): Schweregrad I–III; jede der 6 Organdysfunktionen definiert III; ohne diese definiert jedes der 4 mittelschweren Kriterien II

## Dokumentierte Formel

Grad III (schwer): jede aufgeführte Organdysfunktion.

Grad II (mittelschwer): keine Organdysfunktion des Grades III und eines der vier Kriterien für Grad II: Leukozyten \> 18.000/mm³; tastbare schmerzhafte Raumforderung im rechten Oberbauch; Beschwerden seit mehr als 72 Stunden; oder ausgeprägte lokale Entzündung.

Grad I (leicht): Cholezystitis bei einem Patienten ohne Kriterien für Grad II oder III.

## Grenzen und Population

TG18/TG13 behält die früheren Diagnose- und Schweregradkriterien bei. Die Klassifikation erfordert deren vollständige klinische und Laborbegriffsdefinitionen; das Managementdokument hat zusätzliche Bedingungen und muss getrennt berücksichtigt werden, ohne das Vorgehen allein aus der Kategorie abzuleiten. In Tabelle 7 der TG18 erfordert Grad II eines der vier aufgeführten Kriterien, sofern keine Dysfunktion des Grades III vorliegt; er ist nicht auf ausgeprägte lokale Entzündung beschränkt. Diese Prüfung testet bereits markierte Befunde bei zuvor diagnostizierter Cholezystitis. Sie prüft weder die klinische Zuordnung der Befunde noch Laborgrenzwerte, diagnostische Voraussetzungen oder das Vorgehen.

## Referenzen

- [Yokoe M et al. Tokyo Guidelines 2018: diagnostic criteria and severity grading of acute cholecystitis (with videos). J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.515)

- [Okamoto K et al. Tokyo Guidelines 2018: flowchart for the management of acute cholecystitis. J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.516)

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
