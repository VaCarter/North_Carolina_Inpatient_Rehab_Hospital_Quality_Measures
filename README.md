# North Carolina Inpatient Rehab Hospital Quality Measures
A comparitive analysis of the quality measure scores of Inpatient Rehab Hospitals in North Carolina.

## Table of Contents
* [Presentation](#Presentation)
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normalizing-the-data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Data Sources](#data-sources)
* [Conclusion](#conclusion)

## Presentation
https://www.canva.com/design/DAGwLbN1vs4/PsJTERQtYfK5Nr3FoTzdMQ/edit?utm_content=DAGwLbN1vs4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

## Motivation
As a physical therapist with over 13 years of experience in both acute care and non-clinical settings, I have consistently relied on functional outcome measures as a key component of patient evaluations and periodic reassessments. These tools are essential for tracking patient progress, determining levels of disability, and supporting effective discharge planning.

In a similar manner, inpatient rehabilitation hospitals utilize a standardized measurement tool known as the Patient Assessment Instrument (PAI). This instrument is designed to evaluate various aspects of patient progress and the quality of care delivered by the facility. The data collected through the PAI is submitted to the Centers for Medicare & Medicaid Services (CMS) and contributes to the Inpatient Rehabilitation Facility (IRF) Quality Reporting Program.

For this project, I aim to explore inpatient rehabilitation hospitals in North Carolina and analyze their performance on specific quality measures as reported by CMS. These measures reflect the quality and effectiveness of care provided and are critical for identifying facilities that may be underperforming compared to national benchmarks or failing to meet established quality standards.

## Questions:
1. How does the performance of North Carolina inpatient rehabilitation facilities (IRFs) on the identified quality measures compare to the national average?
2. Does the type of organization (e.g., non-profit, for-profit, government) appear to correlate with performance on these quality measures?
3. Are there notable regional differences in the performance of North Carolina IRFs on the selected quality measures?
4. Are there regions in North Carolina where additional inpatient rehabilitation facilities may be needed, based on senior population growth trends?

## Normalizing the data
To ensure the most recent and relevant quality reporting, I focused on data from the past three years (2023–2025). Since quality measures are reported quarterly, I selected June as a consistent reference point to maintain uniformity in the time intervals between reports. Additionally, I compiled a list of specific counties in North Carolina that contain inpatient rehabilitation hospitals. This list was used throughout the project to ensure consistency in data reporting across all quality measures, geographic regions, and organizational types.

## Problems and Hurdles
During my analysis of the Discharge Function Score, I discovered that this measure was only recently introduced to the Inpatient Rehabilitation Facility Quality Reporting Program in 2023. As a result, it is the only quality measure with a limited dataset—reflecting just about one year of collected data—which makes it inconsistent with the other measures in terms of reporting history and depth.

## Technologies Used
I used Python for data analysis and Power BI for creation of visualizations.

## Data Sources
https://data.cms.gov/provider-data/archived-data/inpatient-rehabilitation-facilities#2025-annual-files

https://www.cms.gov/medicare/quality/inpatient-rehabilitation-facility/irf-quality-reporting-measures-information

https://www.cms.gov/files/document/irf-quality-measure-calculations-and-reporting-users-manual-v40.pdf

https://www.osbm.nc.gov/facts-figures/population-demographics

## Conclusion
Overall, North Carolina outperformed the national average across the four reported quality measures. However, regional analysis revealed that Eastern North Carolina consistently underperformed compared to the state's other two regions. Data also indicates that non-profit inpatient rehabilitation facilities (IRFs) tend to have higher rates of hospital readmissions and falls resulting in major injury. It is important to note, however, that non-profit organizations represent the majority of IRFs in the state, which may influence these trends. Further investigation is warranted to better understand the underlying factors contributing to the lower performance scores in Eastern North Carolina. Additionally, due to limited data availability at the time of this project, a more accurate analysis of the Discharge Function Score could not be completed and will require additional data collection.
