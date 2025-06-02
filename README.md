# SaaS Revenue Intelligence Dashboard (Tableau + Tableau Prep)

mid-level skills show

This project simulates a real-world Business Intelligence solution for a subscription-based SaaS company. It showcases how Tableau Prep and Tableau Desktop can be used together to integrate multiple messy datasets, clean and enrich them, and deliver actionable insights through stakeholder-facing dashboards.

## 🎯 Business Use Case

Executives and customer-facing teams need clear visibility into revenue performance, customer retention, satisfaction (NPS), and operational support trends. This dashboard provides two perspectives:

- 📊 **Executive View**: MRR, churn rate, retention, and customer health insights
- 🛠 **Operations View**: Ticket resolution metrics, engagement scoring, and churn risk indicators

## 🧪 Data Sources

| File | Description |
|------|-------------|
| `raw_saas_data.csv` | Subscription + revenue + churn data  
| `support_tickets.csv` | Support volume, category, and resolution time  
| `nps_feedback.csv` | Customer sentiment and NPS scores  
| `product_usage.csv` | Feature usage, login activity, and engagement  

## 🧼 Data Prep (Tableau Prep)

The Prep flow performs:
- Field cleaning and standardization
- Join across 4 datasets using `Customer_ID` and `Month`
- Churn status normalization
- Calculated fields: Churn Risk Score, Lifetime Value, Engagement Index
- Output to `.hyper` for dashboard use

## 📈 Dashboards (Tableau Desktop)

### Executive Overview
- Monthly Recurring Revenue (MRR)
- Churn Rate (%)
- Net Promoter Score (NPS)
- Churn vs. NPS correlation
- Revenue by Segment & Region

### Customer Success Dashboard
- Support tickets by plan and time
- Avg. resolution time
- Engagement scoring model
- Churn probability heatmap

## 🧰 Tools Used
- Tableau Desktop  
- Tableau Prep  
- Google Sheets / Excel  
- GitHub for documentation  

## 📂 File Structure

