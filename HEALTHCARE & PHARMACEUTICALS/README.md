# Hospital Patient Records Dataset
![Healthcare & Pharmaceuticals logo](https://github.com/danielorigin/Data-Analytics-Datasets/blob/cec8f2252a664a9a093f5f418442aedd64f6cc89/HEALTHCARE%20%26%20PHARMACEUTICALS/Healthcare%20%26pharmaceuticals.png)
**Admissions, Diagnoses, Treatments & Billing — 2022–2025**

## About the Dataset

This synthetic healthcare dataset was created to simulate **real-world hospital patient records** and provide a practical dataset for learning, analysis, visualization, and portfolio development.

It contains patient admission and treatment records covering **patient demographics, diagnoses, treatments, medications, vital signs, laboratory results, hospital departments, insurance, billing, payments, length of stay, and patient satisfaction**.

The dataset is designed to support practical analytics across **patient flow, treatment outcomes, hospital resource utilization, healthcare costs, quality metrics, readmissions, and patient experience**.

The dataset is suitable for:

**Excel · SQL · Python/Pandas · Power BI · Tableau · R/RStudio**

---

## Context

Access to real-world healthcare data can be difficult because of **patient privacy, medical confidentiality, data protection regulations, and healthcare information security requirements**.

This dataset was created as a safe synthetic alternative for students, analysts, data professionals, healthcare analytics practitioners, and portfolio developers who want to practice working with realistic healthcare data.

The dataset represents healthcare activity across **German hospitals in major cities** over a four-year period.

---

## Dataset Overview

| Attribute              | Details                            |
| ---------------------- | ---------------------------------- |
| **Dataset Type**       | Synthetic Hospital Patient Dataset |
| **Industry**           | Healthcare & Pharmaceuticals       |
| **Rows**               | ~48,624                            |
| **Columns**            | 43                                 |
| **Period**             | 2022–2025                          |
| **Primary Geography**  | Germany                            |
| **Data Level**         | Patient & Admission-level          |
| **Healthcare Setting** | Hospitals                          |
| **Time Coverage**      | 4 years                            |

---

## Key Data

The dataset contains information relating to:

* Patient IDs
* Medical Record Numbers (MRN)
* Patient demographics
* Age
* Gender
* Blood type
* Admission dates
* Discharge dates
* Admission types
* Discharge status
* Hospital departments
* Diagnoses
* ICD codes
* Secondary diagnoses
* Treatments
* Medications
* Vital signs
* Laboratory results
* Length of stay
* Insurance information
* Hospital charges
* Payments
* Patient satisfaction scores
* Readmission-related information

### Hospital Departments

The dataset may include departments such as:

* Cardiology
* Oncology
* Emergency Medicine
* Neurology
* Orthopedics
* General Medicine
* Surgery
* Pediatrics
* Other hospital departments

This structure allows users to compare **patient volume, treatment activity, costs, outcomes, and resource utilization across departments**.

---

## What You Can Analyze

The dataset can be used to explore questions such as:

* How do hospital admissions change over time?
* Which departments receive the highest number of patients?
* What are the most common diagnoses?
* How do admission patterns vary by season?
* Which age groups account for the highest number of admissions?
* How does length of stay vary across departments and diagnoses?
* Which treatments are associated with longer hospital stays?
* How do hospital charges vary by diagnosis or department?
* What proportion of patients are readmitted?
* Which factors are associated with readmissions?
* How do patient satisfaction scores vary across departments?
* How do admission types affect length of stay and costs?
* What are the most common laboratory abnormalities?
* How are healthcare costs distributed across patient groups?
* Which departments demonstrate the highest resource utilization?
* How do treatment patterns differ across patient demographics?

---

## Key Performance Indicators

Common KPIs that can be calculated from the dataset include:

| KPI                                  | Description                                                      |
| ------------------------------------ | ---------------------------------------------------------------- |
| **Total Admissions**                 | Number of recorded hospital admissions                           |
| **Unique Patients**                  | Number of distinct patients                                      |
| **Average Length of Stay**           | Average number of days patients remain hospitalized              |
| **Readmission Rate**                 | Percentage of patients or admissions associated with readmission |
| **Average Hospital Charge**          | Average charge per admission                                     |
| **Total Charges**                    | Total hospital charges recorded                                  |
| **Total Payments**                   | Total payments recorded                                          |
| **Average Patient Satisfaction**     | Average patient satisfaction score                               |
| **Department Admission Volume**      | Admissions by hospital department                                |
| **Diagnosis Frequency**              | Number of admissions by diagnosis                                |
| **Treatment Volume**                 | Number of patients receiving particular treatments               |
| **Patient Mortality/Discharge Rate** | Relevant discharge outcome measures where available              |

---

## Potential Use Cases

This dataset can be used for:

* Patient flow analysis
* Hospital admission analysis
* Healthcare analytics
* Diagnosis analysis
* Treatment analysis
* Department performance analysis
* Resource utilization analysis
* Length-of-stay analysis
* Readmission analysis
* Healthcare cost analysis
* Insurance analysis
* Patient satisfaction analysis
* Healthcare quality analysis
* Medical data visualization
* Business intelligence dashboards
* Statistical analysis
* Data visualization
* Machine learning experiments
* Portfolio projects

---

## Data Quality

The dataset intentionally contains some realistic data-quality challenges, making it useful for demonstrating a complete professional healthcare analytics workflow.

### Quality Issues

The dataset includes approximately:

* **2–5% missing values** in selected fields such as blood type, secondary diagnoses, and medications
* **1.3% duplicate patient records**
* Inconsistent gender formats
* Inconsistent admission type formats
* Vital-sign outliers
* Unusual ages
* Date inconsistencies
* Partially missing laboratory results
* Partially missing satisfaction scores

Examples of potential outliers include:

```text id="gk1zpd"
Blood Pressure > 200
Age > 120
```

These values should be investigated and validated rather than automatically assumed to be valid or invalid.

---

## Completeness

The dataset has varying levels of completeness across different fields.

* Patient IDs are complete
* Admission dates are complete
* Laboratory results contain some missing values
* Satisfaction scores contain some missing values
* Blood type information contains some missing values
* Secondary diagnosis information contains some missing values
* Medication information contains some missing values

These characteristics provide opportunities to practice **missing-value assessment and treatment**.

---

## Consistency

Some fields intentionally contain inconsistent formatting.

For example, discharge status may appear as:

```text id="3n4x9a"
Home
home
HOME
```

Other categorical fields, including gender and admission type, may also contain formatting variations.

Admission and discharge dates may contain inconsistencies that require validation.

These issues provide opportunities to practice:

* Standardization
* Data validation
* Date conversion
* Duplicate detection
* Outlier detection
* Missing-value treatment
* Business-rule validation

---

## Time Span

The dataset covers **four years from 2022 to 2025**, making it suitable for:

* Year-over-year admission analysis
* Monthly admission trends
* Seasonal healthcare analysis
* Department utilization trends
* Treatment trends
* Cost trends
* Readmission trends
* Patient satisfaction trends

The four-year period provides enough historical coverage to investigate changes in hospital activity over time.

---

## Geography

The dataset represents healthcare activity across **German hospitals in major cities**.

This geographic structure allows users to analyze and compare:

* Hospital activity
* Patient admissions
* Department utilization
* Treatment patterns
* Healthcare costs
* Patient satisfaction

across different locations.

---

## Recommended Analytics Workflow

The dataset can be used to demonstrate the complete healthcare analytics process:

```text id="0p2hqa"
Raw Data
    ↓
Data Profiling
    ↓
Data Quality Assessment
    ↓
Data Cleaning
    ↓
Data Validation
    ↓
Feature Engineering
    ↓
Exploratory Data Analysis
    ↓
Patient & Admission Analysis
    ↓
Treatment & Outcome Analysis
    ↓
Cost & Resource Analysis
    ↓
Visualization
    ↓
Healthcare Insights
    ↓
Recommendations
```

---

## Recommended Tools

### Spreadsheet & Business Intelligence

* Microsoft Excel
* Power BI
* Tableau

### Programming & Data Analysis

* Python
* Pandas
* NumPy
* R
* RStudio

### Database & SQL

* SQL
* SQL Server
* Other relational database systems

---

## Machine Learning Experiments

The dataset may also be used for exploratory machine learning applications, including:

* Readmission prediction
* Patient segmentation
* Length-of-stay prediction
* Admission classification
* Patient satisfaction analysis
* Treatment outcome analysis
* Healthcare cost prediction
* Anomaly detection

Because the dataset is synthetic, machine learning results should be interpreted as **educational and analytical experiments**, rather than as validated clinical models.

---

## Educational & Portfolio Use

This dataset is designed to support practical development of **Data Analytics and Business Intelligence skills** within the Healthcare & Pharmaceuticals domain.

It can be used to build:

* SQL healthcare analysis projects
* Python/Pandas healthcare analytics
* R/RStudio analytics projects
* Excel healthcare reports
* Power BI hospital dashboards
* Tableau healthcare visualizations
* Patient flow analysis
* Hospital performance analysis
* Healthcare cost analysis
* Readmission analysis
* Business intelligence case studies
* Machine learning experiments

---

## Important Note

> **This is a fully synthetic dataset created for educational, practice, analytical, and portfolio purposes.**

It does **not** contain real patient records, medical histories, hospital records, diagnoses, treatments, billing information, or confidential healthcare information.

Although the dataset simulates healthcare activity within **German hospitals**, the records are artificially generated and should not be interpreted as actual data from any real hospital, healthcare provider, patient, physician, or healthcare organization.

The diagnoses, treatments, laboratory results, vital signs, costs, satisfaction scores, and other healthcare-related fields are provided for **analytics and learning purposes only**.

This dataset should **not be used for clinical diagnosis, treatment decisions, medical research conclusions, patient risk assessment, or real-world healthcare decision-making**.

---

## Author

**Daniel Sowah**

Data Analytics & Business Intelligence

**Analytics Areas:**

**SQL · Python · Pandas · R · RStudio · Excel · Power BI · Tableau · Data Visualization · Business Intelligence · Healthcare Analytics · Financial Analytics · Statistical Analysis**
