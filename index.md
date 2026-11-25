# Polityka prywatności — Premio Agroma

**Data wejścia w życie:** 25 listopada 2026
**Administrator:** PHU AGROMA Sp. z o.o. Jawor, ul. Słowackiego 1, 59-400 Jawor, Polska
**Kontakt:** serwis@agroma-jawor.pl · +48768703071

## 1. O aplikacji

"Premio Agroma" (dalej: **Aplikacja**) to mobilna aplikacja na Androida (Google Play) i iPhone'a (App Store) pozwalająca klientom serwisu AGROMA PREMIO w Jaworze na umawianie wizyt serwisowych, zarządzanie pojazdami i przeglądanie historii wizyt. Aplikacja wykorzystuje wbudowany widok strony internetowej (WebView) do połączenia z systemem rezerwacji `bookingforsure.eu` (operatorem rezerwacji jest podmiot zewnętrzny — patrz pkt 6).

## 2. Jakie dane przetwarzamy

Aplikacja przetwarza wyłącznie dane wprowadzone przez Ciebie samodzielnie:

**Dane właściciela pojazdu (profil):**
- imię i nazwisko
- numer telefonu
- adres e-mail

**Dane pojazdu (możesz dodać dowolną liczbę pojazdów):**
- marka, model, rok produkcji
- numer rejestracyjny
- typ silnika, pojemność
- VIN
- notatki własne

**Dane wizyt:**
- typ usługi, data, godzina
- numer rezerwacji
- status wizyty, notatki

## 3. Gdzie są przechowywane Twoje dane

**Wszystkie powyższe dane są zapisywane wyłącznie lokalnie na Twoim urządzeniu** w bazie danych aplikacji (Android: Room / SQLite, iPhone: SwiftData). **Nie wysyłamy ich na nasze serwery, nie udostępniamy partnerom marketingowym, nie korzystamy z analityki zewnętrznej.**

Aplikacja nie wymaga rejestracji ani logowania.

## 4. Wykorzystanie uprawnień

Aplikacja prosi o następujące uprawnienia (na Androidzie i na iPhonie odpowiadają im te same zgody systemowe). Każde z nich jest opcjonalne lub wykorzystywane wyłącznie w opisanym poniżej celu:

| Uprawnienie | Cel |
|---|---|
| **Internet** | Wyświetlenie formularza rezerwacji `bookingforsure.eu` w WebView. Na Androidzie także pobieranie logotypów marek pojazdów; na iPhonie logotypy są wbudowane w aplikację. Na iPhonie dostęp do internetu nie wymaga osobnej zgody. |
| **Powiadomienia** (POST_NOTIFICATIONS) | Wysyłanie lokalnych przypomnień o wizycie (dzień przed, godzinę przed) oraz o sezonowej wymianie opon. Brak powiadomień marketingowych. |
| **Aparat** (CAMERA) | Skanowanie kodów QR powiązanych z lokalizacją serwisu/depotami. Aparat działa tylko gdy aktywnie korzystasz ze skanera — obraz nie jest zapisywany ani wysyłany. |

## 5. Transmisja danych do systemu rezerwacji

Podczas umawiania wizyty Aplikacja otwiera formularz `bookingforsure.eu/bc?servis=4134` w komponencie WebView. Wybrane dane (imię, nazwisko, telefon, e-mail, opis pojazdu, numer rejestracyjny) są **automatycznie wpisywane** w pola tego formularza, abyś nie musiał ich wpisywać ręcznie. Po zatwierdzeniu rezerwacji dane są wysyłane bezpośrednio do operatora `bookingforsure.eu`.

Polityka prywatności operatora `bookingforsure.eu` dostępna jest pod adresem: https://www.bookingforsure.eu/

## 6. Podmioty trzecie

- **bookingforsure.eu** — operator systemu rezerwacji wizyt (administrator danych przekazywanych przez formularz rezerwacji).
- **Google Play Services** — sklep, z którego pobrałeś Aplikację na Androida. Google przetwarza informacje o instalacji i awariach zgodnie z własną polityką prywatności (https://policies.google.com/privacy).
- **Apple App Store** — sklep, z którego pobrałeś Aplikację na iPhone'a. Apple przetwarza informacje o instalacji i, jeśli wyrazisz na to zgodę, raporty o awariach zgodnie z własną polityką prywatności (https://www.apple.com/legal/privacy/).

Aplikacja **nie zawiera reklam, SDK analitycznych, trackerów, ani mechanizmów profilowania.**

## 7. Bezpieczeństwo

- Wszystkie połączenia sieciowe wykonywane przez Aplikację korzystają z HTTPS.
- Dane lokalne są chronione mechanizmami izolacji aplikacji (sandbox) systemu Android i iOS.
- Android: Aplikacja nie ma kopii zapasowej w chmurze (`allowBackup="false"`). Dane są przypisane do urządzenia.
- iPhone: dane Aplikacji mogą trafić do kopii zapasowej urządzenia (iCloud lub komputer), jeśli masz ją włączoną w ustawieniach telefonu. Kopią zarządzasz Ty i Apple; nie mamy do niej dostępu.

## 8. Twoje prawa

Masz prawo do:
- **wglądu** w swoje dane — w aplikacji, w zakładce *Profil*
- **edycji** danych — bezpośrednio w aplikacji
- **usunięcia danych** — odinstalowując aplikację usuwasz wszystkie dane lokalne; nie istnieje kopia po stronie naszej firmy
- **kontaktu w sprawie ochrony danych** — pod adresem serwis@agroma-jawor.pl

W zakresie rezerwacji wysłanych do `bookingforsure.eu` realizacja praw RODO odbywa się u tego operatora.

## 9. Dzieci

Aplikacja jest przeznaczona dla użytkowników 18+ (kierowców pojazdów). Nie zbieramy świadomie danych osób poniżej 13 r.ż.

## 10. Zmiany polityki

Każda istotna zmiana polityki prywatności zostanie ogłoszona w aplikacji oraz na tej stronie, z aktualizacją daty wejścia w życie u góry dokumentu.

## 11. Kontakt

W sprawach związanych z prywatnością i danymi osobowymi pisz na: **serwis@agroma-jawor.pl**
