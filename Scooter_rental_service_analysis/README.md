# Описание проекта - Анализ сервиса аренды самокатов GoFast
Необходимо выполнить исследование в качестве аналитика популярного сервиса аренды самокатов GoFast. Нам передали данные о некоторых пользователях из нескольких городов, а также об их поездках. Проанализируем данные и проверим некоторые гипотезы, которые могут помочь бизнесу вырасти.

## Данные
В основных данных есть информация о пользователях, их поездках и подписках. Загрузим все датасеты, сохраним их в датафреймы и изучим общую информацию о данных.

Чтобы совершать поездки по городу, пользователи сервиса GoFast пользуются мобильным приложением. Сервисом можно пользоваться:
- без подписки
	- абонентская плата отсутствует;
	- стоимость одной минуты поездки — 8 рублей;
	- стоимость старта (начала поездки) — 50 рублей;
- с подпиской Ultra
	- абонентская плата — 199 рублей в месяц;
	- стоимость одной минуты поездки — 6 рублей;
	- стоимость старта — бесплатно.

## Задача
Целью данного анализа является получение ценной информации для компании GoFast, которая поможет в оптимизации маркетинговых стратегий, управлении подписками и улучшении обслуживания пользователей.

План действий:
- Предобработка данных: удаление пропусков и дубликатов, преобразование форматов данных.
- Исследовательский анализ данных (EDA): анализ возраста пользователей, их распределения по городам, подписок, продолжительности поездок и других показателей.
- Проверка гипотез: проверка гипотез о продолжительности поездок, среднем расстоянии поездок и помесячной выручке от пользователей с подпиской и без неё.
- Дополнительные задачи: определение минимального количества промокодов для акции с учётом заданной вероятности, оценка вероятности открытия push-уведомлений с помощью аппроксимации биномиального распределения нормальным.

## Используемые библиотеки
*pandas*<br>
*numpy*<br>
*matplotlib*<br>
*scipy*