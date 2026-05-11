# Gurgaon Real Estate Market Analysis

A data analysis project focused on understanding residential property trends in Gurgaon using Python, Pandas, Matplotlib, and Seaborn.

This project analyses pricing patterns, locality trends, RERA approval impact, builder pricing behaviour, and property configurations to generate business insights for buyers, investors, and developers.

---

## Project Objective

The goal of this project is to perform Exploratory Data Analysis (EDA) on Gurgaon residential property data and answer important real estate business questions such as:

- Which is the costliest flat in the dataset?
- Which locality has the highest average property price?
- Which locality has the highest price per square foot?
- Do ready-to-move properties cost more?
- Does RERA approval affect pricing?
- Which BHK configuration is the most expensive?
- Do larger homes always have higher per sqft prices?
- Which builders consistently charge premium prices?

---

## Technologies Used

- Python 3
- Pandas
- Matplotlib
- Seaborn

---

## Dataset

Dataset used:
Gurgaon Real Estate Dataset from Kaggle

The dataset contains:
- Property prices
- Area (sqft)
- Locality information
- BHK configurations
- Builder/company names
- Property types
- RERA approval status
- Property status

---

## Project Structure

```bash
Gurgaon-Real-Estate-Market-Analysis/
│
├── main.py
├── data.csv
├── README.md
└── .gitignore
```

---

## Data Cleaning Steps

The dataset was cleaned and standardised before analysis:

- Removed duplicate rows
- Standardised column names
- Converted numeric columns into proper data types
- Cleaned categorical values
- Processed price and area columns

---

## Key Analysis Performed

### 1. Costliest Property Analysis
Identified the highest priced property in the dataset.

### 2. Locality Price Analysis
Calculated:
- Highest average property price locality
- Highest rate per sqft locality

### 3. Property Status Comparison
Compared:
- Ready-to-move properties
- Under-construction properties

### 4. RERA Approval Impact
Analysed whether RERA-approved properties command premium pricing.

### 5. Area vs Price Analysis
Studied how property area impacts total property price.

### 6. BHK Configuration Analysis
Identified the most expensive BHK configuration.

### 7. Property Type Comparison
Compared Apartments, Floors, and Plots based on pricing trends.

### 8. Builder Pricing Behaviour
Analysed builders charging the highest average rate per sqft.

### 9. Area vs Rate Per Sqft
Checked whether larger homes always have higher per sqft prices.

---

## Visualisations

The project includes scatter plots using Seaborn and Matplotlib for:
- Area vs Price
- Area vs Rate Per Sqft

These visualisations help identify pricing trends and correlations.

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Gurgaon-Real-Estate-Market-Analysis.git
```

### 2. Install Required Libraries

```bash
pip install pandas matplotlib seaborn
```

### 3. Run the Python Script

```bash
python main.py
```

---

## Sample Insights

- Premium localities have significantly higher prices and rate per sqft.
- Ready-to-move properties generally cost more.
- RERA-approved properties often command higher pricing.
- Builder reputation strongly affects property prices.
- Larger homes are not always more expensive per sqft.

---

## Learning Outcomes

Through this project, I practised:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- GroupBy Operations
- Data Visualisation
- Business Insight Generation
- Real Estate Data Analysis

---

## Future Improvements

- Build an interactive dashboard using Power BI
- Add predictive price modelling
- Deploy the analysis as a web application
- Add advanced visualisations

---

## Author

Sourav Mukherjee

Aspiring Data Analyst skilled in:
- Python
- SQL
- Power BI
- Excel
- Data Visualisation
- Exploratory Data Analysis
