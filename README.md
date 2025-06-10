⚡ AusEnergyPulse – Australian Renewable Energy Investment Tracker
AusEnergyPulse is a Streamlit-based interactive dashboard and ML pipeline that analyzes Australia’s renewable energy and critical mineral investments using real government data. It includes forecasting (Prophet) and clustering (KMeans) to support smarter energy policy and project decisions.

📊 Features
✅ Real-world investment data cleaned from Excel (Department of Industry, Science and Resources)

![image](https://github.com/user-attachments/assets/e550d9de-a08e-408d-9e88-b6b6dc8ee5aa)

![image](https://github.com/user-attachments/assets/c2e7fefb-784f-4bb8-a59f-bec50bf42abc)

![image](https://github.com/user-attachments/assets/775cebac-fcc0-4a5c-bbd0-e81ac475e05e)


📈 Forecasting future trends with Facebook Prophet

![image](https://github.com/user-attachments/assets/f7dfb9fb-d2be-4818-81f9-da5638902b97)

![image](https://github.com/user-attachments/assets/e695d68b-edb1-4ca3-9aa9-49e7751dc382)

![image](https://github.com/user-attachments/assets/50cd71ad-a0d6-4744-b043-2d2a8983b928)

![image](https://github.com/user-attachments/assets/e6a75420-f116-43ae-8cb5-a44a7c3cf407)

🔍 KMeans clustering on cost, jobs, and timelines

![image](https://github.com/user-attachments/assets/33a37094-8a85-4a09-bd4b-bfa86f40bdc3)


🗺️ Geospatial mapping of projects (with Plotly)

https://github.com/leanhlinh/AusEnergyPulse/blob/main/outputs/critical_minerals_map.html

⏳ Time-based pipeline analysis

![image](https://github.com/user-attachments/assets/6a769770-538c-469d-a430-0c412f237df8)


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
