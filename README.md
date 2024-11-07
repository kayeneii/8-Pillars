# 8-Pillars
This is an analysis of the data obtained from a survey conducted on the Ipetu/Ife Community in Osun State Nigeria. This owner has all rights.

## The 8 Pillars of Positive Peace through the Lens of the Ipetu/Ife Community in Osun State Nigeria.

### Introduction
---
This project was designed to research and analyze the Ipetu/Ife Community under the lens of the [Institute for Economics and Peace](https://www.economicsandpeace.org/) Positive Peace Framework, in order to identify points that can be leveraged to create systemic, sustainable and positive change. The goal is to explore the strengths, weaknesses, and opportunities across the 8 Pillars of Positive Peace in the Ipetu/Ife Community.

The Ipetu/Ife Community is located in Ife North Local Government in Osun State, Nigeria.


### Overview 
---
**What is Positive Peace?**
  
  Positive Peace is the presence of conditions that prevent violence and conflict from arising in the first place. According to the IEP, Positive Peace addresses the underlying factors that sustain peaceful and prosperous societies, such as equitable resource distribution, functioning government, and social cohesion. It differs from *Negative Peace* which simply refers to the absence of war. Through its empirical research and data-driven approach, the IEP developed a Positive Peace Framework to assess and develop positive peace in communities, organizations, and States. This birthed the 8 Pillars of Positive Peace, through which this research and analysis was conducted.

**What are the 8 Pillars of Positive Peace?**

These 8 pillars of positive peace represent the essential factors that contribute to peaceful and resilient societies. They are: 
   1. Well-Functioning Government
   2. Equitable Distribution of Resources
   3. Free Flow of Information
   4. Acceptance of the Rights of Others
   5. Good Relations with Neighbours
   6. High Levels of Human Capital
   7. Low Levels of Corruption
   8. Doing Business Environment

The 8 Pillars of Peace are interconnected, in that a change in one pillar leads to a change in the other pillars.
For instance, a community, organization or state that adopts a well-functioning system of government. A well-functioning government is one with institutions that execute governance and deliver public services efficiently. These institutions represent the government's recognition and acceptance of the rights of its people, including the right to hold the government accountable through the free flow of information (top-bottom and bottom-top). This free flow of information will provide channels for its people to demand and equitably receive resources that will further increase human capital across various social strata and create sound business environments where the corruption level is reduced. As a result, the relationship with neighbours is improved.

Therefore, it can be asserted that a change in any pillar of positive peace would set off a chain of reaction in the others.


### **Data Source**
---
The data used for this projuct was collected through an [online survey](https://forms.gle/6oFXC5cJRzTQyUGy9) with participants from said community. 


### **Methods**
---
The methods used for this project include:
- **Google Forms:** This was used in conducting an online survey of students and residents in the Ipetu/Ife Community. The survey comprised of a series of 8 questions with Yes/No options.

- **Google Sheets:** This was used in collecting said data.
  
- **Microsoft Power BI:** This was used for data processing, analysis and visualization.
  1. **Data Processing:**
        * Data loading and validation
        * Data cleaning
        * Data transformation
 
  2. **Data Analysis:**
     The data obtained was analyzed to derive answers to questions like:
        * How strong is 'Pillar 1: Well-Functioning Government' in the community?
        * How strong is 'Pillar 2: Equitable Distribution of Resources' in the community?
        * How strong is 'Pillar 3: Free Flow of Information' in the community?
        * How strong is 'Pillar 4: Acceptance of the Rights of Others' in the community?
        * How strong is 'Pillar 5: Good Relations with Neighbours' in the community?
        * How strong is 'Pillar 6: High Levels of Human Capital' in the community?
        * How strong is 'Pillar 7: Low Levels of Corruption' in the community?
        * How strong is 'Pillar 8: Sound Business Environment' in the community?
        * What is the strongest pillar of positive peace in the community?
        * What is the weakest pillar of positive peace in the community?
        * What are the rankings of the 8 Pillars of Positive Peace in the community?


     During the analysis, additional columns were created using DAX functions. Conditional Columns such as,
     Pillar 1 Result
     ```DAX
     If Pillar 1 equals Yes Then 1
     Else 0
     ```
        *This was subsequently repeated for Pillar 2-8 Results.*

     Pillar 1 Strength
     ```DAX
     If Pillar 1 equals Yes Then 1
     Else 0
     ```
        *This was subsequently repeated for Pillar 2-8 Strengths.*

  3. **Data Visualization:**
      * Donut Charts were used to illustrate the stregth and weakness of each pillar,
      * Cards were used to illustrate the strongest and weakest pillars in the community,
      * Bar Charts were used to illustrate pillar rankings according to strength in the community.

- **GitHub:** Data documentation and reporting.


### **Findings and Recommendations**
---
   -Findings: These findings were derived from the data collected from students and residents during the survey, to gauge their perception of the strength of the 8 pillars of Positive Peace in the community.
        * 43.8% think public services (schools, hospitals, security i.e. the police force) function effectively in their community.
        * 37.5% think community resources such as housing, jobs, healthcare, and education, are distributed fairly among all groups.
        * 56.3% trust the information shared by local news sources.
        * 56.3% feel that everyone in the community is treated fairly irrespective of tribe or religion.
        * 62.5% believe people in their community generally get along well.
        * 50% say there are good opportunities for skill development in their community.
        * 31.3% think the community leaders act honestly.
        * 43.8% say it is easy for new businesses to start and operate in their area.
        * Pillar 5, Good Relations with Neighbors is the strongest pillar in the community. 
        * Pillar 7, Low Levels of Corruption is the weakest pillar in the community. 
        * Pillar 3 and 4 rank second strongest with Pillar 6 coming in third. Pillar 1 and 8 rank third weakest and Pillar 2 is the second weakest pillar in the community.

   - Recommendations: The following recommendations are based on the findings above,
        * an action plan should be drawn up to address the factors affecting the conditions that foster positive peace in the community,
        * community and stakeholder analysis should be conducted for a better understanding of these factors,
        * a strategy should be drawn for improving and ensuring the sustainability of these 8 Pillars across the Ipetu/Ife Community,
        * collaboration between the various stakeholders should be encouraged to facilitate and implement development initiatives across social, economic, political and technological grounds,
        * further research should be conducted to see how the strong pillars of positive peace in the community can be leveraged to improve others.


### **Visualizations**
---
![Data Viz](https://github.com/kayeneii/8-Pillars/blob/main/Ipetu_Ife-Community-Context-Analysis-Viz.png)


### **Conclusion**
---

