# Отчёт о тестировании Задача №1 - Money Transfer

## Краткое описание

21.08.2021 - 21.08.2021 было проведено проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 1 ч.

В результате тестирования выявлены следующие дефекты:
* [При пополнении счета, выводиться неверное итоговое значение](https://github.com/vitkakim/java-l1.2-z1/issues/1#issue-976196115)

## Описание процесса тестирования

В качестве тестовых данных использовались данные:
* текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)
* сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)
* переменная для хранения итогового значения - тип int

Тестирование производилось в следующем окружении:
* Windows 10, х64
* Java 11.0.10