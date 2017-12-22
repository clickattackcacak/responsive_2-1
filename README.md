# responsiveSmallMedium

Ovaj projekat predstavlja malu modifikaciju [OVOG](https://github.com/clickattackcacak/responsiveFull) projekta.

Razlika se odnosi na raspored blokova u okviru .posts sekcije.

Za tablet layout, dodaj je stil:

.post:nth-child(3n+3) { flex: auto; }

...čime se selektuje svaki treći element. Njemu se 'poništava' flex vrednost, da bi prešao u sledeći red. 

![Alt text](screenshots/medium.png?raw=true "Medium layout")

Za desktop layout, dodat je stil:

#posts-container .post { flex: 1 1 30%;}

... Pri čemu 30% predstavlja širinu svakog bloka. Zahvaljujući tome, u svakom redu će se naći tri bloka.

![Alt text](screenshots/large.png?raw=true "Medium layout")

