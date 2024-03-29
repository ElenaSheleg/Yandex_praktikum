# Проект: Музыка больших городов
#### Описание 
Исследовать предпочтения пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница) 

#### Используемые инструменты и методы:
* изучение общей информации о данных: head(), info(), describe()
* обработка пропущенных значений: isnull(), np.isnan()
* замена типов данных: astype(), value_counts(), unique()
* обработка дубликатов: duplicated()
* анализ данных: groupby()


#### Краткий вывод
День недели по-разному влияет на активность пользователей в Москве и Петербурге. Музыкальные предпочтения не сильно меняются в течение недели — будь то Москва или Петербург. Небольшие различия заметны в начале недели, по понедельникам: в Москве слушают музыку жанра “world”, в Петербурге — джаз и классику. Во вкусах пользователей Москвы и Петербурга больше общего чем различий. Вопреки ожиданиям, предпочтения жанров в Петербурге напоминают московские.