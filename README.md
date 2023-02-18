Aplikacja Vaadin CRM	


Backend: Java

Frontend: Vaadin (framework)

Database: H2 Database (system PostgreSQL)

Adres internetowy aplikacji: 
http://myfirstwebapp-env.eba-eueeuq5v.us-east-1.elasticbeanstalk.com/login

	
  Moja aplikacja w celu połączenia z bazą danych wykorzystuje repozytoria Spring Data JPA. Biblioteki Spring Data 
  pozwalają mi implementować operacje 
  takie jak tworzenie, czytanie, nadpisywanie (update) oraz usuwanie baz danych.  
	Ścieżka: com.example.application.data.repository .

	
  W swojej aplikacji umożliwiam użytkownikowi wykonywanie operacji na bazie danych za pomocą intuicyjnego wykorzystywania “layout’u” (warstwy graficznej
  aplikacji) - za pomocą kliknięć w przyciski na stronie, pod powłoką graficzną wykonują się zmiany w bazie danych. Te operacje na bazie danych zostały
  ułatwione dzięki wykorzystaniu bibliotek Spring Service.
	Ścieżka: com.example.application.data.service .
	Ścieżka: com.example.application.views.list .

	
  W klasie Javy - ListView w konstruktorze klasy jako parametr wykorzystuje obiekt bazujący na bibliotekach Spring Service. W tej klasie wykorzystuje
  metody które są dziedziczone z bibliotek Vaadin, dzięki którym w Javie mogę napisać “layout” aplikacji, która wykorzystuje bazy danych za pomocą
  elementów tego “layout’u” - przycisków.

	
  Korzystałem z bazy danych wykorzystując biblioteki Springboot. Aplikacja ma swój adres internetowy oraz wszelkie postępy w pracy nad aplikacją są
  widoczne w komitach na moim githubie.
