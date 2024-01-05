# Global Terrorism Analysis

## Table of contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitation](#limitation)
  
## Project Overview

This project seeks to offer a thorough examination of worldwide terrorism trends and patterns. Through the analysis of diverse facets of available data, my goal is to discern global terrorism trends, pinpoint the regions and countries most heavily impacted, assess the evolution of terrorism's impact over time, and formulate data-driven recommendations aimed at preventing or mitigating future terrorist attacks.

<img width="553" alt="Terrorism 1" src="https://github.com/Modupe-Adeniyi/Global-Terrorism/assets/151841781/c1575d3e-f69b-41da-8786-abaffbfa67c4">

<img width="461" alt="Terrorism 2" src="https://github.com/Modupe-Adeniyi/Global-Terrorism/assets/151841781/8a067e28-3e6d-4926-802b-4456bf230ba1">

## Data Sources

The central dataset employed in this analysis is the "Terrorism_Dataset.csv" obtained from Intern Career. This dataset encompasses comprehensive details about terrorist attacks on a global scale, including information on the date, location, attack type, weapons utilized, number of casualties, and the groups responsible.

## Tools

- Excel - Data Cleaning
- PowerBI - Data Analysis and Creating reports

## Data Preparation and Cleaning

During the preliminary preparation stage, I undertook the following activities:

1. Loading and inspecting data
2. Handling missing values
3. Cleaning and formatting data
4. Adjusting data types.

## Exploratory Data Analysis

EDA comprised investigating the dataset to address fundamental questions, such as:
- What is the trend in the number of terrorist attacks over time?
- Which countries were most frequently targeted?
- What were the patterns in attack types and the weaponry employed?
- What were the casualties based on regions?

## Data Analysis

Created calculated columns and measures using PowerBI, such as:

```Successful attack = CALCULATE(SUMX('Terrorism cleaned',IF('Terrorism cleaned'[Success attack count]="yes",1,0)))```


## Results

The analysis results are summarized as follows:
1. Between 1970 and 2017, there were 156,613 recorded attacks, peaking in 2014.
2. Iraq had the highest total attacks (22,133), showing a 213.28% increase compared to Colombia, the lowest.
3. Bombing/Explosion was the most frequent attack type, accounting for 50.29% of all attacks.
4. The "Unknown gang" group led in total attacks (74,848), constituting 87.08% of all attacks.
5. The Middle East & North Africa had the highest total fatalities (113,230), representing 33.82% of the overall sum.
6. Iraq accounted for 53.96% of the total sum of fatalities, with 67,858 recorded.
7. Iraq also had the highest number of wounded individuals among the top 5 countries.
8. Private Citizens & Property were the most targeted, with successful attacks ranging from 110 to 34,065.
9. The year 2016 saw the highest number of suicides (875), contributing to 14.36% of the total sum.
10. South Asia recorded the highest number of properties destroyed (18,193), surpassing Australasia & Oceania by 9,525.93%.

## Recommendations
- Preventive Measures for Peak Years: Given the peak in attacks in 2014, consider implementing enhanced security measures, intelligence sharing, and international collaboration during periods where a surge in terrorist activities is observed. This could aid in early detection and prevention.
- Counter-terrorism Strategies: Focus counter-terrorism efforts on addressing Bombing/Explosion incidents, which account for over 50% of attacks. Implement strategies such as improved surveillance, intelligence gathering, and community engagement to mitigate this prevalent threat.
- Targeted Country Interventions: Prioritize interventions in countries with the highest attack rates, such as Iraq. Tailor counter-terrorism strategies to address specific regional challenges, considering factors that contribute to increased vulnerability.
- Unknown Gang Analysis: Investigate and analyze the "Unknown gang" group to better understand its motives and operations. Enhance intelligence efforts to identify and counter emerging threats from lesser-known groups that still pose significant risks.
- Regional Collaboration for Fatalities: Given the disproportionate number of fatalities in the Middle East & North Africa, promote regional collaboration on security measures, intelligence sharing, and coordinated responses to effectively reduce casualties.
- Iraq-focused Initiatives: Develop and implement targeted initiatives in Iraq to address the substantial number of fatalities and wounded individuals. These could include investments in healthcare infrastructure, rehabilitation programs, and community support.
- Security Measures for Successful Attacks: Enhance security measures for Private Citizens & Property, which is identified as the target type with the highest number of successful attacks. This could involve community awareness programs, increased law enforcement presence, and improved surveillance.
- Mental Health Support: Recognize the importance of mental health support and intervention, especially in years with high suicide rates like 2016. Implement programs that address the psychological impact of terrorism and provide support for affected individuals and communities.
- Global Collaboration on Properties Destroyed: Given the significant property destruction in South Asia, encourage international collaboration to address this issue. Share best practices in infrastructure protection and disaster recovery to minimize the impact of such attacks.
- Monitoring and Early Warning Systems: Establish monitoring and early warning systems to detect emerging trends in suicide rates and promptly implement preventive measures. This can include mental health awareness campaigns and community-based support programs.

These recommendations aim to address specific challenges highlighted by the insights and promote a comprehensive and proactive approach to counter-terrorism efforts.

### Limitation
I had to eliminate duplicate values to ensure the accuracy of my conclusions drawn from the analysis.
