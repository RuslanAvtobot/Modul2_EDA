# Modul2_EDA
В данном модуле мы проводили разведовательный анализ данных.
В данном нам файле данные были достаточно "чистые" с выскоми процентом заполнения.
В среднем не заполненые данные были в рамках 5% в каждом столбце.

Кроме столбцов с количеством пропусков занятий и оценок за итоговый тест, остальные данные были однозначными и с ними просто было работать, т.к. нам были известны все значения которые могут там быть.
В столбце количество пропусков был самый большой разброс в данных от 0 до 385 занятий, поэтому для чистоты расчётов мною было принято решение по ограничению данных верхней статистической границей, и при работе с данным столбцом нужно учитывать, что максимальное значение это граница, а не значение.

В итоге мы отвергли 16 столбцов. 3 числовых и 13 номинативных, т.к. они не влияли на итоговую оценку.
