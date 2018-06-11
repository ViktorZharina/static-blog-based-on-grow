---
$title@: Proverka-sushhnostej-na-udovletvorenie-opredelennym-usloviyam
author@: Viktor Zharina
$order: 231
$dates:
  published: 2015-09-16 04:28:36
---
Вознкиают задачи проверки разных сущностей на удовлетворение каким-то параметрам. Я столкнулся с тем, что есть некоторые общие моменты, котоыре следует учитывать.



1. При проверке нужно учитывать характер данных и если данные можно разграничить так, что они не будут пересекаться и будут независимы, то можно попробовать распараллелить процесс.



2. Формируйте отчет в виде файла известного формата, напрмиер csv. Многие пользуются Excel (Calc) и им будет удобно просматривать такой отчет



3. При анализе формируйте отчет с данными, котоыре успешно прошли проверку и не прошли проверку с указанием причины.



4. Подумайте на тем нужно ли повторно проверять те сущности, которые уже были проверены. Может быть их стоит исключить из выборки и тем самым сократить время.


