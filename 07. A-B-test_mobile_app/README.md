# Проверка гипотез по увеличению выручки в интернет-магазине — оценка результатов A/B теста

## Данные

В нашем распоряжении имеется:

* Информация о гипотезах: краткое описание, охват пользователей, влияние на пользователей, уверенность в гипотезе, затраты ресурсов на проверку гипотезы (по 10-бальной шкале).
* Информация о заказах: идентификатор заказа, идентификатор пользователя, совершившего заказ, дата, когда был совершён заказ, выручка, а также группа A/B-теста, в которую попал заказ.

## Выполненные задачи

Используя данные интернет-магазина приоритезировал гипотезы, произвёл оценку результатов A/B-тестирования различными методами

* Провёл приоритизацию гипотез по фреймворкам ICE и RICE.
* Затем провёл анализ результатов A/B-теста.
* Построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным.
* На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.

## Навыки и инструменты

* Python
* Pandas
* Matplotlib
* SciPy
* A/B-тестирование
* Проверка статистических гипотез
