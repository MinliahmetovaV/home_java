# Отчёт о тестировании Credit card validator


18.00 - 22.00  17.10.2021-  было проведено тестирование методом анализа граничных значений приложения Credit Card Number Validator.

На тестирование затрачено: 3 часа.

В результате тестирования выявлены следующие дефекты:
* https://github.com/MinliahmetovaV/home_java/issues/1#issue-1028373028
* https://github.com/MinliahmetovaV/home_java/issues/3#issue-1028375309
* https://github.com/MinliahmetovaV/home_java/issues/2#issue-1028374725

В процессе тестирования использовались следующие артефакты:
* баг-репорт


В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:

* MasterCard 4048371939099371 ожидаемым результат Main Result is OK
* American Express 371887935185489  ожидаемым результат Main Result is OK
* VISA 4024007116393069912 ожидаемым результат Main Result is OK 
* Diners Club - Internationa 36332050729289 ожидаемым результат Main Result is OK
* 40240071163930699 ожидаемым результат Main Result is FAIL


Тестирование производилось в следующем окружении:
* Ноутбук ASUS  X550C
* windows 10 домашняя (64 бит)
* java version "11.0.12
