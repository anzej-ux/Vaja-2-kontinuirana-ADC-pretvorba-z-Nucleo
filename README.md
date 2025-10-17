# Vaja-2-kontinuirana-ADC-pretvorba-z-Nucleo
: S pomočjo programskega okolja STM32CubeIDE in HAL knjižnicami smo sprogramirali mikroprocesor  tako, da je izvajal neprekinjene ADC pretvorbe z izbranim potenciometrom. Takšna pretvorba je primerna za  hitro in nenehno branje vhodne vrednosti.
2) 

b) V Analog razdelku levo od sheme mikroprocesorja kliknite Analog. Koliko je vseh ADC pretvornikov? ODGOVOR:3

c) Izberite en ADC pretvornik in v njem izberite (prosti) kanal, kjer boste zajemali analogno (single-ended) 
meritev. Na oknu Pinout View se določen pin pobarva v zeleno – zapišite naslov dodeljenega pin-a ODGOVOR: PC 2(ADC3_IN3)

d) Kaj se izpiše poleg pina? ODGOVOR: ADC3_IN3

e) V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. (potrdite z ENTER) Kaj 
opazite? ODGOVOR: Nova frekvenca je vplivala na veliko drugih vrednosti npr. timer clock.

g) Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta fpreskalirana? ODGOVOR: 4MHz

i) Pravi čas vzorčenja se nato poveča še za 12 ciklov zaradi procesa samega. Koliko znaša pravi čas 
vzorčenja tvz v mikro sekundah?
(enačba: tvz = t'vz_ciklih / fpreskalriana)? ODGOVOR: 61,9uS

SLIKA PINOUT:
<img width="694" height="584" alt="image" src="https://github.com/user-attachments/assets/f89bb02b-860d-41e5-8018-1bdac4a575a0" />


POSNETEK DELOVANJA:
<img width="500" height="281" alt="image" src="https://github.com/user-attachments/assets/9ff91126-4813-413b-bcca-d6d3b86bd5b4" />

FOTOGRAFIJA IZBRANEGA POTENCIOMETRA:
<img width="3024" height="4032" alt="image" src="https://github.com/user-attachments/assets/bd04e92b-2f1d-4da1-9190-3db121ad9e5c" />





KOMENTAR: Koda deluje kot je potrebno imela sva nekaj težav s kodo ampak sva jih popravila. Debug mode je deloval zato ni bilo potrebno narediti 7. točke.
