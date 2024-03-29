#  Прогнозирование заказов такси

## Описание
Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Нужно построить модель для такого предсказания.

Значение метрики *RMSE* на тестовой выборке должно быть не больше 48.

Нужно:

1. Загрузить данные и выполнить их ресемплирование по одному часу.
2. Проанализировать данные.
3. Обучить разные модели с различными гиперпараметрами. Сделать тестовую выборку размером 10% от исходных данных.
4. Проверить данные на тестовой выборке и сделать выводы.

## Используемые библиотеки
Pandas, Numpy, Matplotlib, Seaborn, CatBoost, LightGBM, statsmodels, scikit-learn

## Итоги
Был произведён анализ имеющихся данных, добавлены новые признаки для улучшения качества модели, были рассмотрены различные модели машинного обучения.

Результат выбранной модели на тестовой выборке: RMSE = 44.89.
