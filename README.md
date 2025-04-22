# Healthcare-Stroke-

## Overview
The stroke dataset comprises 4,072 patient records, each capturing a range of variables that influence stroke risk. It includes demographic information such as gender, age, marital status, and age group classification (youth or adult). Health-related factors captured in the dataset include hypertension, heart disease, diabetes, and obesity status. Lifestyle habits such as smoking behavior (categorized as never smoked, formerly smoked, currently smokes, or unknown) are also included, along with socioeconomic indicators like work type (private, government, self-employed, or never worked) and residence type (urban or rural).
![Screenshot 2025-04-22 065258 stroke121](https://github.com/user-attachments/assets/2e3a64aa-a40e-462f-a041-f0648ab8bedb)


## Objective
The goal of this project is to explore, analyze, and interpret patterns from a dataset containing information on 4,072 individuals, with a focus on stroke occurrence. This analysis aims to identify key demographic, health-related, lifestyle, and socioeconomic factors that may contribute to the risk of stroke.

## Scope
### Data Source: 
Stroke patient records, including variables such as age, gender, marital status, employment, residence, health conditions (e.g., diabetes, hypertension, heart disease), obesity status, and smoking habits.

### Analysis Type: 
Exploratory Data Analysis (EDA)

### Tools Used: 
Microsoft Excel.

### Key Questions Explored
What demographic groups are most affected by stroke?

How do chronic health conditions influence stroke risk?

What lifestyle choices correlate with stroke occurrence?

Are there differences in stroke risk between youth and adults?

Do socioeconomic factors such as employment type or residence location have an impact?

### Expected Impact
This analysis supports proactive public health planning by:

Highlighting high-risk groups.

Uncovering modifiable risk factors.

Informing targeted health education campaigns and medical screening initiatives.

## **Exploratory Data Analysis (EDA) on Stroke Dataset**

## **1. Demographic Insights**

### **Gender Distribution**
- **Female**: 2,488 (61%)  
- **Male**: 1,584 (39%)  
- **Observation**: Females represent a larger portion of stroke patients. This could reflect both **longer life expectancy** and possibly **higher healthcare engagement** among women.

### **Age Profile**
- **Average Age**: 50 years  
- **Mode Age**: 78 years  
- **Observation**: The mode being significantly higher than the average highlights the **disproportionate impact of stroke on the elderly**, even though younger individuals are also affected.
## **2. Health Condition Insights**

### **Hypertension**
- **Overall**: 450 patients (11%) are hypertensive.
  - **Youth**: 5 patients only.
  - **Adults**: 445 patients.
- **Insight**: Hypertension is largely an adult issue and a known **precursor for stroke**. Its low presence among youth underscores the **age-dependent nature** of this condition.

### **Heart Disease**
- **Overall**: 242 patients (6%) have heart disease.
  - **Youth**: 0 cases.
  - **Adults**: 100% of cases.
- **Insight**: The strong association between **age and heart disease** again emphasizes the compounded risk older patients face. Monitoring heart health is crucial in stroke prevention.

### **Diabetes**
- **Overall**: 1,643 patients (40%) are diabetic.
  - **Youth**: 140 (33%)
  - **Adults**: 1,503 (41%)
- **Insight**: Diabetes has a **high presence** in both age groups, with a concerning prevalence among youth. This highlights an emerging **epidemic of metabolic disorders** that could drive up stroke risks in younger populations.

### **Obesity**
- **Overall**: 1,824 patients are obese (~45%).
  - **Youth**: 114 (27%)
  - **Adults**: 1,710 (47%)
- **Insight**: Obesity is highly prevalent in the adult group but emerging in youth. Since it ties closely with **diabetes, hypertension**, and **cardiovascular disease**, its presence reinforces the **multi-factorial risk** leading to strokes.

---

## **3. Lifestyle & Socioeconomic Factors**

### **Smoking Status**
- **Never smoked**: 1,714  
- **Current smokers**: 728  
- **Formerly smoked**: 813  
- **Unknown**: 817  

**By Group:**
- **Youth**:
  - Never smoked: 204
  - Smokes: 67
  - Formerly smoked: 37
  - Unknown: 120  
- **Adults**:
  - Never smoked: 1,510
  - Smokes: 661
  - Formerly smoked: 776
  - Unknown: 697

- **Insight**:
  - A combined **38% have smoking history** (current or former).
  - Adults are significantly more affected, but the **presence of current smokers among youth** indicates a rising trend.
  - Smoking remains a **modifiable behavioral risk** for stroke; public health campaigns targeting youth could help reduce future stroke rates.
  - High “Unknown” counts suggest **data quality issues** in lifestyle reporting.

### **Employment Status**
- **Private**: 2,680 (66%)
- **Self-employed**: 763
- **Government job**: 624
- **Never worked**: 5

- **Insight**:
  - The private sector has the largest share, which could indicate higher stress levels, longer work hours, or less access to preventive healthcare.
  - This suggests that **occupational health** should be explored as a potential risk factor.

### **Residence Type**
- **Urban**: 2,074 (51%)
- **Rural**: 1,998 (49%)

- **Insight**:
  - Stroke occurrence is **evenly split** between urban and rural patients.
  - It underscores that stroke is **not restricted to urbanization**, and healthcare interventions should be **geographically inclusive**.

---

## **4. Cross-Factor Observations & Insights**

### **Multi-Risk Profiles**
- Patients often exhibit **combinations of hypertension, obesity, and diabetes**, especially among adults.
- These clusters could represent **high-risk segments** warranting targeted interventions.

### **Youth Risk Trends**
- Rising trends in **diabetes, obesity, and smoking** among youth are troubling.
- This suggests a **generational shift** where lifestyle diseases are occurring earlier and might lead to earlier strokes.

### **Data Gaps**
- The “Unknown” responses in smoking status and possibly other lifestyle fields imply potential gaps in **data collection or patient disclosure**.
- Better tracking tools or awareness during clinical visits can improve accuracy.

---

## **5. Conclusion and Recommendations**

### **Key Takeaways**:
- **Age and gender** remain dominant demographic indicators, with females and older adults more likely to report strokes.
- **Health conditions** like diabetes, obesity, and hypertension are **strong predictors**, and their overlap creates a compounded risk.
- **Lifestyle factors**, especially smoking and obesity, present **modifiable risks** — early interventions here can greatly reduce stroke prevalence.
- **Socioeconomic attributes** like employment sector and residence type can influence risk, but further analysis is needed to isolate causality.

---

### **Future Steps for Deeper Analysis**:
- Conduct **correlation and regression analysis** to determine significant predictors.
- Create **segmentation models** to identify high-risk groups by age, gender, and employment.
- Incorporate **time-series** or cohort analysis (if available) to track how stroke prevalence evolves.
- Use clustering techniques (like K-means or decision trees) to define patient risk profiles.

---
