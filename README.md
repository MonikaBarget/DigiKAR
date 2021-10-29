<img src="https://github.com/ieg-dhr/DigiKAR/blob/main/DigiKAR_logo-small.png" alt="drawing" width="200" align="left"/>

# DigiKAR

## Skripte zur Bearbeitung von Ortsdaten und biographischen Angaben im DigiKAR Projekt / scripts for managing spatial and biographic data in the DigiKAR project

**1) Datenabruf aus mehreren CSV-/EXCEL-Tabellen / data retrieval from several CSV/EXCEL tables**

a) [XLSX_analysing-multiple-files.py](https://github.com/ieg-dhr/DigiKAR/blob/main/XLSX_analysing-multiple-files.py) 

b) [XLSX_multiple-files_sample-output.md](https://github.com/ieg-dhr/DigiKAR/blob/main/XLSX_multiple-files_sample-output.md)

- Identifikation von Zeitverläufen in Datensätzen / identifying chonologies in data sets
- Datenvergleich / data comparison
- Datenbereinigung und Datennormalisierung / data cleanign and data normalisation

c) *Erweiterte Skripe in Bearbeitung / advanced scripts in progress:*

- "BIOGRAPHY TRACING": select person by ID, match name variants, find all life events recorded, narrow down events by time limits if necessary, put events in chronological order
- "DISAMBIGUATION": script to compare similar names of people and places and assign unique IDs (human intervention necessary)
- "SPATIAL EVOLUTION": extracts events coinciding in specific places, reconstruct political / cultural role of places through human agency

**2) Extrahieren strukturierter Informationen aus TXT Dateien / extracting structured information from TXT files**

a) [TXT_replaceWORDwithREGEX.py](https://github.com/ieg-dhr/DigiKAR/blob/main/TXT_replaceWORDwithREGEX.py) 

- Trennzeichen nach "regular expression" in Text einfügen / adding delimiters to text based on regular expression
- Vorbereitung des Texts für Aufteilung in einzelne Abschnitte / preparing text for splitting into individual sections

b) [TXT_splitUPPERCASE.py](https://github.com/ieg-dhr/DigiKAR/blob/main/TXT_splitUPPERCASE.py)

- Identifizierung von Personeneinträgen durch Großschreibung der Namen / identifiying person entries based on uppercase characters in names

<img src="https://insulae.hypotheses.org/files/2021/10/INSULAE_featured-images_biographic-data-980x450.png" alt="drawing" width="450" align="left"/>


**Ausführliche Beschreibung des Worksflows / detailed workflow description**

Der folgenden Blogpost beschreibt die Verwendung der oben genannten Skripte im Arbeitspaket "Kurmainz": / The following blog post describes the application of the above-mentioned scripts in the "Kurmainz" work package:

[Monika Barget, "Disambiguating people and places in dirty historical data," in INSULAE, last updated 26/10/2021](https://insulae.hypotheses.org/333)



**Verantwortlich für den Inhalt / responsible for content:**

[Monika Barget](https://github.com/MonikaBarget)

*Digitale Kartenwerkstatt Altes Reich (DigiKAR) – Daten & Transfer* 

Leibniz-Institut für Europäische Geschichte (IEG) 
Alte Universitätsstraße 19 
55116 Mainz 

[DigiKAR on Twitter](https://twitter.com/digi_KAR)






