# Gender gap in IT

I am a women, and I do not work in technology... yet. I am a scientist by nature and by formal education, and a data science enthusiast. Since I started being more interested in data science, and technology, in general, I became very aware of the gender gap. I never really noticed it. I am sure a lot of people don't, until it's pointed out to them. It's just the picture you have been exposed to for way too long, to notice there is something wrong with it. 

Almost 4 years ago, I got involved in a few non-profit organisations here in Hamburg whos main aim is closing this gender gap in technology. I identify with this issue, mainly because technology has taken off and has infiltrated every area of our life. It is unfair to leave half of population out of this process.

![](https://github.com/milbajagic/StackOverflow_2017_survey_analysis/blob/master/photography-of-a-woman-using-laptop-1024403.jpg)

## Seeing the gender gap in the Stack Overflow data

Stack Overflow, a question and answer site for professional and enthusiast programmers, conducts a survey of people on the site, covering all sorts of information like programming languages, salary, code style and various other information including gender and race. In 2017 they amassed more than 64,000 responses fielded from 213 countries (available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data)). 

Using descriptive statistics, I wanted to explore this data set and search for possible trends women in tech have in common. Maybe there is a secret we are all missing and only data can reveal. 

## Reproducing the gap
First step in any exploration of data should be reproducing what is already known. Unsurprisingly, Stack Overflow data had 11664 males, 970 females and 169 as other/gender-non-conforming, amounting to 90% male and 7.5% female. It's always nice to see reproduced results, which are the basis for my further work. I took only the data of members who idetify as female for further analysis. 

## What else could be learned from this data set?
First question I asked is "do countries play a role?" 

![alt text](https://github.com/milbajagic/StackOverflow_2017_survey_analysis/female_coutry.png)

According to the analysis of the Stack Overflow data, great majority of the females are from the United States, followed by India, Canada, Germany and Poland. First I thought this might be due to population size, but upon closer examination of population (USA: 329mil, UK: 63mil India: 1.3bil, Canada: 37mil, Germany: 83mil and Poland around 40mil), there is no direct correlation. Does this mean that the USA has the highest percentage of women in tech? It's hard to make that conclusion based on this analysis alone. What we need to take into consideration is also the ratio of men and women in each country, and which percentage of total female population is represented in this survey. Additionally, the question in the survey asked for the country of residence, which doesn't account for immigration factor.

![alt text](https://github.com/milbajagic/StackOverflow_2017_survey_analysis/female_race.png)

If we take a look at the race distribution among the females represented in the survey, we see that majoriy is white/european. This is in agreement with what we saw in the analysis of countries, since most females in this data set come from USA and Europe. 

Another factor that might play a role in education. Are only highly educated women in tech? Analysis shows that most of them have Bachelor's degree (50%), followed by Master's (25%). Women with PhD are 5% and professional degree only 1%. This higher education doesn't seem to be the key for a career in tech.

## Conclusion



