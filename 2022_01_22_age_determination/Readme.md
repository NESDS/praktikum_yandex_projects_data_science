## Определение возраста покупателей

[ссылка на просмотр проекта в nbviewer](https://nbviewer.org/github/NESDS/praktikum_yandex_projects_data_science/blob/main/2022_01_22_age_determination/2022_01_22_age_determination.ipynb)

---
### Данные 📁
Данные взяты с сайта http://chalearnlap.cvc.uab.es/dataset/26/description/. В распоряжении есть набор фотографий людей с указанием возраста.

---
### Задача 📝
Необходимо построить модель, которая по фотографии определит приблизительный возраст человека.

---
### Краткий вывод 💡
Для обучения модели использованы сверточные слои Keras и архитектура ResNet50.
В результате обучения алгоритма на тестовой выборке достигнуто значение МАЕ = 6.8.

---
### Используемые библиотеки 🛠️
``` pandas, numpy, plotly, seaborn, matplotlib,  tensorflow  ```
