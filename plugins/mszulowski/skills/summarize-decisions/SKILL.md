---
name: summarize-decisions
description: Wypisuje ustalenia (decyzje operatora) z bieżącej rozmowy jako krótką listę punktów.
---

# Wypisz ustalenia z tej rozmowy jako listę punktów.

## Zasady

- Ustalenia to **moje** decyzje, nie Twoje propozycje. Wyjątek: zadałem pytanie, odpowiedziałeś, a ja tego nie zakwestionowałem - wtedy przyjmij, że zgodziłem się z Twoją odpowiedzią, ale **tylko w zakresie zadanego pytania**.
- Pomiń wszystko, co padło już w mojej pierwszej wiadomości.
- Każdy punkt maksymalnie krótki.
- Lista może mieć jeden punkt - to normalne. Nie dopisuj punktów, żeby ją wydłużyć.
- Jeśli nie ma żadnych ustaleń, napisz tylko o tym.
- Bez nagłówków, wstępu i podsumowania - tylko lista.

## Przykład (z innej rozmowy, o innej domenie)

```
- w momencie przyjęcia analizy zapisujemy wyniki badań z kodem analizy, bez referencji użytkownika.
- w momencie odczytu rekomendacji zdrowotnych dla użytkownika pobieramy jego najnowszą analizę i na podstawie kodu tej analizy pobieramy powiązane z nią rekomendacje
- wyścig w AnalysisProcessingApplicationService.fetchResult dla tej samej analizy to nie problem - rozwiążemy go innym taskiem później i piszemy tak jakby go nie było, czyli zapisanie rekomendacji dla analizy oznacza po prostu ich wstawienie do bazy.
```


