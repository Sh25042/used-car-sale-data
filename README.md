# 🚗 Used Car Price Analysis

This project performs data analysis and visualization on a used car price dataset to uncover trends, handle missing values, and explore relationships between key features such as price, mileage, brand, and manufacturing year.

---

## 📁 Dataset

**File:** `used_car_price_dataset_extended final.csv`  
The dataset contains information about used cars, including:

- `price_usd`
- `make_year`
- `mileage_kmpl`
- `fuel_type`
- `engine_cc`
- `brand`
- ...and more

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Missingno

---

## 📊 Key Steps in Analysis

### 1. 📥 Load and Inspect Data

```python
data = pd.read_csv('used_car_price_dataset_extended final.csv')
data.info()
data.describe(include='all')
