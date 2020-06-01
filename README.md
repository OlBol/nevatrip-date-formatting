# @nevatrip/date-formatter

Простой модуль для приведения времени и даты к нужному формату.

## Установка
Выполните команду:
```
npm i @nevatrip/date-formatter
```
или 
```
yarn add @nevatrip/date-formatter
```

## Описание
Пакет предоставляет два метода: renderTime() и renderDate(). 
Оба метода в качестве аргументов принимают дату в виде литерала даты и язык в виде литерала строки. 
В качестве второго аргумента принимаются следующие значения: 'en', 'ru', 'de', 'cs'. Значением по умолчанию для языка является 'en'.
 
### Метод renderTime()
Метод возвращает время в формате в зависимости от выставленной локализации, которая в свою очередь зависит от переданного языка вторым аргументом.

### Метод renderDate()
Метод возвращает дату в формате в зависимости от выставленной локализации, которая в свою очередь зависит от переданного языка вторым аргументом.
Если переданное первым аргументом время находится в промежутке с 21 вечера до 4 часов ночи, то выводится дата в формате "в ночь с... на...".