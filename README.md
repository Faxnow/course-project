# Spotify Music Tracks Clustering & Analysis 🎵
> Coursework / Курсовая работа

A Machine Learning and Data Science coursework project focused on exploring audio features from Spotify and grouping music tracks using unsupervised learning (clustering) algorithms. Developed entirely within the **Jupyter Notebook** environment.

Курсовой проект в области машинного обучения и анализа данных, посвященный исследованию аудиохарактеристик Spotify и группировке музыкальных треков с использованием алгоритмов кластеризации (обучение без учителя). Работа полностью выполнена в веб-среде **Jupyter Notebook**.

---

## 🇬🇧 English

### 📊 Dataset
The analysis is based on the **Spotify Music Popularity Analysis** dataset available on Kaggle:
🔗 [Kaggle Dataset Link]([https://kaggle.com](https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset?select=low_popularity_spotify_data.csv))

### 📌 Project Overview
The goal of this project is to process acoustic properties of tracks (such as tempo, loudness, acousticness, and liveness) to find hidden patterns and perform comprehensive audio profiling.

### ⚙️ Project Pipeline
1. **Data Preprocessing & EDA:** Technical audit of 29 features, handling missing values, feature distribution checking, and filtering out outliers using Interquartile Range / Standard Deviation methods (e.g., speechiness filtering).
2. **Feature Engineering:** Encoding metadata using `LabelEncoder` and scale transformation via `StandardScaler` / `MinMaxScaler`.
3. **Clustering Algorithms:** Benchmarking 3 distinct algorithms to group tracks:
   - **K-Means** (optimized via The Elbow Method and Silhouette Analysis)
   - **DBSCAN** (optimized via K-distance graph for optimal EPS detection)
   - **Agglomerative Hierarchical Clustering** (Ward's linkage method)
4. **Evaluation:** Performance validation using *Silhouette Score* and *Davies-Bouldin Index*.
5. **Dimensionality Reduction & Visualization:** Projecting multi-dimensional audio data into 2D/3D space via **PCA** and **t-SNE** for cluster profiling.

### 🛠️ Tech Stack & Libraries
- **Core:** Python (Jupyter Notebook)
- **ML & Data Processing:** Scikit-learn, Pandas, NumPy, SciPy
- **Visualization:** Matplotlib, Seaborn, Plotly Express

---

## 🇷🇺 Русский

### 📊 Датасет
Анализ проведен на основе датасета **Spotify Music Popularity Analysis**, взятого с платформы Kaggle:
🔗 [Ссылка на датасет Kaggle]([https://kaggle.com](https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset?select=low_popularity_spotify_data.csv))

### 📌 Обзор проекта
Цель проекта — обработать акустические свойства треков (такие как темп, громкость, акустичность и динамичность) для поиска скрытых закономерностей и создания профилей музыкальных данных.

### ⚙️ Пайплайн проекта
1. **Предобработка данных и EDA:** Технический аудит 29 признаков, обработка пропусков, визуализация распределения признаков, очистка от выбросов и расчет корреляционной матрицы (например, фильтрация по speechiness).
2. **Инженерия признаков:** Кодирование категориальных данных с помощью `LabelEncoder` и масштабирование фич через `StandardScaler` / `MinMaxScaler`.
3. **Алгоритмы кластеризации:** Сравнительный анализ трех алгоритмов для группировки треков:
   - **K-Means** (оптимизация через Метод локтя и Анализ силуэтов)
   - **DBSCAN** (поиск оптимального EPS через K-distance граф)
   - **Иерархическая кластеризация** (метод связи Уорда)
4. **Валидация:** Оценка качества кластеризации с помощью *Коэффициента силуэта* и *Индекса Дэвиса-Болдина*.
5. **Снижение размерности и визуализация:** Проекция многомерных признаков в 2D/3D-пространство через **PCA** и **t-SNE** для профилирования кластеров.

### 🛠️ Стек технологий
- **Язык:** Python (Jupyter Notebook)
- **ML и аналитика:** Scikit-learn, Pandas, NumPy, SciPy
- **Визуализация:** Matplotlib, Seaborn, Plotly Express
