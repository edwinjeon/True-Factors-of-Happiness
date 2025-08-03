# 📊 True Factors of Happiness – A Tableau Visualization Project  
### By Weongyu Jeon

What truly makes people happy? Is it income, education, status — or something deeper?  
This Tableau-based project explores the **true drivers of happiness**, challenging common assumptions using a mix of **economic**, **psychological**, and **evolutionary** data sources.

---

## 🧠 Project Background

While global reports often tie happiness to GDP per capita, **Evolutionary Psychology (EP)** offers a different lens:  
Humans evolved to seek **social connection**, **purpose**, and **individualistic values** — not just wealth or achievement.

This dashboard integrates:
- **Cross-country economic data** (GDP, Happiness Index)
- **Survey data from ESS Round 11**
- **Theoretical insights from evolutionary psychology**

---

## Used Variables for ESS11:

- Trust_in_Others (ESS11 Code: ppltrst): How much people can be trusted or not
- Happiness (ESS11 Code: strlife): Life satisfaction
- Social_Meeting_Frequency (ESS11 Code: sclmeet): How often respondent socially meets people
- Social_Activity_Level (ESS11 Code: sclact): How much respondent is socially active
- Education_Years (ESS11 Code: eduyrs): Years of education
- Unemployed_And_Looking (ESS11 Code: uempla): Whether respondent is employed, unemployed, or other status
- Main_Activity (ESS11 Code: mainact): What specific role that respondent is in
- Income_Feeling (ESS11 Code: hincfel): Respondent's feeling about household income
- Importance_of_Understanding_Others (ESS11 Code: ipudrsta): Respondent's personal importance of understanding differences
- Importance_of_Behaving_Properly (ESS11 Code: ipbhprpa):Respondent's personal importance of behaving properly in front of people
- Importance_of_Recognition (ESS11 Code: iprspot):Respondent's personal importance to be recognized by others


## 📂 Project Structure

The dashboard is organized into **3 Parts**:

### **Part 1: Money and Happiness**
- Shows the global trend: higher GDP *correlates* with higher average happiness.
- but time-series data from USA, India, and Panama reveals:  
  👉 Happiness does **not** always rise with income over time.

### **Part 2: Perception and Meaning**
- Explores **subjective factors**:
  - People who *feel* financially comfortable are significantly happier.
  - People in **purposeful roles** (community, military, housework) report high happiness — even without income.
- Shows that **perceived value and meaning** matter more than position or wealth.

### **Part 3: Evolutionary Roots**
- Social activity and frequent interactions **strongly** predict happiness.
- Cultures that prioritize **individualistic values** (trust, respect for differences) tend to be happier.
- Suggests that **extraversion**, **freedom**, and **respect** align with our evolved psychological needs.

---

## 💡 Key Takeaways

✅ Income and education matter — but only to a point  
✅ Feeling valued, socially engaged, and trusted has greater emotional impact  
✅ Evolutionary psychology helps explain why **social and cultural factors** are so powerful

---

## 📁 Included Files

- `True_Factors_of_Happiness.twbx` - Tableau workbook (fully interactive)
- `merged_happiness_gdp_2024.csv` - Cleaned dataset of 2024 GDP + WHR scores
- '2011-2024_GDP_Happiness.csv' - Cleaned dataset of 2011-2024 GDP + WHR scores
- 'ESS11_Cleaned_Final.csv' - 11 variables needed for the project from ESS11
- 'Extraversion_vs_Happiness_By_Country.csv' - Extraversion and happiness scores by country
- `images/` - Static visuals of all dashboards
- 'README.md'

---

## 🔗 Tableau Public Version  
Interactive Dashboard Link:  
**[View on Tableau Public](https://public.tableau.com/app/profile/weongyu.jeon/viz/TrueFactorsofHappiness/Page1)**  

---

## 📚 References

### **Data Sources**
- European Social Survey (ESS11, 2022) - https://europeansocialsurvey.org/news/article/third-round-11-data-release-published
- World Happiness Report 2024 - https://www.worldhappiness.report/data-sharing/
- World Bank Open Data - https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?
- Big 5 Traits - https://github.com/automoto/big-five-data?utm
