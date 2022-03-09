# **Preverjanje veljavnosti vozila**

## **Opis storitve**
Ob vnosu registracijske številke vozila, sistem preveri, ali se vozilo nahaja v bazi registriranih vozil. V primeru, da vozilo nima veljavne registracije,
se nakup e-vinjete zavrne, v nasprotnem primeru pa postopek teče dalje.

## **DDD diagram**
![DDD preverjanje veljavnosti vozila](https://user-images.githubusercontent.com/33865439/157536287-089ab3c7-22c3-4f05-88f5-d4c392f88d26.png)


## **Funkcionalne zahteve**

| Funkcionalne zahteve  | Nefunkcionalne zahteve |
| ------------- | ------------- |
| Vnos registrke številke vozila  | Preverjanje formata podatkov |
| Iskanje vozila v bazi registriranih vozil  | Iskanje se izvede v roku 1 minute  |
| Potrditev ali zavrnitev nakupa  |  Obvestilo se izpiše v roku 5s  |
