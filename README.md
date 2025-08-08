**📊 PhonePe Pulse Dashboard — Enhanced Version**

An interactive, data-driven dashboard built with Streamlit, Pandas, Plotly, and SQL to explore and visualize digital payment trends across India using the public PhonePe Pulse dataset.

This enhanced version transforms the static PhonePe Pulse data into a dynamic, user-friendly interface for:

Real-time transaction analysis

State-wise & national-level insights

Category-wise breakdowns with interactive filters

🚀 Features
Dual filters — switch between Year and State instantly

**Three dashboard views:**

Data Highlights — Overall trends, category-wise distribution, and yearly changes

Transactions — Category drill-down with quarterly trends

State-Level Insights — Interactive India map with highlighted state

Dynamic visualizations using Plotly

Clean, responsive UI optimized for usability and aesthetics

📂 Folder Structure

 ┣ 📂 output/                 # Processed CSV data files
 ┣ 📂 pulse/                  # JSON → CSV conversion scripts & raw data
 ┣ 📜 app.py                  # Streamlit dashboard script
 ┣ 📜 map_hover_transactions.csv
 ┣ 📜 transaction_categories.csv
 ┣ 📜 user_metrics.csv
 ┗ 📜 README.md
 
🛠️ Tech Stack
Python

Streamlit — interactive web UI

Pandas — data processing

Plotly & Seaborn — data visualization

SQL — data querying

Requests — fetching live GeoJSON map data

⚙️ Getting Started
1️⃣ Clone the Repository
bash 
git clone https://github.com/Gokulraj721/phonepe-pulse-dashboard-enhanced.git

2️⃣ Navigate to Project Folder
bash
cd phonepe-pulse-dashboard-enhanced/output

3️⃣ Run the Streamlit App
bash
bash python -m streamlit run app.py

Note: The dashboard runs locally by default at http://localhost:8505.

📈 Preview
<img width="1815" height="1087" alt="image" src="https://github.com/user-attachments/assets/545eeb69-159c-4751-8107-5c635c5acafe" />


💡 Insights from the Dashboard
Peer-to-peer payments dominate transaction volumes nationwide.

Certain states show high transaction volumes but low unique user counts — ideal targets for marketing and user growth.

Recharge & bill payments are steady but slower-growing, suggesting market maturity.

Festive season spikes are consistent across years — valuable for campaign planning.
