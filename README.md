# DBSCAN Silicon Defect Detection

A Python project that detects silicon wafer defects using the DBSCAN clustering algorithm. This project aims to identify and visualise potential defect patterns based on wafer coordinate data.

## Project Structure

- **`data/`**: Contains the dataset used for analysis and prediction.
- **`notebooks/`**: Jupyter notebooks for data analysis, feature engineering, and model building.
- **`README.md`**: Project overview and usage instructions.

---

## Features

- Load silicon wafer coordinate data from CSV files
- Apply DBSCAN clustering to detect potential defect patterns
- Automatically save clustering visualisations as images
- Adjustable DBSCAN parameters (`eps` and `min_samples`) for fine-tuning results

## Tools & Libraries

- **Python 3.10+**
- **Pandas** - for data handling
- **NumPy** - for numerical operations
- **Scikit-learn** - for the DBSCAN clustering
- **Matplotlib** - for visualisation

---

## How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nurulashraf/dbscan-silicon-defect-detection.git
   cd dbscan-silicon-defect-detection
   ```

2. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ``` 

3. **Prepare your data**

    Place your silicon wafer coordinate data in the `data/` folder as `silicon_defect_data.csv`. The file should have two columns: `x` and `y`. 

5. **Run the defect detection:**
    ```bash
    python dbscan_silicon_defect_detection.ipynb
    ```

6. Run the cells and explore the analysis.

---

## License

This project is licensed under the [MIT License](LICENSE).
