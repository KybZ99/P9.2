# Zadanie 9.2
Projekt posiada cztery kontenery:
* jeden kontener dla Nginx,
* jeden kontener dla PHP,
* jeden kontener dla MySQL,
* jeden kontener dla phpMyAdmin

## Opis zadania
Założenia dla usługi:
* serwery są budowane zgodnie z dokumentacją obrazów bazowych dostępnych na DockerHub i
umieszczonych tam plików Dockerfile (zbudowanie własnych obrazów a nie wykorzystanie z
gotowych obrazów będzie wyżej oceniane).
* serwery PHP, MySQL, phpMyAdmin są przyłączone do sieci backend a Nginx do backend oraz
frontend. Nginx ma wystawiony na świat zewnętrzy port 6666,
* serwer Nginx ma wyświetlać stronę startową php (index.php),
* serwer phpMyAdmin ma być dostępny na porcie 6001 i powinno być możliwe zalogowanie się do
niego i założenie testowej bazy.

## Pierwsze kroki

### Uruchamianie programu
* Wejdź w katalog projektu
* Wpisz w terminalu komendę
```
docker compose up
```
* Aby zalogować się do phpMyAdmin wpisz w przeglądarkę 
```
localhost:6001
```

## Autor
Jakub Kozłowski

