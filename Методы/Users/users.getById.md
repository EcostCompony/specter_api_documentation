# users.getById
`Требуется токен доступа`  
Метод для получения объекта пользователя

| Параметр                   | Описание                                                |
| :------------------------- | :------------------------------------------------------ |
| **user_id**<br />`integer` | Индетификатор пользователя<br />`Обязательный параметр` |

### Результат
Возвращает [объект пользователя](https://github.com/EcostCompony/specter_api_documentation/blob/master/Объекты/Пользователь.md#Пользователь).

### Ошибки
В ходе выполнения могут произойти [общие ошибки](https://github.com/EcostCompony/specter_api_documentation/blob/master/Основное/Обработка%20ошибок.md#коды-общих-ошибок).
| Ошибка                  | Описание               |
| :---------------------- | :--------------------- |
| **50**<br />`not exist` | Пользователь не найден |