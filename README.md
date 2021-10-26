# [principles.webstream.dev](https://principles.webstream.dev)

Twórca webstream, poświęcił kilkanaście lat pracy nad projektami IT w różnych technologiach, 
aby zbadać czynniki stojące za uzyskaniem najlepszego długofalowego efektu, zaangażowanej energii i czasu do reużycia kodu.

Wnioski są następujące:

# Pryncypia

1. Hipermodularyzacja, czyli używanie jak najmniejszych modułów kodu, ściśle dla określonego środowiska w natywnym jezyku
2. Definiowanie pojedynczych funkcji jako pojedynczego projektu w celu pozbycia się zależności od innych bibliotek
3. Nie używanie frameworków i abstrakcji wprowadzających większą złożoność i wpływającą negatywnie na krzywą uczenia się
4. Budowanie kodu na podstawie jak największej ilości już zdefiniowanej logiki, wkorzystanie już istniejących usług dostępnych przez np RestAPI
5. Wykorzystanie dowolnej technologii dla której można zaoferować środowisko uruchomieniowe, zamiast tworzenia nowego rozwiązania w znanym języku programowania

Te pryncypia są stosowane przy użyciu biblioteki WebStream oraz całego ekosystemu [wapka.pl](https://docs.wapka.pl/))
W chwili obecnej kod jest ładowany w formie drzewa JSON z listą mediów jakie mają być załadowane
więcej informacji tutaj:
[docs.webstream.dev](https://docs.webstream.dev/#/)



## Modele architektoniczne

Bazujemy na pryncypiach oraz idei modularyzacji:
+ [Modularyzacja przy wytwarzaniu oprogramowania.](https://www.hipermodularyzacja.pl/)
+ [hyper modularity](https://www.hypermodularity.com/)


+ [Webintegration](https://de.wikipedia.org/wiki/Webintegration)
+ [WebComponents](https://en.wikipedia.org/wiki/Web_Components)



## Czego nie używamy?
abstrakcji, czyli:
+ JS typowany - typescript, nie działa w przeglądarce, konieczna kompilacja, jedynie jako kod dodatkowy/źródłowy*
+ Frameworków - narzucają architekturę/strukturę projektu
+ Bibliotek poza tymi, które rozwiązują problem funkcjonalny


## Zasady pisania modułu

+ natywny kod
+ pojedyncze funkcje
+ jedno rezpozytorium zawiera:
  + plik dokumentacji: README.md
  + plik konfiguracji (zależności w formacie webstream)
  + plik kodu: nazwa_funkcji.js

## Codereview

## Deployment


## Jakich narzędzi używamy?
+ [tools.webstream.dev](https://tools.webstream.dev/)


## Jakich technologii używamy?
+ [stack.webstream.dev](https://stack.webstream.dev/)


## Jakimi wartościami się kierujemy?
+ Kultura współ-pracy [culture.softreck.dev](https://culture.softreck.dev/)

## Muzyka, gdy słowa nie wystarczą

+ Web is a stream of interfaces, stream of requests [music](https://music.webstream.dev/)


---
+ [edit](https://github.com/web-stream/principles/edit/main/README.md)

```
https://github.com/web-stream/principles.git
```
