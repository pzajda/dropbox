# dropbox #

* Authors: Patrick ZAJDA <patrick@zajda.fr>, Filaos and other contributors
* Preuzmite [Stabilnu inačicu][1]

Ovaj će dodatak dodati prečac koji izgovara status dropboxa, inačicu ili ili
otvara dropboxov izbornik u području obavijesti.  Također možete se
premještati po stranicama / karticama dijaloškog okvira koristeći
ctrl+tab/ctrl+shift+tab i/ili ctrl+pgdn /ctrl+pgup.  Kako bi zaključili,
ovaj dodatak omogućuje da gumb odustani, radi na pritisak tipke escape.

* Shortcut: NVDA+Alt+D
* Ctrl+Alt+T Izgovori aktivnu karticu svojstva.

## Poznati problemi ##

* Ako se prebacujete između kartica svojstava koristeći prečac, kada zatvorite dijaloški okvir, NVDA dobiva krivu informaciju o otvorenim prozorima.
It is a known issue on NVDA and cannot be fixed.


## Izmjene u inačici 4.0 ##

* Add-on help is available from the Add-ons Manager.
* The shortcut to get Dropbox status has been changed to Alt+NVDA+D to avoid
  conflict with audio ducking support.

## izmjene u inačici 3.1 ##

* Koristi drugi način kako bi došao do gumba odustani i do kartice
  svojstva. više ih ne treba fokusirati prije koristeći prečace.
* Kad mijenjate trenutno aktivnu karticu svojstva, fokus ese premješta na
  slijedeću karticu svojstva tako da kada pritisnete tab, prva stavka na
  kartici svojstva je aktivirana umjesto da stoji na prijašnje korištenoj
  kartici svojstva čak iako više nije aktivirana.
* Iz dijaloškog okvira postavki, moguće je pritisnuti control+page up/down
  kako bi ste se prebacivali između kartica svojstava. Control+tab i
  control+shift+tab još uvijek rade.
* Sve lokalizirane manifest datoteke sada trebaju biti u redu.
* Male ispravke.

## promjene u inačici 3.0 ##

* Male ispravke u glavnoj manifest datoteci (autori su ispravno prikazani).
* Unaprjeđeno otkrivanje kontekstnih izbornika kada se pritišće Shift+NVDA+D
  tri puta.
* Tipka escape sada radi (samo kada se dropbox koristi na istom jeziku koji
  koristi NVDA NVDA).
* Puno ispravki u kodu.
* Dodana/osvježena dokumentacija svih skripti.
* Novi jezici: Arapski, Brazilski portugalski, Češki, Nizozemski, Finski,
  Galicijski, Njemački, Mađarski, Japanski, Nepalski, Poljski, Ruski,
  Španjolski, Slovački, Tamilski, Turski.

## Promjene u inačici 2.0 ##

* Novi jezik: Talijanski
* Kada se pritišće prečac u kontekstnom izborniku tri puta više ne stvara
  problem

## Promjene u inačici 1.0 ##

* Prva inačica

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=dx