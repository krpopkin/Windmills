# Windmills Capstone Project

A comprehensive data science and machine learning capstone analyzing the impact of wind farms on housing markets.

## Table of Contents

- [Project Overview](#project-overview)  
- [Directory Structure](#directory-structure)  
- [Data](#data)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Launching Notebooks](#launching-notebooks)  
- [Notebook Workflow](#notebook-workflow)  
- [Contributing](#contributing)  
- [License](#license)  
- [Author](#author)  

## Project Overview

This repository contains a step-by-step capstone project that explores the relationship between wind farm locations and housing market trends. It includes idea generation, a formal proposal, data cleaning, exploratory and inferential analysis, storytelling, machine learning modeling, and final deliverables.

## Directory Structure

```
.
├── .gitattributes
├── README.md                     # Project overview and instructions (this file)
├── 01 Ideas/                     # Initial idea documentation (Word & PDF)
├── 02 Proposal/                  # Project proposal (Word & PDF)
├── 03 Data Wrangling/            # Jupyter notebooks and docs for data cleaning and merging
├── 04 Storytelling/              # Narrative analysis and storytelling notebooks
├── 05 Inferential Statistics/    # Inferential statistics analysis notebooks and docs
├── 06 Milestone Report/          # Interim milestone reports and slides
├── 07 Machine Learning/          # Model training, evaluation, and comparison notebooks
├── 08 Final Report/              # Final report deck, slides, and document
└── 09 CapstoneProject1Data/      # Raw and processed datasets, organized by subfolder
```

## Data

All datasets are stored under `09 CapstoneProject1Data/`, organized into:

- `InferentialStatsData/`: ZIP code-level data for statistical tests  
- `MachineLearningData/`: Prepared feature sets for model training  
- `MergedData/`: Combined Zillow and wind farm data for analysis  
- `WindfarmData/`: Original wind farm source files and supporting codebooks  
- `ZillowData/`: Housing market data files  

> **Note:** Some data files are large; ensure you have sufficient disk space.

## Getting Started

### Prerequisites

- Python 3.7+  
- Jupyter Notebook or JupyterLab  
- Common data science libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels  

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/krpopkin/Windmills.git
   cd Windmills
   ```

2. **Create and activate a virtual environment (optional but recommended)**  
   ```bash
   python3 -m venv venv
   source venv/bin/activate    # macOS/Linux
   venv\Scripts\activate     # Windows
   ```

3. **Install required packages**  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyterlab
   ```

### Launching Notebooks

Start Jupyter Lab or Notebook in the project root:

```bash
jupyter lab
```

Open and run the notebooks in numerical order within each folder.

## Notebook Workflow

1. **01 Ideas**: Brainstorm and capture project ideas.  
2. **02 Proposal**: Solidify objectives, methodology, and expected deliverables.  
3. **03 Data Wrangling**: Clean, merge, and prepare data from raw sources.  
4. **04 Storytelling**: Exploratory data analysis and narrative insights.  
5. **05 Inferential Statistics**: Hypothesis testing and statistical validation.  
6. **06 Milestone Report**: Progress report with interim results.  
7. **07 Machine Learning**: Train and compare multiple predictive models.  
8. **08 Final Report**: Compile final findings and visualizations into a presentation.

## Contributing

This capstone project is provided “as-is” for educational purposes. Contributions or suggestions are welcome via Issues or Pull Requests.

## License

This project is currently unlicensed. Feel free to use or adapt it for non-commercial or educational purposes.

## Author

**Ken Popkin**  
GitHub: [krpopkin](https://github.com/krpopkin)  
Email: krpopkin@gmail.com

