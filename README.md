# J-zyki-Symboliczne---Projekt-Statki
Gra w statki (Battleship)

Tadeusz Ciapała, nr albumu 131949

Link do repozytorium: https://github.com/Tadens/J-zyki-Symboliczne---Projekt-Statki


Chciałbym zaproponować temat, który zgłaszałem na początku semestru u pana doktora M. Ciury : Grę w statki na dwie osoby przez sieć lokalną (Bardzo przepraszam, że z takim opóźnieniem, niestety z powodu koronawirusa dopiero w maju mogłem zdawać 3 termin z zaległego przedmiotu i musiałem się przygotować). 

- Do połączenia dwójki graczy planuję użyc modułu "socket". Gracz będzie mógł wybrać w menu głównym czy chce dołączyć do istniejącej gry w sieci lokalnej czy też sam chce hostować. 
- Program rozpocząłby rozgrywkę, gdy drugi gracz połączy się z hostem. Podczas, gdy gracz tworzy grę aplikacja nastawiałaby port gry na nasłuchiwanie. 
- Gracz dołączający wybierałby pozycje swoich statków jako pierwszy. Współrzędne statków mogą być zapamiętywane lokalnie i dopiero, gdy gracz kliknie na dane pole, to wtedy propozycja zostałaby wysłana i porównana z zapisanymi lokalnie pozycjami statków.
