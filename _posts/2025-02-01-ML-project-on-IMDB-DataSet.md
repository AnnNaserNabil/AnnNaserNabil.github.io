---
title: "Movie Genre Trend Analysis (2010-2020)"
date: 2025-01-30 10:12:43 +0000
categories: [Analysis, EDA, MlOps, DevOps]
tags: 
  - MlOps
description: "End To End Data Enginnering Project on IMDB Dataset"
pin: true
image: 
  path: "/assets/images/images - 2025-02-01T030007.176.jpeg"
  alt: "Movies"
---


# Movie Genre Trend Analysis (2010-2020)



   
  <div style="text-align: center;">
        <a href="https://github.com/AnnNaserNabil/imdb___analysis" 
           style="color: red; font-size: 24px; font-weight: bold;">
            Genre Trend Analysis Project's GitHub Repo
        </a>
    </div>




## Project Overview
This project aims to analyze the trends in movie genres over the years from 2010 to 2020. By leveraging the IMDb API, we collect movie data, store it in a SQL database, and perform detailed analysis to uncover insights into how movie genres have evolved over the decade. The final output is a web-based dashboard deployed on the Streamlit Cloud platform, providing an interactive and visually appealing overview of the analysis.

## Project Workflow

### 1. Data Collection
- **IMDb API Integration**: Use an IMDb API key to fetch movie data, including details such as title, release year, genre, ratings, and more.
- **Data Extraction**: Extract data for movies released between 2010 and 2020.

### 2. Data Storage
- **SQL Database**: Store the collected movie data in a SQL database for efficient querying and management.
- **Database Schema**: Design a schema to organize movie details, genres, and ratings effectively.

### 3. Data Processing and Analysis
- **Data Cleaning**: Handle missing values, duplicates, and inconsistencies in the dataset.
- **Genre Trend Analysis**: Analyze the popularity and trends of different genres over the years.
- **Statistical Insights**: Calculate metrics such as average ratings, number of movies per genre, and year-on-year growth.

### 4. Data Visualization
- **Visualization Tools**: Use libraries like Matplotlib, Seaborn, and Plotly to create visualizations.
- **Key Visualizations**:
  - Genre popularity over the years.
  - Average ratings by genre.
  - Yearly distribution of movies across genres.

### 5. Dashboard Development
- **Streamlit Web App**: Develop an interactive dashboard using Streamlit.
- **Features**:
  - Filters for year and genre.
  - Interactive charts and graphs.
  - Summary statistics and insights.

### 6. Deployment
- **Streamlit Cloud**: Deploy the final dashboard on Streamlit Cloud for public access.
- **User Interface**: Ensure a user-friendly interface with clear navigation and responsive design.

## Technologies Used
- **Programming Language**: Python
- **APIs**: IMDb API
- **Database**: SQL (e.g., MySQL, PostgreSQL)
- **Data Analysis Libraries**: Pandas, NumPy
- **Visualization Libraries**: Matplotlib, Seaborn, Plotly
- **Web Framework**: Streamlit
- **Deployment Platform**: Streamlit Cloud

## Project Deliverables
1. **SQL Database**: Containing cleaned and structured movie data.
2. **Jupyter Notebooks**: For data cleaning, analysis, and visualization.
3. **Streamlit App Code**: Python scripts for the web application.
4. **Deployed Dashboard**: Accessible via a public URL on Streamlit Cloud.
5. **Documentation**: Detailed README file explaining the project setup, workflow, and usage.


## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/AnnNaserNabil/imdb___analysis__Done.git

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
3. Set up the environment variables by creating a .env file with your database and API key configurations:
   ```bash
   PGDATABASE=your_database_name
   PGUSER=your_database_user
   PGPASSWORD=your_database_password
   PGHOST=your_database_host
   PGPORT=your_database_port
   TMDB_API_KEY=your_tmdb_api_key

4. Run the ETL pipeline to populate the database:
   ```bash
   python app/pipeline.py

5. Launch the Streamlit dashboard:

   ```bash
   streamlit run app/dashboard.py


## Thank You
