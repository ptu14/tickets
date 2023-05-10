## Zadanie 1 
1. Stwórz nowe repozytorium na GitHub i sklonuj je na swoim lokalnym komputerze.
1. Utwórz plik index.html i styles.css w głównym katalogu repozytorium.
1. W pliku index.html dodaj podstawowy szablon HTML5 z odpowiednim tytułem strony, np. "Rejestracja na koncert".
1. Podłącz plik CSS do pliku HTML za pomocą elementu `<link>`.
1. Zacommituj i wypchnij zmiany do repozytorium na **GitHub**.
1. Stwórz nowego brancha o nazwie "formularz-rejestracji" i przełącz się na niego.
1. W pliku `index.html` na branchu "formularz-rejestracji" stwórz formularz rejestracji z następującymi polami:
   - Imię (typ: text)
   - Nazwisko (typ: text)
   - Adres e-mail (typ: email)
   - Data urodzenia (typ: date)
   - Przycisk do wysyłania formularza (typ: submit)
   > Upewnij się, że używasz semantycznych elementów HTML, takich jak `<form>`, `<fieldset>`, `<label>` i `<input>`.

   > Szerokość formularza `640px`, wycentrowany na stronie. Użyj fontu `Arial` i koloru `#0d6efd`.


1. W pliku `styles.css` na branchu "formularz-rejestracji" zastosuj odpowiednie style CSS, dbając o estetykę i użyteczność formularza.
1. Zacommituj i wypchnij zmiany na branchu "formularz-rejestracji" do repozytorium na **GitHub**.
1. Utwórz pull request z brancha "formularz-rejestracji" do głównego brancha repozytorium i poproś nauczyciela o sprawdzenie.

---

## Zadanie 2

1. Stwórz nowego brancha o nazwie "dodatkowe-pola" i przełącz się na niego.
1. W pliku `index.html` do istniejącego formularza rejestracji dodaj następujące pola:
   - Wybór miejsca (typ: select) z trzema opcjami: strefa VIP, strefa normalna, strefa taniego biletu
   - Zgoda na przetwarzanie danych (typ: checkbox)
   > tekst zgody: "Wyrażam zgodę na przetwarzanie moich danych osobowych w celu rejestracji na koncert."
1. Powtórz kroki z zacommitowaniem i wypchnieciem zmian z zadania 1.

## Zadanie 3

### Dostosuj formularz do widoku z `zadanie3.png` i dodaj accessibility

1. Dodaj background, wykorzystaj [ten](http://t0.gstatic.com/licensed-image?q=tbn:ANd9GcRSWG4lk-BWHcmRMfh9R0mKFugRj3tqNG29pXhCgDZWzRkGEnO2W5LZfoo_TDG7ufk0gICTd3SP2x-dXwUP--Y) lub własny obrazek.
1. Dodaj efekt blur do formularza. Wykorzystaj  `background: rgba(255,255,255,.7)` oraz `backdrop-filter: blur(8px)`
1. Dodaj stan `hover` do przycisku, zmien mu kolor na `#0b5ed7`
1. Dodaj stan `focus-visible` do inputow. Powinny mieć w tym stanie obramowanie `2px` koloru `#0b5ed7`. Możesz użyć `outline`, `border` lub `box-shadow`. Zastanów się, czym różni się `focus-visible` od `focus`?
