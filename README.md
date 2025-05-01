# task7

# Sales Data Analysis with SQLite and Python

This project demonstrates how to analyze sales data using SQLite for database management and Python for data visualization. The notebook includes SQL queries to extract sales summaries and product performance metrics, followed by visualizations using `matplotlib`.

## Features

- **Database Setup**: Creates an SQLite database and populates it with sample sales data.
- **Sales Summary**: Calculates total quantity sold, total revenue, and average sale amount.
- **Product Performance**: Displays revenue and quantity sold per product in a tabular format.
- **Data Visualization**: Generates a bar chart showing revenue by product.

## Requirements

- Python 3.x
- SQLite3
- pandas
- matplotlib

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sales-data-analysis.git
   cd sales-data-analysis
Install the required packages:

bash
pip install pandas matplotlib
Usage
Run the Jupyter notebook:

bash
jupyter notebook task_7.ipynb
Execute all cells to:

Create and populate the SQLite database.

Generate sales summaries and product performance metrics.

Display the bar chart visualization.

Output
The notebook produces:

A text summary of sales metrics.

A table of product performance.

A bar chart saved as sales_chart.png.

Sample Output
Sales Summary
=== SALES SUMMARY ===
Total Quantity Sold: 82
Total Revenue: $34,399.18
Average Sale Amount: $4,299.90

=== PRODUCT PERFORMANCE ===
   product  total_qty  revenue
Smartphone         22 15399.78
    Laptop          8  7999.92
Headphones         40  5999.60
    Tablet          8  3999.92
   Monitor          4   999.96
Visualization
Product Revenue Bar Chart

License
This project is licensed under the MIT License - see the LICENSE file for details.


### Key Notes:
1. Replace `yourusername` with your actual GitHub username in the clone command.
2. The `LICENSE` file mentioned should be added to your repo if you choose to include one.
3. The requirements are based on the imports seen in the notebook (`sqlite3`, `pandas`, `matplotlib`).
4. The sample output matches the notebook's output format.

You can customize this further by:
- Adding a project logo/banner
- Including contribution guidelines
- Adding more detailed usage examples
- Expanding the visualization section with more plot examples
