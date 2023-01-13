# Task 1
## Subtask 1
10/10
## Subtask 3
Cześć nazywam się Magda. Obecnie pracuję poza branżą IT i od dłuższego czasu myślę o przebranżowieniu się w kierunku testera (na początku manualnego, w planach automatyzującego), dlatego szukam różnych możliwości kształcenia się w tym kierunku i zdobywania doświadczenia. Wzięłam udział w spotkaniu "Junior QA - najbardziej pożądane umiejętności i rola w zespole developerskim", które prowadziła Patrycja. Dzięki temu spotkaniu dowiedziałam się o challengu + bardzo spodobało mi się podejście Patrycji, więc stwierdziłam, że udział w nim będzie strzałem w dziesiątkę - poznanie testowania z praktycznego punktu widzenia:)

W testowaniu podoba mi się to, że jest to praca rozwojowa, wymagająca zaangażowania, ciągłego dokształcania się, czyli cały czas na przód + zdobywanie nowych celów, to jest to co mnie motywuje.

Projekt spodobał mi się, właśnie ze względu na praktyczne zadania, dzięki czemu poznam od podszewki pracę testera + usystematyzuje wiedzę teoretyczną, którą do tej pory zdobyłam. 

Moim celem jest wykonanie terminowo wszystkich zadań, zdobycie doświadczenia, dzięki czemu będę mogła rozpocząć poszukiwania wymarzonej pracy :)
Moje oczekiwania - to przede wszystkim feedback od mentorów, którzy wskażą mi co mogę poprawić / ulepszyć w mojej pracy.

*Magda*

## Subtask 4
### Na czym polega ta aplikacja? Do czego służy?
- aplikacja Scouts Panel 
### Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)
### Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?
### Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).
- aplikacja nie jest intuicyjna - nie ma żadnych informacji do aplikacja czego służy, po zalogowaniu się następuje przekierowanie na stronę główną, przy czym nie jest intuicyjnie wiadomo, która zakładka służy do czego,
### Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)
Przeglądarka Google Chrome (Firefox, Opera, Edge działa), 
- strona główna, panel logowania - przy braku podania loginu i braku hasła oraz zaznaczonej opcji języka polskiego pojawia się komunikat walidacyjny jest w języku angielskim (a powinien w polskim),
- strona główna, przy logowaniu mamy dwa pola do wypełnienia Login i Hasło, komunikat walidacyjny w przypadku braku podania loginu lub błędnego podania loginu wyświetla się pod polem z hasłem, co jest nieczytelne / mylące, nie ma rozbicia na komunikat walidaycjny pod polem login i pod polem hasło osobno;
- w przypadku kliknięcia buttona "Przypomnij hasło" przekierowanie na stronę, na której należy podać hasło e'mail, przy braku podania adresu e'mail i kliknięciu w button WYŚLIJ/SEND pojawia się komunikat "Wysłano wiadomość na podany adres e'mail" (w devtoolsach błąd 400), nie pojawia się komunikat walidacyjny,
- w przypadku kliknięcia buttona "Przypomnij hasło" przekierowanie na stronę, na której należy podać hasło e'mail, w przypadku kliknięcia buttona "Przypomnij hasło" przy podaniu adresu e'mail w złym formacie i kliknięciu w button WYŚLIJ/SEND pojawia się komunikat "Wysłano wiadomość na podany adres e'mail" (w devtoolsach błąd 400), nie pojawia się komunikat walidacyjny,
- strona "Przypomnij hasło" - jeżeli naciśnięty zostanie button WYŚLIJ/SEND to zarówno przy poprawnym jak i niepoprawnym podaniu adresu e'mail button się blokuje i nie ma możliwości ponownego wysłania adresu e'mail, trzeba się cofnąć do strony głównej ponownie kliknąć w przycisk "Przypomnij hasło", po czym następuję przekierowanie do strony z przypomnieniem hasła, wówczas button WYŚLIJ/SEND jest aktywny,

