# Topologie Sieci

## Sieci Fizyczne
Sieci fizyczne odnoszą się do fizycznego ułożenia kabli, urządzeń i połączeń. Przykłady:
- **Topologia magistrali** (Bus) : jest to sieć w której wszystkie urządzenia są podłączone do wspólnego przewodu komunikacyjnego.
  - Wady: Awaria głównej magistrali powoduje zatrzymanie pracy całej sieci, ograniczona wydajność.
  - Zalety: Prosta implementacja i niski koszt, Łatwa rozbudowa poprzez dodanie nowych urządzeń.
  - Gdzie stosowane: W starszych sieciach LAN, które miały ograniczoną liczbę urządzeń, do celów edukacyjnych i testowych.
- **Topologia pierścienia** (Ring): jest to sieć, gdzie urządzenia są połączone w zamkniętą pętlę.
  - Wady: Awaria jednego urządzenia lub połączenia powoduje przerwanie działania całej sieci, trudniejsza diagnostyka i naprawa.
  - Zalety: Brak kolizji danych, ponieważ ruch odbywa się w sposób uporządkowany, stabilna wydajnośc przy dużej liczbie urządzeń.
  - Gdzie stosowane: W sieciach korporacyjnych opartych na technologii FDDI, w starszych systemach telekomunikacyjnych.
- **Topologia gwiazdy** (Star): jest to sieć, w której wszystkie urządzenia są połączone z jednym, centralnym punktem, najczęściej switchem lub routerem.
  - Wady: Awaria centralnego węzła powoduje zatrzymanie całej sieci, wysokie koszty wdrożenia ze względu na potrzebę większej ilości okablowania.
  - Zalety: Łatwe diagnozowanie problemów, prosta rozbudowa.
  - Gdzie stosowane: Nowoczesne sieci LAN w biurach i szkołach, sieci domowe z routerem jako centralym punktem.


## Sieci Logiczne
Sieci logiczne opisują sposób przesyłania danych między urządzeniami, niezależnie od fizycznej struktury. Przykłady:
- **Punkt-punkt** (Point-to-Point): jest to protokól gdzie dane przesyłane są tylko z jednego komputera do drugiego.
  - Wady: Słaba ochrona szyfrowania.
  - Zalety: Przekazywanie danych na duże odległości.
  - Zastosowanie: Łączenie jednego systemu z innym.
- **Przekazywanie żetonu** (Token Passing): jest to protokół, gdzie dane są przekazywane kolejno do urządzeń połączonych w sieć.
  - Wady: Wysoka cena, awaria jednego więzła powoduje zatrzymanie sieci.
  - Zalety: Prędkośc przekazywania danych.
  - Zastosowanie: W przekazywaniu tych samych danych do wielu urządzeń w tym samym czasie.
- **Wielodostępowa** (Multiple Access): jest to protokól który umożliwia komunikację urządzeń w sieci poprzez jedno fizyczne medium transmisyjne.
  - Wady: 
  - Zalety: 
  - Zastosowanie: ?
