# Police-Killings-Project
Here is a draft documentation of your data analysis process, assumptions, methodologies, and findings based on the provided code:

**Introduction**

This project involves an analysis of fatal police shootings data in the United States. The dataset contains information about incidents of police shootings, including details about the victims, locations, armed status, and other relevant factors. The primary objective is to gain insights into the patterns and characteristics of these incidents, with a focus on exploring potential disparities and factors that may influence the outcomes.

**Data Preparation**

The dataset was loaded into a pandas DataFrame, and necessary data cleaning and preprocessing steps were performed:

1. Missing values were handled by either filling them with the mean age or assigning specific values (e.g., 'unknown' for missing race information).
2. Categorical variables like race, gender, and armed status were mapped to more descriptive labels for easier interpretation.
3. New columns were created, such as 'day_of_incident' and 'month_of_incident', to facilitate temporal analysis.

**Exploratory Data Analysis (EDA)**

The EDA phase involved examining various aspects of the data through visualizations and summary statistics:

1. Age distribution: The victims' ages ranged from 6 to 91, with a mean age of 37.1 and a median of 36. The distribution appeared slightly right-skewed, with more victims clustered around the lower end of the age range.

2. Temporal patterns: The analysis revealed higher numbers of police killings during the winter and spring months, particularly in March, January, and February. Additionally, there was a significant decrease in incidents during 2020, potentially attributed to the COVID-19 pandemic.

3. Gender and race distribution: The vast majority of victims were male (95.57%), with females accounting for 4.39%. In terms of race, White individuals comprised the highest proportion (46.38%), followed by Black (24.32%), Hispanic (16.9%), and Asian (1.74%) victims.

4. Manner of death: The most common manner of death was being shot (95.01% of cases), with a smaller percentage involving both shooting and Tasering (4.99%).

5. Armed status and threat levels: A substantial portion of the victims (93.41%) were armed, with guns being the most prevalent weapon. The police perceived the majority of victims as posing an "attack" threat level, regardless of their armed status or race.

**Methodology**

The analysis primarily relied on exploratory data analysis techniques, including:

1. Data visualization: Various plots were created using matplotlib and seaborn libraries to visualize distributions, frequencies, and relationships between variables.
2. Summary statistics: Descriptive statistics, such as counts, percentages, means, and medians, were calculated to quantify patterns and trends.
3. Cross-tabulations: Contingency tables were generated to examine the relationships between categorical variables, such as race, armed status, and threat levels.

**Results and Findings**

Key findings from the analysis include:

1. Temporal patterns: Police killings peaked during the winter and spring months, with a noticeable decrease in 2020, potentially due to the COVID-19 pandemic.

2. Demographic disparities: While the majority of victims were male, there were notable racial disparities, with Black individuals being perceived as posing an "attack" threat at higher rates compared to other racial groups.

3. Armed status and threat levels: The police perceived the majority of victims as posing an "attack" threat, regardless of their armed status or race. However, individuals armed with guns were perceived as an "attack" threat at significantly higher rates compared to those who were unarmed or armed with other weapons.

4. Mental illness and fleeing: Victims exhibiting signs of mental illness did not flee at higher rates compared to those without mental illness.

5. Body camera impact: The use of body cameras by police officers was associated with lower rates of police killings overall. However, when body cameras were used, certain racial groups (Asian, Black, and Hispanic) experienced higher rates of police killings compared to White individuals.

Here are some potential conclusions and recommendations based on the analysis:

**Conclusions**:

1. **Racial Disparities**: The analysis revealed concerning racial disparities in fatal police shootings. Black individuals were perceived as posing an "attack" threat at higher rates compared to other racial groups, even when accounting for armed status. This suggests the presence of potential racial biases that warrant further examination.

2. **Mental Health and Vulnerability**: While victims exhibiting signs of mental illness did not flee at higher rates, the data indicates that their vulnerability may not have been adequately accounted for during encounters with law enforcement.

3. **Armed Status and Use of Force**: The findings suggest that the presence of a weapon, particularly a gun, significantly influenced the perceived threat level and the subsequent use of lethal force by police officers. However, the analysis also revealed instances where unarmed individuals or those with less lethal weapons were subjected to fatal shootings.

4. **Body Camera Impact**: The use of body cameras was associated with lower overall rates of police killings. However, when body cameras were present, certain racial groups experienced higher rates of fatal shootings compared to White individuals, indicating that the potential benefits of body cameras may not have been equally distributed across all communities.

5. **Temporal and Geographic Patterns**: The analysis identified specific temporal patterns, with police killings peaking during certain months and years. Additionally, geographic variations were observed, with some states and cities experiencing higher rates of fatal police shootings compared to others.

**Recommendations**:

1. **Implicit Bias Training and De-escalation Strategies**: Implement comprehensive training programs to address implicit biases, promote cultural competency, and enhance de-escalation techniques for law enforcement officers. This could help mitigate potential biases and improve interactions with individuals from diverse backgrounds, including those experiencing mental health crises.

2. **Stricter Protocols for Use of Force**: Review and strengthen protocols governing the use of lethal force, particularly in situations where individuals are unarmed or pose a low-level threat. Emphasize the prioritization of de-escalation tactics and the preservation of life whenever possible.

3. **Mandatory Body Camera Usage and Accountability Measures**: Mandate the use of body cameras for all law enforcement officers and establish clear accountability measures for incidents involving the use of lethal force. This can enhance transparency, facilitate thorough investigations, and promote public trust in law enforcement agencies.

4. **Community Engagement and Trust-Building**: Develop and implement strategies to foster positive community-police relations, such as community outreach programs, citizen advisory boards, and regular dialogue between law enforcement and diverse community members. Building trust and understanding can contribute to more effective policing practices and reduce potential conflicts.

5. **Data Collection and Ongoing Monitoring**: Establish robust data collection and monitoring systems to track and analyze incidents of police use of force, including non-fatal encounters. This data can inform evidence-based policies, identify areas for improvement, and facilitate ongoing monitoring of progress toward more equitable and accountable policing practices.

6. **Collaborative Efforts and Policy Reform**: Encourage collaborative efforts among law enforcement agencies, policymakers, community leaders, and subject matter experts to jointly develop and implement comprehensive policy reforms aimed at addressing the identified issues and promoting fair and equitable policing practices across all communities.

It is important to note that these recommendations should be tailored to the specific context and needs of the communities involved. Additionally, ongoing evaluation and refinement of policies and practices should be conducted to ensure their effectiveness and alignment with the goal of promoting public safety while upholding civil rights and human dignity.

**References and Appendices**

Data Source: https://www.kaggle.com/datasets/mrmorj/data-police-shootings

This documentation provides an overview of the data analysis process, key findings, and recommendations based on the provided code. It serves as a starting point for communicating the results to stakeholders and facilitating further discussions or actions related to the analysis of fatal police shootings.
