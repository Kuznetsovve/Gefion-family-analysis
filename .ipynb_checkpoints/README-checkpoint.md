# Gefion-family-analysis
Построение гистограмм для основных физических характеристик астероидов семейства Гёфьён

Этот репозиторий содержит Jupyter-ноутбук `Gefion_family_analysis_lab1.ipynb`, в котором выполняется обработка и визуализация данных для астероидного семейства **Gefion** на основе каталогов Nesvorny HCM asteroid families и JPL Small-Body Query.

**Обозначения файлов:**

`Gefion_family_analysis_lab1.ipynb` — Notebook с результатами анализа и построений <br>
`516_gefion.tab.txt` — данные по семейсту Gefion за 2015 год из HCM asteroids families <br>
`sbdb_query_results.csv` — данные из выборки по диапазону a и e из JPL Small-Body Query <br>
`fst_500.csv` — данные из выборки по 500 первым астероидам из JPL Small-Body Query

## Цель работы

- Построение гистограмм основных физических характеристик астероидов семейства Gefion
- Анализ разброса параметров (большая полуось, эксцентриситет и др.) в пределах семейства

## Исходные данные

Используются следующие наборы данных:

1. **Nesvorny HCM Asteroid Families**  
  - Официальная страница: https://sbn.psi.edu/pds/resource/nesvornyfam.html 
  - Файл с семейством Gefion за 2015 год:  
    `ast.nesvorny.families_V2_0/data/families_2015/516_gefion.tab`

2. **JPL Small-Body Database Query**  
  - Веб-интерфейс: https://ssd.jpl.nasa.gov/tools/sbdb_query.html

## Используемые инструменты

В ноутбуке применяются следующие библиотеки Python: 

- `pandas` — загрузка и предобработка табличных данных
- `numpy` — базовые численные операции и работа с массивами
- `matplotlib` — построение базовых графиков и гистограмм
- `seaborn` — улучшенная визуализация и работа со статистическими графиками