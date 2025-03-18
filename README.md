
# Analysis of Cognitive Impairment in Diabetes Patients

## Table of Contents
- [Project Overview](#project-overview)
- [Roles and Responsibilities](#roles-and-responsibilities)
- [Blood related Biomarker Analysis](#blood-related-biomarker-analysis)
- [Key Insights & Findings](#key-insights--findings)
- [Challenges & Solutions](#challenges--solutions)
- [Tools and Technologies](#tools-and-technologies)
- [Impact and Learnings](#impact-and-learnings)
- [Conclusion](#conclusion)

## Project Overview
This project analyzes the impact of diabetes on cognitive impairment using real-world patient data. The dataset consists of diabetic and non-diabetic patients, including biomarkers, demographics, and cognitive test results. The objective was to uncover patterns linking diabetes, obesity, cardiovascular health, and cognitive decline. A prospective observational study of 77 participants was carried out to evaluate the effects.

## Roles and Responsibilities
- Conducted data cleaning to handle missing values, correct erroneous calculations, and ensure consistency.
- Performed data modeling by segmenting the dataset into sub-tables for better analysis in Power BI.
- Built interactive dashboards to visualize key insights, such as BMI trends, blood biomarkers, and cognitive test performance.
- Identified risk factors for cognitive decline by analyzing demographics, medication history, and neurological tests.
- Collaborated in an agile environment, participating in daily stand-ups and sprint reviews.

## Blood related Biomarker Analysis

![Bloodrelatedbiomarkers](https://github.com/user-attachments/assets/447d67a1-e4eb-4955-83f4-2eb6593b93ff)


1. **WBC (white blood cell count)**: In this analysis, we considered patients who have moderate and severe cognitive decline. 14.63% of patients have Leukopenia, and 4.88% have Leukocytosis. Both conditions may be associated with a higher risk of stroke.
2. **MMP-9 (ng/mL)**: 42.86% of patients have elevated MMP9, indicating a high risk of Alzheimer's disease and other neurodegenerative disorders.
3. **Platelet count**: Thrombocytopenia may increase the risk of bleeding, and thrombocytosis may increase the risk of blood clots, indicating a higher risk of stroke.
4. **Low Hct%, Hgb, and RBC (anemia)**: Anemia can worsen cognitive function and increase the risk of stroke and other cardiovascular events. There is a strong correlation between MCV and MCH as they are measures of red blood cell size and volume. Higher MCV and MCH levels increase the risk of developing Alzheimer's disease.
5. **RDW%**: 8.12% of female patients and 13.02% of male patients have abnormal RDW% ranges. A high RDW% may be a sign of an inflammatory condition or anemia, indicating a more severe form of cognitive decline.

## Gait Analysis

![Gait](https://github.com/user-attachments/assets/5f80c9ea-6fd2-493c-bceb-10a88c55ceb9)


1. People with diabetes are more likely to experience problems with thinking, vision, and walking slowly due to subcortical frontal dysfunction.
2. A person’s walking mannerism is a reference to their physical health. Our dataset includes a 6-minute walking test conducted on day 2 of visit 2 and 8 for both groups.
3. Patients with diabetes had significantly shorter walking distances and slower walking speeds than control patients.
4. The average speeds of control patients during normal and dual-task walking tests are slightly more than those of diabetes patients in visit 2. However, diabetes patients in visit 8 who have taken proper care with medication showed improvement.
5. The difference in walking speed between the two groups was greatest among patients aged 50-55 and the oldest patients (aged 75+), suggesting that Cerebral Microvascular Disease (CVD) may be a factor.
6. Female patients with diabetes and CVD have shorter gait distances and slower gait speeds than male patients, suggesting that females may be more susceptible to mobility-impairing effects.
7. The Rating of Perceived Exertion (RPE) is a useful tool to monitor exercise intensity in elderly individuals with diabetes.
8. The study found that the maximum number of diabetes patients exerted moderate intensity at the start of the task, with RPE levels ranging from 6 to 7 by the end of the task.
9. When participants were asked to perform a cognitive task while exercising, there was a significant increase in the number of patients exerting more intensity by the end of the dual task.
10. The majority of patients in the diabetes group were overweight or obese. The analysis showed a negative correlation between BMI and gait distance covered.

## Key Insights & Findings
- **Diabetes & Cognitive Decline**: Patients with diabetes showed accelerated cognitive decline, particularly those with obesity and long disease duration.
- **BMI & Insulin Resistance**: Most diabetic patients were overweight or obese, and high BMI correlated with increased insulin resistance.
- **Neurological Markers**: Elevated inflammatory markers (CRP, sICAM, MMP9) were linked to severe cognitive impairment.
- **Cardiovascular Risks**: Hypertension and high triglycerides were more prevalent in diabetic patients, increasing the risk of heart disease.
- **Ophthalmology Trends**: Diabetic retinopathy and macular edema were more common in diabetic patients, affecting their vision.

## Challenges & Solutions
- **Data Quality Issues**: Addressed missing values using Power Query techniques such as COALESCE and conditional replacements.
- **Lack of Unique Identifiers**: Created a composite key combining Patient ID and visit numbers.
- **Complex Medical Data**: Collaborated with domain experts to interpret clinical biomarkers.

## Tools and Technologies
- **Power BI**: Data visualization & dashboard creation.
- **Power Query**: Data transformation & cleaning.
- **Excel**: Data exploration & preprocessing.

## Impact and Learnings
This project reinforced the importance of data accuracy in healthcare analytics. It demonstrated how biomarkers, demographics, and lifestyle factors collectively influence cognitive health in diabetic patients.

## Conclusion
This study provides valuable insights into the relationship between diabetes and cognitive impairment. The findings highlight the importance of managing diabetes effectively to mitigate cognitive decline and other related health risks.





