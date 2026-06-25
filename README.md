# Life-Expectancy-and-GDP-per-capita

## Overview
In this project I try to trace a relationship between a country's wealth and the life expectancy of its population — and if there is one, what shape does that relationship take?

## Key Findings
- There is a strong positive correlation between GDP per capita and life expectancy
- The relationship is non-linear — applying a logarithmic transformation to GDP significantly improves model fit, suggesting that wealth gains matter more at lower income levels than at higher ones
- Data was sparse in the early and most recent data collection periods (1960-2002, 2022-2025); the 2002–2022 window was identified as the most data-rich period and selected for analysis

## Methodology
1. Merged two World Bank datasets (GDP per capita + life expectancy)
2. Analysed null-value distribution across years to identify the optimal time window
3. Correlation and linear regression between GDP and life expectancy
4. Applied logarithmic transformation to GDP and compared model fit

## Tools & Libraries
- Python (pandas, numpy, scipy, matplotlib, seaborn)
- Tableau
- Data sources: [World Bank GDP per capita](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD), [World Bank Life Expectancy](https://data.worldbank.org/indicator/SP.DYN.LE00.IN)
