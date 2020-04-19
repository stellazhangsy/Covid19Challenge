# COVID 2019 Challenge - Who's Hiring
![COVID 19 Challenge](https://user-images.githubusercontent.com/57570355/79680068-767f9c80-81c0-11ea-873a-0db9a7681046.jpg)


During the special time period of Corona Virus pandemic, it has been especially tough for graduating students and professionals to successfuly land a job. We want to take the initiative to offer help by providing strategic recommendations in job search and accepting offers. Through examining the company's demographic information and funding stauts, we build machine learning models with H2O framework targeting at predicting the future hiring status of companies in the job market in hope to mitigate risks of receiving offer revokes and maximize job search opportunity efficiency during such a hard time.

Here is our presentation slides outlining our key findings and techniques:https://docs.google.com/presentation/d/1YMKYkbKYqozCvDENr0-M3S9cd15C8SJhXGpVFj_Mb3Q/edit

Business Case
Covid-19 pandemic has caused layoff industry-wide, and even the most high-flying startups are feeling the effects of the virus. Layoffs have happened at companies like Bird, ZipRecruiter and ClassPass. As MSBA students are actively looking for jobs currently, we hope our project can provide students with some insightful ideas as which are currently the hardest-hit industries also give recommendation in terms of which companies are likely to freeze hirings in the future based on our model so that we can optimize our job hunting strategy.

=============

Data Source
Data Source are mainly pulled from the below sources:
Company Hiring Status:Candor
Company demographics information and funding status: Crunchbase

=============
Prediction Model
H2O AutoML frame work is utilized to predict the hiring status of companies with their investment, funding information and demographics information including industry, age etc.

Best Performace model: Gradient Boosting Machine (GBM)
False Positive Rate: 3.22%
F1 Score: 94.57%
Gini Index: 97%

=============
Recommendations
Based on the modeling results, we reccommend that job seekers keep in mind the follow suggestions: 

For job seekers:
Seek companies already reached round B of funding
Consider companies with longer operating history
Business-Facing Companies, Finance and Security Industry are promising

For policy makers and state governors:
Keep an eye on vulnerable industries, consider subsidizing Customer-facing education, retail, and social media industries
Encourage states to diversify industries

