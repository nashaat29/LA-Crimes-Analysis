# Los Angeles Crimes Report

![Cover](https://github.com/nashaat29/Car-Price-Prediction/assets/138555343/3a0b6402-afe4-4e8e-b541-d1bf38bc1786)

A comprehensive report on crime trends, spatial analysis, crime categories, demographic insights, and case statuses in Los Angeles.

**Data Cleaning and Transformation:**

![DC](https://github.com/nashaat29/Car-Price-Prediction/assets/138555343/849527d0-99b9-4eff-af08-6b2885561cef)

The entire dataset underwent a comprehensive cleaning and transformation process using Python. This included:

- Removal of unnecessary columns for the analysis
- Thorough investigation of each column
- Creation of a new column 'Age Group'
- Filling null values with 'Unknown'
- And more, detailed in the accompanying notebook.

Dataset: https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8
Data Cleaning Notebook: https://www.kaggle.com/code/mohammednashat/los-angeles-crimes-data-cleaning

## Temporal Analysis:

![Temporal](https://github.com/nashaat29/Car-Price-Prediction/assets/138555343/b9bf4016-94b2-43c7-b4f1-3578454a22f2)

### Trend of Reported Crimes (2020-2023)

The trend of reported crimes from 2020 to 2023 indicates a fluctuating pattern. The year with the highest reported crimes was 2022, totaling 234,099 cases, followed closely by 2021 with 209,302 cases.

### Seasonality in Crime Occurrences

July and August emerge as the peak months for reported crimes over the four-year period. Conversely, there is a notable decline in reported crimes during the last three months of the year (October, November, December). This drop is followed by a significant spike in January, indicating a distinctive pattern.

### Most Common Days of the Month

The most frequently reported days of the month are the 1st, 2nd, 3rd, and 15th. This suggests a possible association with the beginning of the month, possibly due to factors such as the issuance of paychecks, social events, or other societal influences.

**Insights from Temporal Analysis:**

- The year 2022 witnessed the highest number of reported crimes, indicating a potential need for increased law enforcement and community outreach efforts during that period.
- Law enforcement agencies may consider allocating additional resources during July and August to address the surge in crime rates. Conversely, they might reduce resources during the last three months of the year.
- A closer examination of the spike in reported crimes in January could provide insights into potential contributing factors, allowing for targeted preventative measures.

## Spatial Analysis:

![Spatial](https://github.com/nashaat29/Car-Price-Prediction/assets/138555343/2c7a68cc-e310-4481-a22d-4f6ce2a3d74e)

### Hotspots for Reported Crimes in Los Angeles

The Power BI report provides a map plot illustrating the hotspots of reported crimes. Darker red areas represent higher concentrations of reported crimes, while lighter red areas indicate lower occurrences.

### Areas with Higher Crime Rates

Several areas in Los Angeles exhibit higher crime rates, with the following districts reporting significant numbers of incidents:

- Center (54,000 cases)
- 77th Street (51,000 cases)
- Pacific (47,000 cases)
- SouthWest (45,000 cases)
- Hollywood (43,000 cases)

### Spatial Patterns in Different Types of Crimes

Central emerges as the district with the highest overall crime reports, totaling 24,169 cases. Specifically, "Burglary from Vehicle" in the Central area accounts for 12.65% of all crime reports. Additionally, Central has the highest average number of reported crimes per category, with an average of 4,833.80 incidents. This is followed by 77th Street (3,961.20 incidents) and Pacific (3,049.60 incidents).

**Insights from Spatial Analysis:**

- Law enforcement agencies should focus efforts on the identified high-crime districts, allocating resources to address the specific challenges unique to each area.
- Special attention may be required in Central, which consistently reports the highest number of crimes across different categories.
- The prevalence of "Burglary from Vehicle" in the Central area indicates a need for targeted strategies to address this specific type of crime.

## Crime Categories:

![Crime categ](https://github.com/nashaat29/Car-Price-Prediction/assets/138555343/b143c65c-fadf-49cb-8fda-7fe0e83820ef)

### Most Common Types of Crimes

"Vehicle - Stolen" accounts for the highest proportion of crimes at 28.71%, followed by "Battery - Simple Assault" at 21.26%.

### Trends in Specific Crime Categories over Time

Between 2020 and 2023, "Theft of Identity" experienced the largest increase at 10.06%, while "Vehicle - Stolen" saw the most significant decrease at 19.74%. "Burglary from Vehicle" displayed an interesting trend, showing a notable upward trajectory since 2020, with a rise of 12.02% (1,526 cases) over two years.

**Insights from Crime Categories:**

- Strategies to combat identity theft should be prioritized due to its notable increase over the years.
- Efforts to combat vehicle theft have shown success, as evidenced by the significant decrease over the same period.
- "Burglary from Vehicle" demands special attention, with its consistent upward trend indicating a need for preventative measures and law enforcement focus.

## Demographic Analysis:

![Demographic](https://github.com/nashaat29/Car-Price-Prediction/assets/138555343/71ca5029-05de-46b8-a2c9-92b9b3c8de21)

### Distribution of Victim Age Groups:

The dataset contains information on various age groups of victims. The highest representation is in the adult age group, comprising 280,000 records. Following this, the old age group is represented, with the child age group having the lowest number of records.

### Correlation between Victim Age and Types of Crimes Reported:

Upon analyzing the data, it is observed that there isn't a strong correlation between victim age and the types of crimes reported. However, it can be noted that a significant number of crimes occur within the age range of 25 to 40.

## Case Status:

![case status](https://github.com/nashaat29/Car-Price-Prediction/assets/138555343/69783253-461d-4a5d-bc14-2ecf38d6b67b)

### Proportion of Cases:

The data indicates that the majority of cases fall under the "Investigation Continued" category, accounting for approximately 87.83% of the total cases. This suggests that a significant portion of cases is not permanently closed.

### Trends or Patterns in Case Status over Time:

Examining the trends over a three-year period from 2020 to 2023, certain interesting patterns emerge:

- *Juv Other*: This category witnessed the largest increase in the count of crime code, showing a growth of 3.88%.
- *Adult Other*: In contrast, this category experienced the most significant decrease, with a decline of 55.09% in the count of crime code.
- Across various case statuses, *Juv Arrest* is of particular interest. It started trending downwards in 2020 and continued to decline, experiencing a drop of 53.88% (from 111 cases) over the three-year period.

---

This comprehensive analysis provides valuable insights for decision-making, allowing for targeted strategies in law enforcement, resource allocation, and preventative measures to address crime in Los Angeles effectively.
