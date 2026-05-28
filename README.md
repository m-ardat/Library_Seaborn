# Library Seaborn
![Seaborn](seaborn_label.svg)

В данном репозитории содержится гайд библиотеки *Seaborn* о графиках и их настройках на русском языке.

Информация актуальна для библиотеки *Seaborn* версии: 0.13.2

## Содержание
- [Описание](#описание)
- [Наполнение](#наполнение)
- [Автор](#автор)
- [Источники](#источники)
- [Лицензия](#лицензия)

### Описание
**Seaborn** - это библиотека, построенная на основе *Matplotlib*, которая упрощает процесс создания сложных и красивых графиков. Она ориентирована на статистическую визуализацию данных и имеет следующие характеристики:
- **Высокоуровневый интерфейс**: *Seaborn* предоставляет функции для быстрого создания сложных графиков с минимальным количеством кода. Большинство настроек применяются автоматически, что делает графики более привлекательными и удобными для восприятия.
- **Интеграция с Pandas**: Библиотека *Seaborn* отлично работает с объектами `DataFrame` и `Series` из *Pandas*, что упрощает процесс визуализации данных из табличных структур.
- **Статистические графики**: *Seaborn* включает функции для создания статистических графиков, таких как распределения, регрессионные графики, тепловые карты и парные графики.

**Когда использовать Seaborn:**
- Когда требуется быстро создать красивый и информативный график.
- Для визуализации статистических данных и выявления зависимостей между переменными.
- Когда данные хранятся в объекте `DataFrame` и необходимо использовать высокоуровневые функции визуализации.

### Наполнение
Репозиторий содержит:
| Виды графиков | Наименование графиков |
|----------|----------|
|Графики отношений (Relational plots)  | [Диаграмма рассеяния (scatter plot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/scatter%20plot.ipynb) <br> [Линейный график (line plot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/line%20plot.ipynb) <br> [Реляционный график (relplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/relplot.ipynb)|
|Графики распределения (Distribution plots) | [Сглаженная оценка плотности вероятности для непрерывных данных (kdeplot)](https://github.com/m-ardat/chart_ipynb/Library_Seaborn/blob/main/kdeplot.ipynb) <br> [Гистограмма (histplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/histplot.ipynb) <br> [Эмпирическая функция распределения (ecdfplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/ecdfplot.ipynb) <br> [Различные виды графиков распределения (displot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/displot.ipynb)|
|Категориальные графики (Categorical plots) | [Столбчатая диаграмма (barplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/barplot.ipynb) <br> [Визуализация количества наблюдений (countplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/countplot.ipynb) <br> [Диаграмма размаха (boxplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/boxplot.ipynb) <br> [Скрипичные диаграмма (violinplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/violinplot.ipynb) <br> [Диаграмма рассеяния распределения (swarmplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/swarmplot.ipynb) <br> [Точечная диаграмма категориальных данных (stripplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/stripplot.ipynb) <br> [Расширенный ящик с усами (boxenplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/boxenplot.ipynb) <br> [Точечный график для визуализии категориальных данных (pointplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/pointplot.ipynb) <br> [Универсальным инструмент для создания различных типов графиков, визуализация категориальных данных (catplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/catplot.ipynb)|
|Регрессионные графики (Regression plots) | [Построение линейных моделей (регрессий) и их визуализация (lmplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/lmplot.ipynb) <br> [Построение графика регрессии (regplot)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/regplot.ipynb)|
|Матричные графики (Matrix plots) | [Тепловая карта (heatmap)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/heatmap.ipynb) <br> [Тепловая карта с иерархической кластеризацией (clustermap)](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/clustermap.ipynb)|
|Facet, Pair, Joint | [FacetGrid](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/FacetGrid.ipynb) <br> [PairGrid](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/pairplot.ipynb) <br> [JointGrid](https://github.com/m-ardat/Library_Seaborn/blob/main/chart_ipynb/jointplot.ipynb)|

### Автор
- Максим Ардат - [GitHub](https://github.com/m-ardat), [Telegram](https://t.me/m_ardat)

### Источники
Используемые источники при составлении репозитория:
1. [Документация библиотеки Seaborn](https://seaborn.pydata.org/)
2. [Материал курса](https://stepik.org/course/204124/promo)

### Лицензия
Для получения дополнительной информации смотрите [LICENSE](/LICENSE).
