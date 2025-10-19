# data_anlysis_project

# Video Game Data Analysis Project

This project explores various dimensions of the video game industry using multiple datasets and research questions. The analysis focuses on player engagement, perception differences between users and critics, and sales performance across global markets.

## Folder Structure

### 📁 Data Collection/
Contains the notebook used to retrieve raw data from external APIs and sources.

- `0000_rawg_data_collection.ipynb`: Script for collecting data from the RAWG API.
- `Raw Data/`: Directory holding unprocessed raw data files.

---

### 📁 Data Cleaning/
Includes notebooks and files for data exploration, cleaning, and integration.

- `1000_understanding_data.ipynb`: Initial data exploration and feature understanding.
- `1001_cleaning_data.ipynb`: Full data cleaning and merging process.
- `final_dataset.csv`: The final cleaned dataset used across all analyses.
- `raw_rawg.csv`, `steam.csv`, `vgsales.csv`: Source datasets.

---

### 📁 Data Analysis/
Divided into three thematic areas based on the research questions.

#### Engagement Analysis/
Analyzes how players interact with games, especially in terms of playtime and monetization models.

- `RQ1.ipynb`: Identifies games with the highest playtime per user.
- `RQ2.ipynb`: Compares player engagement between free-to-play and paid games.
- `Visualization/`: Contains visuals used for analysis and presentation purposes.

#### Perception Analysis/
Focuses on differences between critic and player ratings, and how these affect sales.

- `RQ1_RQ2.ipynb`: Examines whether user-rated games perform better commercially than critic-rated ones, and how this varies by genre/platform.
- `RQ3.ipynb`: Analyzes how score gaps (critic vs user) relate to game sales.
- `RQ3 Visuals/`: Contains relevant visual assets.

#### Regional Analysis/
Looks at how game sales and genre/platform preferences vary by region.

- `RQ3-1.ipynb`, `RQ3-2.ipynb`, `RQ3-3.ipynb`: Notebooks addressing regional differences in game success and preferences.
- `final_dataset.csv`: Dataset reused for regional analysis.

---

## Getting Started

To understand the structure and purpose of the project:
1. Start by reviewing the `Data Cleaning/` notebooks to understand how the final dataset was prepared.
2. Move to the `Data Analysis/` folders to follow the insights derived from each research question.

Each notebook is self-contained and includes inline commentary and conclusions based on the visual outputs and statistical methods used.
