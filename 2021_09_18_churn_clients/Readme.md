## Отток клиентов

[ссылка на просмотр проекта в nbviewer](https://nbviewer.jupyter.org/github/NESDS/praktikum_yandex_projects_data_science/blob/main/2021_09_18_churn_clients/2021_09_18_churn_clients.ipynb)

---
### Данные 📁
Исторические данные о поведении клиентов и расторжении договоров с банком.

---
### Задача 📝
Построить модель оттока клиентов. Ключевая метрика - F1.

---
### Краткий вывод 💡
Оптимальная модель - RandomForestClassifier(random_state = 0, n_estimators=50, max_depth=13) с компенсацией дисбаланса классов путем уменьшения отрицательного класса в 0,4 раза.
Метрика F1 на валидационной выборке = 0.592, можно улучшить до 0.593 если взять порог вероятности = 0.51. auc_roc = 0.841.
Самые важные признаки - Age, NumOfProducts, Balance.

---
### Используемые библиотеки 🛠️
``` pandas, seaborn, matplotlib, plotly, numpy, sklearn ```
