# Economic Development and Health Outcomes Analysis

## Project Overview
This project analyzes the relationship between GDP per capita, healthcare spending, and life expectancy across 12 countries from 2000-2023 using World Bank data.

## Research Question
How do GDP per capita and healthcare spending influence life expectancy across different development levels?

## Countries Analyzed
- **South Asia**: Sri Lanka, India, Bangladesh, Pakistan
- **East Asia**: Singapore, Japan, South Korea
- **Western Countries**: United States, Norway, Germany
- **Africa**: Ethiopia, Nigeria

## Dataset
- **Source**: World Bank Open Data
- **Time Period**: 2000-2023
- **Indicators**:
  - GDP per capita (current US$)
  - Life expectancy at birth (years)
  - Healthcare expenditure per capita (current US$)

## Key Findings
1. **Strong GDP-Life Expectancy Correlation**: r = 0.719 (p < 0.001)
2. **Healthcare-Life Expectancy Correlation**: r = 0.601 (p < 0.001)
3. **GDP-Healthcare Correlation**: r = 0.892 (p < 0.001)
4. **Sri Lanka Success**: 288.6% GDP growth, +6.1 years life expectancy improvement
5. **Diminishing Returns**: Countries above $40,000 GDP show marginal life expectancy improvements

## Files in Repository
```
├── analysis.py                      # Main analysis code
├── merged_data_complete.csv         # Cleaned and merged dataset
├── API_NY.GDP.PCAP.CD_DS2_en_csv_v2_174336.csv     # GDP data
├── API_SP.DYN.LE00.IN_DS2_en_csv_v2_132.csv        # Life expectancy data
├── API_SH.XPD.CHEX.PC.CD_DS2_en_csv_v2_174048.csv  # Healthcare data
├── outputs/
│   ├── correlation_heatmap.png
│   ├── scatter_plots_all.png
│   ├── gdp_trends_all_countries.png
│   ├── life_expectancy_trends.png
│   ├── avg_life_expectancy_bar.png
│   ├── srilanka_analysis.png
│   └── srilanka_detailed_analysis.png
└── README.md
```

## Technologies Used
- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization
- **scipy** - Statistical analysis

## How to Run
1. Clone this repository:
```bash
   git clone https://github.com/YOUR-USERNAME/economic-health-analysis.git
```

2. Install required packages:
```bash
   pip install pandas numpy matplotlib seaborn scipy
```

3. Run the analysis:
```bash
   python analysis.py
```

## Analysis Methods
- **Pearson correlation coefficients** for relationship strength
- **Linear regression** for trend analysis
- **Time series analysis** for temporal patterns
- **Descriptive statistics** for data characterization

## Key Insights

### Sri Lanka Case Study
Sri Lanka demonstrates exceptional healthcare efficiency:
- Achieves life expectancy comparable to countries with 3-4x higher GDP
- Universal healthcare with free access
- Strong emphasis on preventive medicine
- High literacy rates enabling health education

### The US Paradox
- Highest healthcare spending does not guarantee best outcomes
- Life expectancy lags behind lower-spending countries
- Suggests system inefficiencies and access disparities

### Policy Implications
1. Universal healthcare access is essential
2. System design matters more than absolute spending
3. Preventive care delivers high returns
4. Economic growth must be coupled with health policies

## Author
**Student ID**: 25001675  
**Course**: Data Science Laboratory 1 - Coursework 2  
**Institution**: University of Hertfordshire  
**Year**: 2025/26


## Data Sources
World Bank. (2024). World Development Indicators. Retrieved from https://data.worldbank.org/

---
*This analysis was conducted as part of coursework requirements and demonstrates data science techniques including data cleaning, statistical analysis, and visualization.*
