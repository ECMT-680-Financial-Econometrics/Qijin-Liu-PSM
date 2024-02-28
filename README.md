# ECMT680
# Replication for "Heat Exposure and Youth Migration in Central America and the Caribbean"

## Overview
This paper investigates how environmental changes, particularly heat exposure, drive youth migration in Central America and the Caribbean. It addresses the gap in understanding the environmental drivers of migration in the region, focusing on the impact of prolonged or repeated exposure to high temperatures on inter-province migration patterns.

## Methodology
The study employs a triple difference-in-difference quasi-experimental design, using migration data from censuses across several countries in the region. It integrates climate data on daily temperatures to assess heat exposure and examines its relationship with migration patterns, employing a linear probability model to quantify effects.

## Formula
The core of the analysis is represented by the following linear probability model formula, notated here in a simplified textual format for readability:

$$
\begin{align}
M_{ijkat} = & \beta_1 (Temp_k \times Age_a \times After) + \beta_2 (Temp_k \times Age_a) + \\
& \beta_3 (Temp_k \times After) + \beta_4 (Age_a \times After) + \theta X_{ijkat} + \alpha_j + \delta_t + \gamma_a + \epsilon_{ijkat}
\end{align}
$$



Where M_ijkat indicates migration within the last five years, incorporating interactions between temperature exposure, age groups, and periods.

## Conclusion
The findings reveal a nuanced impact of heat exposure on migration, with significant effects observed particularly among young women and the unskilled, suggesting a gendered and socioeconomic dimension to environmental migration. The patterns do not correlate with broad economic losses, indicating individual and household strategies to mitigate income fluctuations due to temperature variability.

## Appendix
- **Data Sources**: Migration data from censuses, daily temperature from the Global Land Data Assimilation System, GDP data from the World Bank and World Development Indicators. 
- **Statistical Analysis**: Summary statistics, regression models, and standard errors are detailed in the online Appendix, highlighting the methodology's robustness and assumptions.
- **References**: A comprehensive list of references supports the research framework and findings, including works on climate change, migration, and economic impacts.
- **Google Colab link**:https://colab.research.google.com/drive/1B_Ol_0r0biFx47Z8TIUEX48ZTOISTmmw?usp=sharing
- **Overleaf link**:(Empirical exercise)https://www.overleaf.com/read/wskjfhjkgfxh#28844d
-                   (Poster)
