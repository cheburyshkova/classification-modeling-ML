Датасет представляет собой выборку из реальных данных и содержит зашиврованные значения, за исключением целевой переменной f_triggered. Целевая переменная f_triggered является бинарной и определяет, активировано ли определенное предложение для клиента.

Цель
Основная цель проекта - построить модель классификации, которая максимизирует метрику Gini (2*ROC_AUC-1). Полученная модель будет использоваться для прогнозирования активации предложений для клиентов.