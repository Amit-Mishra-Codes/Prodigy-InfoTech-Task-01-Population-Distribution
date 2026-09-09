# Prodigy-InfoTech-Task-01-Population-Distribution
python data-science data-visualization pandas matplotlib world-bank prodigy-infotech internship population-analysis


Prodigy InfoTech – Data Science Internship Task 1

Population Distribution Visualization

This project is completed as part of the Data Science Internship at Prodigy InfoTech.

The objective of this task is to create a bar chart or histogram to visualize the distribution of a categorical or continuous variable, such as age or gender in a population.

For this task, the World Bank Population, total dataset provided in the Prodigy InfoTech Task 1 reference repository is used.

---

🎯 Task Objective

Create a visualization that represents the distribution of population using an appropriate chart.

In this project, a bar chart is created to visualize the population of the Top 10 most populous countries in 2024.

---

📊 Dataset

Dataset: Population, total

Source: World Bank

The dataset contains population information for countries and regions across multiple years.

The original dataset is provided through the Prodigy InfoTech Data Science datasets repository.

Original Source: World Bank – Population, total

---

🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- CSV Dataset
- Jupyter Notebook / Python

---

📁 Project Structure

Prodigy-InfoTech-Task-01-Population-Distribution/
│
├── README.md
├── population_distribution.py
├── requirements.txt
│
├── data/
│   └── population_data.csv
│
└── output/
    └── top_10_population_2024.png

---

⚙️ Methodology

The following steps were performed:

1. Loaded the World Bank population dataset.
2. Selected the population data for the year 2024.
3. Removed invalid or missing population values.
4. Used country-level data for the analysis.
5. Sorted countries according to their population.
6. Selected the Top 10 most populous countries.
7. Created a bar chart using Matplotlib.
8. Added appropriate title, axis labels, and population values.
9. Saved the final visualization as a PNG image.

---

📈 Visualization

The final bar chart shows the Top 10 most populous countries in 2024.

The X-axis represents the countries and the Y-axis represents their total population.

"Top 10 Population 2024" (output/top_10_population_2024.png)

---

💻 How to Run

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/Prodigy-InfoTech-Task-01-Population-Distribution.git

2. Open the project directory

cd Prodigy-InfoTech-Task-01-Population-Distribution

3. Install required libraries

pip install -r requirements.txt

4. Run the Python program

python population_distribution.py

The generated chart will be saved inside the "output" folder.

---

📦 Requirements

The project requires the following Python libraries:

pandas
matplotlib

---

🎓 Internship

Program: Data Science Internship
Organization: Prodigy InfoTech
Task: Task 1 – Population Distribution Visualization

---

👨‍💻 Author

Amit Mishra

B.Sc. Data Science and Data Analytics

---

📜 License

This project is created for educational and internship purposes.

The population data is sourced from the World Bank.

Requirments 
pandas
matplotlib
__pycache__/
*.py[cod]
*.ipynb_checkpoints/
.venv/
venv/
env/
.idea/
.vscode/
.DS_Store
📁 Prodigy-InfoTech-Task-01-Population-Distribution
│
├── 📄 README.md
├── 📄 population_distribution.py
├── 📄 requirements.txt
├── 📄 .gitignore
│
├── 📁 data
│   └── population_data.csv
│
└── 📁 output
    └── top_10_population_2024.png