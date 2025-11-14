# Investigating Noise Levels in Campus Study Locations

## University of Arizona - STAT571B Design of Experiments

#### Problem

Students have diverse preferences for study environments, and noise levels play a major role in their ability to concentrate. However, noise patterns across different study locations on the University of Arizona campus — especially how they vary by time of day and day of the week — have not been systematically documented. This lack of data makes it difficult for students to choose study spots that match their needs.

This project aims to address three key questions:
1. Which study location is the most comfortable in terms of noise and distraction?
2. How does expected noise differ between morning and afternoon across locations?
3. Does expected noise change depending on the day of the week (beginning, middle, end)?


#### Data source
Noise data were collected using two measurement methods across campus study locations. Objective noise levels were recorded using a mobile app that captured average decibel readings. Subjective noise levels were obtained from observers who rated the environment on a 0–10 scale. Both measures were normalized to a common scale and combined into a single composite score, calculated by averaging the normalized subjective and objective scores with equal weighting (0.5 each). This composite score serves as the response variable for analysis.

#### Approach
To answer these questions, the study measures noise across multiple campus locations using both objective (decibel readings) and subjective (0–10 ratings) methods, combined into a normalized composite score. A full factorial ANOVA is used to analyze the effects of location, time of day, and day of the week, along with diagnostic checks and Tukey-adjusted comparisons to identify differences between groups.


#### Key results


#### Technical stack


#### Data visualisations



#### Recommendations






#### Tasks
1. Design a Full Factorial experiment
2. Fit an ANOVA model
3. Create interaction plots
4. Perform formal tests with Tukey’s test for additivity
5. Check model assumptions with model diagnostics
6. Compute Tukey-adjusted confidence intervals
7. Make recommendations based on statistical analysis

#### References
- To view code: [Stat571B_Code.R](https://github.com/kai-shuen-neo/doe-noise/blob/main/Stat571B_Code.R) 
- To view report: [Stat571B_Group2_Report.pdf](https://github.com/kai-shuen-neo/doe-noise/blob/main/Stat571B_Group2_Report.pdf)
- To view appendix: [STAT571B_Group2_Appendix.pdf](https://github.com/kai-shuen-neo/doe-noise/blob/main/STAT571B_Group2_Appendix.pdf)
- To view slides: [Stat571B_Group2_Slides.pdf](https://github.com/kai-shuen-neo/doe-noise/blob/main/Stat571B_Group2_Slides.pdf) 


