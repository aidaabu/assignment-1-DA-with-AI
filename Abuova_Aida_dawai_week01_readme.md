## assignment-1-DA-with-AI
# 1. Research question: Is there a correlation between perceived freedom of choice (Q48) and life satisfaction (Q49)?

# 2. The most relevant variables
- Q48 - How much freedom of choice and control (Main independent variable);
- Q49 - Satisfaction with your life (Main dependent variable);
- **Demographic variables**: Q260 - Sex; Q261 - Year of birth; Q262 -  Age; Q275 - Highest educational level: Respondent [ISCED 2011]; Q288 - Scale of incomes; Q289CS - Religious denomination - detailed list. 
- **Other influencing factors**: Q50 - Satisfaction with financial situation of household; Q46 - Feeling of happiness, Q57 - Most people can be trusted.

# 3. I created a single read.me file as .md
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

## 4. A table with descriptive statistics for 5 selected most important variables
<img width="557" alt="Screenshot 2025-02-26 at 22 13 30" src="https://github.com/user-attachments/assets/b4579e64-7248-43de-8b9a-c0a7d9e88683" />

