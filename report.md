# Отчёт о тестировании приложения Bonus

## Краткое описание

02.11.2020 было проведено функциональное тестирование приложения Bonus.

На тестирование затрачено: 5 минут.

В результате функционального тестирования приложения Bonus выявлены следующие дефекты:
* [Ошибка при расчете дополнительного бонуса в приложении](https://github.com/DinaOrlova/lec-1.2-zadacha-2/issues/1)

## Описание тестов

Функциональное тестирование проводилось для проверки функции расчета нового бонуса.

В процессе данного тестирования использовались следующие артефакты:
* Баг-репорты (ссылки даны в разделе результатов функционального тестирования).

В качестве тестовых данных использовались данные, выданные разработчиком:

1. Постоянный бонус (переменная типа double) - 0.3.

2. Дополнительный бонус (переменная типа double) - 0.6.

3. Переменная для хранения итогового значения - тип double.

Тестирование производилось в следующем окружении:
* Windows 10 Pro х64
* openjdk version "11.0.9" 2020-10-20
* JetBrains Toolbox version 1.18.7455.0

## Результаты

1. Данный тест показывает, что функция расчета дополнительного бонуса выполняется неверно.

2. Ссылка на баг-репорт:
* [Ошибка при расчете дополнительного бонуса в приложении](https://github.com/DinaOrlova/lec-1.2-zadacha-2/issues/1)


