# Проект: Определение перспективного тарифа для телеком-компании
#### Описание 
На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и найти оптимальный тариф для его дальнейшего развития.

#### Используемые инструменты и методы:
* изучение общей информации о данных: head(), info(), describe()
* обработка пропущенных значений: isna()
* замена типов данных: astype(), to_datetime()
* подготовка к данных анализу: groupby(), merge()
* построение графиков: boxplot(), plot(kind='hist')
* проверка гипотез: st.ttest_ind()


#### Краткий вывод
В ходе проверки 2 гипотез,  выяснили: средняя выручка пользователей тарифов Ультра и Смарт различается и cредняя выручка пользователей из Москвы близка к равной выручке пользователей из других регионов.
Рекламный бюджет выгоднее всего перераспределить в пользу тарифа Ультра несмотря на то, что его пользователи меньше выходят за рамки тарифного пакета, в отличие от абонентов тарифа Смарт.