# Cestninski sistem **E-vinjete**

## Kaj je **E-vinjeta**? 
E-vinjeta je sodoben način plačevanja cestnine za motorna vozila z največjo dovoljeno maso do 3500 kilogramov. Osnovne značilnosti e-vinjete se od klasične vinjete v obliki nalepke bistveno ne razlikujejo. To pomeni, da si tudi z nakupom e-vinjete zagotovite pravico do uporabe vseh avtocest in hitrih cest v Republiki Sloveniji za čas veljavnosti e-vinjete in torej ne gre za cestninjenje po prevoženi razdalji.
E-vinjeta je vezana na registrsko označbo vozila. Ob nakupu morate zato navesti pravilno registrsko oznako in državo registracije vozila ter izbrati e-vinjeto za pravilen cestninski razred. Če se registrska oznaka v sistemu e-vinjete ne ujema z registrsko oznako vozila, ki uporablja avtocesto ali hitro cesto, to pomeni, da cestnina ni plačana. Za pravilnost vnosa registrske oznake in izbiro cestninskega razreda je odgovorna stranka.

## Vrste, cestninski razredi in cene e-vinjet
* **Cestninski razred 1:** V prvi cestninski razred se uvrščajo enosledna motorna vozila (npr. motorna kolesa). To so vsa vozila, katerih sled ni širša od 50 centimetrov. Meritev sledi lahko opravite s tračnim ali krojaškim metrom, in sicer od enega do drugega zunanjega roba sledi.  
* **Cestninski razred 2A:** V cestninski razred 2A sodijo vozila z največjo dovoljeno maso do 3500 kilogramov, katerih višina nad prvo osjo ne presega 1,3 metra (večina osebnih avtomobilov, enoprostorcev, terenskih vozil, SUV in t. i. pick-upov)
* **Cestninski razred 2B:** V cestninski razred 2B se uvrščajo vozila z največjo dovoljeno maso do 3500 kilogramov, katerih višina nad prvo osjo presega 1,3 metra (večina kombiniranih in lahkih dostavnih vozil).

## Mikrostoritve
| Funkcionalne zahteve  | Nefunkcionalne zahteve |
| ------------- | ------------- |
| [Naročanje vinjete](https://github.com/KitekMaja/ITA_naloga1/tree/main/microservices/ordering)  | Naročilo mora biti obravnavano v roku 10 minut  |
| [Preverjanje veljavnosti vozila](https://www.google.com "Microservice-check-registration")  | Veljavnost vozila moramo preveriti v roku 10 sekund  |
| [Pošiljanje potrditvenega sporočila](https://www.google.com "Microservice-send-confirmation-mail")  | Potrditveno sporočilo mora biti poslano v roku ene minute  |
