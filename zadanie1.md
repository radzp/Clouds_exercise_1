# Clouds_exercise_1

## Polecenia niezbędne do:

a. zbudowania opracowanego obrazu kontenera

``` docker build -t z1 . ```

<img width="1061" alt="Zrzut ekranu 2024-05-19 o 21 05 56" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/ab7084a0-c28f-4e82-a230-79ef2e1dd929">


b. uruchomienia kontenera na podstawie zbudowanego obrazu
``` docker run -d -p 8000:8000 --name kontener1 z1 ```

<img width="1056" alt="Zrzut ekranu 2024-05-19 o 21 07 10" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/eb7e4a6f-d72e-4c12-9fe9-f8b355f0d30d">

c. sposobu uzyskania informacji, które wygenerował serwer w trakcie uruchamiana kontenera

``` docker logs kontener1 ```

<img width="1068" alt="Zrzut ekranu 2024-05-19 o 21 08 18" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/848635c4-71f8-4ade-814d-7a0ceae8610f">



d. sprawdzenia, ile warstw posiada zbudowany obraz.

``` docker history z1   ```


<img width="1368" alt="Zrzut ekranu 2024-05-19 o 21 22 48" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/a110dcf7-5185-4296-8577-76540a4eaed5">


### Wygląd działania aplikacji na localhost:8000

<img width="1204" alt="Zrzut ekranu 2024-05-19 o 21 55 45" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/390dd237-f2e5-4d50-80f4-e917d1cdcc6c">


### Mój kontener w aplikacji Docker Desktop: 

<img width="1437" alt="Zrzut ekranu 2024-05-19 o 21 11 10" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/d1b9f6bb-0df7-4b22-addb-61468e763d79">


##  Składowe mojego obrazu nie uzyskują oceny CVSS w zakresie High lub Critical (powyżej 7.0). Przetestowałam za pomocą narzędzia Docker Scount.

Polecenia użyte do sprawdzenia w terminalu:

<img width="1389" alt="Zrzut ekranu 2024-05-19 o 21 18 20" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/78a65547-9fc2-49f8-8e1e-180e9185aa5d">

### Docker hub: 

<img width="1434" alt="Zrzut ekranu 2024-05-19 o 21 19 11" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/78bb9673-08a0-46b9-aef5-6d91b0263a1d">

