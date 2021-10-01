# Отчёт о тестировании Java 1.1 (Money transfer)

## Краткое описание

30.09.2021 было проведено дымовое тестирование приложения Java 1.1.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Итоговое значение в проекте Java 1.1 вычисляется неверно](https://github.com/ESE58/Java-Homework-1_1/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг-репорт


В качестве тестовых данных использовались [данные](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md):
* int currentBalance = 2_000_000_000;
* int creditAmount = 500_000_000;
* int newBalance = currentBalance + creditAmount;

Ожидамый результат: 2_500_000_000

Тестирование производилось в следующем окружении:
* Ноутбук HP, Windows 10, версия 92.0.4515.159;
* IntelliJ IDEA 2021.3 EAP (Community Edition)
Build #IC-213.3714.440, built on September 22, 2021
Runtime version: 11.0.12+7-b1649.1 amd64;
* Java 11.0.1