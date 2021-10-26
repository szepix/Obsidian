tags: #EWA

### Mosfet
![[Pasted image 20211026142757.png]]

- Podłoże typu N (półprzewodnik P w mosfet typu N)
- Wyspy(w mosfecie typu N obszary typu N)
- Nad wyspami izolator(tlenek krzemu, bardzo cienka)
- na dielektryku kladziemy metal
kondensator typu MOS

![[Pasted image 20211026143332.png]]
NPN - strzałka w stronę podłoża
PNP - odwrotnie

MOS - jest cztero końcówkowy(podłoże też jest istotne)

Napięcie między podłożem a bramką =0 nic się nie dzieje

Gdy Ug > 0V inwersja typu polprzewodnika na granicy miedzy ***izolatorem*** a podlozem, pod wplywem przylozonego pola elektrycznego

Gdy Ug jest zbyt duże elektrony przepływają między drenem a źródłem

Obszar inwersji nazywamy kanałem.

MOSFET nie wymaga prądu, żeby pracować. Nie jest potrzebny ciągły prąd do sterowania.

Podłoże zwiera się ze źródłem, przez co zostają tylko 3 nóżki. Wyróżnione zostaje źródło.

Jeśli $$U_{ds}$$ jest odpowiednio wysokie, to
$$I_D = \beta*(U_{GS}-U_T)^2 $$ beta inna niż w bipolarnym
Gdzie $$U_T$$ to napięcie progowe(próg inwersji, czyli kiedy się włączy), $$\beta$$ to parametr modelu

$$I_D = I_S$$ bo przez bramkę nie płynie prąd
$$I_G = 0$$

Wspólna elektroda dla wejścia i wyjścia, ***układ wspólnego źródła***

![[Pasted image 20211026145758.png]]

Zakres rezystancyjny - nienasycenia, jesteśmy w stanie zmieniać strumień nośników w warstwie inwersyjnej

Zakres nasycenia - nie jesteśmy w stanie przesłać większej liczby nośników niż określona najwyższa

$$U_{D(sat)} = U_{GS}-U_T$$

MOS - sterowany opornik, sterowane źródło prądu


### Tyrystor
- Tyrystor to element trójkońcówkowy, cztery warstwy półprzewodników
- Właściwości zbliżone do diody półprzewodnikowej

Struktura PNPN:
- Działanie podobne jak trzy diody

- gdy źródło jest źródłem wyprostowanego sinusoidalnego, gdy co jakiś czas napięcie spada do 0
- regulacja sygnału pozwala na wpływanie na moc tyrystora poprzez pole, które pokrywa impuls

Tyrystor jest zbyt wolny, czasy zapłonu/wyłączania są duże
impuls zapalający(sterujący) ma duże napięcie
Skłonność do przebijania się zależy od temperatury

Dodatne sprzężenie zwrotne - po przebiciu tyrystor przewodzi prąd do momentu odcięcia napięcia

![[Pasted image 20211026153229.png]]

