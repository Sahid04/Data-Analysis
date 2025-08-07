# 🧠 Handedness, Age, and Mortality: A Data Science Exploration

This project investigates the relationship between handedness (left- or right-handed), age, and mortality using real-world datasets and Python data science tools. Through data visualization and probabilistic modeling, we explore how the prevalence of left-handedness varies by age and birth cohort, and how this relates to observed differences in age at death.

---

## 📊 Project Features

- **Data Loading & Visualization:**  
  - Loads and visualizes left-handedness rates by age and gender.
  - Plots the mean percentage of left-handed people by birth year.
  - Loads and visualizes US death distribution data by age.

- **Probabilistic Modeling:**  
  - Implements functions to compute conditional probabilities:
    - Probability of being left-handed given age at death.
    - Probability of dying at a certain age given handedness.
  - Calculates and compares average ages at death for left- and right-handed groups for different study years.

- **Reproducible Analysis:**  
  - All code is provided in a Jupyter Notebook for easy exploration and modification.

---

## 📁 File Structure


---

## 🚀 Getting Started

### 1. Requirements

- Python 3.7+
- Jupyter Notebook (or VS Code with Jupyter extension)
- numpy
- pandas
- matplotlib

Install dependencies with:


### 2. Running the Notebook

1. Open `notebook.ipynb` in Jupyter Notebook or VS Code.
2. Run each cell in order to reproduce the analysis and plots.

---

## 📈 Data Sources

- **Left-handedness by Age:**  
  [lh_data.csv](https://gist.githubusercontent.com/mbonsma/8da0990b71ba9a09f7de395574e54df1/raw/aec88b30af87fad8d45da7e774223f91dad09e88/lh_data.csv)

- **US Death Distribution (1999):**  
  [cdc_vs00199_table310.tsv](https://gist.githubusercontent.com/mbonsma/2f4076aab6820ca1807f4e29f75f18ec/raw/62f3ec07514c7e31f5979beeca86f19991540796/cdc_vs00199_table310.tsv)

---

## 🧩 Analysis Overview

- **Visualize** the percentage of left-handed people by age and gender.
- **Calculate** mean left-handedness by birth year.
- **Model** the probability of being left- or right-handed at different ages of death.
- **Compare** average ages at death for left- and right-handed groups in different years (e.g., 1990, 2018).

---

## 📚 Example Plots

- Percentage of left-handed people by age and gender.
- Mean left-handedness by birth year.
- US death distribution by age.
- Probability of dying at a certain age given handedness.

---

## 📝 License

This project is licensed under the Apache License 2.0.  
See [LICENSE](LICENSE) for details.

---

## 🤝 Acknowledgements

- Data and inspiration from [mbonsma](https://gist.github.com/mbonsma).
- Analysis and notebook structure inspired by real-world epidemiological studies.

---

## 💡 Contributing

Pull requests and suggestions are welcome!  
Feel free to fork the repo and submit improvements.

---

## 📬 Contact

For questions or collaboration, open an issue or contact the maintainer.

---

*Happy analyzing!*