
![WA-GIT](https://github.com/user-attachments/assets/12d0aded-4001-42e9-bada-7491ad1f1afa)

![WA2_GIT](https://github.com/user-attachments/assets/48cfe620-4b58-43aa-a1bc-9598d0072d6a)

#Aplikacja Sprawdzajaca pogode

Ten projekt to prosta aplikacja pogodowa napisana w Javie przy użyciu frameworka Spring Boot. Pozwala użytkownikowi na wprowadzenie nazwy miasta i wyświetla aktualne warunki pogodowe dla tego miasta.

##Na czym polega projekt

Głównym celem aplikacji jest pobieranie danych pogodowych z zewnętrznego API OpenWeatherMap i prezentowanie ich w przystępny sposób. Użytkownik wchodzi na stronę główną, gdzie może wpisać nazwę miasta. Po zatwierdzeniu, aplikacja wysyła zapytanie do API OpenWeatherMap, przetwarza otrzymane dane i wyświetla je na nowej stronie.

Aplikacja pokazuje następujące informacje pogodowe:

 - Nazwa miasta i kraj
 - Opis warunków pogodowych (np. "zachmurzenie", "słonecznie")
 - Temperatura
 - Wilgotność
 - Prędkość wiatru
 - Ikona pogody (bazując na ID z OpenWeatherMap)
W przypadku, gdy miasto nie zostanie znalezione lub wystąpi błąd podczas pobierania danych, aplikacja wyświetli komunikat o błędzie.
