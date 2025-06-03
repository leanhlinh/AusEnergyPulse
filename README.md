⚡ AusEnergyPulse – Australian Renewable Energy Investment Tracker
AusEnergyPulse is a Streamlit-based interactive dashboard and ML pipeline that analyzes Australia’s renewable energy and critical mineral investments using real government data. It includes forecasting (Prophet) and clustering (KMeans) to support smarter energy policy and project decisions.

📊 Features
✅ Real-world investment data cleaned from Excel (Department of Industry, Science and Resources)

📈 Forecasting future trends with Facebook Prophet

🔍 KMeans clustering on cost, jobs, and timelines

🗺️ Geospatial mapping of projects (with Plotly)

⏳ Time-based pipeline analysis

📂 Easy Streamlit deployment

📁 Project Structure

ausenergypulse/
├── streamlit_app.py
├── requirements.txt
├── data/
│   └── resources-and-energy-major-projects-2024-data.xlsx
├── outputs/
│   └── critical_minerals_map.html
└── README.md

💡 Future Enhancements
We plan to add LangChain integration in the next version to allow natural language querying of the dashboard (e.g., "Show me all hydrogen projects in Victoria with over $1B investment").
LangChain is easy to plug in using Streamlit chat components and OpenAI or Claude APIs.

👤 Author
Anh Linh Le
