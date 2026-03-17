# Mieszkanie dla studenciaka MiNI 🏠🎓

### Autorzy
**Wiktoria Grodzka | Maria Harbaty | [cite_start]Michał Grzegory** [cite: 42]
[cite_start]*Wydział Matematyki i Nauk Informacyjnych Politechniki Warszawskiej* [cite: 40, 41]

---

##  Cel projektu
[cite_start]Projekt analizuje rynek mieszkaniowy w Warszawie, aby pomóc studentom i absolwentom MiNI podjąć decyzję o zakupie pierwszego mieszkania w świecie rosnących cen[cite: 8, 9, 10]. [cite_start]Analiza skupia się na optymalizacji kosztów pod kątem metrażu, liczby pokoi oraz lokalizacji[cite: 4, 13, 22].

##  Główne Analizy

### 1. Najkorzystniejszy Metraż
[cite_start]Przeanalizowano mieszkania wybudowane w Warszawie w latach 1960-2023[cite: 5].
* **Wniosek:** Najniższa cena za metr kwadratowy występuje w przedziale **(50, 70) m²**[cite: 6].
* [cite_start]Na tym metrażu skupiają się dalsze rozważania projektowe[cite: 6].

### 2. Liczba Pokoi
[cite_start]Zbadano zależność między liczbą pokoi a ceną za m²[cite: 13, 15].
* **Wniosek:** Najniższa cena jednostkowa przypada na **mieszkania trzypokojowe**[cite: 14].

### 3. Lokalizacja (Odległość od MiNI)
Analiza przestrzenna ofert w Warszawie z punktem orientacyjnym na wydziale MiNI[cite: 21, 22, 25].
* [cite_start]**Centrum:** Najwyższe ceny koncentrują się w Śródmieściu i na Mokotowie[cite: 24].
* [cite_start]**Optymalizacja:** Wybrano zakres **5 – 7.5 km** od centrum, aby zachować balans między ceną a dojazdem[cite: 25, 26].

---

##  Analiza Finansowa i Oszczędności
[cite_start]Wyliczono czas potrzebny na zgromadzenie funduszy na wkład własny lub zakup przy następujących założeniach[cite: 34, 36]:
* [cite_start]**Koszt lokum:** Oszacowany na poziomie **400 tys. zł** (na osobę, przy zakupie w parze)[cite: 35, 37].
* **Zarobki:** Średnie zarobki absolwentów MiNI z rocznym wzrostem pensji o 5%[cite: 36].
* [cite_start]**Oszczędności:** Pieniądze odkładane na konto z oprocentowaniem 4-5%[cite: 36, 39].

| Procent odkładanych dochodów | Szacowany wiek zakupu (w parze) |
| :--- | :--- |
| 10% | ok. [cite_start]45-50 lat [cite: 48, 49] |
| **15%** | [cite_start]**37 lat** [cite: 38] |
| 20% | ok. [cite_start]32 lata [cite: 48, 49] |

---

##  Technologie
Projekt został przygotowany w środowisku **RStudio**.
* **Język:** R
* **Pakiety:** `ggplot2` (wizualizacje), `dplyr` (obróbka danych).

##  Jak korzystać z projektu?
1. Otwórz plik projektu `.Rproj` w RStudio.
2. Upewnij się, że masz zainstalowane niezbędne biblioteki.
3. Uruchom skrypty, aby odtworzyć wykresy i analizę finansową.

---
[cite_start]*Projekt zrealizowany w ramach zajęć na Wydziale MiNI PW.* [cite: 40, 41]
