[Engleska verzija](README.md).

Uvod
============
Semafor za vozila je učilo za programiranje mikropravljača Arduino Uno.
![Shield application](images/traffic_lights_vehicle.jpg)


Autori
------------
- Robert Sedak — svojstva, prilagodba za Arduino, dizajn el. scheme, CAD dizajn.


Application
-----------
Robert Sedak je snimio video s primjerom programiranim u Arduino IDE:

[![Shield application](images/default.png)](https://youtu.be/m3OTxSKJVn8 "Semafor za vozila - primjer programiranja")




Primjere za Arduino IDE možete preuzati [ovdje](examples/).


Popis komponenti
-----------------
- 1 kom, PCB
- 3 kom, 330 ohm 1/4W 1% otpornik(R1, R2, R3)
- 1 kom, LED 3mm - crvena (D1)
- 1 kom, LED 3mm - žuta (D2)
- 1 kom, LED 3mm - zelena (D3)
- 1 kom, 1x4Pin 2.54mm desni kut Pin Header - crni


Datoteke s dizajnom
------------
Ovaj semafor je dizajniran pomoću programa [KiCad](http://kicad.org/). Datoteke se nalaze u mapi [design_files](design_files/). Elekroničku schemu možete pogledati [ovdje](images/traffic_lights_vehicle_schematic.png).


Gerber datoteke
------------
Gerber datoteke možete preuzeti [ovdje](gerber/traffic_lights_vehicle.zip).


Firmware
--------
Ovo učilo može biti progrmairano pomoću [Arduino IDE](https://www.arduino.cc/).
Primjer za Arduino IDS se nalazi u mapi [examples](examples/).


Licenca
-------
[Imenovanje-Dijeli pod istim uvjetima 4.0 međunarodna (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.hr)

Slobodno možete:
- Dijelite dalje — možete umnažati i redistribuirati materijal u bilo kojem mediju ili formatu
-  Stvarajte prerade — možete remiksirati, mijenjati i prerađivati djelo u bilo koju svrhu, pa i komercijalnu

Davatelj licence ne može opozvati slobode korištenja koje Vam je ponudio dokle god se pridržavate uvjeta licence.

Pod sljedećim uvjetima:
- Imenovanje — Morate adekvatno navesti autora, uvrstiti link na licencu i naznačiti eventualne izmjene. Možete to učiniti na bilo koji razuman način, ali ne smijete sugerirati da davatelj licence izravno podupire Vas ili Vaše korištenje djela.
- Dijeli pod istim uvjetima — Ako remiksirate, mijenjate ili prerađujete materijal, Vaše prerade morate distribuirati pod istom licencom pod kojom je bio izvornik.

Bez daljnjih ograničenja — Ne smijete dodavati pravne uvjete ili tehnološke mjere zaštite koji će druge pravno ograničiti da čine ono što im licenca dopušta.

Odricanje od odgovornosti
-------------------------
NAPOMENA - Dizajn je objavljen u dobroj namjeri i "takav kakav je" ("AS IS"), te sa mogućim greškama. Autor je kreirao učilo, slike, video i programski kod. Autoru je radilo i uspjelo raditi na način kako je opisano, što ne znaći da će raditi i Vama. Ne odgovaram ni za kakve posljedice koje mogu nastati prilikom korištenja učila, uputa ili programskog koda. Odričem se sve odgovorosti i jamstva- sami ste odgovorni za ono što radite i sami ste odgovorni što ste pristali pratiti i koristiti naše upute i informacije.

Autor može mijenjati specifikacije i opise proizvoda u bilo kojem trenutku, bez prethodne obavijesti. Korisnik se ne smije osloniti na odsutnost ili karakteristike bilo kojih značajki ili uputa označenih kao "rezervirano" ili "nedefinirano".
Autor zadržava pravo budućih izmjena definicija i neće snositi nikakvu odgovornost za sukobe ili nekompatibilnosti koje proizlaze iz budućih promjena. Podaci o proizvodu na web stranici ili materijalima podložni su promjenama bez prethodne obavijesti. Nemojte finalizirati dizajn s ovim podacima.