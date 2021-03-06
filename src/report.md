# Отчёт о тестировании функциональности валидации номеров банковских карт

## Краткое описание

18.08.2021 - 18.08.2021 было проведено функциональное тестирование приложения для валидации номеров банковских карт.

На тестирование затрачено: 3 часа.

В результате тестирования выявлены следующие дефекты:
* [Баг-репорт в репозитории](https://github.com/vmlysenkov/1.1-Java/issues/1#issue-973342316)

## Описание процесса тестирования

В качестве тестовых данных использовались данные с [сайта генератора номеров кредитных карт](https://www.getcreditcardnumbers.com/)

<b> AMEX </b>

* 343013318406062
* 346064414297019
* 348711672719344

<b> Diners Club </b>

* 30153345596192
* 38354509065857
* 30147202399179

<b> Discover </b>

* 6011846519923007
* 6011418316588902
* 6011345170709847

<b> enRoute </b>

* 201434064720624
* 214913042919932
* 201441395551644

<b> JCB </b>

* 3337472973845786
* 3337859630322151
* 3088670521346402

<b> MasterCard </b>

* 5313182659163064
* 5502982593608590
* 5166884249848637

<b> Visa </b>

* 4603936019126786
* 4858525336666764
* 4929796787953002

<b> Voyager </b>

* 869998241009013
* 869965080232238
* 869946879693699

Тестирование производилось в следующем окружении:
* Windows 7 64-разрядная
* версия Java 11.0.11