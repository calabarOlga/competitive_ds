🏷️ **Competitive Data Science**  
[https://github.com/calabarOlga/python_mfti/blob/main/HW_1_RPS.ipynb](https://github.com/calabarOlga/competitive_ds/blob/main/Leonteva_Olga_Gennadyevna_CDS_HW4.ipynb)  
*Учебная задача*: Есть каршеринговая компания, которая управляет крупным автопарком машин. Наша цель — предотвратить длительные периоды простоя машин из-за поломок через своевременное обслуживание и ремонт.  
*Идея для решения проблемы*: создать приоритизированный список обхода машин. Этот список поможет технической бригаде сосредоточиться на автомобилях, которые наиболее вероятно выйдут из строя в ближайшее время.  
**Реализовано:**
- Генерация и фильтрация признаков при помощи линейной корреляции, Phik-корреляции, Feature и Permutation Importance, SHAP Values, CatBoost Feature Selection
- Обучение модели `CatBoostClassifier`
- Тюнинг гиперпараметров при помощи `Optuna`
- Блендинг моделей `CatBoostClassifier`, `LightGBMClassifier (goss)`, `XGBoostClassifier (dart)`, `RandomForestClassifier` двумя способами `Hard Voting`, `Soft Voting`
