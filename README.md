Napisz aplikację WWW spełniającą wysokie standardy bezpieczeństwa. Aplikacja przechowuje hasła użytkownika do witryn.

Wymagania:

- restrykcyjna walidacja danych pochodzących z formularza login-hasło,
- przechowywanie hasła chronione funkcją hash, solą i pieprzem,
- możliwość umieszczenia na serwerze haseł dostępnych prywatnie lub dla określonych użytkowników,
- szyfrowanie symetryczne przechowywanych haseł. 
- zabezpieczenie transmisji poprzez wykorzystanie protokołu https,
- możliwość zmiany hasła,
- możliwość odzyskania dostępu w przypadku utraty hasła,
- dodatkowa kontrola spójności sesji (przeciw atakom XSRF),
- wielokrotne wykorzystanie funkcji hash, żeby wydłużyć ataki brute-force na hash,
- weryfikacja liczby nieudanych prób logowania,
- dodanie opóźnienia przy weryfikacji hasła w celu wydłużenia ataków zdalnych,
- sprawdzanie jakości hasła (jego entropii),
- informowanie użytkownika o nowych podłączeniach do jego konta.
