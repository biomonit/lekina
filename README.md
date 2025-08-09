# lekina.pl 

***

## Specyfikacja portalu lekina.pl

### 1. Cel portalu  
- Umożliwienie pacjentom zgłaszanie problemów zdrowotnych, szybkie znalezienie optymalnych ofert na leki dostępne na receptę,  
- Integracja z serwisami typu e-recepta poprzez API dla uzyskania kodów recept elektronicznych,  
- Optymalizacja zakupów leków poprzez wskazanie aptek oferujących najniższe ceny,  
- Umożliwienie zamówienia leków kurierowi z pełnomocnictwem pacjenta, z zachowaniem wymogów prawnych dotyczących wydawania i transportu leków.

### 2. Kluczowe funkcje

#### a) Rejestracja i profil użytkownika  
- Bezpieczna rejestracja z weryfikacją tożsamości (np. profilem zaufanym, bankowością elektroniczną lub e-podpisem),  
- Dane pacjenta: imię, nazwisko, PESEL, dane kontaktowe.

#### b) Zgłaszanie problemu zdrowotnego  
- Formularz zgłoszenia opisu problemu, ewentualne dane uzupełniające, opcjonalna historia choroby lub lista leków,  
- Przekierowanie do lekarza online z serwisu e-recepta.

#### c) Integracja API z serwisami e-recept (np. erecept.pl)  
- Automatyczne pozyskiwanie danych o wystawionych e-receptach, kodach recept, szczegółach leków,  
- Możliwość wyboru apteki na podstawie dostępności i ceny.

#### d) Porównanie cen leków w aptekach  
- Aktualizacja ofert aptek (dostępność, cena), ranking wg najniższej ceny,  
- Wskazanie apteki do odbioru lub realizacji wysyłki.

#### e) Obsługa pełnomocnictw  
- Formularz online generujący i akceptujący upoważnienia z elektronicznym podpisem,  
- Zapisywanie i przesyłanie pełnomocnictwa do apteki.

#### f) Obsługa kuriera  
- Możliwość przypisania kuriera jako pełnomocnika do odbioru leku,  
- System potwierdzania odbioru przez kuriera z podpisem elektronicznym,  
- Automatyczne przesyłanie potwierdzeń odbioru do aptek.

#### g) Panel apteki i kuriera  
- Apteki otrzymują zamówienia, weryfikują pełnomocnictwa i wydają leki,  
- Kurierzy mają dostęp do listy odbiorów i potwierdzeń.

#### h) Bezpieczeństwo i zgodność prawna  
- Zgodność z wymogami RODO i prawa farmaceutycznego,  
- Monitorowanie procesu zgodnie z Dobrą Praktyką Dystrybucyjną,  
- Archiwizacja pełnomocnictw i potwierdzeń odbioru.

#### i) System powiadomień i raportowania  
- SMS, e-mail o statusie zamówienia i dostawy,  
- Raporty dla administracji portalu i aptek.

### 3. Wymagania techniczne

- Responsywny design dostosowany do urządzeń mobilnych i desktop,  
- Bezpieczne uwierzytelnianie i autoryzacja (OAuth2, JWT),  
- Szyfrowanie danych w spoczynku i w transmisji (TLS),  
- Skalowalność dla dużej liczby użytkowników,  
- Integracja z serwisami zewnętrznymi (API e-recept),  
- Mechanizm podpisu elektronicznego (np. integracja z usługami podpisu lub padem do podpisu odręcznego),  
- Panel administracyjny z rolami i uprawnieniami,  
- System audytu i logowania zdarzeń.

***

## Przykładowe prompty do generowania kluczowych elementów portalu

1. **Generuj formularz zgłoszenia problemu zdrowotnego z polami obowiązkowymi i opcjonalnymi, z walidacją danych i przyjaznym UI dla seniorów.**

2. **Stwórz schemat API integracji z serwisem erecept.pl do pobierania i potwierdzania e-recept, uwzględniając bezpieczeństwo i autentykację.**

3. **Napisz opis funkcji porównywania cen leków w aptekach online, uwzględniając aktualizację danych i wygodne sortowanie ofert.**

4. **Wygeneruj formularz online pełnomocnictwa z checkboxem na akceptację regulaminu i miejscem na odręczny podpis, zgodnego z polskim prawem farmaceutycznym i RODO.**

5. **Napisz regulamin korzystania z portalu mobilneleki.pl, skupiając się na przetwarzaniu danych osobowych i odpowiedzialności za usługi pośrednictwa leków.**

6. **Stwórz design panelu użytkownika (pacjenta) z widokiem aktualnych recept, historii zamówień oraz statusu dostawy.**

7. **Opisz mechanizm potwierdzania odbioru leków przez kuriera, w tym zapisywania podpisu elektronicznego i automatycznego przesyłania potwierdzeń do apteki.**

8. **Zaprezentuj plan wdrożenia zabezpieczeń danych zgodnych z RODO i wymogami prawa farmaceutycznego w kontekście przechowywania i przesyłania danych medycznych oraz pełnomocnictw.**
