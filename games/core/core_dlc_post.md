### Games community
#### POST comments

Тестовые данные: https://games.alpha.g-spot.website/swagger/

1. Запустить Postman
2. Создать новую коллекцию или импортировать информацию с swaggera https://games.alpha.g-spot.website/swagger/?format=openapi
3. Создать новый запрос
4. Авторизироваться: используя валидные значения Username:tester, Password:tester(в Postman выбрать пункт Autorization)
5. Выбрать метод POST для Request
6. Ввести в Body: 
7. {
  "game": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "dlc": [
    "3fa85f64-5717-4562-b3fc-2c963f66afa6"
  ]
}
8. Ввести URL: https://games.alpha.g-spot.website/api/v1/core/dlc/
9. Отправить Request

Ожидаемый результат:
Server response: status code 201 - Created

Постусловие: удалить тестовые данные

Автор: Дмитрий

Тест выполнен
| Дата | Время | Результат | Имя | Баг № Trello |
| --- | --- | --- | --- | --- |
| 2023-06-10 | 13:10 | FAIL | Дмитрий | https://trello.com/c/XFuZKCua | 