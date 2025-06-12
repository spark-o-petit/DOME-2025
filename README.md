# DOME: Bariatric Surgery Complication Analysis at Dongsan Hospital

A Python-based data analysis and visualization project investigating pre- and post-operative complication differences in bariatric surgery patients at Dongsan Hospital.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Project Workflow](#project-workflow)
- [Development Environment](#development-environment)
- [How to Run](#how-to-run)
- [Key Libraries](#key-libraries)
- [Data Policy](#data-policy)
- [Version Control Strategy](#version-control-strategy)
- [Contact](#contact)

---

## Project Overview

This project aims to analyze and visualize the differences in complication rates before and after bariatric surgery among patients at Dongsan Hospital.  
The main objectives are:

- Quantitatively assess changes in complication rates pre- and post-surgery
- Visualize trends and patterns using Python-based tools
- Provide reproducible and modular research code

---

## Project Workflow

1. **Problem Definition**  
   Define the research question and objectives.

2. **Data Collection**  
   Gather necessary patient data from hospital records, ensuring compliance with privacy regulations.

3. **Data Preprocessing**  
   Clean, standardize, and anonymize data. Handle missing values and outliers.

4. **Exploratory Data Analysis (EDA)**  
   Explore data distributions, relationships, and patterns using statistical summaries and visualizations.

5. **Analysis/Modeling**  
   Apply statistical tests or models to compare pre- and post-operative complication rates.

6. **Visualization & Interpretation**  
   Create clear, insightful visualizations and interpret the results in a clinical context.

7. **Reporting**  
   Summarize findings in reports, presentations, or manuscripts for stakeholders and publication.

8. **Action & Feedback**  
   Apply insights to clinical practice or further research, and iterate based on feedback.

---

## Development Environment

- **Python 3.9+** (recommended)
- **Anaconda/Miniconda** or Python venv for virtual environment management
- **VS Code** (with Python and Jupyter extensions) or JupyterLab

### Setting Up the Environment

**Using conda:**
```bash
conda env create -f environment.yml
conda activate dome
```

**Using venv:**
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

---

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/spark-o-petit/DOME-2025.git
   cd DOME-2025
   ```

2. **Activate your virtual environment** (see above)

3. **Run Jupyter notebooks for EDA and visualization**
   ```bash
   jupyter lab
   # or
   code .  # Open in VS Code and use interactive cells (# %%)
   ```

4. **Execute scripts for preprocessing or analysis**
   ```bash
   python scripts/run_preprocessing.py
   python scripts/run_analysis.py
   ```

---

## Key Libraries

- pandas, numpy: Data manipulation
- matplotlib, seaborn, plotly: Visualization
- scipy: Statistical analysis
- jupyter: Notebook interface
- (Optional) dask, pyspark: For large-scale data processing

---

## Data Policy

- **data/raw/** contains the original data and must not be tracked by git (see .gitignore).
- All sensitive patient information must be handled according to institutional and legal guidelines.
- Do not upload raw patient data to any repository.
- Only share code and de-identified, sample data for reproducibility.

---

## Version Control Strategy

- **Branching:**  
  - `main`: Stable, production-ready code  
  - `develop`: Ongoing development and integration  
  - `feature/xxx`: Feature or analysis-specific branches (e.g., `feature/eda-complication`)
- **.gitignore:**  
  - All data directories (e.g., `data/`) are excluded from version control to protect sensitive information[1].
- **Commit Messages:**  
  - Use clear, descriptive messages (e.g., `Add data preprocessing script for complication analysis`)
- **Pull Requests:**  
  - All changes are merged via Pull Request for review and traceability.

---

## Contact

For questions or collaboration inquiries, please contact [alexchoi970@gmail.com].

---

**본 프로젝트는 환자 개인정보 보호와 데이터 보안을 최우선으로 하며, 재현성과 협업을 위한 표준적인 데이터 분석 워크플로우를 따릅니다.**
