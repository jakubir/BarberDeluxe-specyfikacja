# System umawiania wizyt dla salonu Barber Shop Deluxe

Wersja: v1.0

Autor: Jakub Irla

## Spis treści

1. [Cel aplikacji](#cel-aplikacji)
3. [Cel biznesowy](#cel-biznesowy)
4. [Korzyści z wdrożenia](#korzyści-z-wdrożenia)
5. [Charakterystyka użytkowników](#charakterystyka-użytkowników)
8. [Wymagania](#wymagania)
   * [funkcjonalne](#funkcjonalne)
   * [niefunkcjonalne](#niefunkcjonalne)
5. [Rozplanowanie prac w czasie](#rozplanowanie-prac-w-czasie)
7. [Technologie](#technologie)
9. [Wycena](#wycena)

## Cel aplikacji

Celem aplikacji jest usprawnienie procesu umawiania wizyt oraz zarządzania harmonogramem pracy i cennikiem. Dzięki temu, firma może lepiej zarządzać swoim czasem i zasobami oraz zwiększyć swoją efektywność. Aplikacja ma na celu także poprawę jakości obsługi klienta, dzięki łatwiejszemu i szybszemu umawianiu wizyt oraz lepszemu zarządzaniu informacjami o preferencjach i potrzebach klientów. Dodatkowo, system potwierdzania wizyty przez link w mailu, mailowe przypomnienie dzień przed wizytą o jej terminie oraz automatyczna informacja w przypadku anulowania wizyty przez właściciela, wpływa na poprawę komunikacji z klientami i zwiększenie ich zadowolenia.

## Cel biznesowy

Barber Shop Deluxe jest renomowanym salonem fryzjerskim działającym na rynku od 2006 roku. Brakuje jej jednak odpowiedniego systemu, który uprościłby proces komunikacji klientów z firmą, szczególnie w sprawie umawiania wizyt oraz zarządzania nimi przez właściciela.

Proponowane rozwiązanie umożliwi usprawnienie procesu umawiania wizyt, zwiększenie efektywności wykorzystania czasu oraz poprawa komunikacji z klientami. Poprzez zastosowanie systemu rezerwacji terminów zintegrowanego z harmonogramem pracy firmy oraz cennikiem, właściciel salonu będzie miał lepszą kontrolę nad przepływem klientów i zasobów, minimalizując zaangażowanie pracowników w ten proces. Z kolei, klientom zostanie zapewniona wygoda i łatwość w umawianiu wizyt, a także pewność co do potwierdzenia terminu. Wdrożenie tej aplikacji pozwoli na zwiększenie liczby wykorzystanych rezerwacji oraz poprawę relacji z klientami, co w efekcie przyczyni się do zwiększenia przychodów i rozwoju firmy.

## Korzyści z wdrożenia

Przede wszystkim, aplikacja usprawni proces rezerwacji wizyt przez klientów, co wpływa na pozytywną opinię o firmie i zwiększa szanse na pozyskanie nowych klientów. Dzięki systemowi umawiania wizyt zintegrowanemu z harmonogramem pracy, salon może zaplanować swój czas i zminimalizować ryzyko przeciążenia grafiku. Ponadto, możliwość zarządzania cennikiem przez właściciela pozwala na łatwe wprowadzanie zmian oraz dostosowanie oferty do aktualnych potrzeb rynku.

System potwierdzania wizyty przez link w mailu oraz mailowe przypomnienia o terminie wizyty zwiększają skuteczność rezerwacji oraz minimalizują liczbę nieobecności klientów. Dodatkowo, automatyczne powiadomienie o anulowaniu rezerwacji w salonie uniemożliwia występowanie problemów z niezrealizowanymi wizytami, a także minimalizuje ryzyko utraty klienta, przez jednoczesne zaproponowanie terminów zastępczych.

Wprowadzenie powyższej aplikacji ma zatem na celu zwiększenie efektywności, lepszą organizację pracy w salonie i minimalizację strat, a także poprawę jakości obsługi klientów, co przekłada się na wzrost zadowolenia klientów oraz zwiększenie przychodów firmy.

## Charakterystyka użytkowników

Aplikacja dla salonu fryzjerskiego będzie przeznaczona dla trzech grup użytkowników: klientów, właściciela i pracowników. Wszyscy z nich będą mieli dostęp do informacji o dostępności wizyt, cenniku i harmonogramie pracy.

Klienci to główni użytkownicy aplikacji, którzy będą korzystać z niej w celu umawiania wizyt, przeglądania cennika i zarządzania swoimi preferencjami. Klienci oczekują łatwego i intuicyjnego interfejsu użytkownika, który pozwoli im szybko i bezproblemowo umówić wizytę w dogodnym dla nich terminie, zgodnie z harmonogramem pracy salonu.

Właściciel salonu będzie korzystał z aplikacji w celu zarządzania harmonogramem pracy i cennikiem. Będzie mógł modyfikować cennik, dodawać lub usuwać usługi, a także nadzorować realizację rezerwacji, bądź też anulować je w wygodny sposób w przypadku nagłych zdarzen. Właściciel oczekuje, że aplikacja pozwoli mu lepiej zarządzać swoim biznesem i zwiększyć jego efektywność.

Pracownicy salonu fryzjerskiego będą korzystać z aplikacji w celu korzystania z listy wizyt, by zarządzać swoją pracą, dodawania wizyt rezerwowanych telefonicznie lub w salonie. Pracownicy oczekują, że aplikacja będzie intuicyjna i łatwa w obsłudze, co pozwoli im skupić się na swojej pracy i zapewnić klientom wysoką jakość obsługi.

## Wymagania

### Funkcjonalne
* Jako klient chcę zarezerwować wizytę w wybranym terminie, żeby mieć pewność, że zostanę obsłużony w dogodnym dla mnie czasie.
* Jako klient chcę umawiać wizyty online, żeby zaoszczędzić czas i uniknąć oczekiwania w kolejce.
* Jako klient chcę móc wybrać usługę fryzjerską z cennika, żeby mieć pełną kontrolę nad kosztami.
* Jako klient chcę móc otrzymać przypomnienie o nadchodzącej wizycie drogą mailową, żeby nie zapomnieć o umówionej wizycie.
* Jako klient chcę otrzymywać potwierdzenie wizyty w formie mailowej z linkiem do potwierdzenia, żeby mieć pewność, że wizyta została umówiona i potwierdzona.
* Jako właściciel salonu chcę mieć dostęp do harmonogramu pracy pracowników, żeby móc zarządzać wizytami i dostosowywać grafik do zapotrzebowania klientów.
* Jako właściciel salonu chcę mieć możliwość aktualizowania cennika usług, żeby dostosować go do zmieniających się potrzeb klientów i rynku.
* Jako właściciel chcę mieć możliwość dodawania i edytowania usług w cenniku, żeby mieć aktualne informacje na stronie internetowej i aplikacji.
* Jako pracownik salonu chcę móc zobaczyć harmonogram pracy i informacje o wizycie klienta, żeby być przygotowanym do jego obsługi.

### Niefunkcjonalne
* Baza danych
![image](https://github.com/jakubir/jakubirla-projekt-specyfikacja/assets/76539255/4a5eed6e-8722-4688-b604-6b4a90babc32)
* Diagram klas
![image](./zasoby/diagram_klas.png)
* Diagram przypadków użycia
![image](./zasoby/diagram_przypadkow_uzycia.png)
