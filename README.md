
###******NYC Airbnb and Netflix Data Analysis******



### **Project Overview**



This project performs in-depth analysis on two major datasets:



- **Airbnb Listings in New York City (2019)**: We explore rental trends in NYC, including pricing, neighborhood popularity, and availability.

  
- **Netflix Titles**: We analyze Netflix's catalog of shows and movies, investigating various aspects like genres, production countries, and release years.
  

We employ **Python** for data cleaning, exploration, and basic analysis, while **Tableau** is used for advanced visualizations, particularly with the Netflix dataset.


------------------------------------------------------------------------------


## **Objectives**



The main goals of this project are:


1. **Analyze Airbnb Listings in NYC**: Identify key factors such as price distribution, availability trends, and neighborhood insights.

2. **Examine Netflix Titles**: Discover trends within Netflix's global content offerings, such as genre popularity, production patterns, and country-based preferences.

3. **Data Visualization**: Build engaging visualizations in **Tableau** to easily convey insights.




## **Data Sources**




### 1. **AB_NYC_2019.csv**


- **Description**: This dataset contains detailed information about Airbnb listings in New York City for the year 2019.


- **Columns**:

  - `id`: Listing ID

  - `name`: Name of the listing

  - `host_id`: Host's unique ID

  - `neighbourhood_group`: Area of the city (e.g., Brooklyn, Manhattan)

  - `price`: Price per night

  - `availability_365`: Availability of the listing throughout the year


    
- **Data Link**: [Airbnb NYC Data](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data) (Optional if publicly available)



### 2. **netflix_titles.csv**



- **Description**: This dataset includes information about Netflix's shows and movies, covering details such as title, release year, genre, cast, and more.


- **Columns**:

  - `show_id`: Unique ID for each show/movie

  - `type`: Movie or TV Show

  - `title`: Name of the title

  - `director`: Director of the title

  - `cast`: Cast members

  - `release_year`: Year of release

  - `country`: Country where the title was produced

  - `listed_in`: Genres of the title


    
- **Data Link**: [Netflix Titles Data](https://www.kaggle.com/shivamb/netflix-shows) (Optional if publicly available)



### 3. **Netflix.twbx**


- **Description**: A Tableau workbook that provides interactive data visualizations for the Netflix dataset, allowing users to explore trends by genre, release year, and country.




## **Project Structure**



Here’s the structure of the project’s files and directories:

```

.
├── AB_NYC_2019.csv             # Airbnb NYC dataset
├── netflix_titles.csv          # Netflix dataset
├── Netflix.twbx                # Tableau workbook for Netflix data visualization
├── README.md                   # Project description and details
├── analysis/
│   ├── airbnb_analysis.ipynb   # Jupyter notebook for Airbnb analysis
│   └── netflix_analysis.ipynb  # Jupyter notebook for Netflix analysis
└── visualizations/
    └── screenshots/            # Images/screenshots of key visualizations
```



## **Usage**



### **Airbnb NYC Data Analysis**


1. Open the `airbnb_analysis.ipynb` notebook.

2. Load the Airbnb dataset (`AB_NYC_2019.csv`).

3. Run the code to explore:

   - Price distribution across neighborhoods

   - Availability trends

   - Relationship between price and location



### **Netflix Titles Data Analysis**


1. Open the `netflix_analysis.ipynb` notebook.

2. Load the Netflix dataset (`netflix_titles.csv`).

3. Analyze:

   - Genre distribution over time

   - Country-wise production trends

   - Popular directors and actors




### **Visualizations**


To explore interactive visualizations:

1. Open the `Netflix.twbx` file in Tableau.

2. Browse the different dashboards:


   - **Genre Distribution by Year**


   - **Country-based Production Insights**


   - **Top Movies and Shows by Country**






