# 🍽️ Zomato Restaurant Data Analysis

This project performs **exploratory data analysis (EDA)** on restaurant data from Zomato. Using Python and visualization libraries, it uncovers insights into locations, ratings, cuisines, and service availability.

## 📂 Project Structure

├── ana.ipynb # Main analysis notebook
├── zomato.csv # Dataset (restaurant information)
└── README.md # Project documentation

## 🛠️ Requirements

Make sure you have Python installed. You can install the dependencies with:

```bash
pip install pandas numpy matplotlib seaborn



📈 Analysis Overview
The analysis includes:

Data Loading

Read zomato.csv into a pandas DataFrame.

Data Cleaning

Remove rows with missing values in key columns: rate, votes, online_order, book_table.

Exploratory Analysis

Count restaurants by location.

Examine online ordering and table booking availability.

Analyze ratings distribution.

Identify the most popular cuisines.

Visualization

Bar charts of locations.

Count plots of online ordering and table booking.

Pie charts of top-rated restaurants and cuisines.

📊 Example Visualizations
Top Locations by Restaurant Count

Top 10 Cuisines

Online Ordering Availability Distribution

Table Booking Availability Distribution

🚀 How to Run
Make sure zomato.csv is in the same folder as ana.ipynb.

Open a terminal and start Jupyter Notebook:

bash
Copy
Edit
jupyter notebook ana.ipynb
Run all cells to reproduce the analysis and visualizations.

📄 Dataset
The zomato.csv dataset is expected to contain columns such as:

location

rate

votes

online_order

book_table

cuisines

If your dataset has a different structure, you may need to adjust the code accordingly.

✨ Author
This project was created for educational purposes to practice data cleaning, analysis, and visualization in Python.
