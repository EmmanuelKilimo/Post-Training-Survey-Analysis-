  # Post-Training-Survey-Analysis-
This repository presents survey questionnaire and analysis results from data gathered from farmers trained on container farming techniques. The survey aimed to assess effectiveness, gauge satisfaction ,  gather needs and provide feedback and recommendations.
                        BFWAI Container Farming Training Survey Analysis 

SWB Project 297 — Beellahy Foundation Women for Agricultural Initiative 
Statistical analysis of a post-training survey conducted among participants (farmers) 
of the Beellahy Foundation Women for Agricultural Initiative (BFWAI), which 
provides container farming training and resources to women in Lagos State, Nigeria. 
This project was completed through Statistics Without Borders (SWB), Project 
297, in collaboration with the Beellahy Foundation. 

Project Overview 

The analysis evaluates farmers experiences and outcomes following the BFWAI 
container farming training. The project focused on understanding: 
• Participant demographics and farming experience 
• Changes in understanding of container farming techniques 
• Satisfaction with training and post-training support 
• Usefulness and accessibility of training materials 
• Agricultural knowledge and knowledge application 
• Challenges encountered during training and whether participant expectations 
were met 
• Household food production and surplus sales 
• Perceptions of the future of container farming 
• Additional support needs and interest in future training 
The analysis focused on identifying assessment of programme impact, participant 
needs, satisfaction, and recommendations for future initiatives as its core objectives. 

Data 

The analysis uses responses from a post-training survey administered to BFWAI 
participants. 

• Target population: 267 women participating in the BFWAI 
• Analysis dataset: 217 completed survey responses 
• Location: Lagos State, Nigeria 
• Survey type: Post-training participant survey 
• Data type: Primarily structured quantitative survey responses, including 
Likert-scale items and multiple-choice questions 
• Additional data: Open-ended responses were available for selected questions 

Analytical Approach 

The analysis was conducted in Python and included:

1. Data cleaning and validation 

o Missing-value checks 
o Response-frequency checks 
o Preparation of analysis-specific dataframes 
2. Likert-scale encoding 
o Conversion of categorical response options to numerical scores 
o Reverse scoring of selected knowledge-assessment items

4. Descriptive analysis 

o Participant demographics 
o Farming experience 
o Training experience 
o Satisfaction 
o Training materials and support 
o Farming outcomes and future support needs 

5. Inferential analysis 

o Spearman correlation analysis 
o Ordinary Least Squares (OLS) regression 
o Chi-square tests of association 
o Group comparisons 

6. Knowledge assessment 

o Construction of an agronomic knowledge score from selected survey 
items 
o Analysis of relationships between knowledge, farming experience, and 
other participant characteristics 

7. Programme and implementation insights 

o Satisfaction drivers 
o Training material engagement 
o Post-training support 
o Expectation and challenge patterns 
o Farming impact and market access 
o Future support requirements 

Key Findings 

Training and learning

• Participants reported substantial improvement in their understanding of 
container farming, with a mean training-improvement score of 3.75/5. 
• Material coverage was weaker, with a mean score of 3.10/5. 
• The mean frequency of revisiting training materials was 2.39/5, suggesting 
limited continued engagement with the materials. 

Satisfaction and support

• Support accessibility and ease were strongly associated with overall 
satisfaction (Spearman ρ = 0.63, p < 0.001). 
• Satisfaction differed significantly across training sites. 
• Mangoro had the highest reported satisfaction score among the sites 
examined. 

Knowledge and application

• Farming experience was positively associated with agronomic knowledge. 
• Age was positively associated with application of knowledge, while farming 
experience was not significantly associated with application. 
• This highlighted a potential knowing–doing gap: factors associated with 
what participants know were not necessarily the same factors associated with 
what they apply. 

Farming outcomes and market access

• 83.4% of participants reported that their harvest provided at least some 
household food sufficiency. 
• Only 32.3% believed container farming was a practical solution for the future 
of agriculture in their area. 
• The analysis indicated an important disconnect between production outcomes 
and perceptions of economic sustainability. 
• Ability to sell surplus was associated with perceptions of the future viability 
of container farming, highlighting market access as an important 
programme consideration. 

Future support 

The most requested additional support services included: 
1. Financial assistance / microloans 
2. More advanced training 
3. Access to markets 
4. Additional farming materials 
5. Cooperative group formation 
6. Mentorship 

Programme Recommendations 

The analysis suggested several areas for consideration by the programme:

• Strengthen the depth and practical usefulness of training materials. 
• Encourage continued use and revisiting of training materials after training. 
• Strengthen post-training support and make it easier for participants to access 
assistance. 
• Consider differentiated training pathways for participants with different levels 
of farming experience. 
• Incorporate market access, pricing, negotiation, cooperative selling, and basic 
farm-record practices into future programming. 
• Consider financial support mechanisms where lack of capital is an important 
barrier to participation or expansion. 
• Use both age and farming experience when designing peer-support or mentor
mentee approaches rather than relying on farming experience alone. 
These recommendations are intended as analytical findings for programme 
consideration; implementation of recommendations was outside the scope of the 
project. 

Tools and Technologies 
• Python 
• Pandas 
• NumPy 
• Matplotlib 
• SciPy 
• Statsmodels 
• GeoPandas 
• Shapely 
• Squarify 
• Jupyter Notebook 

Reproducibility 
The notebook contains the data-cleaning, transformation, statistical analysis, and 
visualization workflow used for the project. 
To reproduce the analysis, install the required Python packages and provide an 
appropriately anonymized version of the survey dataset in the expected project 
location. 

Project Scope and Limitations

The analysis is based on participant self-reported survey responses. Important 
limitations include: 
• Self-reported responses may be subject to response bias. 
• The survey provides a snapshot of participant experiences rather than a 
longitudinal assessment. 
• Findings are specific to the surveyed BFWAI participants and should not 
automatically be generalized to broader populations. 
• External factors that may influence farming outcomes were not directly 
measured. 

Acknowledgements

This project was conducted through Statistics Without Borders (SWB), Project 
297, in collaboration with the Beellahy Foundation. 
The project was designed to generate evidence on participant experiences, training 
effectiveness, satisfaction, agricultural knowledge, farming outcomes, and future 
support needs. 
