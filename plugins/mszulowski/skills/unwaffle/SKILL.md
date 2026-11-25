---
name: unwaffle
description: Przepisuje ostatnią odpowiedź agenta, zostawiając tylko to, co wpływa na decyzje lub działania operatora.
argument-hint: [tekst]
---

# Usuń z odpowiedzi wszystko, co nic nie wnosi

Przepisz swoją ostatnią odpowiedź w tej rozmowie albo tekst podany na wejściu: $ARGUMENTS

## Zasady

- Zostaw tylko to, od czego zależy, co operator zdecyduje lub zrobi: odpowiedź na jego pytanie, wynik zadania, problem wymagający jego reakcji, uwagę, która może zmienić jego działanie, pytanie do niego.
- Usuń każde zdanie i fragment zdania, bez którego operator zdecydowałby i zrobił to samo, nawet jeśli jest prawdziwe.
- Nie dodawaj nowej treści i nie zmieniaj sensu tego, co zostaje.
- Odpowiedź ma najkrótszą formę, która to przekazuje, bez wstępu, podsumowania i komentarza o tym, co usunąłeś.
