# Portfolio 
# About me 👩
My name is Natalia Jęcz and I'm 32 years old. I've been studying English Philology for five years and graduated with Master Degree. I've also gained Bachelor Degree at Managment in Public Administration. Since the beginning of my career, I've been occupied with working with children in the positions of teacher and entertainer. I am an enthusiastic team player with the experience of working in the international environments in many countries in Europe. For the last three years, I found my way back in Poland, where I've been developing my skills in IT industry as Quote and Configuration Specialist. Recently, I've started my interest in software testing and I continuously develop my skills to become a tester. 
Throughout my whole career, I've always been professional and passionate about what I've been doing. Thanks to my experience I learnt how important the high quality of service is. I enjoy learning new things and I'm always keen on making changes and improvements.

# Courses 📘
* Praktyczny kurs testowania oprogramowania (Udemy)
* Tester Manualny (zgodnie z metodologią ISTQB) from Codebrainers - ongoing
* Kurs SQL od podstaw | MySQL (Udemy) - ongoing
* Zostań testerem manualnym - DareIT Portfolio Challenge

# Tools 🛠
* Jira
* Testlink
* Slack
* DevTools
* BrowserStack
* XAMPP
* GitHub
* OWASP ZAP
* DeskPro
* Microsoft Dynamics AX

# Skills 💻
* SQL
* Creating test cases
* Reporting bugs 

