tagi: #PODA 

### Uchyb regulacji 
> Błąd, np różnica między prędkościa zadaną a prędkościa aktualną samochodu

## Przykłady:

### Regulacja temperauty mikroprocesora:
> Zakłócenia: obciążenie mikroprocesora
> Sygnał sterujący: temperatura, prędkość wentylatora

### Serwerownia
> Zakłócenia: obciążenie serwerów
> Sygnał sterujący: włączenie nowego serwera, przerzucenie na inny serwer

### Klimatyzacja
> Zakłócenia: otwieranie okien, ludzie w środku
> Sygnały sterujące: chłodzi bardziej

### Destylacja ropy
> Sygnały sterujące: przepuść lub nie
> Zakłócenia: skład chemiczny, temperatura

### Jakość produktu reaktora polimeryzacji
> Sygnały sterujące: natężenie dopływu surowców
> Zakłócenia: wahania składu surowców

### Stabilizacja działa czołgu
> Sygnał sterujący: w przypadku gdy czołg zjeżdża w dół podnieś działo w góre i na odwrót
> Zakłócenia: teren

### Robot kroczący
> Cel sterowania: utrzymywanie równowagi, chodzenie, położenie przegubów/stawów
> Zakłócenia: teren, środowisko zewnętrzne
> sygnały sterujące: dla silników

### Autopilot w samolocie:
> Cele sterowania: utrzymanie samolotu na kursie
> Zakłócenia: opór powietrza, wiatr, atmosfera
> Sygnały sterujące: silniki, obrót, rozkład skrzydeł

#### Wady wzmacniacza bez sprzężenia zwrotnego:
- zniekształcenie sygnału

## Wzmacniacz elektroniczny:
> zalety:
> - liniowość (redukcja zniekształceń)
> - stabilna praca
> - stałe wzmocnienie

## Układy sterowania i regulacji są systemami informacyjnymi:
> funkcje:
> - pozyskiwanie informacji
> - przesyłanie informacji
> - przechowywanie informacji
> - przetwarzanie informacji (podejmowanie decyzji sterujących)
> - prezentacja informacji

### System informatyczny:
> System informacyjny zrealizowany w oparciu o urządzenia i środki informatyki (komputery i oprogramowanie)
> Jednostka obliczeniowa wyznacza dane

## Platformy systemów informatycznych:
- [[Języki programowania sterowników PLC|PLC]]: 
> łatwo napisać różne programy, które są ładowane do pamięci
> Sterownik ten umożliwia implementację algorytmów regulacji

![[Pasted image 20211018205301.png]]

- Regulatory - algorytmy regulacji
- sterowniki przemysłowe - wydajna jednostka do implementacji złożonych algorytmów
- Systemy wbudowane:
> Pierwszy mikrokontroler jednoukładowy: Intel 8051
> Współczesne mikrokontrolery: STM

## Platformy obliczeniowe automatyki:
- PLC
- Regulatory
- Sterowniki przemysłowe
- Systemy wbudowane

## Cechy systemów sterujących:
1. Bezpieczeństwo i niezawodność działania:
- testowanie przed uruchomieniem systemu
- im droższy sprzęt tym większa redundacja(nadmiarowość w stosunku do tego, co konieczne lub zwykłe)
- urządzenia o wysokiej wytrzymałości

2. Przestrzeganie ograniczeń czasowych:
> algorytmy sterowania i regulacji działają w systemach czasu rzeczywistego

3. Złożone systemy działają pod nadzorem operatora


