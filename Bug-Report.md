Raport z testów aplikacji APCOA FLOW (iOS)

1. O projekcie
APCOA FLOW wersja 6.84.1 (wersja na iOS)
Cel testów: Weryfikacja formularza dodawania pojazdu pod kątem błędów.

2. Zgłoszony błąd


Bug #1 Wprowadzanie nimeru rejestracjyjnego przy dodawaniu pojdazdu.

Jesli dodajemy pojazd i wpisujemy nr rej. pojazdu to nie mamy ograniczeń co szablonu numeru tzn. nie wyrzuca błędu przy ilosci znakow (mozemy wrzucic dowlona), nie wyrzuca błędow przy przerwach w nie odpowiednim momencie, oraz dopuszcza znaki specjalne.
dzieje sie tak w wiekszosci krajow z wyjatkiem: Polski, Austrii, Danii, Holandii, Niemiec, Szwajcarii i Szwecji tutaj sytuacja wyglada tak ze wymaga odpowiedniego formatu numeru, pilnuje w ktorych miejscach odstepy oraz nie pozwala na znaki specjalne typu "€&@" i inne.
Trzeba w pozostalych panstwach dodac aby pilnowal tych zmiennych co wyzej.
w krajach w ktorych wystepuje ten problem podczas proby zapisu samochodu wyrzuca blad ale tylko wtedy jesli mamy znak specjalny lub ilosc znakow powyzej 20, jezeli nie ma
znaku specjalnego i jest 20 i mniej znakow pozwala zapisac 


Kroki odtworzenia: lewy gorny rog (3 kreski) -> Moje Pojazdy -> Dodaj pojazd -> wybieramy Państwo np Albania -> wprowadzamy dowolny numer nawet ze znakow specjalnycn
Zdjecie ponizej
![Opis zdjęcia](IMG_2168.jpeg)


Bug #2 Black screen
w ciagu testow kilka razy pojawil mi sie black screen
jednak nie umiem wywolac tego błedu, pojawial sie randomowo zwykle jezeli intensywnie klikalem i przechodzilem miedzy aplikacjami, jednak kiedy probowalem wymusic nic takiego mi sie juz nie przydarzyło.
nie wiem do konca czy to wina telefonu czy samej aplikacji, zdjecie rowniez zamieszczam.

![Opis zdjęcia](IMG_2169.jpeg)
