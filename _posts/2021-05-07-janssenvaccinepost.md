---
layout: post
title: "Janssen COVID-19 Vaccine"
date: 2021-05-07
excerpt: "As of April 13th 2021 the Janssen COVID-19 vaccine administration was paused to the public in the United States. This was then resumed on the 23rd. In this post I try to explain and understand how many 'missed' doses could have been given out during this time. Furthermore, what were the complications of not having these doses administered to the general public?"
tags: [update]
comments: false
---

## Hypothesis  
The temporary halt in distribution of the Janssen COVID-19 vaccine led to more hospitalizations and deaths compared to the amount of people who had vaccine complications.  

* The complications mentioned are those that led to the pause of the vaccine distribution. These complications are elaborated on further in the document.  

This issue has similar notes as the problem with short-term climate change effects. Most citizens are more worried about smaller short-term complications rather than the larger issue that continues to grow.  

---

## Background

Name: JNJ-78436735  
Type: [Viral-Vector Vaccine](https://www.cdc.gov/coronavirus/2019-ncov/vaccines/different-vaccines/viralvector.html)  
One-Shot Vaccine  

### Possible Side Effects    
-Injection Site  
1. Pain
2. Swelling
3. Redness    

-Body Reactions    

1. Tiredness
2. Headache
3. Muscle Pain
4. Chills
5. Fever
6. Nausea

The Janssen vaccine has been 66.3% effective in clinical trials with the most protection arriving two weeks after vaccination  
This is considered having a high efficacy at preventing hospitalization and death  

### Vaccine Efficacy  
Per Medical News Daily, vaccine efficacy is  
> The percentage reduction in a disease in a group of people who ahve received vaccination in a clinical trial  
This is different from *effectiveness* which tells us how well a vaccine works under real conditions (outside of clinical trials)  

---

## Reasoning

Early April 2021 the Centers for Disease Control and Prevention (CDC) and the Food and Drug Administration (FDA) recommended a pause in the Janssen COVID-19 Vaccine.  
The vaccine was paused due to "reports of \[a] small number of women in the US who developed a rare and severe type of blood clot within two weeks [of recieving the vaccine]"

Per the CDC and FDA, distribution of the vaccine were being administered again in late April (23rd) after just over one week.  

Putting this in perspective, the vaccine was first given emergency use authorization on February 27th 2021. The vaccine was then paused on April 13th and resumed April 23rd.  

![Date Visualization](/assets/img/DateVisualization.png)

The main purpose is to understand how many people could have been vaccinated and hypothetically protected from COVID-19 comlications over the dashed blue period of time (April 13th-23rd)  

---

## Data

Per the [NY Times](https://www.nytimes.com/interactive/2021/world/covid-vaccinations-tracker.html) as of May 7th, 2021...    

251,973,752 doses of vaccine have been administered   
* This includes all three approved vaccines at the time  

The Janssen Vaccine has been administered to 15 countries with the US being included    

![Janssen Country](/assets/img/jandjcountries.png)

According to the [CDC Covid-19 Vaccine data tracker](https://covid.cdc.gov/covid-data-tracker/#vaccination-demographic) the US COVID Vaccine Administration for the Janssen vaccine has reached 8,739,657 vaccines administered. This information is as of May 7th 2021 at 8PM Eastern Time.  

During the pause from April 13th to April 23rd there were approximately 400-450 thousand COVID-19 reported cases per week    


Continuing from information gathered by the New York Times the Janssen vaccine daily reported doses was at its highest when paused in early April  

![Vaccine Pause Chart](/assets/img/VaccinePause.png)

This means that the vaccine was being allocated daily to approximately 4.947 million people per seven-day average. From this data we will consider two separate cases  

Case 1: The vaccine would see no increase or decrease in vaccine administration during this time period. This means that there would be a linear relationship of approximately 4.9 million allocated vaccines per seven-day average over this time period.   
Considering a stark decrease in the amount of doses administered over the pause of the Janssen vaccine there was a notable decrease in the amount of vaccines being administered over the time showing a decrease to and average of 700,000 delivered per day on this seven-day average      

Here is the visualized data from the [CDC](https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/w9zu-fywh)...    

![Data Visualization](/assets/img/VaccineDistribution.png)  

Taking this information in this case we can conclude that over the 10 day pause we would have allocated 49 million vaccines. Deducting the vaccines that were administered over this time (~7 million), there would have been and additional 42 million vaccines allocated during this time period.  

This means that as of May 07 2021, we would have been able to deliver a total of approximately 371,840,055 vaccine doses.  

![Total Doses](/assets/img/TotalVaccineDoses.png)

Case 2: This case takes the same information from the previous but shows what it would have been like in a good scenario where the vaccine doses continued to rise.   
Considering the rate of increase in vaccine doses the slope reaching April 13th was approximately 2.461. This means that we were increasing the amount of allocated vaccines doubly per week on this seven day average.  

![Slope](/assets/img/SlopeGraph.png)
![Slope Continuation](/assets/img/SlopeIncrease.png)

Therefore, it can be measured that we would have been experiencing approximately 9,528,885 doses per day over this seven-day average. Considering this increase we are left with a simple equation to understand how many doses would have been administered.    

The bounds of our integral are 0 to 10 (days) and our equation will use a simple linear y = mx + b fit  

Our equation is [y = 2.461x + 1.118 * 10^7]  

![Equation](/assets/img/Equation.png)  

Therefore, we would have allocated 111.8 million vaccines over this time period. Deducting what we did allocate during this time period, that means we would have an additional 104.8 million allocated Janssen vaccines.   

This totaled as before would give us 434,640,055 delivered vaccines as of [May 8th, 2021 at 6:00am](https://covid.cdc.gov/covid-data-tracker/#vaccinations)  

---

## Closing Statement

It has been found that from both cases there would have been 42 million to 105 million more allocated Janssen COVID-19 vaccines allocated if there were no pause during the middle of April 2021.  
Considering the 66.3% clinical efficacy of the vaccine this means that there was a chance to prevent an additional 27.8 - 70 million people from being hospitalized or killed by the COVID-19 disease.  

---

Sources:

Johnson & JOHNSON'S Janssen Covid-19 Vaccine overview and safety. (n.d.). Retrieved May 09, 2021, from https://www.cdc.gov/coronavirus/2019-ncov/vaccines/different-vaccines/janssen.html  

CDC COVID Data Tracker. (n.d.). Retrieved May 09, 2021, from https://covid.cdc.gov/covid-data-tracker/#vaccination-demographic  

Morris, S. (2021, April 30). Johnson &amp; Johnson Janssen Covid-19 Vaccine PAUSE: Johns hopkins Medicine. Retrieved May 09, 2021, from https://www.hopkinsmedicine.org/coronavirus/covid-19-vaccine/jj-vaccine-pause.html  

Path to normality - covid-19 vaccine projections. (n.d.). Retrieved May 09, 2021, from https://covid19-projections.com/path-to-herd-immunity/#comparison-projected-vs-actual  

The New York Times. (2020, December 17). See how the Vaccine rollout is going in your County and state. Retrieved May 09, 2021, from https://www.nytimes.com/interactive/2020/us/covid-19-vaccine-doses.html  

Holder, J. (2021, January 29). Tracking coronavirus VACCINATIONS around the world. Retrieved May 09, 2021, from https://www.nytimes.com/interactive/2021/world/covid-vaccinations-tracker.html  

COVID-19 vaccine Distribution allocations by jurisdiction - JANSSEN. (n.d.). Retrieved May 09, 2021, from https://data.cdc.gov/Vaccinations/COVID-19-Vaccine-Distribution-Allocations-by-Juris/w9zu-fywh    


CDC COVID Data Tracker. (n.d.). Retrieved May 09, 2021, from https://covid.cdc.gov/covid-data-tracker/#vaccinations  
