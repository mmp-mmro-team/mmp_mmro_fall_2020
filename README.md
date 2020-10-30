# Семинары по машинному обучению для бакалавров 3 курса кафедры ММП и магистров 1 курса кафедр ИИТ и МФ факультета ВМК МГУ, осенний семестр 2020/2021
В репозитории находятся материалы и домашние задания по семинарам "ММРО 2020/2021"

<p align="center">
<img src="http://funzoo.ru/uploads/posts/2009-11/1258648863_tn.jpg" height=200pt> <img src="https://github.com/mmp-mmro-team/mmp_mmro_spring_2020/blob/master/trash/kernel_trick.jpg" height=200pt>
</p>

**Курс сдается через систему [anytask](https://anytask.org/course/738)**

На семинары и работу ассистентов можно оставить отзыв: [[анонимно без регистрации и смс](https://docs.google.com/forms/d/e/1FAIpQLSeW89-GCnceWDvd439vqZBY69-oSUzo-UWtL5aq-fCnOWOzow/viewform)]

**Полезные ссылки:**

* Материалы прошлых лет:
  - [Раз](https://github.com/esokolov/ml-course-msu)
  - [Два](https://github.com/esokolov/ml-course-hse)
* [Курс лекций по ММРО](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)
* [Курс Практикума на ЭВМ, осень](https://github.com/mmp-practicum-team/mmp_practicum_fall_2020)
* [Курс ММРО 19/20, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2019)

## Правила выставления оценок

Общая оценка выставляется по следующей формуле:
![](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/trash/formula.png)
, где 

* Check --- 5 * <сумма баллов за проверочные> / <суммарный макс балл за проверочные>
* Labs --- min(5, 5 * <сумма баллов за лабораторные + конкурсы + теор. дз.> / <суммарный макс балл за (лабораторные + теор.дз) (без бонусов и конкурсов)>
* Exam --- оценка за экзамен, до 5 баллов

Причем
* Для общей оценки 5 необходимо сдать **все (5)** _лабораторные работы и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за эказамен не меньше 4;
* Для общей оценки 4 необходимо сдать **не менее 3-х** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* Для общей оценки 3 необходимо сдать **не менее 2-х** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* floor --- округление дробного числа до ближайшего целого вниз.

**Обратите внимание,** что округление общей оценки (и только ее) производится вверх.

## Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 7 сентября  | Семинар 1  | <ul><li>Табличные данные</li><li>Разведочный анализ</li></ul> | [Ноутбук](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/seminars/sem01-pandas-mmp.ipynb) | [ДЗ на разведочный анализ данных](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/homework-practice/hw-practice-1.ipynb) |
| 14 сентября  | Семинар 2  | <ul><li>kNN</li></ul> | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/seminars/sem02_knn.pdf) | ¯\\\_(ツ)\_/¯ |
| 21 сентября  | Семинар 3  | <ul><li>Sklearn</li><li>Линейная регрессия</li></ul> | [Ноутбук](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/seminars/sem03-sklearn-linreg.ipynb) | ¯\\\_(ツ)\_/¯ |
| 28 сентября  | Семинар 4  | <ul><li>kNN:быстрый поиск соседей</li></ul> | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/seminars/sem04_knn.pdf) | [ДЗ на kNN](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/homework-practice/hw-practice-2.ipynb)|
| 5 октября  | Семинар 5  | <ul><li>Векторное и матричное дифференцирование</li></ul> | [Хороший cheat sheet по дифференцированию](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/seminars/sem05_vect_matrix_diff.pdf) | ¯\\\_(ツ)\_/¯ |
| 12 октября  | Семинар 6  | <ul><li>L1-регуляризация</li><li>Градиентный спуск</li></ul> | <ul><li>[Регуляризация, см. раздел 5](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/lecture-notes/lecture03-linregr.pdf)</li><li>[Градиентный спуск, ноутбук](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem03-gd.ipynb)</li></ul> | ¯\\\_(ツ)\_/¯ |
| 19 октября  | Семинар 7  | <ul><li>Логистическая регрессия</li><li>Оценивание вероятностей</li><li>Счетчики</li></ul> | <ul><li>[Лог. регрессия, глава 1](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/lecture-notes/lecture05-linclass.pdf)</li><li>[Счетчики, раздел 3.3](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/lecture-notes/lecture06-linclass.pdf)</li></ul> | ¯\\\_(ツ)\_/¯ |
| 26 октября  | Семинар 8  | <ul><li>AUC-ROC</li><li>Особенности метрик классификации</li></ul> | [Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem05-linclass-metrics.pdf)| ¯\\\_(ツ)\_/¯ |
