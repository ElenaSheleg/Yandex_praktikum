# Проект: Исследование поведения пользователей в мобильном приложении продажи продуктов питания
#### Описание 
Необходимо разобраться в поведение пользователей мобильного приложения продажи продуктов питания. Проанализировать данные лога с действиями пользователей трех групп: 2 контрольных и одной тестовой, для которой изменен шрифт приложения. Необходимо проанализировать воронку продаж и оценить результаты А/А и А/В тестов.

#### Используемые инструменты и методы:
* изучение общей информации о данных: head(), info(), describe()
* замена типов данных: to_datetime(), dt.strftime()
* обработка дубликатов: duplicated(), drop_duplicates
* анализ данных: groupby(), sort_values(),
* построение графиков: sns.countplot(), plot(kind='barh'), go.Funnel()
* проверка статистической значимости: st.norm(), cdf()


#### Краткий вывод
Наибольшее количество пользователей ~ 48% теряется на первом шаге при выборе товара. Было проведено 16 экспериментов. Их результаты показали, что нет статистически значимой разницы между исследуемыми группами. Аналогичный результат был достигнут при применении поправки Бонферрони. Этот результат говорит о том,что изменение шрифта не повлияло существенным образом на поведение пользователей и, если дизайнеры считают это изменение необходимым, они могут его осуществить.