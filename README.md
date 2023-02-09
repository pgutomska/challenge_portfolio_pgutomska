# challenge_portfolio_pgutomska

# Spis Treści


1. [Task 1](#task-1)
* [Subtask 1. Wyciągmy karteczki](#subtask-1-wyciągamy-karteczki)
* [Subtask 3. O mnie](#subtask-3-o-mnie)
* [Subtask 4. Testy eksploracyjne](#subtask-4-testy-eksploracyjne)
* [Subtask 5. Jira dla chętnych](#subtask-5-jira-dla-chętnych)
2. [Task 2](#task-2)
* [Subtask 1. Pisanie przypadków testowych na podstawie User Story](#subtask-1-pisanie-przypadków-testowych-na-podstawie-user-story)
* [Subtask 2. Pisanie przypadków testowych na podstawie własnych doświadczeń - aplikacja webowa](#subtask-2-pisanie-przypadków-testowych-na-podstawie-własnych-doświadczeń---aplikacja-webowa)
* [Subtask 3. Po co piszemy test case’y?](#subtask-3-po-co-piszemy-test-casey)
* [Subtask 4. Pisanie przypadków testowych na podstawie własnych doświadczeń - aplikacja mobilna](#subtask-4-pisanie-przypadków-testowych-na-podstawie-własnych-doświadczeń---aplikacja-mobilna)
3. [Task 3](#task-3)
* [Subtask 1. Formatka do zgłaszania błędów](#subtask-1-formatka-do-zgłaszania-błędów)
* [Subtask 2. Testowanie według planów testów i raportowanie błędów](#subtask-2-testowanie-według-planów-testów-i-raportowanie-błędów)
* [Subtask 3. Raport](#subtask-3-raport)
4. [Task 4.](#task-4)
* [Subtask 1. Formatka do zgłaszania błędów systemu](#subtask-1-formatka-do-zgłaszania-błędów-systemu)
* [Subtask 2. Testowanie eksploracyjne i raportowanie błędów](#subtask-2-testowanie-eksploracyjne-i-raportowanie-błędów)
* [Subtask 3. Do czego służy ta aplikacja?](#subtask-3-do-czego-s%C5%82u%C5%BCy-ta-aplikcja)
* [Subtask 4. Zgłaszanie błędów w Jirze](#subtask-4-zgłaszanie-błędów-w-jirze)

# Task 1
 
## Subtask 1. Wyciągamy karteczki
  
5 punktów
  
## Subtask 3. O mnie
  
<p align="justify">
Cześć, nazywam się Patrycja. Do challengu dołączyłam, żeby dowiedzieć się czegoś o pracy jako Tester Manualny. Kurs znalazłam ostatniego dnia zapisów i stwierdziłam: raz kozie śmierć - wypełnilam formularz, zapłaciłam i tak oto jestem. Mam nadzieję, że dam radę przejść cały challenge i wynieść z tego coś dla siebie. Już jakiś czas szukam dla siebie ścieżki kariery. Do tej pory nie miałam nic wspólnego z IT, więc zdaję sobie sprawę, że lekko nie będzie :see_no_evil:, ale się nie poddaję.
</p>
 
## Subtask 4 Testy eksploracyjne

### Na czym polega aplikacja? Do czego służy?
Aplikacja służy do wprowadzania danych o piłkarzach, meczach i tworzenia raportów z nich. 

### Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmieniła?

Aplikacja posiada takie funkcjonalności jak: dodawanie gracza, edycja jego danych, tworzenie meczów i raportów i otrymanie statystyk z nich. Można też wydrukować listę graczy z podstawowymi danymi o nich, filtrować graczy po imieniu, nazwisku, wieku, pozycji, klubie i ocenie.

Dodałabym możliwość drukwania raportów i usuwania graczy

Zmieniłabym ikonkę zapisu meczu np. na dyskietkę, żeby było to bardziej oczywiste.

### Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?

Aplikacja jest prosta z wyglądu, ale nie porywa. Działa szybko.

### Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).

Na pewno łatwo wejść do formuarza dodawania gracza - wyświetla się to na głównej stronie.

Wpisywanie raportu nie jest intuicyjne, jak klikam ikonkę pogrubienia, itp. trzeba znów kliknąć w tekst, żeby kontynuować pisanie. 

Długo zajęło mi ogarnięcie, jak dodać statystyki do raportu.

### Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń!

* Weszłam w rozgrywanie meczu, wyszłam bez zapisywania i... Nie mogę wrócić do raportu 😿
![Błąd1](https://i.imgur.com/uHtH7GS.png)
* *Według mnie* powinna być sprawdzana poprawność daty urodzenia, wagi i wzrostu, ponieważ można wpisać datę urodzenia z przyszłości, a wagę i wzrost ujemny.
* Poprawiłabym okna do wpisania imienia i nazwiska, żeby nie można było wprowadzać cyfr i nieużywanych w nazwiskach znaków specjalnych.
* Link do youtuba w dodawaniu gracza może w ogóle nie być linkiem (zatwierdza obojętny ciąg znaków).
* Dodawanie wieku gracza: jak wpisze się za dużą liczbę w dniu miesiąca to zmienia ją automatycznie na 31, a potem wymaga zmienienia tego na poprawną datę.
* Hiperłącze do "dev team contact" przekierowuje do stworzenia Slacka.
* *Według mnie* jest błędne tłumaczenie zdania "rozpoznij mecz" na język angielski ("start report") i jest to mylące. 
* Nie wiem, czy to jest bład, ale na etapie dodawania gracza nie informuje, że trzeba wpisać województwo, a jest ono potrzebne, żeby otrzymać raport.
* W stronie dodawania gracza przycisk Clear nie działa praidłowo, usuwa tylko ostatnie zmiany.
* Na stronie głównej są literówki, tj. za~~a~~ktualizowany lub Aktywnosć.

### Subtask 5. Jira dla chętnych

Dołączyłam do zespołu w [Jirze](https://wannai.atlassian.net/jira/software/projects/DIT/boards/2).

# Task 2

## Subtask 1. Pisanie przypadków testowych na podstawie User Story

Napisane przeze mnie przypadki testowe na podstawie User Story dostępne są pod tym [linkiem](https://docs.google.com/document/d/1Nugy81i-qjqrOQDaUlxDpq8gY8DRlNZDSZEQa8Yp7YA/edit?usp=share_link).

## Subtask 2. Pisanie przypadków testowych na podstawie własnych doświadczeń - aplikacja webowa

Napisane przeze mnie przypadki testowe na podstawie własnych doświadczeń dostępne są pod tym [linkiem](https://docs.google.com/document/d/1YRDIOQvrbB-8L77hRTqiGg1yvgKjiYIGKWvk3LYt234/edit).

## Subtask 3. Po co piszemy test case’y?

*Według mnie* test case'y piszemy po to, by:
* było wiadomo jak test został zrobiony - dla nas i innych testerów
* móc sprawdzać oprogramowanie w trakcie testów regresji
* do oceny, czy oczekiwania klienta są spełnione

## Subtask 4. Pisanie przypadków testowych na podstawie własnych doświadczeń - aplikacja mobilna

Plik z napisanymi przeze mnie przypadkami testowymi dostępny pod tym [linkiem](https://docs.google.com/document/d/1hlEo65Lzn8OgfEHM1tB7eEXgob9C85AyI043NdviVSc/edit).

# Task 3

## Subtask 1. Formatka do zgłaszania błędów

Moja formatka dostępna jest pod [linkiem](https://docs.google.com/document/d/1BgqcYjhT6Az-61R7eg9hDAuFmnwa4Z3-LI_eeVeUUbI/edit).

## Subtask 2. Testowanie według planów testów i raportowanie błędów

Moje raporty błędów znajdują się [tutaj](https://docs.google.com/document/d/1EmkNx5qp1kCTks8WTv7mbIuncSpynDsv53T68aa-5_I), natomiast plany testów są opisane w [Tasku 2](#task-2) - Subtask 1 i Subtask 2

## Subtask 3. Raport

Mój raport z testów dostępny pod tym [adresem](https://docs.google.com/document/d/19ihWjwXELDIiIsyVEEKJ_eT4FaK2ZSFzIaj33SLo9h0).

# Task 4

## Subtask 1. Formatka do zgłaszania błędów systemu

Moja formatka do zgłaszania błędów aplikacji mobilnych znajduje się [tutaj](https://docs.google.com/document/d/1z1fhQujmnakAMaqOj5QjcLpryMzAyexnlqxYytM2weM).

## Subtask 2. Testowanie eksploracyjne i raportowanie błędów

Udało mi się znaleźć jeden błąd, oto moje [zgłoszenie](https://docs.google.com/document/d/14SAxmyREywUqruGBuJfxcgwt88sd567khHbz-pgoBCk) błędu. 

Zdarzyły się też rzeczy, które były nie do zreprodukowania:

* Raz, gdy kliknęłam "Zobacz więcej" pod Prawammi konsumenta to ten napis nie zniknął, jak na obrazku poniżej.

<img src="/images/Screenshot_OLXpl.jpg" alt="screenshot of olx page" width="50%"
height="50%" title="screenshot">

* Po przeglądaniu strony "Szukaj" z wybranymi dla mnie pozycjami miałam wrażenie, że nie klikane przeze mnie produkty pokazywały się potem w "Ostatnio oglądanych ogłoszeniach"

## Subtask 3. Do czego służy ta aplikcja?

*Według mnie* aplikacja OLX służy do:

 * Sprzedawania i kupowania rzeczy, mieszkań i wynajmowania ich
 
 * Szukania pracy

Użytkownikiem końcowym są osoby prywatne i firmy, które chcą coś wystawić na sprzedaż, albo kupić. Może to być też osoba, która poszukuje pracy.

Aplikacja jest czytelna, łatwo dodać nową ofertę przyciskiem na dole ekranu. Wszystko jest wyraźnie oznaczone. Można też wybrać, jakie powiadomienia chcemy dostawać. Jednak nie przypominam sobie, by aplikacja prowadziła mnie po kolei, np. jak dodać nowe ogłoszenie, albo jak coś wyszukać. Klikając w "Pomoc" użytkownik jest przekierowany do strony "Centrum pomocy", które to jest tylko pytaniami i odpowiedziami - nie widzę kontaktu z infolinią, czy czatu. Nie ma też weryfikacji dwuskładnikowej.

Dodałabym opcję kontaktu z supportem - mailowy, telefoniczny, czy poprzez czat. Dodałabym też weryfikację dwuskładnikową do logowania, żeby preciwdziałać oszustwom. Na ten moment weryfikuje się tylko numer telefonu sprzedającego.

Testowanie aplikacji internetowej i natywnej zdecydowanie ma swoje różnice, m. in. w natywnej nie ma takich narzędzi, jak DevToolsy. Aplikację natywną trzeba też zainstalować, internetowej nie. Istnieje też różnica w rozdzielczości, przez co aplikacje mobilne trudniej zrobić czytelnymi. Natywne aplikacje też trudniej zobić dostępne dla wszystkich (np. ustawienie większej czcionki w telefonie dla osób słabowidzących powoduje czasem brak możliwości używania danej aplikacji).

## Subtask 4. Zgłaszanie błędów w Jirze

Zadanie było robione grupowo, moje zgłoszenia w aplikacji Jira dotępne są pod [linkiem](https://wannai.atlassian.net/jira/software/projects/DIT/boards/2) oraz na githubie w [folderze](https://github.com/pgutomska/challenge_portfolio_pgutomska/tree/main/Jira).
