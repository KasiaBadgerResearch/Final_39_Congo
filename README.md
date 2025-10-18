# How have female and male primary school repetition rates evolved relative to one another in the Republic of Congo between 1972 and 2012?

## Abstract

Using World Bank World Development Indicators (WDI), this study examines the evolution of male and female primary school repetition rates in Congo between 1972 and 2012. The analysis compares two key indicators: the percentage of female students repeating primary grades and the percentage of male students repeating primary grades. Over this forty-year period, repetition rates for both genders followed very similar trajectories, with male rates consistently slightly higher than female rates throughout. Despite this small gender gap, the overall pattern was marked by strong volatility — with pronounced fluctuations and sudden shifts in repetition levels over time. The data reveal a significant U-shaped decline between 1975 and 1985, followed by a period of sharp increases and irregular oscillations until around 2000, when repetition rates dropped abruptly. From 2000 onward, both male and female repetition rates displayed moderate volatility but an overall downward trend. These results suggest persistent structural challenges within the primary education system, despite gradual improvements in reducing grade repetition toward the end of the period.

## 1. Question

How have female and male primary school repetition rates evolved relative to one another in the Republic of Congo between 1972 and 2012?

- **Female repetition proxy**: Repeaters, primary, female (% of female enrollment)
- **Male repetition proxy**: Repeaters, primary, male (% of male enrollment)

## 2. Data

- **Source**: World Bank World Development Indicators (WDI)
- **Indicators**:
  - Repeaters, primary, female (% of female enrollment)
  - Repeaters, primary, male (% of male enrollment)
- **Coverage**: Republic of Congo, 1972–2012
- **Notes**: National-level data only

## 3. Method

1. Filtered dataset for Congo and selected the two primary repetition rate indicators.
2. **Extracted relevant columns**: Year, Indicator Name, and Value.
3. Pivoted the dataset to create a side-by-side comparison of male and female repetition rates between 1972 and 2012.
4. Generated a dual-line time series plot to visualize gender differences and overall volatility in repetition trends.

(Analysis is descriptive; no causal inference applied.)

## 4. Results

- **Female repetition rates**: Showed a volatile trajectory between 1972 and 2012, with significant ups and downs, but an overall moderate downward trend toward the end of the period.
- **Male repetition rates**: Mirrored female repetition rates closely, also exhibiting strong volatility and sudden shifts, while remaining consistently slightly higher than female rates.
- **Comparison**: The two indicators moved largely in parallel over time, with males slightly above females throughout. Both experienced a pronounced U-shaped drop between 1975 and 1985, followed by irregular increases and fluctuations until a sharp drop around 1999–2000, then moderate volatility with an overall downward trend to 2012.

(Figure 1. Congo: Female vs. Male Primary School Repetition Rates, 1972–2012)

(Table 1. Pivoted dataset summary)

## 5. Interpretation

- The near-identical trajectories for male and female repetition rates indicate that gender was not a major differentiating factor in primary school retention.
- The persistent volatility points to structural instability in Congo’s primary education system — likely linked to political upheavals, funding fluctuations, and inconsistent policy implementation.
- The sharp drop around 2000 may reflect reforms in educational policy or data reclassification coinciding with post-conflict reconstruction efforts.
- The overall downward trend in the 2000s suggests gradual progress toward reducing grade repetition and improving educational efficiency.
- These findings highlight both the resilience of the education system and the need for more sustained interventions to maintain consistent learning outcomes over time.

## 6. Limitations

- The data are aggregated at the national level and do not capture regional or rural-urban differences in repetition rates.
- WDI estimates for earlier decades may rely on incomplete administrative records, introducing potential uncertainty in year-to-year variation.
- The descriptive approach does not isolate causal factors such as teacher quality, resource allocation, or curriculum reforms that may explain observed fluctuations.

## 7. Next Steps / Extensions

- Extend the analysis to include total repetition rates and enrollment levels to assess efficiency in the broader primary education system.
- Explore correlations between repetition rates and macro variables such as education expenditure, conflict intensity, or teacher–student ratios.
- Compare Congo’s trajectory with neighboring Central African countries to identify regional convergence or divergence in educational performance.
- Conduct time-series decomposition to separate long-term trends from short-term volatility and structural breaks, particularly around major policy shifts.
