# Bezpieczeństwo
Nie należy zapisywać haseł ani kluczy dostępu w repozytorium,ponieważ w przypadku publicznego repozytorium każda osoba może je przeglądać lub sklonować. 
Tworzy to możliwość przejęcia danych dostępowych przez osoby trzecie nieuprawnione.
Samo usuniecie pliku nie wystarcza, ponieważ Git przechowuje całą historie zmian, nawet po usunięciu danych możliwe jest ich odczytanie w poszczególnych zatwierdzeniach.
Aby usunąć je z historii, należy ją odpowiednio zmodyfikować, jednak nie gwarantuje to, że dane nie zostały wcześniej skopiowane.
