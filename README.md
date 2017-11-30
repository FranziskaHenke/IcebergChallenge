# Iceberg Challenge

[Iceberg Challenge Kaggle Link](https://www.kaggle.com/c/statoil-iceberg-classifier-challenge)

## Grober Zeitplan:
- Woche 
   - 48 
      - Planung, Datensatz analysieren, Architekturen recherchieren, 
   - 49 
      - Architektur entscheiden
      - vorläufiges System aufsetzen (Server)
   - 50 
      - Server klar machen
      - Implementieren
   - 51 
      - Implementieren
      - Ende der der Woche: AWS testlauf
    Feiertage => erste Resultate
   - 1  
      - verbessern/Optimieren
   - 2  
      - verbessern/Optimieren
    
    
## Arbeitsform: 
   - Zuerst über GitHub Code implementieren; erst zum Ende hin auf Server migrieren, falls Datenlast/ Rechenlast (wohl eher) sonst zu groß
   -  Bei den Übungen treffen und besprechen
    5.12. Architektur entscheiden und ob mit oder ohne geglättetes Datensatz. Bitte alle da sein!! ;P können dann ja auch nochmal mit Voigt besprechen, ob unsere Überlegungen sinnvoll sind.
    

## Aktuelle ToDos:
   - [ ] Daten einlesen
   - [ ] sinnvolle Architektur recherchieren
   - [ ] Datensatz analysieren (Franzi)
   - [x] Git Repository erstellen (Franzi)
   - [ ] Auf welcher Hardware lassen wir das Netzwerk laufen?
   - [ ] z.B. Server für 5€ kaufen? https://www.digitalocean.com/pricing/ (Alex)
   - [ ] HTW Admins fragen (Lotta)


## Inhaltliche Fragen:
   - Sollen wir mit dem flattened Datensatz arbeiten? Wenn wir ein convolutional neuronal network aufbauen wollen und Filter verwenden, wäre doch ein nicht-flattened Datensatz sinnvoll, oder?
   - Brauchen wir wirklich einen GPU-fähigen Server? Der Trainingsdatensatz ist kleienr 50 Mb. 
   - Wann wollen wir wie Visualisieren? z.B. alle Ergebnisse der Filter?
    
    
## Mögliche Optimierungen:
   - Regularisierung
   - Data Augmentation
   - Aktivierungsfunktion ReLu
   - Dropout
   - Lernrate
   - Rate Adaption
   - Momentum
   - Softmax