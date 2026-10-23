# 🐍 Python & Multi-Language Project Showcase

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

A comprehensive collection of practical tools, data science explorations, GUI/web apps, and algorithmic implementations built while mastering Python and software development fundamentals.

---

## 📌 Repository Overview

This repository is organized into distinct categories covering real-world simulations, interactive tools, numerical computing, and algorithmic exercises:

### 1. ⚙️ Real-World Applications & Simulation Tools
Practical console and data-driven utility programs solving everyday problems:
* **`home_power_grid_optimizer/`**: Simulates power load balancing, weather conditions, and energy rate adjustments.
* **`personal_finance_and_expense_simulation_tool/`**: Tracks expense breakdowns and calculates personal financial projections.
* **`smart_billing_&_tiered_discount_system/`**: Implements dynamic customer billing with tiered discount logic.
* **`inventory_management_system/`**: Stock tracking, catalog updates, and order workflows.
* **`household_utility_analyzer/`**: Utility consumption tracking and reporting.
* **`report_card/`**: Student marks calculation, grade ranking, and CSV exports.

### 2. 🌐 Interactive Web & GUI Applications
Web dashboards and lightweight user interfaces:
* **`streamlit_projects/`**: Data apps covering API queries, file handlers, and interactive parameter widgets.
* **`calculator_web_app/`**: Multiple versions (`v1`, `v2`) of interactive web-based calculators.
* **`flet_tut/`**: Multi-part UI tutorial series built with Flutter-backed Python Flet.

### 3. 📊 Data Science, Machine Learning & Scientific Computing
Jupyter Notebooks exploring numerical pipelines and exploratory analysis (`python_lib_notes/`):
* **Data Processing & Analysis**: In-depth tutorials with `pandas` (cleaning, correlations, JSON/CSV I/O).
* **Numerical Computing**: Array vectorization and universal functions with `numpy`.
* **Data Visualization**: Charts, plots, and figures with `matplotlib`.
* **Symbolic & Scientific Math**: Symbolic calculus via `sympy` and scientific routines in `scipy`.
* **Machine Learning**: End-to-end data pipelines and basic machine learning workflows (`ML_and_scipy`).

### 4. 🧮 Everyday Utilities, Games & Mini Tools
* **`currency_converter/`**: Real-time or configured exchange rate calculations.
* **`number_guessing_game/` & `capital_quiz/`**: Interactive CLI games with scorekeeping.
* **`to_do_list/`**: Task manager supporting additions, status toggles, and removals.
* **`arithmetic_solver/`, `bmi_calculator/`, `factorial/`, `palindrome/`, `si_and_ci/`**: Mathematical utility scripts.

### 5. ☕ Foundational Java Programs (`java_programs/`)
A collection of classic algorithmic challenges and number-theory problems implemented in Java:
* **Number Properties**: Armstrong, Automorphic, Buzz, Disarium, Duck, Kaprekar, Neon, Niven, Perfect, Pronic, Spy, and Twin Prime checks.
* **Series & Math**: Fibonacci sequences, HCF/LCM, factorial loops, and digit extraction.

---

## 📂 Directory Layout

```text
├── calculator_web_app/               # Browser-based calculator implementations
├── home_power_grid_optimizer/        # Grid optimization scripts & datasets
├── inventory_management_system/      # Store inventory tracking program
├── personal_finance_and_expense_.../ # Expense tracker and financial summaries
├── python_lib_notes/                 # Jupyter notebooks (Pandas, NumPy, ML, etc.)
├── smart_billing_&_tiered_discount/  # Tiered retail billing logic
├── streamlit_projects/               # Streamlit web applications
├── java_programs/                    # Core Java algorithmic implementations
├── notes/                            # Virtual environment & Git cheat sheets
├── requirements.txt                  # Python dependencies
└── README.md                         # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/hiteshthedev/python-projects.git
cd python-projects
```

### 2. Create and Activate a Virtual Environment
```bash
# Windows
python -m venv .venv
.venv\Scripts\activate

# macOS / Linux
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Any Application

* **Run a standard CLI script:**
  ```bash
  python to_do_list/to_do_list.py
  ```

* **Launch a Streamlit web app:**
  ```bash
  streamlit run streamlit_projects/api_call.py
  ```

* **Open Jupyter Notebooks:**
  ```bash
  jupyter notebook python_lib_notes/
  ```

* **Compile and run a Java program:**
  ```bash
  cd java_programs
  javac armstrong.java
  java armstrong
  ```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE) (or default repository terms).