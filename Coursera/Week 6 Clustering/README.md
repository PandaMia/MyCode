### Уменьшение количества цветов изображения

Задание посвящено использованию метода k-средних (K-Means).  

- Загрузите картинку parrots.jpg. Преобразуйте изображение, приведя все значения в интервал от 0 до 1.  
- Создайте матрицу объекты-признаки: характеризуйте каждый пиксель тремя координатами - значениями интенсивности в пространстве RGB.  
- Запустите алгоритм K-Means. После выделения кластеров все пиксели, отнесенные в один кластер, попробуйте заполнить двумя способами: медианным и средним цветом по кластеру.  
- Измерьте качество получившейся сегментации с помощью метрики PSNR.  
- Найдите минимальное количество кластеров, при котором значение PSNR выше 20.
