System zarządzania cyfrową biblioteką

## Spis treści

1. Opis projektu
2. Pobieranie dodatkowych paczek
3. Uruchomienie aplikacji
4. Funkcjonalności
5. Przykładowe dane


## 1. Opis projektu
Projekt systemu zarządzania cyfrową biblioteką jest aplikacją internetową wykorzystującą model MVC, która umożliwia użytkownikowi:
przeglądanie biblioteki książek, edycja informacji o książkach, dodawanie oraz usówanie nowych dzieł literackich.


## 2. Pobieranie dodatkowych paczek
Aby projekt działał prawidłowo należy poprać zewnętrzne biblioteki:
- Ekspress.js,
- EJS,

Aby zainstalować wyżej wymienione biblioteki należy uruchomić środowisko programistyczne(Visual Studio Code), następnie przejść do folderu z naszym projektem, uruchomić terminal i wpisać następujące polecenia:
1) npm install express
2) npm install ejs


## 3. Uruchomienie aplikacji
- Upewnij się, że na Twoim systemie jest zainstalowany Node.js.
- Sklonuj repozytorium projektu z GitHuba.
- Wykonaj działania z punktu 2.
- Po zainstalowaniu paczek wpisz w terminalu node app.js.
- Uruchom przeglądarkę.
- Wpisz następujący adres: "http://localhost:3000", następnie wcisnij Enter.

## 4. Funkcjonalności
- Przeglądanie zawartości biblioteki: Wytkownicy mogą przeglądać zawartość biblioteki na stronie głównej aplikacji. Znajdą tam informacje takie jak nawa dzieła, autor, oraz rok powstania.
- Edycja: użytkownik po naciśnięciu przyciku edytuj zostanie przekierowany na osobny widok, w którym może zmienić informacje na temat danego dzieła.
- Usówanie: użytkownik może usunąć książki z biblioteki za pomocą przycisku usuń.
- Dodawanie książek: użytkownik po kliknięciu przycisku dodaj książke zostanie przekierowany na osobny widok, w którym po wypełnieniu formuklarza może dodać nowe dzieło do biblioteki


## 5.Przykładowe dane
Plik nie wymaga żadnego pliku z danymi, ponieważ zostały one zapisane na stałe tak aby można było przetestować aplikację.
