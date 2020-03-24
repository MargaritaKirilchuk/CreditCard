# Отчёт о тестировании Credit Card Number Validator

## Необходимо проверить функциональность валидации номера банковской карты.

21.03.2020 с 17:00 до 17:30 было проведено функцилональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 00:30

В результате тестирования выявлены следующие дефекты:
* https://github.com/MargaritaKirilchuk/CreditCard/issues/1#issue-585521127

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* баг репорт
* отчет о тестировании


В качестве тестовых данных использовались валидные данные генератора номеров банковских карт https://www.prepostseo.com/tool/ru/credit-card-generator, а также выдуманные невалидные номера карт:
* 4661913736156320
* 5595269370985922
* 343056140960574
* 6011988733204465
* 123456789123456789123
* 1234 5678 1234 5678
* 1234.5678.1234.5678
* 123456789123456R
* 1234567891234ABC
* 559526937098592215264696456798674986786738476397
* IVANIVANOV

Тестирование производилось в следующем окружении:
* macOS High Sierra 10.13.6
* Java JDK 11.0.6
