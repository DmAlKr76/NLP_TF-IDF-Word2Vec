# Задание

Необходимо решить задачу нахождения похожих товаров в интернет-магазинах по их описанию.

1. Представьте массив текстов в виде векторов (как с помощью TF-IDF, так и с помощью Word2Vec).
2. Выберите расстояние, с помощью которого вы будете оценивать близость векторов, представляющих тексты (рекомендуется использовать косинусное расстояние, но вы можете попробовать и другие подходы).
3. Для полученных векторов попарно найдите косинусное расстояние (попробуйте сделать это без цикла, с помощью матричных операций).
4. Задайте какой-то порог значимости (с которым вы сравните значения расстояния между векторами), на основе которого вы будете судить о том, похожи два текста или нет.