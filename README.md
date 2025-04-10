<h1> Bangkok Airbnb Listings 2023 Data Analysis </h1>

## 1. Project Overview
Mammoth Homes Inc. is looking to purchase a property to start an Airbnb business in Bangkok. As a city of tourism, Bangkok is an optimal place to start renting. HALU Group is a strategy consultant hired by Mammoth Homes Inc. to give recommendations on the Airbnb business investment.

The problem arises from the limitation of resources and high property price, requiring an informed investment.

Thus, it is crucial to know the following:
1. What is the best area in Bangkok to invest in a property for Airbnb?
1. What is the best listing type (apartment/hotel/etc.)?
1. What is the most sought after price range per night?

## 2. Data Sources
- Bangkok Airbnb Listings 2023 (https://www.kaggle.com/datasets/minemartin/bangkok-airbnb-listings) - A dataset containing all Airbnb listings in the year 2023
- Thailand Tourism Public Data (https://www.kaggle.com/datasets/ponthakornsodchun/thailand-tourism-public-data?resource=download) – Tourism data of all cities in Thailand from the year 2019-2023

## 3. Technologies Used
- Programming Language: Python (Pandas, NumPy, Scipy)
- Visualization: Matplotlib, Seaborn, Plotly
- Interactive Dashboard: Tableau
- Version Control: Git
- Others: Jupyter Notebook

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
|
├── data
│   ├── raw            <- Data from third party sources.
│   └── cleaned        <- The data that has been cleaned.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── reports            <- Generated analysis as PowerPoint, PDF, LaTeX, etc.
|   ├── slide          <- Generated PowerPoint
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding

From our analysis, we made the following recommendations:

1. Depending on the investment budget, the ideal room type in general is **Entire home/apartment**.
2. The ideal minimum stay requirement is **short stays of 1-3 days**.
3. **Khlong Toei** remains the best area to start an Airbnb because it has the highest activity (Airbnb businesses and customer reviews) due to its tourist spots. In this area, a price range of **2000-5000 THB** per night is optimal.
4. If you are looking for cheaper investment price per sqm (150,000 THB), aim for an **Entire home/apartment** in **Vadhana (Watthana)**. In this area, you could set a mid-to-high price of **1000-5000 THB** for better profitability since the demand for such price range is apparent.
5. **Shared rooms** are generally not recommended, but if you are looking to host a shared room, **Pom Prap Sattru Phai** is your best bet. However, the price per night has to be **around 500-1000 THB** or lower.

## 6. Contact
- Name: Cindy Handoko Tantowibowo
- Email: cindyhtantowibowo@gmail.com
- Linkedin: Cindy Handoko Tantowibowo
