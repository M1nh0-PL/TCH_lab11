# Technologie Chmurowe — Laboratorium 11 #

## Autor: Ireneusz Witek ##

## Opis zadania: ##
Celem zadania było uruchomienie trzech kontenerów nginx połączonych wspólną siecią mostkową Docker oraz wykorzystujących bind mount do współdzielenia strony HTML i zapisywania logów na hoście.

## Tworzenie i sprawdzenie sieci lab11net: ##
![](scrinki/1.png)

## Utworzenie sieci Docker

```bash
docker network create --driver bridge lab11net
```
## Sprawdzenie sieci

```bash
docker network inspect lab11net
```
