## Key Findings

### 📈 Revenue & Sales
- Analyzed **96,477 real orders** with **R$ 19.4M+ total revenue**
- **São Paulo (SP)** is the top revenue-generating state
- Revenue peaked in **November 2017** (Black Friday effect) 
  then dropped sharply in late 2018 — raising data completeness questions
- Peak order hours are **10am–4pm on weekdays** — ideal window 
  for marketing campaigns and push notifications

### 🚚 Delivery & Logistics
- Average delivery time: **12 days** — significant opportunity 
  for logistics optimization
- Customers receiving orders in **under 7 days order 40% more frequently** 
  — proving delivery speed directly drives retention
- Freight costs **exceed the product price** in thousands of orders 
  — a hidden margin killer affecting profitability

### 🤖 Machine Learning & Customer Segmentation
- Engineered **RFM (Recency, Frequency, Monetary)** features 
  from raw transactional data
- Applied **KMeans clustering** (K=4 via Elbow Method) to segment 
  customers into 4 actionable groups:
  - 💎 Champions — high spend, frequent, recent
  - 🔄 Recent Buyers — just started, high potential
  - 🌱 Potential Loyalists — moderate activity, can be nurtured
  - 😴 At-Risk — haven't purchased in 200+ days
- Achieved **Silhouette Score of 0.525** — confirming 
  well-separated, meaningful clusters

### 📊 Hidden Business Insights
- **Pareto Principle validated** — top 20% of customers 
  drive majority of total revenue
- Retention marketing should **laser-focus on Champions segment** 
  to maximize ROI
- At-Risk customers identified — a **churn prediction model** 
  (Logistic Regression on RFM) could flag them 30 days before leaving

### 🔮 Future Scope
- Build a **churn prediction model** using Logistic Regression 
  on RFM features
- Implement **dynamic pricing** on high freight-ratio orders 
  to reduce cart abandonment
- Train an **LSTM model** on delivery data to predict delays 
  and enable proactive customer communication
