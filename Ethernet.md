
![[Recording 20211109102144.webm]]

***gejmerzy szybki internet
szkielet - szybszy internet***

Metody dostępu do medium:
- Przepytywanie:
> kontroler sieci odpytuje urządzenia czy są gotowe do nadania sygnału. Wymaga dedykowanego urządzenia do kontroli sieci
- Dostęp z przekazywaniem znacznika
> Topologia pierścienia, niewykorzystujace - arcnet
> W sieci generowany jest pakiet(znacznik), który przekazywany jest cyklicznie między urządzeniami podłączonymi do sieci, jeśli urządzenie otrzymało znacznik może nadawać pakiety, po przesłaniu przekazuje znacznik dalej
- Dostęp jednoczesny z wykrywaniem kolizji
> tą metodą posługuje się ethernet
> wszystkie urządzenia potrafią wykryć kolizję(dwa lub więcej urządzeń nadaje jednocześnie) i czekają aż inne urządzenie przestanie nadawać pakiety. Wszystkie urządzenia biorące udział w kolizji przestają nadwać i odczekują pewnien moment.
> tania, prosta w konstrukcji, czesto wykorzystywana

- Dostęp jednoczesny z unikaniem kolizji
>  przed wysłaniem pakietów, wysyła się pakiet żądzania transmisji, jeśli wystąpi kolizja podczas przesyłania tego małego pakietu, to nie przesyła nic. Używana w sieciach bezprzewodowych

![[Pasted image 20211109105412.png]]

Ethernet encapsulation - wybór nagłówka ethernet

UTP - wrazliwe na wygięcia itp

## Routing vs VLAN
Port based - przełączniki logiczne, ręczne przydzielanie

Tagged - w ramkach dodawana jest informacja do którego vlanu ramka należy

MAC based - na podstawie adresów fizycznych urządzeń

8100 w typ określa pozycje tagu
QinQ pozwala na tworzenie vlan w vlan