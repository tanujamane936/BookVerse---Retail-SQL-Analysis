# 📚 BookVerse Retail Business Intelligence & Sales Analytics

## 📌 Project Overview

BookVerse Retail Business Intelligence & Sales Analytics is a SQL-based data analysis project designed to analyze bookstore sales, customer purchasing behavior, product performance, and inventory levels.

Using **MySQL**, we analyzed data from three related tables to identify sales trends, top-performing books and authors, valuable customers, and inventory management opportunities. The project demonstrates how SQL can transform raw business data into meaningful insights for better decision-making.

## 🎯 Project Objectives

- Analyze total orders, quantity sold, and revenue.
- Identify top-performing books, authors, and genres.
- Understand customer purchasing behavior and spending patterns.
- Analyze monthly sales trends.
- Identify low-stock books and inventory imbalances.
- Recommend restocking and promotional opportunities.

## 🛠️ Tools & Technologies

- **Database:** MySQL
- **Language:** SQL
- **Analysis Techniques:** Data aggregation, joins, filtering, grouping, sorting, and subqueries
- **Documentation & Presentation:** PowerPoint

## 🗂️ Database Structure

The project uses three relational tables, each containing 500 rows.

| Table | Description | Key Columns |
|---|---|---|
| `Books` | Book details and inventory | Book_ID, Title, Author, Genre, Price, Stock |
| `Customers` | Customer information | Customer_ID, Name, City, Country |
| `Orders` | Sales transaction details | Order_ID, Customer_ID, Book_ID, Order_Date, Quantity, Total_Amount |

**Relationships:**
- `Orders.Customer_ID` references `Customers.Customer_ID`.
- `Orders.Book_ID` references `Books.Book_ID`.
- One customer can place multiple orders.
- One book can appear in multiple orders.

## 🔍 Key SQL Concepts Used

- SELECT, WHERE, ORDER BY and LIMIT
- Aggregate functions: SUM(), COUNT(), AVG()
- GROUP BY and HAVING
- INNER JOIN and relational data analysis
- Date functions: YEAR() and MONTH()
- Revenue and sales aggregation
- Top-selling product analysis
- Customer spending analysis
- Inventory filtering and stock analysis

## 📊 Key Business Insights

The following findings are based on the project's analysis.

| Metric | Result |
|---|---:|
| Total Orders | 500 |
| Total Copies Sold | 2,697 |
| Total Revenue | $75,628.66 |
| Highest-Revenue Author | Sheena Harris |
| Highest-Revenue Genre | Romance |
| Highest-Sales-Volume Genre | Mystery |
| Most-Ordered Customer | Carrie Perez |

Additional findings:

- Romance generated the highest genre revenue at **$13,086.98**.
- Mystery recorded the highest sales volume with **504 copies sold**.
- The top-selling book sold 28 copies.
- Some books had zero stock and required restocking assessment.
- High-stock, low-sales books presented potential opportunities for targeted promotions.

## 💡 Business Recommendations

1. **Inventory Optimization:** Prioritize restocking books with low inventory and demonstrated customer demand.
2. **Targeted Promotions:** Consider promotions for books with high stock but low sales.
3. **Revenue Growth:** Study successful genres, authors, and books to identify opportunities for expanding sales.
4. **Customer Retention:** Reward frequent and high-value customers through loyalty programs.
5. **Sales Planning:** Use monthly revenue trends to support future sales and inventory planning.

## 📁 Project Structure

A suggested GitHub repository structure:

```text
BookVerse-Retail-SQL-Analysis/
│
├── README.md
├── BookVerse_PPT_Project.pptx
├── sql/
│   ├── create_tables.sql
│   ├── data_analysis_queries.sql
│   └── business_insights.sql
│
└── images/
    └── er_diagram.png
```

*Note: Add the SQL files and image only if you have created them. The PPT filename can be adjusted to match the file uploaded to your repository.*

## 🚀 How to Run the Project

1. Install MySQL Server and MySQL Workbench.
2. Create a database named `BookVerse_DB`.
3. Create the `Books`, `Customers`, and `Orders` tables.
4. Import the corresponding dataset into each table.
5. Execute the SQL analysis queries.
6. Review the results to understand sales, customer behavior, and inventory performance.

## 📈 Project Outcome

This project strengthened our practical understanding of MySQL, relational database design, SQL joins, aggregate functions, and business-oriented data analysis. It demonstrates how SQL can support data-driven decisions in retail sales and inventory management.

## 👥 Team Members

- **Saurabh Patil**
- **Tanuja Mane**

## 🔗 Connect With Us

- GitHub: [Saurabh Patil](https://github.com/saurabhpatil8010)
- GitHub: [Tanuja Mane](https://github.com/tanujamane936)

---

⭐ If you find this project useful, consider giving the repository a star!
