- Описание проекта: cервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. Требуется построить модель, которая умеет определять рыночную стоимость автомобиля на основе данных о технических характеристиках, комплектации и ценах других автомобилей

- Использованные инструменты и библиотеки: pandas, sklearn, lightgbm

- В результате работы рассмотрены "обычные" модели регрессии (DecisionTreeRegressor, LinearRegression, и DummyRegressor для сравнения с константной моделью) и модель градиентного бустинга для задачи регресии LGBMRegressor с подбором гиперпараметров в pipeline. Лучший результат по метрике RMSE показала модель LGBMRegressor, она может быть выбрана в качестве лучшей модели по критерию качества. Метрика качества на тестовой выборке RMSE составляет 1714.18
