# 🌦️ OptiFlow: Intelligent Cloud Workflow Optimization Using Weather and Genetic Algorithms

### Overview
OptiFlow is a research-driven framework for optimizing task scheduling across heterogeneous cloud environments.  
It integrates **Genetic Algorithms (GA)** with **real-time weather data** to make intelligent task placement decisions that minimize cost, execution time, and weather-based performance risks.

---

### 🧠 Features
- Genetic Algorithm for task-resource optimization  
- Weather-aware scheduling (OpenWeatherMap API)  
- ETL pipeline for loading tasks, resources, and weather data  
- Visualization with Matplotlib and Seaborn  
- (Planned) Apache Airflow DAG integration  

---

### 📁 Project Structure
- `data/` – CSV datasets (tasks, resources, weather)  
- `src/` – Core source code  
- `notebooks/` – Jupyter notebooks for experiments  
- `docs/` – Reports, architecture diagrams, and literature review  
- `airflow/` – Airflow DAG for workflow automation  

---

### ⚙️ Installation
```bash
git clone https://github.com/<your-username>/OptiFlow.git
cd OptiFlow
pip install -r requirements.txt
```

---

### 🚀 Usage
Run the main notebook:
```bash
jupyter notebook notebooks/OptiFlow_Main.ipynb
```
Or execute directly:
```bash
python src/genetic_optimizer.py
```

---

### 📊 Visualization
OptiFlow produces:
- Fitness evolution curve (convergence of GA)
- Task distribution across regions
- Weather conditions per cloud provider

---

### 🔍 Example Output
```
🏁 Best assignment found:
Task 1 → AWS us-east-1
Task 2 → GCP us-central1
Task 3 → Azure westeurope
⭐ Best fitness score: 23.5
```

---

### 📚 References
1. OpenWeatherMap API — https://openweathermap.org/api  
2. AGORA: Adaptive Global Resource Orchestration Framework (2023)  
3. Flow-Bench: Workflow Anomaly Detection Dataset (arXiv, 2023)  
4. SpotLake: Spot Instance Data Analysis (ACM, 2024)  
5. Kumar & Suresh (2024). Reliability-Aware Multi-Cloud Scheduling  
6. Chen et al. (2024). HEFT-based Adaptive Workflow Optimization

---

### 👩‍💻 Contributors
- **[Your Name]** — Research, Implementation, and Report  
- Advisor / Supervisor (if applicable)

---

### 📜 License
This project is licensed under the MIT License — see `LICENSE` for details.
