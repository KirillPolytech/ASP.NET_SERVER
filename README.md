# ASP.NET_SERVER
 
Серверное приложение с использованием jwt токенов.

Описание программы:
API принимает запрос от клиента на регистрацию. Идёт проверка логина и пароля. Если всё в порядке, то отправляет клиенту JWT-токен.
API принимает запрос на авторизацию. Идёт проверка хэш суммы паролей и сравнение логинов. Если всё в порядке, возвращаются необходимые клиенту данные.

В проекте используется Clean Architecture. Это архитектурный стиль, разработанный Робертом Мартином, автором книги “Чистый код”. Этот стиль призван помочь разработчикам создавать более понятные, гибкие и легко поддерживаемые программные системы. Суть Clean Architecture заключается в разделении системы на слои, каждый из которых имеет свою четкую функцию и ограничен определенным набором абстракций. Это позволяет изменять или расширять функциональность системы без необходимости изменять другие ее части.

Для работы с базой данных в ASP.NET используется Entity Framework
(EF), который позволяет разработчикам работать с данными через объекты и
классы, а не через SQL-запросы. EF позволяет создавать модели данных на
основе существующей базы данных или создать новую базу данных на основе
существующих моделей данных.
