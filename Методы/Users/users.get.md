# users.get
Временный метод для получения индетификатора пользователя в «specter»

| Параметр                    | Описание                                                          |
| :-------------------------- | :---------------------------------------------------------------- |
| **ecost_id**<br />`integer` | Индетификатор пользователя в «ecost»<br />`Обязательный параметр` |

### Результат
Возвращает объект с полем `service_id`, который содержит индетификатор пользователя в «specter».

### Ошибки
В ходе выполнения могут произойти [общие ошибки](https://github.com/EcostCompony/specter_api_documentation/blob/master/Основное/Обработка%20ошибок.md#коды-общих-ошибок).
| Ошибка                                     | Описание                                    |
| :----------------------------------------- | :------------------------------------------ |
| **1000**<br />`the user is not registered` | Пользователь не зарегистрирован в «specter» |