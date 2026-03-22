# Ecommerce Sales Dashboard

## 📖 Project Description
The **Ecommerce Sales Dashboard** is a Power BI project designed to provide a comprehensive view of ecommerce sales performance across multiple dimensions such as states, customers, product categories, payment modes, and time periods. By consolidating transactional data into interactive visuals, this dashboard empowers business owners, analysts, and managers to monitor trends, identify high-performing areas, and address potential issues in ecommerce operations.

The dashboard highlights **key performance metrics** including:
- Total Sales Amount
- Quantity Sold
- Profit
- Average Order Value (AOV)

Filters such as **quarter selection** and **state selection** allow users to drill down into specific timeframes or regions for deeper insights.  

Sales distribution is visualized across states, with Maharashtra contributing the highest revenue, while Delhi shows the lowest. Customer-level analysis identifies top buyers like Harivansh and highlights opportunities to engage lower-spending customers.  

Category insights reveal that **Clothing dominates sales volume (63%)**, followed by Electronics and Furniture. Payment mode analysis shows **Cash on Delivery (COD)** as the most preferred option, while UPI, debit cards, credit cards, and EMI contribute smaller shares.  

Profit trends are tracked monthly, with December showing peak profitability, while June and July reflect losses. Sub-category analysis highlights **Printers** as the most profitable item, whereas Tables generate the least profit. These insights help businesses optimize product strategies, pricing, and promotions.

---

## 🗂️ Data Model
The project uses a **two-table relational model**:
- **Orders Table**: Contains customer and order-level information (City, CustomerName, Order Date, State, Order ID).
- **Details Table**: Contains transaction-level details (Amount, AOV, Category, PaymentMode, Profit, Quantity, Order ID).

A **one-to-many relationship** is established between `Orders` (one side) and `Details` (many side) using the **Order ID** field. This ensures accurate aggregation of sales metrics across customers, states, and product categories.

---

## ⚙️ Installation    
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecommerce-dashboard.git


   Usage Instructions
- Open the Ecommerce.pbix file in Power BI Desktop.
- Use filters (Quarter, State) to customize views.
- Explore sales by state to identify regional performance.
- Review customer-level sales to target top buyers.
- Analyze category and payment mode charts for product and payment insights.
- Track monthly profit trends to plan seasonal strategies.
- Compare sub-category profits to optimize product portfolios

  Future Enhancements
- Integration of real-time sales data feeds.
- Predictive analytics for customer churn and demand forecasting.
- AI-driven recommendations for product bundling and promotions.
- Automated reporting for quarterly and annual performance reviews.


---
 

