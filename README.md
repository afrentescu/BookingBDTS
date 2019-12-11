# BookingBDTS
Java Spring booking platform- university project 

- Crearea coturilor in aplicatie  ( un user/accomodation owner se pot inregistra in platforma, se pot loga si deloga). Vor exista cele 3 roluri pentru utilizatori: User, Accomodation Owner, Admin. Hint: Spring Security
- Filtrari, detaliile cazarilor cu filtrari
- Adaugarea de cazari de catre accomodation owner, editarea si stergerea acetora
- Rezervarea cazarilor de catre useri pe o anumita perioada, anularea rezervarilor si notificare prin email a acestora cu o saptaman inainte de apropierea perioadei
- Obtinerea detaliilor pentru afisarea rezervarilor
- Istoricul rezervarilor pentru un user
- Administroatorul poate avea access la toate reverarile din platforma, toate cazarile si toti userii ( separati pe roluri) si ii poate sterge.
- Sectiunea de review si commentarii si de asemenea posibiliatatea de a le acorda. Aceste pot fi data de catre un user catre acomodare si de catre accommodation owner catre user. Administratorul poate sterge commentarii si review-uri
- In locul integrarii cu Google Maps care se axeaza destul de mult pe parte de frontend deoarece acolo este nevoie de afisare locatiei pe harta, as sugera generarare unor rapoarte legate de locatii pe care sa le genereze accommodation owner-ul (suggestie: highcharts api)

Structura echipei:
- 1: Partea de authenticare cu parola criptata si securitatea asupra tuturor endpointurilor cu permisiuni per rolul userului. Generarea sesiunii si utilizarea acestei a in toate requesturile
- 2 & 3: Adaugarea de cazari, editare, stergere, filtrari, rezervarea cazarilor de catre useri, anularea rezervarilor si notificare prin email si istoricul rezervarilor
- 4 & 5: Detaliile pentru afisarea rezultatealor, funtionalitatile userului, sectiunea de review, commentarii cu functionalitatile sale, integrarea cu api-ul extern si partea de forntend
