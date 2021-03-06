### Градиентный бустинг над решающими деревьями

Задание посвящего градиентному бустинг, подбиру его гиперпараметров и сравнению градиентного бустинга со случайным лесом.

- Загрузите выборку из файла gbm-data.csv с помощью pandas и преобразуйте ее в массив numpy. Разбейте выборку на обучающую и тестовую.  
- Обучите GradientBoostingClassifier с параметром n_estimators=250 и для каждого значения learning_rate из списка [1, 0.5, 0.3, 0.2, 0.1] вычислите и постройте график значений log-loss на обучающей и тестовой выборках, а также найдите минимальное значение метрики и номер итерации, на которой оно достигается.  
- Как можно охарактеризовать график качества на тестовой выборке, начиная с некоторой итерации: переобучение (overfitting) или недообучение (underfitting)?  
- Приведите минимальное значение log-loss на тестовой выборке и номер итерации, на котором оно достигается, при learning_rate = 0.2.  
- На этих же данных обучите RandomForestClassifier с количеством деревьев, равным количеству итераций, на котором достигается наилучшее качество у градиентного бустинга при learning_rate = 0.2. Какое значение log-loss на тесте получается у этого случайного леса?  
