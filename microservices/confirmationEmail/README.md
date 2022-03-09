# **Pošiljanje potrditvenega sporočila**

## **Opis storitve**
Ko uporabnik uspešno vpiše vse potrebne osebne podatke in podatke o vozilu, mu sistem pošlje potrditveno sporočilo, ki hkrati vsebuje tudi povezavo do varnega spletnega plačila.

## **DDD diagram**
![DDD pošiljanje potdritvenega sporočila](https://user-images.githubusercontent.com/33865439/157537420-b8ce1265-ae7c-4e4d-8cf5-f1b3b1b583c9.png)

## **Funkcionalne zahteve**

| Funkcionalne zahteve  | Nefunkcionalne zahteve |
| ------------- | ------------- |
| Generiranje povezave za plačilo  | Generirana povezava poteče po 5 minutah  |
| Sestavljanje potrditvenega sporočila  | Sestavljanje sporočila se izvede v 60 s  |
| Pošiljanje potrditvenega sporočila  |  Uporabnik prejme sporočilo v roku 30s  |
