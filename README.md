# Data Cleaning - Medical Appointment No Shows

## 📌 Objective
To clean and preprocess the raw dataset by handling missing values, duplicates, incorrect data formats, and inconsistent column names using Python and Pandas.

## 📁 Dataset Used
[Medical Appointment No Shows Dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

## 🧪 Tools & Libraries
- Python
- Pandas
- Jupyter Notebook 

## 🔧 Steps Performed
1. **Loaded the dataset** using `pandas.read_csv()
2. **dataset information**using .info()`
3. **Checked for missing values** using `.isnull().sum()`
4. **Dropped duplicates** with `.drop_duplicates()`
5.**changing patientid column from significant value to normal integer** with .apply(lambda x: '{:.0f}'.format(float(x)))
6. **Converted date columns** to proper datetime format using `pd.to_datetime()`
  

## ✅ Final Output
- Cleaned dataset file: `cleaned_appointments.csv`

## 🔍 Insights / Observations
-changing patientid column from significant value to normal integer
- Dates were initially in ISO format; now standardized

---

## 🙌 Acknowledgements
- Kaggle for the dataset
