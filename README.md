# Документация API «specter»
Данная документация описывают работу API «specter», её принципы, методы и другое. Перед использованием API внимательно ознакомьтесь с его документацией.

## Запросы
Данный раздел рассказывает о том, как осуществляются запросы к API «specter».

### Синтаксис
Запросы к API осуществляется по следующему правилу:
```
http://thespecterlife.com:3501/api/method/<METHOD>?<PARAMS>
```
Метод HTTP-запроса не важен — он может быть, как GET, так и другим.  
Все методы (\<METHOD\>) и параметры к ним (\<PARAMS\>) определены в [данной документации](https://github.com/EcostCompony/specter_api_documentation/blob/master/Методы/Список%20методов.md#список-методов).

### Query-параметр версии
Каждый запрос должен сопровождаться параметром `v` — используемая версия API.  
Со списком версий можно ознакомиться [здесь](https://github.com/EcostCompony/specter_api_documentation/blob/master/Основное/Версии%20API.md#версии-api).

## Содержание документации
### [Версии API](https://github.com/EcostCompony/specter_api_documentation/blob/master/Основное/Версии%20API.md#версии-api)
Информация о версиях API и их изменениях.

### [Roadmap](https://github.com/EcostCompony/specter_api_documentation/blob/master/Основное/Roadmap.md#roadmap)
Карта будующих масштабных изменений в API.

### [Обработка ошибок](https://github.com/EcostCompony/specter_api_documentation/blob/master/Основное/Обработка%20ошибок.md#обработка-ошибок)
Список всех ошибок: их коды, краткие и подробные описания.

### [Список объектов](https://github.com/EcostCompony/specter_api_documentation/blob/master/Объекты/Список%20объектов.md#список-объектов)
Список объектов, описывающих что-либо. Например, объект канала — описывает канал.

### [Список методов](https://github.com/EcostCompony/specter_api_documentation/blob/master/Методы/Список%20методов.md#список-методов)
Список всех методов.