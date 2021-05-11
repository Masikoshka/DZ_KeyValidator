# Отчёт о тестировании KeyValidator

## Краткое описание

11.05.21 - 11.05.21 было проведено функциональное тестирование приложения KeyValidator и его совместимость c Java 11.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [Валидные ключи считаются невалидными.]()
* [Невалидный ключ считается валидным.]()

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство использования KeyValidator.](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* [Инструкция по установке OpenJDK 11.](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Чек-лист.](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0-1)

В качестве тестовых данных использовались:
* [Ключи для проверки.](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8)

Тестирование производилось в следующем окружении:
* Windows 10, версия: 20H2, разрядность 64.
* Версия Java: 11.