# Отчёт о тестировании приложения Money Transfer

## Краткое описание

Был написан, следующий код:


1. public class Main {
2.    public static void main(String[] args) {
3.        int a = 2_000_000_000;
4.        int b = 700_000_000;
5.        int c;
6.        c = a + b;
7.            System.out.println(c);
8.        }
9. }

## Описание тестов

25.12.2020 - 25.12.2020 было проведено Функциональное тестирование (functional testing) приложения Money Transfer.

int b = 100_000_000

Результат:

2100000000


## Результаты

1. 100 % успешных тестов
2. https://github.com/NetologyQA12/MoneyTransfer/issues/1

## Общие рекомендации

Рекомендовано использовать переменную long или float.



ОС Windows 10 x64
Java Version 11.0.8
ПО IntelliJ IDEA Community Edition 2020.2.3 x64