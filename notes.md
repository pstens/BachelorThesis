# Notizen 

*“Mobile Bildbearbeitung als Ansatz für die effiziente Aufmaßerfassung im Gerüstbau”*

- **VOB/C - Gerüstarbeiten (TODO: make bibtex)**
  - Abrechnungseinheiten (S 75)
    - Längenmaße (m)
    - Flächenmaße (m^2)
    - Raummaße (m^3)
    - Anzahl (Stück)
  - Leistungsverzeichnis-Muster (S 77)
  - Auftraggeber kann Gütenachweis für Gerüste verlangen (30 0.2.12)
    - Art & Umfang müssen unmissverständlich beschrieben sein
  - Abrechnung nach bestimmten Zeichnungen oder Tabellen (31 0.2.21)
    - Es muss vorher fesgelegt werden, auf welchen Ursprung die Abrechnung zugrunde liegt
  - Abrechnungseinheiten im Leistungsverzeichnis sind nach *ATV DIN 18451, Abschnitt 0.5* anzugeben
  - Bearbeitete Bilder sollten aktualisierbar sein (118 5.1/2)
  - Vorgefertigte Gerüsttypen sollten auswählbar sein (118 5.1/5)
  - Entscheidener Maßstab ist die **eingerüstete Fläche**, und nicht die alleinige Größe der Gerüsts (119 5.1.1)
    - Ausnahme bei Gitterträgern, Überbrückungen, Schutzgerüsten, Wetterschutzdächern, Auflagegerüsten und
    Gerüstbekleidungen -> Hierbei gelten die Gerüstaußenkanten als Aufmaßgrundlage
    - eingerüstete Fläche = die zu bearbeitenden Flächen und diese, die dafür notwendig sind (119/120)
  - Unterscheidung nach Voll- und Teileinrüstung (121 2)
  

### Usability
  
- threshold für diverse touch aktionen sehr wichtig, da nur wenig Platz verfügbar (rausfinden durch tests?)
- undo/redo essentiell, da Fehler toleriert, und nicht bestraft werden sollen (Minimierung der Gedächtnisbelastung, da man nicht alles von vorne malen muss)
- Lupe für Bereich unter Finger, da man sonst nicht sieht, wo man gerade malt (widerspricht WHAT YOU SEE IS WHAT YOU GET)
- Intuitive Icon für diverse Aktionen (redo, undo, color, delete) um Applikation intuitiv benutzbar zu machen
- Schwierigere Aktionen (add label, resize point) durch geführtes Overlay beim ersten Start verdeutlichen
- alle configuration changes sollten supported werden, damit der Nutzer das Gerät auch kippen kann
- welche Kombination von modes is am besten für den User? (Dragging & Drawing gleichzeitig, oder getrennt?!)
- Cropping & Resizing beim Importieren/Foto machen sollte dem Benutzer helfen, bereits vorher den gewünschten Bereich auszuwählen
- Statebar am unteren Rand der App, um zwischen Modi zu wechseln und den aktiven Modus zu sehen
- Delete button in toolbar anstatt ans shape, weil sonst unabsichtliches löschen beim resizen


### Feedback

18.12
- threshold fürs resizing muss aufjedenfall noch größer
- aktiver state nicht erkennbar -> muss gemerkt werden, da keine interaktiven Bilder
- text besser direkt auf die Kanten, und nicht daneben, weil sonst schwer zuordbar

