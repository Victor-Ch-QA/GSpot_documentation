### Games community
#### Get comments

Тестовые данные: https://games.alpha.g-spot.website/swagger/

1. Запустить Postman
2. Создать новую коллекцию или импортировать информацию с swaggera https://games.alpha.g-spot.website/swagger/?format=openapi
3. Создать новый запрос:(для этого в окне Postmana выбрать '+'в вкладках наверху или нажать на '...' в созданной коллекции и выбрать Add request
4. Авторизироваться:Тип Basic Auth, используя валидные значения Username:tester, Password:tester(в Postman выбрать пункт Autorization)
5. Выбрать метод GET для Request(Запрос)
6. Ввести URL: https://games.alpha.g-spot.website/api/v1/community/comments/787141/?page=1&per_page=2
7. Отправить Request(Запрос) (для этого нажать на синию кнопку 'Send')

Ожидаемый результат:
Server response: status code 200 - OK(Просмотр в сообществе созданных комментариев по ID)

Постусловие: удалить тестовые данные

Автор: Дмитрий

Тест выполнен
| Дата | Время | Результат | Имя | Баг № Trello |
| --- | --- | --- | --- | --- |
| 2023-06-10 | 10:39 | PASS | Дмитрий |  | 