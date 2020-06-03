# Рейтинг маршрутов 

__Идея:__ помочь планировщикам выбрать самые выгодные маршруты за период. 
 
__Цель:__ Оценка маршрутов (регионов, почтовых кодов) при помощи разных методик и составление рейтинга маршрутов.
 
__Задачи:__ 
1.	Разработать методики оценки маршрутов (регионов, почтовых кодов).
2.	Рассчитать рейтинги маршрутов (регионов, почтовых кодов) по различным методикам.
3.	Проанализировать и сопоставить результаты полученных рейтингов.

__Методики:__
1.	Principal Component Analysis (PCA)
2.	Data Envelopment Analysis (DEA)

__Исходные данные:__
1.	Маршрут (Route)
2.	Регионы (Regions)
3.	Почтовые коды (PostCodes)
4.	Тип прицепа (TrailerType)
5.	Тип груза (CargoWeight)
6.	Вес груза (CargoType)
7.	Пробег (Mileage)
8.	Дни (Days)
9.	Доход (Income)

__Файлы:__
- [data.csv](https://github.com/jugo839/routes/blob/master/data.csv) - исходные данные 
- [dea_routes.png](https://github.com/jugo839/routes/blob/master/dea_routes.png) - DEA-frontier (результат DEA рейтинга на графике, маршруты на линии - эффективные)
- [dp1.ipynb](https://github.com/jugo839/routes/blob/master/dp1.ipynb) - код (ноутбук)
- [rating_DEA_routes.csv](https://github.com/jugo839/routes/blob/master/rating_DEA_routes.csv) - результаты DEA рейтинга по маршрутам
- [rating_PCA_postcodes.csv](https://github.com/jugo839/routes/blob/master/rating_PCA_postcodes.csv) - результаты PCA рейтинга по почтовым кодам
- [rating_PCA_regions.csv](https://github.com/jugo839/routes/blob/master/rating_PCA_regions.csv) - результаты PCA рейтинга по регионам
- [rating_PCA_routes.csv](https://github.com/jugo839/routes/blob/master/rating_PCA_routes.csv) - результаты PCA рейтинга по маршрутам
