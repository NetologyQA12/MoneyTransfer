# Отчёт о тестировании приложения Money Transfer

## Краткое описание

Был написан, следующий код:

```
public class Main {
    public static void main(String[] args) {
        int a = 2_000_000_000;
        int b = 100_000_000;
        int c;
        c = a + b;
        System.out.println(c);
    }
}
```
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