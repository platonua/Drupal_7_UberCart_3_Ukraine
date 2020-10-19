# Модуль Drupal 7 UberCart 3 для Украины

## Установка:

* В админ панеле перейти в Modules → Install, выбрать архив модуля и нажать “Install”.

* Вернитесь в раздел Modules, рядом с “Platon” переведите переключатель в значение "Enabled" под разделом "Ubercart - Payment" и нажмите "Save configuration".

* Перейдите в Store → Configuration → Payment settings, выберите "Settings" модуля “Platon”.

* В настройках укажите ключ и пароль. Нажмите "Save configuration".

* Вернитесь в Store → Configuration → Payment settings, активируйте метод оплаты “Platon” и нажмите "Save configuration".

## Ссылка для коллбеков:
https://ВАШ_САЙТ/cart/platon/complete

## Тестирование:
В целях тестирования используйте наши тестовые реквизиты.

| Номер карты  | Месяц / Год | CVV2 | Описание результата |
| :---:  | :---:  | :---:  | --- |
| 4111  1111  1111  1111 | 02 / 2022 | Любые три цифры | Не успешная оплата без 3DS проверки |
| 4111  1111  1111  1111 | 06 / 2022 | Любые три цифры | Не успешная оплата с 3DS проверкой |
| 4111  1111  1111  1111 | 01 / 2022 | Любые три цифры | Успешная оплата без 3DS проверки |
| 4111  1111  1111  1111 | 05 / 2022 | Любые три цифры | Успешная оплата с 3DS проверкой |
