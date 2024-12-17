# Spring Web Application - Hello Vistula

Aplikacja "Hello Vistula" jest prostym projektem opartym na frameworku Spring, który umożliwia użytkownikowi interakcję z dwiema stronami internetowymi. Projekt ma na celu zaprezentowanie podstawowych możliwości Springa oraz Thymeleaf jako silnika szablonów. Aplikacja wyświetla powitanie na pierwszej stronie oraz umożliwia wprowadzenie imienia, które jest następnie wyświetlane na drugiej stronie.

## Funkcjonalności

### Strona główna ("/")
Po wejściu na stronę główną użytkownik widzi powitaną wiadomość:

**"Hello Vistula, in my first Spring controller!"**

### Strona powitania ("/greeting")
Na tej stronie użytkownik może podać swoje imię poprzez parametr URL, na przykład:

`http://localhost:8080/greeting?name=John`

Aplikacja wyświetli spersonalizowane powitanie, takie jak:

**"Hello, John!"**

Jeśli użytkownik nie poda imienia, aplikacja użyje domyślnej wartości **"World"**, wyświetlając:

**"Hello, World!"**

### Obrazek
Na stronie powitania użytkownik zobaczy również obrazek (kot), który jest załadowany z zewnętrznego źródła:

![Cool Cat](https://gratisography.com/wp-content/uploads/2024/10/gratisography-cool-cat-800x525.jpg)

## Technologie

- **Spring Boot** – użyty jako główny framework do stworzenia aplikacji backendowej.
- **Thymeleaf** – silnik szablonów, który renderuje HTML na podstawie danych z kontrolerów.
- **Java** – język programowania wykorzystywany do budowy logiki aplikacji.
