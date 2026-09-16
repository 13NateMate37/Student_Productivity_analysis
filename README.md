# Student Productivity Analysis

**Student Productivity Analysis** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content
This dataset is a synthetic example, based upon real dataset patterns of an array of students and curated aspects that affect producitivity.

* These aspects include:

* Hours of sleep per night. 
* Total screen time in hours.
* Total social media consumption in hours.
* Part-time employment. 
* How much physical activity in hours the student engages in.
* Prrior Grade Point Averages.
* A total Productivity Score and Performance categorisation.


## Business Requirements

* To investigate and identify which lifetstyle factors have a strong positive effect on student productivity and performance.

* To compare performance patterns across demographic groups in a respectful, evidence-based way, while avoiding unsupported assumptions.

* Identify students who may be at risk of lower performamce based upon their habits and lifestyle.

## Broader Applications of Data Analytics in Education

Data analytics can be applied across education to support both students and educators. Examples include identifying students who may require additional support, monitoring academic performance and attendance, evaluating teaching methods, and identifying patterns in student engagement.

Analytics can also support planning and decision-making by helping educational institutions understand student outcomes, allocate resources and develop more targeted learning support.

## Potential AI Solution

A potential AI solution would be an early-warning system for identifying students at risk of lower performance. A machine-learning model could analyse factors such as previous grades, sleep, screen time and physical activity to identify patterns associated with lower performance.

Students identified as potentially at risk could then be highlighted for further review and additional support. The model should support, rather than replace, educator judgement, as predictions may contain errors or bias.

## Hypotheses and how to validate? 

### Hypothesis 1: Gender and Academic Performance
- **Prediction**: Female students will achieve higher productivity scores and performance ratings than male students.
- **Validation method**: Compare average productivity scores and performance distribution across gender groups using descriptive statistics.
- **Expected output**: Bar chart or box plot comparing productivity by gender; mean and median values for each group.

### Hypothesis 2: Sleep Duration Impact
- **Prediction**: Students sleeping 7-9 hours per night will have higher productivity scores and better performance ratings compared to those sleeping significantly more or less.
- **Validation method**: Group students by sleep duration ranges (e.g., <7 hours, 7-9 hours, >9 hours) and compare average productivity scores.
- **Expected output**: Bar chart showing productivity by sleep range; correlation coefficient between sleep hours and productivity score.

### Hypothesis 3: Screen Time and Social Media Impact
- **Prediction**: Higher total screen time and social media consumption will negatively affect student productivity scores and performance ratings.
- **Validation method**: Calculate correlation between screen time/social media usage and productivity score; compare performance across low/medium/high usage groups.
- **Expected output**: Scatter plots showing relationships between screen time and productivity; correlation coefficients for both metrics.

### Hypothesis 4: Physical Activity Benefit
- **Prediction**: Students who engage in regular physical activity will demonstrate higher productivity scores and better performance ratings than those with minimal or no physical activity.
- **Validation method**: Compare average productivity scores across physical activity levels; examine correlation between exercise hours and performance.
- **Expected output**: Bar chart or scatter plot showing productivity by activity level; correlation analysis results.  


## Project Plan

As my first data analytics project, I followed a structured approach to move from the original dataset towards answering the defined business requirements.

1. Ideation and Planning - Generative AI, including ChatGPT, was used during the early ideation stage to explore potential business requirements, hypotheses and approaches to analysing the student productivity dataset. The suggestions were reviewed and used to help shape the final project direction.

2. Data Collection - Source the student productivity dataset and review the available variables to understand what could be investigated.

3. Data Exploration - Inspect the dataset using methods such as ".info()", ".describe()" and ".nunique()" to understand its structure, data types, distributions and identify potential data-quality issues.

4. Data Cleaning and Transformation - Create a copy of the raw data for cleaning and transformation while preserving the original dataset. The cleaned dataset was then exported for use during analysis.

5. Data Analysis and Visualisation - Use descriptive statistics and appropriate visualisations to explore patterns and relationships within the student data and investigate the project's hypotheses.

6. Interpretation - Review the visual and numerical results to determine what they suggest about student productivity and performance, while avoiding unsupported assumptions or claims of causation.

7. Communication - Present the findings through clear visualisations and supporting narrative, linking the results back to the original business requirements.

This process helped me understand how the stages of a data analytics project connect, from initial ideation and preparing raw data through to analysing and communicating meaningful findings.

## Analysis techniques used

The project followed an ETL, exploratory analysis and visualisation approach. The dataset was first inspected using methods such as ".info()", ".describe()" and ".nunique()" to understand its structure, data types and distributions before cleaning and transformation.

Descriptive statistics and data visualisations were then used to investigate the business requirements and hypotheses. Bar charts and box plots were used to compare groups, while scatter plots and correlation analysis were used to explore relationships between numerical variables. These methods were chosen because they provided a clear way to identify patterns in student productivity and performance.

The analysis was limited by the synthetic nature of the dataset. Although the data reflects realistic student patterns, the findings should not be assumed to represent a real student population. The analysis also identifies associations rather than causation, meaning that a relationship between a lifestyle factor and productivity does not prove that one directly causes the other.

Generative AI tools, including ChatGPT and GitHub Copilot, were used to support project ideation, troubleshooting, code optimisation and data storytelling. AI-assisted outputs were reviewed against the project's data and analysis before being included.

## Development Roadmap

Development Roadmap

As this was my first data analytics project, many of the tools and techniques used were new to me. Key challenges included learning how to clean and explore a dataset, selecting suitable visualisations, interpreting the results correctly, and understanding how each stage of the analysis connected to the business requirements.

These challenges were addressed through experimentation, course material, documentation and AI-assisted troubleshooting. Completing the project gave me a stronger understanding of the overall data analysis process and highlighted areas for further development.

Going forward, I would like to build my knowledge of statistical analysis, machine learning and interactive dashboards, while continuing to improve my confidence in interpreting and communicating data-driven findings.

## Main Data Analysis Libraries

Main Data Analysis Libraries

This project provided my first practical experience of using Python libraries for data analysis and visualisation.

- Pandas - Used to load, inspect, clean and transform the dataset, as well as produce descriptive statistics and prepare data for analysis.
- Matplotlib - Used to create and customise visualisations to explore patterns within the student data.
- Seaborn - Used to create statistical visualisations, including box plots and scatter plots, making relationships and differences between groups easier to explore.

Using these libraries throughout the project helped develop my understanding of how Python can be used to move from raw data through to analysis and visual communication.

## Credits

Generative AI

ChatGPT (OpenAI) and VSCodes nuilt in Copilot were used to assist with project ideation, troubleshooting and code optimisation, and to develop narrative storytelling commentary from the project's data visualisations. All AI-assisted content was reviewed against the analysis before being included in the project.
