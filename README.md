# Модуль Drupal 7 UberCart 3 для Украины

## Чеклист интеграции:
- [x] Установить модуль.
- [x] Передать тех поддержке PSP Platon  ссылку для коллбеков.
- [x] Провести оплату используя тестовые реквизиты.

## Установка:

* В админ панеле перейти в Modules → Install, выбрать архив модуля и нажать “Install”.

* Вернитесь в раздел Modules, рядом с “Platon” переведите переключатель в значение "Enabled" под разделом "Ubercart - Payment" и нажмите "Save configuration".

* Перейдите в Store → Configuration → Payment settings, выберите "Settings" модуля “Platon”.

* В настройках укажите ключ и пароль. Нажмите "Save configuration".

* Вернитесь в Store → Configuration → Payment settings, активируйте метод оплаты “Platon” и нажмите "Save configuration".

## Иностранные валюты:
Готовые CMS модули PSP Platon по умолчанию поддерживают только оплату в UAH.

Если необходимы иностранные валюты необходимо провести правки модуля вашими программистами согласно раздела [документации](https://platon.atlassian.net/wiki/spaces/docs/pages/1810235393).

## Ссылка для коллбеков:
https://ВАШ_САЙТ/cart/platon/complete

## Тестирование:
В целях тестирования используйте наши тестовые реквизиты.

| Номер карты  | Месяц / Год | CVV2 | Описание результата |
| :---:  | :---:  | :---:  | --- |
| 4111  1111  1111  1111 | 01 / 2024 | Любые три цифры | Успешная оплата без 3DS проверки |
| 4111  1111  1111  1111 | 02 / 2024 | Любые три цифры | Не успешная оплата без 3DS проверки |
| 4111  1111  1111  1111 | 05 / 2024 | Любые три цифры | Успешная оплата с 3DS проверкой |
| 4111  1111  1111  1111 | 06 / 2024 | Любые три цифры | Не успешная оплата с 3DS проверкой |
