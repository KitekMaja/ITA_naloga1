# **Naročanje**

## **Opis storitve**
Uporabnik bo lahko naročil e-vinjeto preko spletnega obrazca. Vpisati bo moral osebne podatke(ime, priimek, EMŠO, datum rojstva, naslov), podatke o vozilu(registrska številka).
Zahteva se bo poslala naprej in uporabnikovo naročilo se bo shranilo v bazo naročil. 

## **DDD diagram**
![DDD naročilo](https://user-images.githubusercontent.com/33865439/157535390-18be6430-2f8e-4073-a717-73df54e0b008.png)

## **Funkcionalne zahteve**

| Funkcionalne zahteve  | Nefunkcionalne zahteve |
| ------------- | ------------- |
| Vnos podatkov  | Preverjanje formata podatkov |
| Shranjevanje naročila v bazo  | Naročilo se shrani v bazo v roku 10s  |
| Obvestilo o končanem postopku  |  Obvestilo se izpiše v roku 5s  |
