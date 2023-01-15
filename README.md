# challenge_portfolio_pgutomska
  # Task 1
  ## Subtask1
  5 punktów
  ## Subtask 3
  Cześć, nazywam się Patrycja. Do challengu dołączyłam, żeby dowiedzieć się czegoś o pracy jako Tester Manualny. Kurs znalazłam ostatniego dnia zapisów i stwierdziłam: raz kozie śmierć - wypełnilam formularz, zapłaciłam i tak oto jestem. Mam nadzieję, że dam radę przejść cały challenge i wynieść z tego coś dla siebie. Do tej pory nie miałam nic wspólnego z IT, więc zdaję sobie sprawę, że lekko nie będzie, a już co chwila walę głową o klawiaturę :see_no_evil:
  
## Subtask 4
### Na czym polega aplikacja? Do czego służy?
Aplikacja służy do wprowadzania danych o piłkarzach, meczach i tworzenia raportów z nich. 
### Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmieniła?
Aplikacja posiada takie funkcjonalności jak: dodawanie gracza, edycja jego danych, tworzenie meczów i raportów i otrymanie statystyk z nich. Można też wydrukować listę graczy z podstawowymi danymi o nich, filtrować graczy po imieniu, nazwisku, wieku, pozycji, klubie i ocenie.

Dodałabym możliwość drukwania raportów, usuwania graczy

Zmieniłabym ikonkę zapisu meczu np. na dyskietkę, żeby było to bardziej oczywiste.
### Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?
Aplikacja jest prosta z wyglądu, ale nie porywa. Działa szybko.
### Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).
Na pewno łatwo wejść do formuarza dodawania gracza - wyświetla się to na głównej stronie.

Wpisywanie raportu nie jest intuicyjne, jak klikam ikonkę pogrubienia, itp. trzeba znów kliknąć w tekst, żeby kontynuować pisanie. 

Długo zajęło mi ogarnięcie, jak dodać statystyki do raportu.
### Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń!
Weszłam w rozgrywanie meczu, wyszłam bez zapisywania i... Nie mogę wrócić do raportu 😿
![Błąd1](https://i.imgur.com/uHtH7GS.png)

Według mnie powinna być sprawdzana poprawność daty urodzenia, wagi i wzrostu, ponieważ można wpisać datę urodzenia z przyszłości, a wagę i wzrost ujemny. Wiek powinien sam się wyliczać, bo nikt nie będzie zmieniał wieku co czyjeś urodziny.

Poprawiłabym okna do wpisania imienia i nazwiska, żeby nie można było wprowadzać cyfr i nieużywanych w nazwiskach znaków specjalnych.
Link do youtuba w dodawaniu gracza może w ogóle nie być linkiem (zatwierdza obojętny ciąg znaków).

Dodawanie wieku gracza: jak wpisze się za dużą liczbę w dniu miesiąca to zmienia ją automatycznie na 31, a potem wymaga zmienienia tego na poprawną datę.

Hiperłącze do "dev team contact" przekierowuje do stworzenia Slacka.

Według mnie jest błędne tłumaczenie zdania "rozpoznij mecz" na język angielski ("start report") i jest to mylące.

Nie wiem, czy to jest bład, ale na etapie dodawania gracza nie informuje, że trzeba wpisać wojewódtwo, żeby otrzymać raport.
