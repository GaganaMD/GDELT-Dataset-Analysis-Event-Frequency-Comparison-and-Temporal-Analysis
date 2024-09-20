# GDELT Dataset Analysis: Event Frequency Comparison and Temporal Analysis 

This repository provides a comprehensive analysis of the **GDELT (Global Database of Events, Language, and Tone)** dataset, focusing on event frequency comparisons across countries, temporal patterns, and hypothesis testing. This project also implements predictive models based on various event characteristics, offering insights into global media coverage and political stability from 1979 to 2021.

---

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Dataset Overview](#dataset-overview)
3. [Research Objectives](#research-objectives)
4. [Methodology](#methodology)
5. [Key Analyses](#key-analyses)
6. [Hypothesis Testing](#hypothesis-testing)
7. [Predictive Models](#predictive-models)
8. [Installation and Usage](#installation-and-usage)
9. [Directory Structure](#directory-structure)
10. [Contributing](#contributing)
11. [License](#license)

---

## **Project Overview**
This project explores global events using the **GDELT dataset**, covering the years 1979 to 2021. The primary focus areas include:
- **Event frequency analysis** across various regions and time periods.
- **Geospatial distribution** of events and their impact on political stability.
- **Media coverage and tone**, including correlations between media attention and event significance.
- **Predictive modeling** of events using key indicators such as the Goldstein scale and media mentions.

The project also aims to test several hypotheses about political stability, event types, and their coverage in media.

---

## **Dataset Overview**
The GDELT dataset tracks global events in terms of:
- **Date**: Year of occurrence.
- **Country**: The country where the event took place, represented by a country code and name.
- **Event Root Code & Description**: The type of event using the CAMEO code system.
- **Goldstein Scale**: A score representing the event's impact on political stability, ranging from -10 to +10.
- **Media Mentions**: Number of news articles mentioning the event.
- **Tone**: Average tone of the media coverage about the event.

The dataset is rich in detail, covering a wide range of global events and how they are perceived and reported by the media.

---

## **Research Objectives**
The main goals of this project are:
1. To **analyze event frequencies** and compare them across countries and time periods.
2. To **explore global trends** and examine their relationship with political stability, especially using the Goldstein scale.
3. To **study media coverage** patterns, especially how media attention (measured through mentions and tone) correlates with event significance.
4. To build **predictive models** to forecast future event occurrences based on past data and trends.

---

## **Methodology**
This project employs the following steps:
1. **Data Exploration**: Initial exploration of the dataset to identify patterns and any potential issues like missing data.
2. **Data Preprocessing**: Cleaning the data by handling missing values, normalizing features, and ensuring the data is ready for analysis.
3. **Temporal and Geospatial Analysis**: Examining event trends across different regions and over time.
4. **Hypothesis Testing**: Conducting statistical tests to verify the formulated hypotheses.
5. **Predictive Modeling**: Applying machine learning models such as regression to predict future events and classify event types.

---

## **Key Analyses**
### **1. Temporal and Geospatial Trends**
- Analyze how **event frequencies** change over time and across different regions, exploring political stability through the Goldstein scale.

### **2. Media Coverage and Event Impact**
- Investigate how the **tone** of news coverage correlates with event significance and how frequently events are mentioned in the media. This analysis provides insights into global media biases and trends.

### **3. Event-Type Comparisons**
- Compare different event types, such as violent conflicts versus coercive actions, and explore their media coverage and political impact.

---

## **Hypothesis Testing**
### **Hypothesis 1: Event Frequency in Politically Stable vs. Unstable Countries**
- **H0**: No difference in event frequency between politically stable and unstable countries.
- **H1**: Politically unstable countries have a higher average event frequency.

### **Hypothesis 2: Media Mentions of Different Event Types**
- **H0**: No difference in media mentions between different event types (e.g., "FIGHT" vs. "COERCE").
- **H1**: "FIGHT" events receive significantly more media mentions.

### **Hypothesis 3: Temporal Changes in Event Frequency**
- **H0**: No significant change in event frequency over time.
- **H1**: Significant temporal changes exist in event frequency.

---

## **Predictive Models**
### **1. Linear Regression**
- A linear regression model is built to predict **event frequency** using the Goldstein scale, number of media mentions, and tone as independent variables.

### **2. Event Classification Using Logistic Regression**
- Logistic regression is applied to classify events into categories like "FIGHT" vs. "COERCE" based on the Goldstein scale, number of mentions, and tone of coverage.

---

## **Installation and Usage**
### **Requirements**
- Python 3.7 or higher
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

### **Installation**
To get started, clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/gdelt-event-analysis.git
cd gdelt-event-analysis
pip install -r requirements.txt

```

## **Usage**
### **Run the Jupyter Notebook**
Open the notebook provided in the repository and execute the cells to reproduce the analysis.

### **Python Scripts**
Alternatively, run the Python scripts directly to perform specific analyses such as hypothesis testing or predictive modeling.

---

## **Directory Structure**

```bash
gdelt-event-analysis/
│
├── data/                        # Contains raw and processed GDELT data
├── notebooks/                   # Jupyter notebooks for exploratory analysis and modeling
├── scripts/                     # Python scripts for hypothesis testing, modeling, and visualization
├── results/                     # Output files, figures, and model predictions
├── requirements.txt             # List of Python dependencies
└── README.md                    # Project documentation
```

## **Contributing**
Contributions to this project are welcome. If you would like to contribute:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed explanation of your changes.

Please ensure that your contributions are consistent with the overall code style and structure of the project.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


