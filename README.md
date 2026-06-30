# Movie Recommender System (Neural Network)

## 🇬🇧 English

This is a neural network-based movie recommendation system project.

### Description
The model predicts user ratings for movies using collaborative filtering with embedding layers.

- learns user and item embeddings
- trained on explicit rating data
- predicts rating for a given user-movie pair

### Model Architecture
- User embedding layer
- Movie embedding layer
- Concatenation of embeddings
- Fully connected dense layers
- Output layer for rating prediction (regression)

### Dataset

The project uses the MovieLens dataset provided by GroupLens:

- https://grouplens.org/datasets/movielens/

Files used:
- movies.csv
- ratings.csv

### Training Process
- Data preprocessing and ID mapping
- Train/test split (80/20)
- Loss function: MSE
- Optimizer: Adam
- Training epochs: 5

### Evaluation Metrics

Model performance on test data:

- ROC-AUC: 0.773  
- RMSE: 0.8883  
- MAE: 0.6836  
- MSE: 0.7890  

### Features
- Neural collaborative filtering model
- Embedding-based recommendation system
- Regression-based rating prediction
- Model evaluation using multiple metrics
- ROC curve analysis (binary threshold ≥ 4)
- Model saving for inference

### Technologies Used
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Output
The model predicts user preferences and estimates movie ratings based on historical interaction data.

---

## 🇷🇺 Русский

Это проект системы рекомендаций фильмов на основе нейронной сети.

### Описание
Модель предсказывает оценки пользователей для фильмов с использованием коллаборативной фильтрации и эмбеддингов.

- изучает эмбеддинги пользователей и фильмов
- обучается на данных оценок
- предсказывает рейтинг для пары пользователь–фильм

### Архитектура модели
- эмбеддинги пользователей
- эмбеддинги фильмов
- объединение эмбеддингов
- полносвязные слои
- выходной слой для предсказания рейтинга

### Данные

Используется датасет MovieLens от GroupLens:

- https://grouplens.org/datasets/movielens/

Файлы:
- movies.csv
- ratings.csv

### Процесс обучения
- предобработка данных и маппинг ID
- разделение train/test (80/20)
- функция потерь MSE
- оптимизатор Adam
- 5 эпох обучения


### Метрики качества

Результаты на тестовой выборке:

- ROC-AUC: 0.773  
- RMSE: 0.8883  
- MAE: 0.6836  
- MSE: 0.7890  

### Возможности
- модель коллаборативной фильтрации
- рекомендации на основе эмбеддингов
- предсказание рейтингов
- оценка качества модели
- ROC-кривая
- сохранение модели для использования

### Технологии
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Результат
Модель способна предсказывать предпочтения пользователей и оценивать фильмы на основе исторических данных взаимодействий.
