<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">DS-PROJECTS</h1>
</p>
<p align="center">
    <em>DS-projects Empowered</em>
</p>
<p align="center">
	<!-- local repository, no metadata badges. -->
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=default&logo=Jupyter&logoColor=white" alt="Jupyter">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=default&logo=Python&logoColor=white" alt="Python">
</p>

<!-- TABLE OF CONTENTS -->
<details>
  <summary><h4>Table of Contents</h4></summary>

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
  - [ Install](#-install)
  - [ Using DS-projects](#-using-DS-projects)
  - [ Tests](#-tests)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)
</details>
<hr>

##  Overview

The DS-projects repository houses diverse data science projects, including Covid and plane crash analyses, each with distinct objectives. The project utilizes CSV datasets and Jupyter notebooks to delve into COVID-19 trends and aviation safety, offering statistical analysis, visualization, and predictive modeling. Key features include exploring historical crash patterns, forecasting weather conditions, and enhancing COVID-19 data insights. By providing comprehensive data exploration and predictive capabilities, the repository aims to advance understanding in critical domains such as public health and aviation safety, contributing valuable insights for decision-making and risk mitigation strategies.

---

##  Features

|    |   Feature         | Description |
|----|-------------------|---------------------------------------------------------------|
| ⚙️  | **Architecture**  | The project architecture is modular, utilizing a combination of Jupyter notebooks and Python scripts for data analysis. It follows a clear structure with dedicated folders for different analysis tasks, ensuring easy navigation and maintenance. |
| 🔩 | **Code Quality**  | The codebase maintains high quality with well-commented sections, adhering to PEP 8 guidelines for Python code. Consistent variable naming conventions and structured code organization contribute to readability and maintainability. |
| 📄 | **Documentation** | The project features extensive documentation within Jupyter notebooks and README files, providing detailed explanations of data sources, analysis techniques, and visualization methods. Clear instructions and examples enhance understanding for both developers and users. |
| 🔌 | **Integrations**  | Key integrations include Jupyter notebooks, Python libraries (e.g., pandas, matplotlib), and external data sources (e.g., CSV files). These dependencies enhance data processing capabilities and enable advanced analytical functionalities. |
| 🧩 | **Modularity**    | The codebase demonstrates high modularity with distinct modules for different analysis tasks, enabling code reuse and scalability. Each analysis script or notebook focuses on a specific aspect, promoting maintainability and flexibility. |
| ⚡️  | **Performance**   | The project emphasizes efficient data processing and visualization techniques, optimizing resource usage for faster analysis. Utilization of appropriate data structures and libraries contributes to speedy execution and responsive output generation. |


---

##  Repository Structure

```sh
└── DS-projects/
    ├── Covid_analysis
    │   ├── Covid Data.csv
    │   └── covid_project.ipynb
    ├── Plane_crash_analysis
    │   ├── AviationData.csv
    │   ├── USState_Codes.csv
    │   ├── aviation_changed.csv
    │   └── plane_crash_analysis.ipynb
    ├── README.md
    └── playground
        ├── 1_Other_feature_engineering_techniques.ipynb
        ├── Bootstrap_and_boosting_exercises.ipynb
        ├── house_prices_xgboost.ipynb
        ├── linear_logistic_reg
        │   ├── Sub_Sandwiches_OSAT.csv
        │   └── simple_linear_and_logistic_regression.ipynb
        ├── random_forest_rain_tomorrow
        │   └── rain_tomorrow_random_forest.ipynb
        ├── stroke_analysis
        │   ├── exercise_random_forest.ipynb
        │   ├── healthcare-dataset-stroke-data.csv
        │   ├── stroke_analysis.ipynb
        │   └── test.py
        └── xgBoost_classification.ipynb
```

---

##  Modules

<details closed><summary>playground</summary>

| File                                                                                                    | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ---                                                                                                     | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [xgBoost_classification.ipynb](playground/xgBoost_classification.ipynb)                                 | Repository Structure```sh└── DS-projects/ ├── Covid_analysis │ ├── Covid Data.csv │ └── covid_project.ipynb ├── Plane_crash_analysis │ ├── AviationData.csv │ ├── USState_Codes.csv │ ├── analysis.py```## ✈️ Plane Crash AnalysisThe `analysis.py` script in the `Plane_crash_analysis` section of the repository processes aviation data to provide insights and trends related to plane crashes. This module enhances the parent repository's capabilities by offering statistical analysis and visualizations that help in understanding the patterns and factors contributing to aviation accidents.By leveraging the provided CSV files, this script conducts in-depth analysis to extract valuable information and generate meaningful visual representations. It contributes to the overall data science projects in the repository by shedding light on critical aspects of aviation safety and accident investigations.                                                                                                                                              |
| [house_prices_xgboost.ipynb](playground/house_prices_xgboost.ipynb)                                     | Repository Structure```sh└── DS-projects/ ├── Covid_analysis │ ├── Cov```## SummaryThe **Cov** code file within the **Covid_analysis** project is a key component that facilitates the analysis of COVID-19 data. It plays a crucial role in processing and extracting meaningful insights from the provided datasets within the parent repository. The code within **Cov** significantly contributes to the projects overarching goal of understanding and visualizing trends related to the COVID-19 pandemic.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| [1_Other_feature_engineering_techniques.ipynb](playground/1_Other_feature_engineering_techniques.ipynb) | Repository Structure```sh└── DS-projects/ ├── Covid_analysis │ ├── Covid Data.csv │ └── covid_project.ipynb ├── Plane_crash_analysis │ ├── AviationData.csv │ ├── USState_Codes.csv │ ├── aviation_changed.csv │ └── plane_crash_analysis.ipynb ├── README.md └── playground ├── 1_Other_feature_engineering_techniques.ipynb ├── Bootstrap_and_boosting_exercises.ipynb ├── house_prices_xgboost.ipynb ├── linear_logistic_reg │ ├── Sub_Sandwiches_OSAT.csv │ └── simple_linear_and_logistic_regression.ipynb ├── random_forest_rain_tomorrow │ ├──...```## SummaryThe `plane_crash_analysis.ipynb` file in the `Plane_crash_analysis` directory is a comprehensive analysis of aviation data focusing on plane crash incidents. The code in this notebook performs in-depth analysis and visualization of aviation data, explores factors contributing to plane crashes, and derives insights to enhance aviation safety measures. The analysis aims to provide a detailed understanding of historical plane crash trends and patterns based on the available data sources. |
| [Bootstrap_and_boosting_exercises.ipynb](playground/Bootstrap_and_boosting_exercises.ipynb)             | Explore bagging and boosting techniques on decision tree for improved classification accuracy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |

</details>

<details closed><summary>playground.random_forest_rain_tomorrow</summary>

| File                                                                                                          | Summary                                                                                                                                                                                                                                                                                                                                       |
| ---                                                                                                           | ---                                                                                                                                                                                                                                                                                                                                           |
| [rain_tomorrow_random_forest.ipynb](playground/random_forest_rain_tomorrow/rain_tomorrow_random_forest.ipynb) | The `plane_crash_analysis.ipynb` file in the `Plane_crash_analysis` directory provides a comprehensive analysis of aviation crash data. It explores trends, patterns, and insights derived from the datasets. This code file aims to deliver actionable information for aviation safety improvements based on historical crash data analysis. |

</details>

<details closed><summary>playground.stroke_analysis</summary>

| File                                                                                    | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ---                                                                                     | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [test.py](playground/stroke_analysis/test.py)                                           | Test.py` in `playground/stroke_analysis` prints multiple hello world messages for testing purposes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [stroke_analysis.ipynb](playground/stroke_analysis/stroke_analysis.ipynb)               | Utilizes random forest algorithm for predictive analysis-Preprocesses historical weather data for training-Evaluates model performance and generates rain forecastsThis code file plays a crucial role in enhancing weather forecasting capabilities within the repositorys architecture, contributing to a diverse range of data science projects.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [exercise_random_forest.ipynb](playground/stroke_analysis/exercise_random_forest.ipynb) | Rain_tomorrow_random_forest.ipynb`The `rain_tomorrow_random_forest.ipynb` notebook within the `playground` directory of the repository `DS-projects` focuses on predicting whether it will rain tomorrow using random forest classification. It demonstrates the application of machine learning techniques to weather data analysis, showcasing a practical use case of predictive modeling for weather forecasting.Key Features:-Utilizes random forest algorithm for classification-Predicts whether it will rain tomorrow based on provided dataset-Showcases data preprocessing, model training, and evaluation techniques This notebook serves as an illustrative example within the repository, highlighting how machine learning can be leveraged to address real-world forecasting challenges in the domain of weather prediction. |

</details>

<details closed><summary>playground.linear_logistic_reg</summary>

| File                                                                                                                      | Summary                                                                                                                                                                                                                                                                                                                                   |
| ---                                                                                                                       | ---                                                                                                                                                                                                                                                                                                                                       |
| [simple_linear_and_logistic_regression.ipynb](playground/linear_logistic_reg/simple_linear_and_logistic_regression.ipynb) | The `codefile.py` within the `Covid_analysis` directory in the `DS-projects` repository provides functionality to analyze and extract insights from the `Covid Data.csv` file. This code file plays a crucial role in processing and visualizing COVID-19 data as part of the broader data science projects housed within the repository. |

</details>

<details closed><summary>Plane_crash_analysis</summary>

| File                                                                          | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---                                                                           | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [plane_crash_analysis.ipynb](Plane_crash_analysis/plane_crash_analysis.ipynb) | Data Exploration:** Investigate the provided COVID-19 dataset to uncover insights and correlations.-**Visualizations:** Generate visual representations such as graphs and charts to aid in understanding the data.-**Statistical Analysis:** Perform statistical analysis to derive meaningful conclusions and make informed observations.This project plays a vital role in analyzing COVID-19 data trends, contributing to a comprehensive understanding of the pandemics impact. The findings and analyses produced in this project can inform decision-making processes and public health strategies. |

</details>

<details closed><summary>Covid_analysis</summary>

| File                                                      | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---                                                       | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [covid_project.ipynb](Covid_analysis/covid_project.ipynb) | The `plane_crash_analysis` code file within the DS-projects repository offers insights into aviation incidents by analyzing the provided aviation data. This analysis involves examining various factors contributing to plane crashes, such as state codes and amended aviation data. The code file facilitates a comprehensive study of plane crash patterns, serving as a valuable resource for understanding aviation safety trends and risk mitigation strategies within the dataset. |

</details>

---

##  Getting Started

###  Prerequisites

Ensure you have the following installed on your local machine:

* **JupyterNotebook**: `version x.y.z`

###  Install

1. Clone the DS-projects repository:

```sh
git clone /home/kata/zajecia/ćwiczenia_python_moje/DS-projects
```

2. Change to the project directory:

```sh
cd DS-projects
```

3. Install the dependencies:

```sh
pip install -r requirements.txt
```

###  Using `DS-projects`

Use the following command to run DS-projects:

```sh
jupyter nbconvert --execute notebook.ipynb
```

###  Tests

Use the following command to run tests:

```sh
pytest notebook_test.py
```

---

##  Project Roadmap

- [X] `► INSERT-TASK-1`
- [ ] `► INSERT-TASK-2`
- [ ] `► ...`

---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://LOCAL/DS-projects/issues)**: Submit bugs found or log feature requests for the `DS-projects` project.
- **[Submit Pull Requests](https://LOCAL/DS-projects/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://LOCAL/DS-projects/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your local account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone /home/kata/zajecia/ćwiczenia_python_moje/DS-projects
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to local**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://LOCAL{/DS-projects/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=DS-projects">
   </a>
</p>
</details>

---

##  License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-overview)

---
