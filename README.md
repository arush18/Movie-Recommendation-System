# Movie Recommendation System

## Overview

This project is a **Movie Recommendation System** that analyzes a dataset of **50,000+ movies** from Kaggle.  
It leverages **content-based filtering** and **collaborative filtering** techniques to suggest relevant movies to users.  
Additionally, **Exploratory Data Analysis (EDA)** is performed to understand the dataset better.  

## Project Structure

```
Movie-Recommendation-System/
│── datasets/ (Not included in repo)
│── results/
│ ├── visualizations/
│ │ ├── heatmap_features.png
│ │ ├── rating_dist.png
│── src/
│ ├── main.ipynb
│── .gitignore
│── README.md
│── LICENSE.md
```


## Features

✔️ **Data Preprocessing:** Handling missing values and cleaning the dataset.  
✔️ **Exploratory Data Analysis (EDA):**  
   - Correlation heatmaps  
   - Rating distribution plots  
✔️ **Content-Based Filtering:**  
   - Recommends movies using metadata features such as genres, descriptions, and keywords.  
✔️ **Collaborative Filtering:**  
   - Suggests movies based on user interactions and preferences.  

## Installation

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/arush18/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### 2️⃣ Create a Virtual Environment (Optional)
```sh
python -m venv venv
source venv/bin/activate  # On Window use `venv\Scripts\activate`
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Download Dataset
- The dataset is not included in this repository due to size limitations.
- Download the dataset from Kaggle and place it in the datasets/directory.

### 5️⃣ Run the Jupyter Notebook

```sh
jupyter notebook src/main.ipynb
```

## Visualizations

- 🔥 Feature Correlation Heatmap
This heatmap shows correlations between different numerical features in the dataset.

- 🎬 Movie Rating Distribution
The following graph represents the distribution of user ratings for movies.

## License

This project is licensed under the MIT License.