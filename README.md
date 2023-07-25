### Regression_of_complex_numbers_using_sklearn
### Горшков Андрей Вячеславович
### Обучение моделей регрессии для переменных, содержащих комплексные числа, с использованием алгоритмов scikit-learn
------------------------------------------

Алгоритмы scikit-learn не поддерживают работу с **комплексными числами**, что не позволяет построить непосредственные модели регрессии для данных, содержащих **комплексные числа**, с помощью стандартных регрессоров scikit-learn.

Разработан метод преобразования исходного датасета размером M×N с **комплексными числами** в датасет размером 2M×(2N-1) с **вещественными числами**, что позволяет использовать для построения достоверных моделей регрессии комплексных чисел стандартные модели регрессоров scikit-learn.
