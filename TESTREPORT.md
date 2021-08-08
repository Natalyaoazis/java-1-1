# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

7.08.2021 было проведено Smoke-тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Не проходят валидацию номера карт ПС Diners Club - Carte Blanche, Diners Club - International, American Express](https://github.com/Natalyaoazis/java-1-1/issues/1)
* [Не проходят валидацию карты ПС с номером карт более 16 цифр](https://github.com/Natalyaoazis/java-1-1/issues/2)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [предоставленный программный код](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)



В качестве тестовых данных использовались данные сайтов www.freeformatter.com, www.getcreditcardnumbers.com.


Тестирование производилось в следующем окружении:
* ОС Windows 10, x64
* Java 11.0.11