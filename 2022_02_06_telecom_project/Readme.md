## Проект "Телеком"

[ссылка на просмотр проекта в nbviewer](https://nbviewer.jupyter.org/github/NESDS/praktikum_yandex_projects_data_science/blob/main/2022_02_06_telecom_project/2022_02_06_telecom_project.ipynb)

---
### Данные 📁
Информация о договоре, персональные данные клиента, информация об интернет-услугах, информация об услугах телефонии.

---
### Задача 📝
Построить модель с максимальным значением AUC-ROC, c целью предсказания оттока клиентов.

---
### Краткий вывод 💡
Обучили несколько базовых моделей. Метрики финальной модели (XGBoost) на тестовых данных: roc_auc = 0.945, accuracy=0.86, что выше целевого показателя.

---
### Используемые библиотеки 🛠️
``` pandas, seaborn, matplotlib, plotly, numpy, sklearn, catboost, lightgbm, xgboost ```
