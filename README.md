# 🎨 SQL Paintings Case Study

This project explores a dataset of **Famous Paintings & Museums** using **SQL queries** to answer various analytical questions.

## 📂 Project Structure

- **`load_csv_files.py`**: Script to load dataset CSV files into a **PostgreSQL** database.
- **`Questions.txt`**: A list of SQL problems to solve using the dataset.
- **`Solutions.txt`**: SQL queries solving the problems.
- **`SQL Paintings Casestudy - Questions.pdf`**: PDF version of the problem statements.

## 📊 Dataset

The dataset used in this project can be found on **Kaggle**:  
🔗 [Famous Paintings Dataset](https://www.kaggle.com/datasets/mexwell/famous-paintings)

## 🛠️ Setup Instructions

1. **Database Setup**  
   - Install PostgreSQL and create a database named `painting`.
   - Update the `conn_string` in `load_csv_files.py` with your database credentials.

2. **Load Data**  
   - Download the dataset from the link above and place the CSV files in the appropriate directory.
   - Run `load_csv_files.py` to populate the database.

3. **Run Queries**  
   - Use the queries in `Solutions.txt` to analyze the data.

## ✅ SQL Problems Covered

✔️ Find paintings that are not displayed in any museum.  
✔️ Identify museums without any paintings.  
✔️ Compare asking price vs. regular price of paintings.  
✔️ Identify the most and least popular painting styles.  
✔️ Find museums that are open every day.  
✔️ Detect and remove duplicate records.  
...and many more!

## 📌 Additional Notes

- This project demonstrates SQL skills such as **JOINs, RANK, GROUP BY, and WINDOW functions**.
- Queries can be modified for different **business insights**.

## 📜 License

This project is licensed under the **Apache License 2.0**.  
See the [LICENSE](LICENSE) file for more details.

---

🚀 *Happy Querying!*
