## CZĘŚĆ DODATKOWA ---------------------------------------

### Wybrane przeze mnie polecenie dodatkowe, to polecenie 3 (max. 30%)
## Użyte polecenia oraz wyniki ich działań: 

``` docker buildx create --use --name builderz1  ```

<img width="946" alt="Zrzut ekranu 2024-05-19 o 22 49 20" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/3bafc017-f58a-4988-ad11-3d7c99267f50">

``` docker buildx build --platform linux/amd64,linux/arm64 -t annepvcz/clouds_exercise_1:e1_extra -f Dockerfile_extra . --push  ``` 

<img width="1372" alt="Zrzut ekranu 2024-05-19 o 22 51 06" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/232d949a-2755-4fc2-bc01-24b8bfbbb0b8">


## Upewniam się, że polecenia zadziałały i obie platformy są już uwzględnione

``` docker buildx imagetools inspect annepvcz/clouds_exercise_1:e1_extra ```

<img width="1066" alt="Zrzut ekranu 2024-05-19 o 22 52 23" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/e54fa6a4-7e1b-4c8f-bbaf-60449c768091">

## Jak również na Docker Hub 

<img width="1162" alt="Zrzut ekranu 2024-05-19 o 22 53 13" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/8a3bfb42-c78b-4ccd-b6f0-29c3842afc98">

## Dockerfile_extra do zadania dodatkowego znajduje się poniżej (jak również zamieszczony został w plikach):

<img width="959" alt="Zrzut ekranu 2024-05-19 o 22 56 04" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/edc1b14d-cd30-4e23-aad4-5a37d41a253c">

<img width="1084" alt="Zrzut ekranu 2024-05-19 o 22 57 43" src="https://github.com/radzp/Clouds_exercise_1/assets/98003017/39eb1e03-1b9d-4e11-a446-4dfaea031120">
