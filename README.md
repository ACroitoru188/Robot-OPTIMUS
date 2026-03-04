Acest proiect are ca scop proiectarea si implementarea unui robot mobil autonom, capabil sa se activeze prin lumina, sa urmeze un traseu predefinit si sa revina la punctul initial.

Proiectul a fost realizat de la zero si a implicat planificarea arhitecturii, selectarea componentelor hardware, realizarea conexiunilor electrice si dezvoltarea codului necesar pentru controlul robotului.

Functionalitati principale

- Activare prin lumina

Robotul ramane nemiscat intr-o cutie si este activat atunci cand detecteaza o sursa de lumina (de exemplu o lanterna), folosind senzori LDR.

- Navigatie autonoma pe traseu

Dupa activare, robotul urmareste un traseu predefinit folosind senzori cu infrarosu. Traseul este compus dintr-o linie si o bucla, permitand revenirea automata la punctul de pornire.

- Revenire in cutie

Robotul poate fi ghidat din nou cu ajutorul luminii pentru a intra inapoi in cutia de stationare.

- Evitarea obstacolelor (functie dezvoltata, neintegrata)

A fost realizat un modul software pentru evitarea obstacolelor, folosind un senzor ultrasonic, destinat ghidarii robotului la iesirea din cutie. Aceasta functionalitate nu este inca integrata in fluxul principal de navigatie.

Modul de functionare:

1. Robotul stationeaza initial in cutie
2. Detecteaza o sursa de lumina si se activeaza
3. Urmareste traseul folosind senzorii IR
4. Parcurge bucla si revine la punctul initial
5. Este ghidat prin lumina pentru a reveni in cutie
