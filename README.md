# Отчёт о тестировании MoneyTransfer

## Краткое описание

14.05.21-14.05.21  было проведено Functional test приложения MoneyTransfer.

На тестирование затрачено: 00h30mm

В результате тестирования выявлены следующие дефекты:

[Выход за пределы значений int при пополнении счёта Vip-клиента](https://github.com/Alexsandra2203/MoneyTransfer_Java/issues/1#issue-892371833)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

[Типы данных](https://metanit.com/java/tutorial/2.12.php)


В качестве тестовых данных использовалось ТЗ:

* текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)

* сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)

* переменная для хранения итогового значения - тип int

Тестирование производилось в следующем окружении:

Название ОС: Майкрософт Windows 10 Домашняя
Версия ОС: 10.0.19042 Н/Д построение 19042; тип системы - x64

версия Java 11

ПО:
Браузер Chrome 90.0.4430.93 OE

IntelliJ IDEA Community Edition 2021.1.1
