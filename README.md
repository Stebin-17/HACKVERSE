# HACKVERSE
To bring together aspiring CHRIST University Lavasa Campus developers and AI/ML enthusiasts to address real-world business problems. By participating in the hackathon, students will gain knowledge of the fundamentals, problem-solving techniques, and applications of Al. Participants must devise a solution and submit it to the judges, audience, and evaluators. To overcome challenges and ensure they have a diverse team, students should form a TEAM OF FOUR with individuals from different backgrounds.


**PROBLEM STATEMENT**

Several research on the factors influencing life expectancy have been conducted in the past,
taking into account demographic demographics, income composition, and mortality rates but, 
It was discovered that the impact of vaccinations and the human development index had not previously been taken into consideration. 
Additionally, a number of earlier studies used data from all the countries collected over the course of one year and multiple linear regression.
This provides incentive to develop a regression model based on a mixed-effects model and multiple linear regression while taking data from a period of 
2000 to 2015 for all the countries, in order to address both of the previously mentioned problems.
Hepatitis B, polio, and diphtheria vaccinations are also important to consider. In essence, this study will concentrate on elements connected to immunisation,
mortality, the economy, society, and other aspects of health. A country will find it easier to identify the predicting factor causing a lower value of
life expectancy as the observations in this dataset are based on multiple countries. This will assist in recommending to a nation which region should be prioritised 
in order to effectively raise the population's life expectancy.

**AIM**

The data-set aims to answer the following key questions:
1. Do all the features available in the dataset really affect the Life expectancy? What are the predictingvariables actually affecting the life expectancy?
2. Should a country having a lower life expectancy value(<65) increase its healthcare expenditure in order
to improve its average lifespan?
3. How does Infant and Adult mortality rates affect life expectancy?
4. What is the impact of schooling on the lifespan of humans?
5. Does Life Expectancy have positive or negative relationship with drinking alcohol?
6. Do densely populated countries tend to have lower life expectancy?
7. What is the impact of Immunization coverage on life Expectancy? 
- Build life expectancy prediction model 
- Build a simple UI using either flask or Django or any other


**METHODOLOGY**


![Beige Colorful Minimal Flowchart Infographic Graph](https://user-images.githubusercontent.com/114398530/204119671-877a3b41-6695-4c92-8d3c-6fca47dda677.png)



**RESULT AND DISCUSSION**

The dataset is available in the following website: 

https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who

The code for EDA and Modeling is in HACKATHON_MODELLING.ipynb and VISUALIZATION.ipynb


**PowerBI Dashboard:**

<img width="576" alt="snip of life expectancy" src="https://user-images.githubusercontent.com/114398530/204119732-1acc4c8b-5a5c-421f-9f5c-6909d3740979.png">


**Presentation for the Analysis can be accessed using the below link:**

https://prezi.com/view/HCYe2ryfVgAJ8KYMURG2/

**Project report for the analysis can be accessed using the below link:**

https://www.canva.com/design/DAFTGsALR7A/ThRuXJi1VC4HHwE940_W2Q/view?utm_content=DAFTGsALR7A&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

**MODEL DEPLOYMENT**
Project Structure
This project has four major parts :

1.life.py - This contains code fot our Machine Learning model to predicting life expectancy based on training data in 'Life_Expectancy_Data' file.
2.app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.
3.templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted life expectancy contains after.html and     index.html
4.Static - Contains all the images used for modelling 
--Navigate to URL: http://localhost:5000

