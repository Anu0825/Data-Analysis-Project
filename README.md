# 🧠 Mental Health in Tech — Survey Data Analysis

This project analyzes responses from the **2014 Mental Health in Tech Survey** conducted by OSMI. The focus is on understanding how workplace resources influence employees’ willingness to discuss mental health challenges.


## 📄 Project Summary

The notebook `data_analysis.ipynb` performs an in-depth analysis of:

- Mental health trends among tech employees
- Impact of company size, benefits, and remote work on mental health disclosure
- Willingness to speak to coworkers/supervisors
- Perceived consequences of mental health discussions in the workplace

---

## 📊 Dataset

- 📥 Source: [Kaggle - Mental Health in Tech Survey](https://www.kaggle.com/osmi/mental-health-in-tech-survey)
- 📆 Year: 2014

### Columns used:

| Feature | Description |
|--------|-------------|
| Gender | Gender identity of the respondent |
| self_employed | Whether the person is self-employed |
| family_history | Family history of mental illness |
| treatment | Whether they have sought mental health treatment |
| work_interfere | Perceived interference of mental health with work |
| remote_work | Work-from-home status |
| benefits, care_options, seek_help, anonymity | Company-provided mental health support |
| mental_health_consequence | Expected consequences of disclosure |
| coworkers, supervisors | Willingness to talk to colleagues or superiors |

> Columns like `timestamp`, `state`, `country`, and `comments` were excluded due to irrelevance or missing data.

## Key Analysis Steps

- **Data Cleaning:** Removed irrelevant columns and standardized gender responses
- **Grouping & Aggregation:** Analyzed responses across multiple dimensions 
- **Visual Insights:** Plotted distributions of mental health treatment, remote work effects, and company benefits

## Requirements

Install dependencies using:

```bash
pip install pandas matplotlib seaborn jupyter
```

## Credits
-  Survey by: [OSMI](https://osmihelp.org/)
-  Dataset from: [Kaggle](https://www.kaggle.com/osmi/mental-health-in-tech-survey)


