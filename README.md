# Investigating Noise Levels in Campus Study Locations

## University of Arizona - STAT571B Design of Experiments

#### Problem

Students have diverse preferences for study environments, and noise levels play a major role in their ability to concentrate. However, noise patterns across different study locations on the University of Arizona campus — especially how they vary by time of day and day of the week — have not been systematically documented. This lack of data makes it difficult for students to choose study spots that match their needs.

This project aims to address three key questions:
1. Which study location is the most comfortable in terms of noise and distraction?
2. How does expected noise differ between morning and afternoon across locations?
3. Does expected noise change depending on the day of the week (beginning, middle, end)?

To answer these questions, the study measures noise across multiple campus locations using both objective (decibel readings) and subjective (0–10 ratings) methods, combined into a normalized composite score. A full factorial ANOVA is used to analyze the effects of location, time of day, and day of the week, along with diagnostic checks and Tukey-adjusted comparisons to identify differences between groups.

#### Data source
Noise data were collected using two measurement methods across campus study locations. Objective noise levels were recorded using a mobile app that captured average decibel readings. Subjective noise levels were obtained from observers who rated the environment on a 0–10 scale. Both measures were normalized to a common scale and combined into a single composite score, calculated by averaging the normalized subjective and objective scores with equal weighting (0.5 each). This composite score serves as the response variable for analysis.

#### Approach
The study uses a full factorial experimental design to evaluate how noise levels vary by location (3 levels), day of the week (3 levels), and time of day (2 levels). Data were collected across 4 observers with 2 replicates, resulting in a total of 144 observations. The order in which locations were visited was randomized to reduce ordering bias, and observers were treated as blocks to control for personal differences and device variability.

A full factorial ANOVA was then used to assess main effects and interactions among the factors. Model validity was checked through residual diagnostics, including normality and homoscedasticity assessments. Tukey-adjusted pairwise comparisons were conducted to identify specific group differences. This design provided strong power to detect moderate to large effects and supported robust hypothesis testing to answer the study’s research questions.


#### Statistical Analysis
To evaluate how noise and distraction levels vary across locations, days, and times, a mixed-effects model was fitted using the composite score as the response variable. The model included fixed effects for Location (3 levels), Day of Week (3 levels), and Time of Day (2 levels), along with all two-way and three-way interactions. Observers (4 levels) were included as a random effect to account for individual differences in rating sensitivity and device variation. Each condition was measured with two replications.

The statistical model followed a full factorial structure, enabling estimation of main effects and interactions while treating observers as random blocks. Constraints were imposed to ensure parameter identifiability, with baseline levels set for each factor.

Model assumptions were assessed through diagnostic checks:
- Normality of residuals was confirmed through Q–Q plots.
- Homoscedasticity was evaluated using residual-versus-fitted and residual boxplots, showing no major violations.
- Additivity was examined using interaction plots and Tukey’s Test for Nonadditivity, which indicated that interaction effects were significant and necessary in the model.

This analysis framework provided a robust basis for identifying the conditions under which students experience higher or lower noise levels.

#### Key results







#### Technical stack


#### Data visualisations



#### Recommendations






