# Практическая лабараторная работа 2

## Цель

* Знакомоство со способами визуализаций переменных и их отношений

#### 1. Загрузить любой набор данных с https://www.kaggle.com, который содержал бы различные типы свойств: числовые, номинальные, категориальные.
В качестве примеров можно использовать (Можно выбрать свой вариант, важно - содержание как минимум трех непрерывных величин, двух категориальных):

[1. https://www.kaggle.com/datasets/uciml/student-alcohol-consumption](https://www.kaggle.com/datasets/greeshmagirish/crime-against-women-20012014-india)

[2. https://www.kaggle.com/datasets/fbi-us/california-crime?select=ca_offenses_by_city.csv](https://www.kaggle.com/datasets/fbi-us/california-crime?select=ca_offenses_by_city.csv)

[3. https://www.kaggle.com/datasets/danofer/law-school-admissions-bar-passage](https://www.kaggle.com/datasets/danofer/law-school-admissions-bar-passage)

[4. https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

[5. https://www.kaggle.com/datasets/mylesoneill/world-university-rankings](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings)

[6. https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database)

P.S. Если в наборе данных не существует, либо недостаточно категориальных признаков, сгенерируйте интервалы относительно непрерывной величины (на свое усмотрение), которое будет использовано в качестве категориальное. Например:
```
Переменная имеет min, max = 1,100.
Тогда:
В категорию 1 войдут значения входящие в интервал [1, 30]
В категорию 2 войдут значения входящие в интервал [31, 70]
В категорию 3 войдут значения входящие в интервал [71, 100]
```

#### 2. В среде Jupyter выполнить анализ выбранного набора данных:

    1. Открыть набор данных и вывести техническую информацию о наборе данных .info()
    
    2. Выбрать в качестве переменной - непрерывное значение
    
        2.1 Построить диаграмму плотности распределения (гистограмму). Как вы думаете, на какой вид распределения похож график?
        
        2.2 Построить boxplot
        
        2.3 Объясните полученный результат
        
    3. Выбрать несколько непрерывных переменных и провести визуализацию отношений между переменными
    
        3.1 Построить диаграмму рассеивания, гистограмму (относительно двух переменных), матрицу корреляций
        
        3.2 Объяснить результат
        
    4. Выбрать несколько переменных, X - категориальное, Y - непрерывное
    
        4.1 Построить гистограмму Y относительно переменной X
        
        4.2 Построить диаграмму размаха (boxplot) относительно переменной X
        
        4.3 Построить столбчатую диаграмму относительно переменной X
        
        4.4 Объяснить полученный результат
        
    5. Дополнительно проведите исследование отношений между переменными на свой выбор, объясните полученный результат.

### **Результат выполнения работы должен быть отражен в тетради (notebook) Jupyter с текстовыми вставками пояснений и комментариев**
