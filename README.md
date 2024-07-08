# Grocery Store Purchase Pattern Analysis

## Project Overview
This project analyzes customer purchase patterns in a grocery store using the Apriori algorithm for association rule mining. The goal is to uncover insights about customer behavior and product associations that can inform business strategies.

## Repository Contents
- `MasketBasketAnalysis.ipynb`: Jupyter notebook containing the entire analysis pipeline, from data loading to visualization of results.

## Dataset
The project uses a Kaggle dataset containing grocery store purchase information. The dataset includes:
- Member number
- Date of purchase
- Item description

Note: The dataset file is not included in this repository. Please ensure you have the 'Groceries_dataset.csv' file in the same directory as the notebook when running the analysis.

## Technologies Used
- Python 3.x
- Pandas: For data manipulation and analysis
- NumPy: For numerical operations
- Matplotlib and Seaborn: For data visualization
- Apyori: For implementing the Apriori algorithm

## Project Structure

The Jupyter notebook covers the following steps:

1. Data Loading and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Association Rule Mining with Apriori
4. Visualization of Association Rules

## Key Insights

The notebook provides insights after each major step, including:
- Identification of most popular items
- Understanding of sales trends over time
- Recognition of busiest days of the week
- Discovery of strong product associations

## How to Run
1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed and all required libraries (pandas, numpy, matplotlib, seaborn, apyori).
3. Place the 'Groceries_dataset.csv' file in the same directory as the notebook.
4. Open the `MasketBasketAnalysis.ipynb` file in Jupyter Notebook.
5. Run all cells in the notebook to see the analysis and results.

## Future Improvements
- Implement more advanced association rule algorithms
- Develop a recommender system based on the findings
- Integrate with a dashboard for real-time analysis

## Contributing
Feel free to fork this project and submit pull requests with improvements or open issues for any bugs or suggestions.

## License
This project is open source and available under the [MIT License](LICENSE).
