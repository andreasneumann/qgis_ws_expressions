# QGIS Workshop Expressions und Geometriegeneratoren

## Dynamische Planlayouts

1. Erstellen sie ein neues leeres oder öffnen Sie ein bestehendes QGIS-Projekt. Stellen Sie sicher, dass im
   Menü "Projekt" --> "Projekteigenschaften" --> Reiter "Allgemein" --> "Projekttitel" ein Wert abgefüllt ist.

2. Importieren Sie das Layout-Template "Planlayout_Dynamisch.qpt" aus dem Github Repo. Menü "Projekt" --> "Layout-Verwaltung"
   --> "Neu aus Vorlage" --> "Bestimmtes" --> ".qpt-Datei auswählen" --> "Knopf Erzeugen" --> "Neuen Name für Layout eingeben"

3. Nach dem Import werden im Layout folgende neue Variablen erstellt, da diese im Template-File mitkommen.
   Diese können im "Layout" im Panel "Layout" --> ganz runter scrollen --> Sektion "Variablen":
   * "layout_rand" (mm): 10
   * "layout_plankopfhoehe" (mm): 36
   * "abteilung": Abteilungname
   * "amt": Amtsname
   * "direktion": Direktionsname
   * "adresse": Strasse + Hausnr
   * "plz_ort": PLZ + Ort

4. Sehen Sie sich die einzelnen Layout-Objekte an (gegebenenfalls im "Elemente"-Bedienfeld das "Schloss öffnen"
   um Elemente editierbar zu machen) und sehen Sie die Formeln in der Sektion "Position und Grösse" an. Dazu verwenden Sie
   die Knöpfe "Datendefinierte Übersteuerung".

5. Ein Rechts-Klick im Layout öffnet das Kontextmenü. Wir möchten darüber die "Seiteneigenschaften" ändern. Wir wechseln
   entweder die Orientierung oder die Seitengrösse. Das Seitenlayout sollte sich dynamisch anpassen.
