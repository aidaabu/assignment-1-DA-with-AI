## assignment-1-DA-with-AI
# 1. Research question: 
## Is there a correlation between perceived freedom of choice (Q48) and life satisfaction (Q49)?

# 2. The most relevant variables
- Q48 - How much freedom of choice and control (Main independent variable);
- Q49 - Satisfaction with your life (Main dependent variable);
- **Demographic variables**: Q260 - Sex; Q261 - Year of birth; Q262 -  Age; Q275 - Highest educational level: Respondent [ISCED 2011]; Q288 - Scale of incomes; Q289CS - Religious denomination - detailed list. 
- **Other influencing factors**: Q50 - Satisfaction with financial situation of household; Q46 - Feeling of happiness, Q57 - Most people can be trusted.

# 3. I created a single read.me file as .md
# World Values Survey (WVS) Dataset - Subset

## 1. Key Info on the Dataset
- **Dataset Name**: WVS Subset
- **Source**: World Values Survey (Wave 7, 2017-2022)
- **Total Rows**: 97,220
- **Total Columns**: 168
- **Data Types**:
  - 161 integer columns (survey responses)
  - 2 float columns (weights, scores)
  - 5 object columns (country codes, identifiers)

## 2. Dataset Location, Path
- **File Path**: 'import delimited "C:\Users\Abuova_Aida\Downloads\WVS_subset.csv", clear'
                 'save "C:\Users\Abuova_Aida\Downloads\WVS_subset.dta", replace'

## 3. Variables Description
The dataset includes demographic information, values, beliefs, and opinions on social, economic, and political topics. Some key variables:

| Variable Name   | Description |
|----------------|-------------|
| Q48            | How much freedom of choice and control (on a scale from -5 to 10) |
| Q49            | Satisfaction with your life (on a scale from 1 to 10) |
| Q260           | Sex (on a scale from 1, 2, -2, -4, -5) |
| Q261           | Year of birth (on a scale from -5 to -1) |
| Q262           | Age (on a scale from -5 to -1) |
| Q275           | Highest educational level: Respondent [ISCED 2011] (on a scale from -5 to -1 and from 1 to 8) |
| Q288           | Scale of incomes (on a scale from -5 to -1 and from 1 to 10)|
| Q289CS         | Religious denomination - detailed list (Country-specific list of codes in Annex) |
| Q50            | Satisfaction with financial situation of household (on a scale from -5 to -1 and from 1 to 10) |
| Q46            | Feeling of happiness (on a scale from -5 to -1 and from 1 to 4)|
| Q57            | Most people can be trusted (on a scale from -5 to -1 and from 1 to 2)|

## 4. A table with descriptive statistics for 5 selected most important variables
summarize 
<img width="557" alt="Screenshot 2025-02-26 at 22 13 30" src="https://github.com/user-attachments/assets/b4579e64-7248-43de-8b9a-c0a7d9e88683" />
<img width="524" alt="Screenshot 2025-02-26 at 22 16 06" src="https://github.com/user-attachments/assets/7881b11c-3642-4ce5-8128-58fdfeaa07b6" />

