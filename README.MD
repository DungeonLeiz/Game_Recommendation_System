# Game_Recommendation_System

Welcome to **Game_Recommendation_System**! This is a personal project where I use machine learning to recommend games based on previous input game.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Setup](#setup)
4. [Usage](#usage)

## Introduction

This project is designed to use collaborative filtering abd content-based filtering to extract most neareast games of the input games and result the recommended games based on similarity distances. This project may contain multiple components, including scripts, applications, and documentation.

## Project Structure

```
├── data/                   # Video Game Dataset
│   ├── processed/
│   │   ├── processed_data.csv
│   │   ├── scaled_features.csv
│   ├── raw/
│   │   ├── video_game_dataset.csv
├── docs/                   # Requirement libs
│   ├── requirements.txt
├── model/
│   ├── Nearest_Neighbor.pkl   
│   ├── Vectorizer.pkl                     
├── notebooks/              # Jupyter notebooks
│   ├── config.yaml
│   ├── data_exploration.ipynb
│   ├── model_training.ipynb
├── report/                 # Project Report
│   ├── Video_Game_Recommendation_System.docx
│   src/
│   ├── config.yaml
│   ├── Game_Recommender.py
│   └── main.py
```

## Setup

**Install dependencies**
   ```bash
   git clone https://github.com/DungeonLeiz/Game_Recommendation_System.git
   cd Atmospheric_Weather_Classification
   pip install -r requirements.txt
   ```
   or 
   ```bash
   git clone https://github.com/DungeonLeiz/Game_Recommendation_System.git
   cd Atmospheric_Weather_Classification
   pip3 install -r requirements.txt
   ```

## Usage

   ```bash
   cd src
   python main.py
   ```
   or 
   ```bash
   cd src
   python3 main.py
   ```
