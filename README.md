# Final-project
Финальная работа
1.	Взять набор данных исходя из ваших интересов.
2.	Не используйте датасеты, которые вы уже брали.
3.	Описать колонки, какие характеристики.
4.	Проведите анализ EDA.
5.	Провести предварительную обработку данных, если это необходимо (сделать данные понятными для модели машинного обучения: заполнить пропущенные значения, заменить категориальные признаки и т.д.)
6.	Решить задачу сегментации или анализа временного ряда при помощи не менее 5-ти подходов ML. Составьте ансамбль моделей.
7.	Решить задачу поиска аномалий.
8.	Визуализация. Создать графики ошибок прогнозирования, метрик качества обученной модели и важности признаков.
9.	Результат выполнения финальной работы разместить в гит репозиторий.





Датасет:
https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data/data


Кластеризация стран исходя из обучающих данных (социально-экономических).

Файл Final progect.ipynb содержит EDA-анализ данных, их предварительную обработку для ML, детекцию поиска аномалий. 
Решается задача кластеризации при помощи 5 алгоритмов с последующей визуализацией при помощи графиков PCA и t-SNE и определением метрик качества.

Наилучшим образом с задачей сегментации справляется спектральная кластеризация, что визуально определяется по графикам, а также по метрикам качества:
Silhouette Score: 0.3654355518017844
Davies-Bouldin Score: 1.078555752378587
Calinski-Harabasz Score: 81.64123739103711
