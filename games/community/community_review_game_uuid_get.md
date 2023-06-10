### Games community
#### Get comments

Тестовые данные: https://games.alpha.g-spot.website/swagger/

1. Запустить Postman
2. Создать новую коллекцию или импортировать информацию с swaggera https://games.alpha.g-spot.website/swagger/?format=openapi
3. Создать новый запрос
4. Авторизироваться: используя валидные значения Username:tester, Password:tester(в Postman выбрать пункт Autorization)
5. Выбрать метод GET для Request
6. Ввести URL: https://games.alpha.g-spot.website/api/v1/community/review/3/?limit=10&offset=5
7. Отправить Request

Ожидаемый результат:
Server response: status code 200 - OK

Постусловие: удалить тестовые данные

Автор: Дмитрий

Тест выполнен
| Дата | Время | Результат | Имя | Баг № Trello |
| --- | --- | --- | --- | --- |
| 2023-06-10 | 12:35 | FAIL | Дмитрий | https://trello.com/c/Ycxrefru | 