# Оптимизация регрессии
## Постановка задачи
Рассмотрим несколько моделей линейной регрессии, чтобы выяснить более оптимальную для первых 20 зданий.
Данные:
•	http://video.ittensive.com/machine-learning/ashrae/building_metadata.csv.gz
•	http://video.ittensive.com/machine-learning/ashrae/weather_train.csv.gz
•	http://video.ittensive.com/machine-learning/ashrae/train.0.csv.gz Соревнование: https://www.kaggle.com/c/ashrae-energy-prediction/
© ITtensive, 2020
____
## Решение.
1) Подключение библиотек.
2) Загрузка данных, отсечение 20 зданий, объединение и оптимизация.
3) Обогащение данных: час, дни недели, праздники, логарифм.
4) Разделение данных.
5) Линейная регрессия: по часам.
6) Проверим модели: LinearRegression, Lasso, BayesianRidge.
Наиболее точные - LinearRegression, BayesianRidge.
