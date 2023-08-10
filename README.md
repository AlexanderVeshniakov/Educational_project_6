### 1
Перечисли имена клиентов, которым должны одобрить заявку на кредит, исходя из следующих условий:
- возрас больше 18 лет
- доход выше 10_000 в месяц

### 2
Загружаем датасет [классификации ирисов](https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-plants-dataset).
Отрисуй диаграмму рассеяния (Scatterplot) в координатах "Длина чашелистика" / "Длина лепестка"

### 3
Решаем задачу классификации ирисов с помощью дерева решений:
- Делим датасет на обучающую и тестовую выборки с параметрами `test_size=0.2`, `random_state=42`
- Используя только признаки "Длина чашелистика" и "Длина лепестка", обучаем дерево решений с глубиной дерева 2
- Считаем точность (accuracy) классификации

### 4
- Строим [разделяющую поверхность](code-samples/surface.py) по признакам "Длина чашелистика" и "Длина лепестка". 
- Оотрисовываем дерево, которое получилось в результате обучения модели. 
- Выводим количество листов у получившегося дерева.

### 5
- Генерируем синусоидный сигнал с шумами размером 250
- Делим датасет на обучающую и тестовую выборки с параметрами `test_size=0.2`, `random_state=42`
- Обучаем дерево решений для предсказания синусоидального сигнала c глубиной дерева 1
- Строим график истинных ответов и предсказаний модели

### 6
- Строим график зависимости среднеквадратичной ошибки (MSE) предсказания на тестовой выборке от глубины дерева
(от 1 до 30).
- Пишнм глубину дерева, при которой качество модели наилучшее.

### 7
- Обучаем большее количество деревьев
- Рассчитываем среднеквадратичную ошибку (MSE) предсказания на тестовой выборке.
- Строим график зависимости MSE 
- Выводим количество деревьев, при котором качество модели наилучшее. 

### 8
- Обучаем алгоритм случайного леса с параметрами `max_depth=5,n_estimators=100, max_features=1, random_state=42`.
- Считаем MSE на тестовой выборке.
_________________________________________________________________________________________________________________________

### 1
Listed the names of customers who must approve the loan application based on the following conditions:
- more than 18 years old
- income above 10_000 per month

### 2
We load the datacet [classification of irises] (https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-plants-dataset).
Draw Scatterplot at Sepal Length/Petal Length

### 3
We solve the problem of classifying irises using the decision tree:
- We divide the data set into training and test samples with the parameters' test _ size = 0.2 ',' random _ state = 42'
- Using only the signs "Sepal length" and "Petal length," we teach the decision tree with tree depth 2
- We consider accuracy of classification

### 4
- Build the [separating surface] (code-samples/surface.py) by the characteristics "Sepal length" and "Petal length."
- We draw a tree, which was obtained as a result of model learning.
- We display the number of sheets in the resulting tree.

### 5
- Generate a sinusoidal signal with a noise size of 250
- We divide the data set into training and test samples with the parameters' test _ size = 0.2 ',' random _ state = 42'
- We teach the decision tree for sinusoidal signal prediction with tree depth 1
- We plot the true answers and predictions of the model

### 6
- Plot the mean square error (MSE) of the prediction on the test sample against the tree depth
(1 to 30).
- We write the depth of the tree, at which the quality of the model is the best.

### 7
- We train more trees
- Calculate the prediction mean square error (MSE) on the test sample.
- Plot MSE dependency
- We display the number of trees in which the quality of the model is best.

### 8
- We train a random forest algorithm with parameters' max _ depth = 5, n _ estimators = 100, max_features=1, random_state=42'.
- We count the MSE on the test sample.