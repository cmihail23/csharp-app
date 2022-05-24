# csharp-app


Aplicatie pentru gestionarea unei activitati de livrare Pizza, folosind c# .net WPF 
Aplicatie se conecteaza la o baza de date SQL Server

Clase folosite:
Client
Factura
Pizza

Clasele au atributele setate pe private si au proprietati cu get/set, dupa caz.
Clasele suprascriu ToString() iar Factura implementeaza CompareTo() din interfata Comparable.

Din pacate aplicatia este abia la inceput, am create 2 pagini: adauga pizza in db, pagina ce adauga o piza primita ca input in baza de date si pagina comanda noua ce reprezinta interfata grafica prin care clientul poate comanda. Aceasta pagina se leaga la baza de date prin combobox select pizza ce contine pizza din baza de date. Cand este trimisa comanda apar detaliile din baza de date in list view.

