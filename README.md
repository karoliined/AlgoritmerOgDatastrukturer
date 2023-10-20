# Obligatorisk oppgave 3 i Algoritmer og Datastrukturer

Denne oppgaven er en innlevering i Algoritmer og Datastrukturer. 
Oppgaven er levert av følgende student:
* Karoline Dahl, S359106, s359106@oslomet.no


# Oppgavebeskrivelse

**Oppgave 1:**
Metoden legger inn verdier i treet, med referanser til barn og forelder.
Jeg brukte programkode 5.2.3 a) fra kompendiet, og skrev inn q så den nye noden får riktig forelder.

**Oppgave 2:**
Metoden returnerer antall forekomster av verdi, og 0 hvis verdi ikke finnes i treet.
Jeg har brukt koden fra oppgave 2 i avsnitt 5.2.6 i kompendiet.
Den bruker en while-løkke for å sammenligne verdiene i treet, og teller samtidig.

**Oppgave 3:**
FørstePostorden finner første node i postorden. Jeg brukte deler av  programkode 5.1.7 h), og endret så den returnerer noden og ikke verdien til noden.

NestePostorden skal finne den neste noden i postorden. Det har jeg løst ved å returnere neste i postorden hvis noden er ulike steder i treet, ved hjelp av if-setninger. For å finne neste node til et venstre barn med søsken så har jeg brukt en hjelpevariabel og en while-løkke.

**Oppgave 4:**
Jeg har brukt deler av koden fra oppgave 1 fra avsnitt 5.1.15 i kompendiet, og endret litt så det passer oppgaveteksten.
Metoden postorden finner først den første noden i postorden ved hjelp av en while-løkke. Deretter finner den alle de resterende nodene i postorden ved hjelp av nestePostorden-metoden. Verdiene brukes til å utføre oppgaven.

Metoden postordenRecursive bruker et rekursivt kall for å traversere treet i postorden rekkefølge. Her har jeg brukt kode fra oppgave 7 i avsnitt 5.1.7 i kompendiet. 


