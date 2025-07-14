# Colorectal Cancer Screening Awareness & Lifestyle Factors: A Health Informatics Approach

## Overview

This project analyzes the relationships between patient awareness of colorectal cancer screening tests and key lifestyle factors—exercise, diet, and smoking status—using the HINTS 6 dataset. By applying health informatics principles, our goal is to uncover actionable insights that inform public health policy, awareness campaigns, and technology-driven interventions.

---

## Project Story

Despite advances in health informatics, disparities remain in colorectal cancer screening rates. This project started as an exploration of how behavioral and lifestyle factors—such as physical activity, diet, and tobacco use—correlate with patient awareness of screening tests. Leveraging data from the National Cancer Institute's HINTS 6 survey, we aimed to:

- Identify which lifestyle factors most strongly relate to screening awareness.
- Visualize key trends to inform data-driven public health strategies.
- Discuss implications for personalized health interventions and technology adoption.

---

## Dataset

- **Source:** HINTS 6 (Health Information National Trends Survey), National Cancer Institute (2022)
- **Sample:** 6,252 U.S. adults (18+)
- **Variables:** Behavioral, socioeconomic, and health-related domains

**Key Features Used:**
- `DocTellColorectalTests`: Whether a provider informed about screening (Yes/No)
- `WeeklyMinutesModerateExercise`: Physical activity (minutes/week)
- `SmokeStat`: Smoking status (Current/Former/Never)
- `UseECigNow`: Current e-cigarette use (Yes/No)
- `IncreaseCancer_NEFruitVeg`: Fruit/vegetable intake (Low/Moderate/High)
- `IncreaseCancer_TMProcMeat`: Processed meat consumption (Low/Moderate/High)
- `IncreaseCancer_TMFastFood`: Fast food consumption (Low/Moderate/High)

---

## Analytical Approach

1. **Preprocessing:**  
   - Data cleaning, handling missing values, and standardizing variables.

2. **Exploratory Analysis:**  
   - Summary statistics and trend identification for exercise, awareness, and smoking.

3. **Visualization:**  
   - Histograms, boxplots, and stacked bar charts for lifestyle and awareness variables.
   - Correlation heatmap to identify relationships between dietary/lifestyle factors and screening awareness.

4. **Discussion & Implications:**  
   - Analyzed which factors most impact screening awareness.
   - Explored how health informatics can target interventions, such as patient portals, wearable fitness trackers, and tailored education.

---

## Key Results

- **Awareness Gaps:**  
  Lower awareness of screening correlated with unhealthy dietary habits (high fast food/processed meat, low fruits/vegetables) and negative lifestyle factors (low exercise, current smoking).
- **Correlations:**  
  Notable positive correlation between healthy behaviors and screening awareness.
- **Implications:**  
  Results support integrating technology (e.g., patient portals, fitness apps) to personalize screening reminders and health education.

---

## Visualizations

- **Distribution of Weekly Exercise Minutes**
- **Awareness Bar Graphs**
- **Boxplots:** Exercise vs. Screening Awareness
- **Stacked Bar Charts:** Smoking Status vs. Awareness
- **Correlation Heatmap:** Relationships between all key factors

---

## Limitations & Future Work

- Dataset limited to self-reported survey responses; unmeasured confounders possible.
- Future work: Apply NLP to clinical notes for richer behavioral data; conduct longitudinal studies on intervention effectiveness.

---

## Acknowledgements

Thanks to the National Cancer Institute for providing the HINTS 6 dataset and to all team members for their equal contribution in data analysis and presentation.

---

## Contact

Rutvik Deshmukh  
Masters in Information Systems  
University of Maryland, Baltimore County  
rutvikdeshmuk5@gmail.com

---