# My projects ✏
## Futbol Kolektyw 
* [Test cases based on User Story](https://docs.google.com/spreadsheets/d/1syqu9mJb71_WnkooivLK1zLWJ-v2yaMQrSzOwwVtOYU/edit#gid=0)
* [Test cases based on my own experience](https://docs.google.com/spreadsheets/d/1bkr1_z5aCD0tA7HTI9IfEyB1jdgK-0rv5SbLUGD6NGw/edit#gid=0)
* [Bugs report](https://docs.google.com/spreadsheets/d/1BcC22mjQuX5peX6jiFsOTzkBLZ9Dn8q0PMSzjsb14_I/edit#gid=0)
* [Test summary report](https://docs.google.com/document/d/143ppGo7Bm9uzuukY2kQC4twtTQvb9AqcUboSy8JxD7Q/edit)

## OLX - mobile app
* [Bugs report](https://docs.google.com/spreadsheets/d/19Cd6dE9-cTbnNsbfb2whdoJUfcf0KW8z8OvX10PbQtQ/edit#gid=0)

## Swipe to
*  [Bugs report in Jira](https://challangedareit.atlassian.net/jira/software/projects/CHAL/boards/1)

## SQL exercises
:question: 1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

:arrow_right: SELECT * FROM `actors` ORDER BY surname ASC

![image](https://user-images.githubusercontent.com/121819761/218564256-da6ed609-d51a-4a11-91fa-32e444d3f34d.png)

:question: 2. Wyświetl film, który powstał w 2019 roku.

:arrow_right: SELECT title FROM `movies` WHERE year_of_production = 2019

![image](https://user-images.githubusercontent.com/121819761/218565126-015ee78c-3a37-466f-814c-83cbcfa784f5.png)

:question: 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

:arrow_right: SELECT * FROM `movies` WHERE year_of_production BETWEEN '1900' AND '1999'

![image](https://user-images.githubusercontent.com/121819761/218565638-7a065ebf-85d6-4bec-8f23-769783828161.png)

:question: 4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.

:arrow_right: SELECT title, price FROM `movies` WHERE price < 7

![image](https://user-images.githubusercontent.com/121819761/218566083-3ae2a49a-5a3c-443d-9a6a-db5643dee0de.png)

:question: 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

:arrow_right: SELECT * FROM `actors` WHERE actor_id >=4 AND actor_id <=7

![image](https://user-images.githubusercontent.com/121819761/218566915-e4b8dcd8-d021-4d6e-ad71-d2b7e37bae5b.png)

:question: 6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

:arrow_right: SELECT * FROM `customers` WHERE customer_id % 2 = 0

![image](https://user-images.githubusercontent.com/121819761/218567909-2865483a-76aa-4045-a2eb-825b09273444.png)

:question: 7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

:arrow_right: SELECT * FROM `customers` WHERE customer_id IN ('1', '3', '5')

![image](https://user-images.githubusercontent.com/121819761/218568735-b68526f5-1a87-43d9-ab17-822efa69d14e.png)

:question: 8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An".

:arrow_right: SELECT * FROM `actors` WHERE name LIKE 'An%'

![image](https://user-images.githubusercontent.com/121819761/218569178-e5fbd1a6-be52-459d-a97c-81df44a40e21.png)

:question: 9. Wyświetl dane klienta, który nie ma podanego adresu email.

:arrow_right: SELECT * FROM `customers` WHERE email IS null

![image](https://user-images.githubusercontent.com/121819761/218569587-33a8687f-13a7-4faf-be35-55972e2461d2.png)

:question: 10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

:arrow_right: SELECT * FROM `movies` WHERE price > 9 AND movie_id BETWEEN 2 AND 8

![image](https://user-images.githubusercontent.com/121819761/218570296-0dc233c8-c5b1-4f7e-b9d0-f5b963e896f4.png)

:question: 11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój błąd.

:arrow_right: UPDATE customers SET surname = "Miler" WHERE surname = "Muler"

![image](https://user-images.githubusercontent.com/121819761/220195367-869af78b-16f5-4821-8542-fe628bc84ff0.png)

:question: 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila.

:arrow_right: SELECT customers.name, customers.email FROM customers JOIN sale ON sale.customer_id = customers.customer_id WHERE movie_id = 4

![image](https://user-images.githubusercontent.com/121819761/220754722-936bc86e-0b13-4eb7-ac5b-245ab576b907.png)

:question: 13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com.

:arrow_right: UPDATE customers SET email = "pati@mail.com" WHERE email IS NULL

![image](https://user-images.githubusercontent.com/121819761/220197824-4c25f721-edd2-41de-ab5f-069cf1f72f71.png)

:question: 14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

:arrow_right: SELECT customers.name, customers.surname, movies.title FROM customers JOIN sale ON customers.customer_id = sale.customer_id JOIN movies ON sale.movie_id = movies.movie_id 

![image](https://user-images.githubusercontent.com/121819761/220755548-825927ac-3618-4ca6-91c4-76ef862f36b9.png)

:question: 15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

:arrow_right: ALTER TABLE customers ADD pseudonym varchar (40)

![image](https://user-images.githubusercontent.com/121819761/220200067-635e6e2e-fe91-4e0c-a1f0-a362136dd6f3.png)

:arrow_right: UPDATE customers SET pseudonym = Concat(LEFT(name,2),RIGHT(surname,1))

![image](https://user-images.githubusercontent.com/121819761/220760705-572b4470-45d7-4eea-ab3b-4b74a058dd44.png)

:question: 16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

:arrow_right: SELECT DISTINCT sale.movie_id, movies.title FROM sale INNER JOIN movies on sale.movie_id = movies.movie_id

![image](https://user-images.githubusercontent.com/121819761/220449424-03375051-e53b-4e84-a980-f3a54f2ef3ff.png)

:question: 17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

:arrow_right: SELECT name FROM customers UNION SELECT name FROM actors ORDER BY name

![image](https://user-images.githubusercontent.com/121819761/220450642-22b82d5e-6856-4bf9-98ee-38ea50b8ecb3.png)

:question: 18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

:arrow_right: UPDATE movies SET price = price + 2.5 WHERE year_of_production > 2000

![image](https://user-images.githubusercontent.com/121819761/220452392-04c04150-73cf-4c0c-ae49-99123106580d.png)

:question: 19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał.

:arrow_right: SELECT actors.name, actors.surname, movies.title FROM actors JOIN cast ON actors.actor_id = cast.actor_id JOIN movies ON cast.movie_id = movies.movie_id WHERE actors.actor_id = 4

![image](https://user-images.githubusercontent.com/121819761/220759922-491b61cb-956d-403c-a9cb-e9b2a03b5d5e.png)

:question: 20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa.

:arrow_right: INSERT INTO customers VALUES (7, "Honia", "Stuczka-Kucharska", "honia@mail.com", "Hoa")

![image](https://user-images.githubusercontent.com/121819761/220746628-7ef74ad9-33a8-45dc-87e5-e313600c343b.png)
