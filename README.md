Заголовок и краткое описание
# Titanic Survival Prediction — Kaggle Competition

Репозиторий с решением задачи [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic).

## Описание
Проект включает:
- Предварительный анализ данных (EDA)
- Обработку пропусков и генерацию признаков
- Построение пайплайна с `ColumnTransformer`
- Подбор гиперпараметров с `RandomizedSearchCV`
- Оценку по метрикам **F1** и **ROC-AUC**
- Ансамблирование лучших моделей
- Формирование сабмита для Kaggle

## Структура
```
titanic-survival-prediction/
├── data/
│   ├── train.csv
│   └── test.csv
├── kaggleTitanic.ipynb
├── requirements.txt
└── README.md
```



## 🚀 Результат
- Лучшая модель: **GradientBoosting + RandomForest (Voting)**
- Public LB: **0.78708**


## 🛠 Установка
```bash
git clone https://github.com/Braxlysh/Titanic---Machine-Learning.git
cd Titanic---Machine-Learning
pip install -r requirements.txt
