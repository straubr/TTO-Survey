# Survey Module #

Durch dieses Paket wird dem Survey Modul ein zusätzlicher Fragetyp hinzugefügt. Er besteht aus einer  
Sterne-Skala (5 Sterne) und jeweils einer Beschreibung zu beiden Seiten der Skala.  

Da im OTRS-Standard die Auswertung durch einen Count pro Antwort erfolgt, wird in diesem Fragetyp  
automatisch fünf Antworten erstellt. Jede Antwort entspricht dabei dem prozentualen Wert (0%, 25%, 50%, 75%, 100%).  

Eine Frage von diesem neuen Typ ist komplett sobald genau zwei Beschreibungen (links + rechts) der Skala  
eingestellt wurden. Änderungen an diesem Fragetyp überschreiben nur die Antworten 1 + 5. Beim Löschen  
einer dieser Antworten werden automatisch alle Antworten gelöscht.  

Dieses Paket enthält:  
*   Drei angepasste Templates (jeweils Perl + .tt)  
    Edit  
    Zoom  
    Public  
* Eine .css Datei für die Darstellung  

  