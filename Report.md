# Отчёт о тестировании KeyValidator

## Краткое описание

27.04.2020 - 27.04.2020 было проведено тестирование методом белого ящика и функциональное тестирование кода CreditCardNumberValidator.

На тестирование затрачено: 1 hour

### Чек лист
* Установить IntelliJ IDEA согласно [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md) **Failed**
* Проверить работу программы CreditCardNumberValidator **Passed**
* запускать программу с разными тестовыми данными **Passed**

В результате тестирования выявлены следующие дефекты:
* [Bug#1 Опечатка в руководстве пользователя по установке IntelliJ IDEA, шаг 19 повторяется 2 раза](https://github.com/MIkhail19870105/CreditCardNumberValidatorDemo/issues/1)
* [Bug#2 При нажатии на ссылку в шаге 19 Руководства по установке IntelliJ IDEA ошибка 404](https://github.com/MIkhail19870105/CreditCardNumberValidatorDemo/issues/2)
* [Bug#3 При вводе номера карты превышающего 16 цифр приложение выдает результат FAIL](https://github.com/MIkhail19870105/CreditCardNumberValidatorDemo/issues/3#issue-607433189)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Чек лист под кратким описанием в отчете.
* Bug Report в Issues проекта.


В качестве тестовых данных использовались данные из [руководства по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md):

Тестирование производилось в следующем окружении:
* Windows 10 Pro X64
* openjdk version "11.0.7" 2020-04-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)
* git version 2.26.0
* Google Chrome Версия 81.0.4044.122
* IntelliJ IDEA 2020.1 (Community Edition)
Build #IC-201.6668.121, built on April 8, 2020
Runtime version: 11.0.6+8-b765.25 amd64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o

