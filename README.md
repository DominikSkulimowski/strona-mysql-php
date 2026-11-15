# strona-mysql-php

Aby uruchomić stronę
1. Uruchom MySQL: sudo service mysql start
2. Uruchom serwer PHP: php8.3 -S 0.0.0.0:8080
3. Otwórz zakładkę "Porty"
4. Kliknij adres przy porcie 8080

Gdy port jest zajęty
1. Zakończ proces zajmujący port: sudo fuser -k 8080/tcp
2. Uruchom ponownie serwer PHP: php8.3 -S 0.0.0.0:8080