# Arduino-ESP32
Un cronometru 00-99 realizat cu Arduino/ESP32 și un display cu 7 segmente (2 cifre), folosind tehnica de multiplexare


Cronometru 00-99 cu Display 7 Segmente

Acest proiect conține codul sursă (C++/Arduino) pentru un numărător care crește de la 00 la 99, actualizându-se o dată pe secundă.

Cum funcționează:
Codul folosește tehnica de multiplexare. Deoarece un display cu 2 cifre are pinii segmentelor (A-G) comuni, codul aprinde rapid doar prima cifră (unitățile) timp de 10 milisecunde, apoi o stinge și o aprinde pe a doua (zecile) pentru alte 10 milisecunde. Această alternanță se face atât de repede încât ochiul uman percepe ambele cifre ca fiind aprinse simultan.

Componente necesare:

O placă de dezvoltare compatibilă Arduino (ex: ESP32, judecând după numărul pinilor).

Un display cu 7 segmente și 2 cifre (Catod sau Anod comun).

Rezistențe pentru protecția ledurilor.

Fire de conexiune.
