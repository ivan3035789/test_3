# Отчёт о тестировании приложения Precision

## Краткое описание

10.05.2021 - 10.05.2021  было проведено функционадьное тестирование приложения Precision.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Cумма двух чисел (с типом "double") выводится неверный результат](https://github.com/ivan3035789/test_3/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг-репорт
* Отчет о тестировании


В качестве тестовых данных использовались данные: [Precision](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)

* double regularBonus = 0.3 ,     double regularBonus = 0.3
* double specialBonus = 0.6   ,    double specialBonus = 0.6
* double totalBonus = regularBonus + specialBonus   ,   double totalBonus = 0.9

Тестирование производилось в следующем окружении:
* 64-разрядная операционная система windows_10 домашняя Version 10.0.18363.1500
* версия java 11.0.10" 2021-01-19