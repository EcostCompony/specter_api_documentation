# subscribers.setAdmin
`Требуется токен доступа`  
Метод для назначения подписчика заданного канала администратором

| Параметр                      | Описание                                                |
| :---------------------------- | :------------------------------------------------------ |
| **channel_id**<br />`integer` | Индетификатор канала<br />`Обязательный параметр`       |
| **user_id**<br />`integer`    | Индетификатор пользователя<br />`Обязательный параметр` |

### Результат
В случае успеха возвращает `1`.

### Ошибки
В ходе выполнения могут произойти [общие ошибки](https://github.com/EcostCompony/specter_api_documentation/blob/master/Основное/Обработка%20ошибок.md#коды-общих-ошибок).
| Ошибка                                      | Описание                                                                         |
| :------------------------------------------ | :------------------------------------------------------------------------------- |
| **50**<br />`not exist`                     | Канал или пользователь не найден,<br />либо пользователь не является подписчиком |
| **600**<br />`the user is already an admin` | Данный пользователь уже является администратором                                 |