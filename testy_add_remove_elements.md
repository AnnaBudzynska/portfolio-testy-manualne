# Testy na stronie "[Add/Remove Elements](https://the-internet.herokuapp.com/add_remove_elements/)"

## Test 1: Dodawanie nowego elementu
**Cel**: Sprawdzić, czy kliknięcie przycisku „Add Element” dodaje nowy przycisk na stronie.

**Kroki**:
1. Wejdź na strone "https://the-internet.herokuapp.com/add_remove_elements/".
2. Kliknij przycisk "Add Element".
3. Sprawdź, czy nowy prrzycisk "Delete"pojawił się na stronie.

**Oczekiwany rezultat**: Po klieknięciu przycisku "Add Element" powinien pojawić się nowy przycisk "Delete" na stronie.

_ _ _

## Test 2: Usuwanie elementu
**Cel**: Sprawdzić, czy kliknięcie przycisku "Delete" usuwa przycisk "Delete"

**Kroki**:
1. Wejdź na strone "https://the-internet.herokuapp.com/add_remove_elements/".
2. Kliknij przycisk "Add Element" (jeśli jeszcze nie dodałeś elementu).
3. Kliknij przycisk "Delete".
4. Sprawdź ,czy przycisk "Delete" zniknął ze strony.

**Oczekiwany rezultat**: Po kliknięciu "Delete" przycisk powinien zniknąć ze strony

_ _ _

## Test3: Dodawanie wielu elementów
**Cel**: Sprawdzić, czy można dodać wiele przycisków "Delete na stronie"

**Kroki**:
1. Wejdź na stronę "https://the-internet.herokuapp.com/add_remove_elements/".
2. Kliknij przycisk "Add Elements" kilka razy (np. 3-5 razy).
3. Sprawdź, czy wszystkie kliknięte przyciski "Delete" są widoczne na stronie.

**Oczekiwany rezultat**: Po kilku kliknięciach przycisku „Add Element” na stronie powinno pojawić się tyle przycisków „Delete”, ile razy kliknęliśmy przycisk.

## Test 4: Sprawdzzenie działania przycisków po odświeżeniu strony
**Cel**: Sprawdzić, czy elementy dodane do strony pozostają na niej po odświeżeniu strony.

**Kroki**:
1. Wejdź na stronę "https://the-internet.herokuapp.com/add_remove_elements/".
2. Kliknij przycisk "Add Elemnts" (dodaj conajmniej jeden przycisk "Delete").
3. Odśwież stronę (naciśnij F5 lub przycisk "Reload" w przeglądarce).
4. Sprawdź, czy przycisk "Delete" pozostał na stronie.

**Oczekiwany rezultat**: Po odświeżeniu strony, elementy dodane wcześniej (przyciski "Delete") powinny zniknąć, ponieważ nie zostały zapisane w stanie aplikacji.
