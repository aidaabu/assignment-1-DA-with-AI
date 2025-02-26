# assignment-1-DA-with-AI
1. Research question: Is there a correlation between perceived freedom of choice (Q48) and life satisfaction (Q49)?

2. The most relevant variables: Q48 - Perceived freedom of choice and control (Main independent variable); Q49 - Life satisfaction (Main dependent variable); 
Demographic variables: Q260 - Age (Age may influence both freedom of choice and life satisfaction); Q261 - Gender (Differences in gender roles could affect perceptions of control and satisfaction); Q262 -   Marital status (Being married or single might affect perceived control over life and happiness levels); Q275 - Education level (Higher education may lead to greater perceived control and satisfaction); Q288 - Income scale (Financial status could impact both perceived choice and happiness)
Other influencing factors: Q50 - Satisfaction with financial situation (Financial stability may impact both variables directly); Q46 - Happiness (General happiness might mediate the relationship between perceived freedom and life satisfaction).

3. I created a single read.me file as .md
# World Values Survey (WVS) Dataset - Subset

## 1. Key Information
- **Dataset Name**: WVS Subset
- **Source**: World Values Survey (Wave 7, 2017-2022)
- **Total Rows**: 97,220
- **Total Columns**: 168
- **Data Types**:
  - 161 integer columns (survey responses)
  - 2 float columns (weights, scores)
  - 5 object columns (country codes, identifiers)

## 2. Dataset Location
- **File Path**: `/mnt/data/WVS_subset.csv`

## 3. Variables Description
The dataset includes demographic information, values, beliefs, and opinions on social, economic, and political topics. Some key variables:

| Variable Name   | Description |
|----------------|-------------|
| `B_COUNTRY`    | Country code (numeric) |
| `B_COUNTRY_ALPHA` | Country code (Alpha-3 format) |
| `A_YEAR`       | Year of the survey |
| `A_WAVE`       | Survey wave number |
| `W_WEIGHT`     | Weighting factor for responses |
| `Q290`         | Racial/Ethnic belonging |
| `Q57`          | Trust in people (binary: trust/distrust) |
| `Q46`          | Self-reported happiness level |
| `Q49`          | Life satisfaction score (scale 1-10) |
| `Q50`          | Household financial satisfaction |
