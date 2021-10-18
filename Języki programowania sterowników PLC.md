Tagi: #SP
# Jęzki programowania sterowników PLC
---
## Języki IT
> Języki typu python, c++
> Przetwarzanie danych, bezpieczeństwo, analiza, itd.
---
## Języki OT(operational technology)
> Skupione na procesach przemysłowych
> Dotyczą głównie zarządzania pracą maszyn oraz systemów automatyki
> Nierozerwalne z urządzeniami, które współpracuje - sterowniki PLC, komputerami przemysłowymi, sterownikami silników(falownikami) itd.
> Analizuje mniej danych ale ***muszą być realizowane w gwarantowanym nieprzekraczalnym czasie***
---
## Bezpieczeństwo
> IT skupia się na bezpieczeństwie/rzetelności Danych
> OT najważniejsze jest bezpieczeństwo procesu oraz ludzi
---
## Długość cyklu życia
> W IT cykl trwania tendów/nowych technologii to ok. **5 lat**
> W OT wprowadzenie nowych rozwiązań wiąże się z wysokimi kosztami, więc cykl życia rozwiązań OT wynosi ok **20-25 lat**
---
## Czym różnią się jezyki OT od języków IT?
### IT:
>1. Paradygmat programowania obiektowego
>2. Realizują algorytmy w sposób ogólny
>3. Programy są skalowane
>4. Użycie w różnych zastosowaniach
>5. Dużo myślenia abstrakcyjnego

### OT:
>1. Służą do realizacji liniowych algorytmów wykonywanych cyklicznie
>2. Programy są dedykowane konkretnym, zazwyczaj niepowtarzalnym systemom automatyki
>3. Programowanie wymaga dobrego rozumienia wymagań stawianych przez technologię produkcji i sposób pracy urządzeń
>4. Programy powinny być możliwe do napisania i zrozumienia przez osoby nieprzyzwyczajone do myślenia abstrakcyjnego

## NORMA IEC 61131-3
- Norma opisująca graficzne i tekstowe języki programowania dla sterowników PLC
- Norma przewiduje możliwość łączenia w ramach jednego projektu podprogramów, napisanych w różnych językach
- Większość środowisk programistycznych dla przemysłowych sterowników pozwala na wykonystanie wszystkich lub niektórych języków, zdefiniowanych w normie IEC 61131-3

## Typy języków PLC

| ang.                   | pol.                     | typ       | opis                                                                                                  |
| ---------------------- | ------------------------ | --------- | ----------------------------------------------------------------------------------------------------- |
| Ladder diagram         | Język drabinkowy         | Graficzny | Programy są przedstawiane jako obwody elektryczne zawierające styki przekaźników                      |
| Function Block Diagram | Język Bloków Funkcyjnych | Graficzny | Programy są przedstawiane jako połączenie bloków funkcyjnych podobnych do schematów układów cyfrowych |
| Instruction List       | Lista instrukcji         | Tekstowy  | Język tekstowy niskiego poziomu, przypominający język asemblera                                       |
|                         |                          |           |                                                                                                       |
