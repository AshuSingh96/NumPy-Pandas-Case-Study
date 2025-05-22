# Sales Data Analysis Project

## Project Setup

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
   cd <repository_folder>
````

2. **Create a virtual environment (optional but recommended):**

   ```
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install required dependencies:**

   ```
   pip install -r requirements.txt
   ```

4. **Prepare your dataset:**

   * Place your CSV dataset file (e.g., `sales_data.csv`) in the project folder or update the data path in the code accordingly.

---

## Build Commands

* **Run the main Python script to clean and analyze data:**

  ```
  python main.py
  ```

* (Optional) To export cleaned data:

  ```
  python export_cleaned_data.py
  ```

* For Jupyter notebooks, start with:

  ```
  jupyter notebook
  ```

---

## Functionalities

This project performs the following:

* **Data Cleaning:**

  * Handles missing values in sales data (`Quantity`, `UnitPrice`, `TotalSales`, etc.)
  * Converts date columns to proper datetime format
  * Fills or drops incomplete rows as needed

* **Sales Analysis:**

  * Calculates total and average sales by region and product
  * Identifies highest and lowest selling products
  * Computes statistical measures such as mean, median, and standard deviation of numeric columns


