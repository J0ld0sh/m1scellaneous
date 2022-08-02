# m1scellaneous

1. Recommend - разработка рекомендательной системы на основе PCA-components
оценка рейтинга фильма 
$$WeightedRating=(\frac{v}{v+m}⋅R)+(\frac{m}{v+m}⋅C)$$

где:
- v (votes) число оценок фильма;

- m (minimum) минимальное число оценок для попадания в топ;

- R (rating) средний рейтинг фильма;

- C (across) средний рейтинг по всем фильмам.

в качестве метрики используем косинусное расстояние

2. Tensor_decomposition - разработка собсвтенного алгоритма разложения 3d-тензора на основе градиентоного спуска и сравнение с пакетным алгоритмом Tucker в точности разложения тензора 
