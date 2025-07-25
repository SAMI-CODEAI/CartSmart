#🛒 CartSmart

## Overview
CartSmart is a Market Basket Analysis project that leverages the Apriori algorithm to uncover associations between items purchased together in transactional data. By analyzing shopping patterns, CartSmart provides valuable insights for optimizing product placement, marketing strategies, and inventory management.

## Features
- **Data Preprocessing**: Converts raw transactional data into a format suitable for Apriori analysis.
- **Apriori Algorithm**: Identifies frequent itemsets and generates association rules based on minimum support, confidence, and lift thresholds.
- **Results Visualization**: Outputs association rules in a structured DataFrame for easy interpretation.
- **Scalable Analysis**: Processes datasets with up to 7,500 transactions and 20 items per transaction.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CartSmart.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CartSmart
   ```
3. Install the required Python packages:
   ```bash
   pip install numpy pandas matplotlib apyori
   ```

## Usage
1. Place your dataset (`dataset.csv`) in the project directory. Ensure the dataset contains transactional data with items listed across columns.
2. Run the analysis script:
   ```bash
   python 23_marketbasketanalysisusingapiriori.py
   ```
3. View the results, which include:
   - A DataFrame with columns: `Left Hand Side`, `Right Hand Side`, `Support`, `Confidence`, and `Lift`.
   - Console output of the dataset shape and sample records.

## Dataset
- **Format**: CSV file (`dataset.csv`) with 7,500 rows and up to 20 columns, where each row represents a transaction and each column an item.
- **Example**:
  ```
  item1,item2,item3,...
  milk,bread,eggs,...
  ```

## Dependencies
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `apyori`

## Project Structure
- `README.md`: Project documentation.
- `23_marketbasketanalysisusingapiriori.py`: Main script for running the analysis.
- `23_MarketBasketAnalysisusingAPIRIORI.ipynb`: Jupyter Notebook version of the analysis.
- `dataset.csv`: Input dataset (not included; user-provided).

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss improvements or bug fixes.

## License
This project is licensed under the MIT License.

