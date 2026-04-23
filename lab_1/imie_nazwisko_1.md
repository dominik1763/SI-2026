# Raport do Labu 1

## 1. Szybka mapa przypadków

| ID przypadku | Ocena | Jednozdaniowy dowód |
| --- | --- | --- |
| `c1_beginner_explanation` | `niejasne` | Bez `compare.md` nie da się sprawdzić, czy `v1` faktycznie lepiej tłumaczy początkującemu, czy tylko brzmi bardziej uporządkowanie. |
| `c2_brief_comparison` | `niejasne` | Ten przypadek powinien być oceniony na podstawie porównania odpowiedzi `v0` i `v1`, a tego materiału tutaj brakuje. |
| `c3_self_check_mode` | `niejasne` | Nie mam odpowiedzi systemu ani jawnego sprawdzenia, więc nie mogę pokazać, czy `v1` naprawdę lepiej wspiera samosprawdzenie. |
| `c4_course_uncertainty` | `niejasne` | Bez wyników porównania nie da się wykazać, czy `v1` lepiej zaznacza niepewność zamiast zgadywać. |
| `c5_feedback_mode` | `niejasne` | Sam opis zadania nie wystarcza, żeby stwierdzić poprawę w trybie feedbacku bez konkretnych odpowiedzi z obu wersji. |
| `c6_personalized_plan_limit` | `niejasne` | Brakuje dowodu, czy `v1` lepiej trzyma granicę personalizacji, bo nie ma odpowiedzi dla tego case’u. |

## 2. Główny argument

### Usprawnienie 1

- `case_id:` `brak pewnego wskazania`
- `dowód:` W przesłanych materiałach nie ma `src/outputs/compare.md`, więc nie ma konkretnego przypadku, w którym da się uczciwie pokazać poprawę.
- `dlaczego to jest realna poprawa:` Żeby mówić o realnej poprawie, trzeba porównać odpowiedzi `v0` i `v1`, a nie tylko założyć, że kontrakt zadania pomaga.

### Usprawnienie 2

- `case_id:` `brak pewnego wskazania`
- `dowód:` Wzór raportu wymaga, żeby każdy ważny wniosek miał `case_id` i konkretny dowód z odpowiedzi albo z jawnego sprawdzenia.
- `dlaczego to jest realna poprawa:` Bez takiego dowodu nie wiadomo, czy poprawiło się działanie systemu, czy tylko styl odpowiedzi.

### Jedno pozostałe ograniczenie

- `case_id:` `wszystkie przypadki`
- `dowód:` Analiza ma się opierać na odpowiedziach `v0` i `v1`, kontrakcie zadania `v1`, jawnych sprawdzeniach w `compare.md` i ocenie jakości odpowiedzi, a z tych rzeczy brakuje najważniejszego pliku z porównaniem.
- `dlaczego sam kontrakt zadania tego nie rozwiązuje:` Sam kontrakt może uporządkować odpowiedź, ale nie jest dowodem, że system działa lepiej albo bardziej poprawnie.

### Jedno odrzucone słabsze wyjaśnienie

- `słabsze wyjaśnienie:` `v1 jest lepsze tylko dlatego, że ma bardziej dopracowany opis zadania`
- `case_id:` `wszystkie przypadki`
- `dowód przeciw temu wyjaśnieniu:` Z materiału wprowadzającego wynika, że lepszy prompt albo kontrakt nie zastępuje kontekstu, weryfikacji ani szerszego projektu systemu, więc sam jego zapis nie dowodzi poprawy.

## 3. Ocena końcowa

- `werdykt:` `na podstawie tych dowodów nie wiadomo`
- `uzasadnienie z case_id:` Dla żadnego `case_id` nie mam tutaj odpowiedzi `v0` i `v1` ani jawnych sprawdzeń z `compare.md`, więc nie da się rzetelnie wskazać, gdzie `v1` rzeczywiście pomogło.

## 4. Wymagana ograniczona zmiana

- `edytowany plik:` `src/versions/v1_task_contract/task_contract.txt`
- `jednozdaniowy opis zmiany:` Dodałbym zapis, że jeśli system nie ma wystarczających danych, powinien to jasno zaznaczyć zamiast zgadywać odpowiedź.
- `docelowe case_id:` `c4_course_uncertainty`
- `co zmieniło się po uruchomieniu:` Nie mogę tego potwierdzić, bo w przesłanych materiałach nie ma wyniku po ponownym uruchomieniu porównania.

- `ocena zmiany:` `niejasne`
- `dowód:` Bez nowego `compare.md` nie da się sprawdzić, czy odpowiedź po zmianie była realnie lepsza.

## 5. Jak doszedłem lub doszłam do wniosku

- `2-4 najważniejsze obserwacje:`
  1. Laboratorium dotyczy różnicy między surową generacją a systemem z warstwą kontroli.
  2. Kontrakt zadania może poprawić format, ograniczenia i sposób odpowiedzi, ale sam nie daje gwarancji poprawności.
  3. Raport wymaga konkretnych dowodów przypisanych do `case_id`.
  4. W przesłanych plikach jest wzór raportu i opis zadania, ale nie ma wyników właściwego porównania.

- `czego te wyniki jeszcze nie dowodzą:` Nie dowodzą, że `v1` było lepsze albo gorsze; pokazują tylko, że bez danych z porównania nie da się tego uczciwie ocenić.

- `następny sensowny krok:` `dodatkowa weryfikacja`
- `krótkie uzasadnienie:` Trzeba zobaczyć rzeczywiste odpowiedzi `v0` i `v1` oraz jawne sprawdzenia z `compare.md`, bo dopiero wtedy można ocenić, czy kontrakt zadania dał realną poprawę.
