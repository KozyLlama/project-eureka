Trends of Health Factors on Insurance Claims
================
KozyLlama
2023-01-24

## Introduction

“Needing insurance is like needing a parachute. If it isn´t there the
first time, chances are you won´t be needing it again.”

How insurances operate has been often times fascinating to me in the way
of when eventually filling a claim after months or even years of
payments, the use of the service may end up costing you with an
increased rate.

That aside, the impact of health factors such as age, Body Mass Index
(BMI) and blood pressure on insurance claims serves as a fun project
that presents a way to gain a better understanding and insights on the
operation of insurances. The following points will be investigated to
grasp the goal:

1.Identifying trends in insurance claims based on age, gender, BMI, and
blood pressure.

2.Investigating correlations between health traits (such as BMI and
blood pressure) with the likelihood of making a claim

    ## Rows: 1340 Columns: 11
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (4): gender, diabetic, smoker, region
    ## dbl (7): index, PatientID, age, bmi, bloodpressure, children, claim
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

## Overview

Relationship between age, gender and claims:

An immediate observation is the abundance of female claims over age of
50 while also a lack of claims for females under the age of 25.
Interesting enough, there is an inverse with the males, lack of claims
over the age of 50. This presents an engaging point to follow during the
investigative analysis on if an answer could be determined for the lack
of male claims over the age of 50.

![age, gender and claims-1](https://user-images.githubusercontent.com/119358123/214977581-51714e11-8d3c-4732-ab87-1b3575fc7b63.png)
<!-- -->

## Health Factor: Body Mass Index

**Underweight Body Mass Index**

An underweight Body Mass Index (BMI) is scored at a value of 18.5 or
under.This severity shows a minor impact on insurance claims, making the
relationship between an underweight BMI and claims close to be
negligible.

![bmi under weight-1](https://user-images.githubusercontent.com/119358123/214977748-226f497b-88da-4e4e-950b-d6f0cf086a89.png)
<!-- -->

**Normal Body Mass Index**

A normal Body Mass Index (BMI) is scored at a value between 18.5 and
24.9.This health factor shows an increase in sample size of insurance
claims, approximately 20 times more than an individual with an
underweight BMI yet this range accounts for a small portion of total
claims.

![bmi normal weight-1](https://user-images.githubusercontent.com/119358123/214977821-26203a50-174b-4e76-95cb-88d4cb31eea2.png)
<!-- -->

**Overweight Body Mass Index**

An overweight Body Mass Index (BMI) is scored at a value between 25 and
29.9.This severity shows a similar impact on insurance claims in
comparison to the normal BMI group. Only difference being a couple of
larger “outlines” which thereby increases the average insurance claims
of this subgroup when compared to the aforementioned group.

![bmi over weight-1](https://user-images.githubusercontent.com/119358123/214977849-df051c84-1d3e-46ff-b683-6de856481536.png)
<!-- -->

**Obese Body Mass Index**

An obese Body Mass Index (BMI) is scored at a value over 30.This
subgroup not only accounts for a larger percentage of all claims but is
also responsible for higher insurance claim cost. To make a comparison,
individuals considered obese accounted for three times as much insurance
claims. This severity shows a higher risk factor and most vulnerable in
filling a claim.

![bmi obese-1](https://user-images.githubusercontent.com/119358123/214977869-b10b62fe-3ec1-4e56-8d04-a5635badf535.png)
<!-- -->

### Revisting 1

A point brought up in the earlier analysis was to evaluate the lack of
insurance claims in comparison to females over the age of 50. The
analysis provides insights into females that were either obese or
overweight were more vulnerable and likely to file an insurance claim.

![bmi gender relationship-1](https://user-images.githubusercontent.com/119358123/214977922-ac5a9b38-02d2-49a5-9559-2cb9f95aa004.png)
<!-- -->

## Health Factor: Blood Pressure

According to Centers for Control of Disease and Prevention, the higher
the blood pressure levels, the more risk you have for other health
problems, such as heart disease, heart attack, and stroke. High blood
pressure is defined as a systolic pressure of 130 or higher
<https://www.cdc.gov/bloodpressure/about.htm>

Individuals at risk for high blood pressure had a higher minimum
monetary claim value around \$26,000, although fewer overall claims in
total but a very costly starting point in comparison to the rest.

![high bloodpressure-1](https://user-images.githubusercontent.com/119358123/214977964-96ab3b36-2d44-47e8-a2a6-b7941d4f5645.png)
<!-- -->

Similarly to the risks of high blood pressure, individuals that are at
risk of pre-hypertension (high blood pressure) also share the comparable
analysis with the aforementioned group. This includes fewer claims but
also a higher minimum monetary claim amount.

Another key point that should have leaped off the previous and following
plot is the relationship between an individual being a smoker and the
claim amount. There appears to be a strong positive correlation between
smokers and high claims monetary amount.

![prehypertension bloodpressure-1](https://user-images.githubusercontent.com/119358123/214977991-6d56b383-939f-4430-ab36-e10eb5ec2773.png)
<!-- -->

### Revisting 2

In an effort to evaluate the relationship between gender and insurance
claims, males were slightly more likely to be responsible for the higher
monetary value.

![gender and bloodpressure-1](https://user-images.githubusercontent.com/119358123/214978051-3798968b-56bc-41f1-b4db-0fa0eaf6a675.png)
<!-- -->

## Health Factor: Diabetic

Diabetes causes damage by scarring the kidneys, which in turn leads to
other possible health risks that are responsible for raising blood
pressure.

There happens to be no strong correlation between diabetics and claim
amounts. Both diabetics and non-diabetics show comparable results in
this analysis.

![diabetic-1](https://user-images.githubusercontent.com/119358123/214978082-a424289d-090f-4f7a-a752-fc83d3fac900.png)
<!-- -->

### Revisting 3

No noticeable relationship between gender and diabetics.

## Conclusion

On average, males insurances claims were more likely to result in a
higher insurance bill when compared to the females. Which held firm when
analyzing the over age 50 subgroup which the women far outnumbered men.

Health traits such as BMI and blood pressure saw a noticeable trend on
insurance claims. People at risk of pre hypertension, high blood
pressure, overweight, and obesity all have a costly insurance bill. No
strong correlation was detected if the individuals were diabetic or
non-diabetic. In a surprise and not so shocking aspect, smokers were
also at an higher risk in filling a costly claim.

Health factor risks contributes greatly in the relationship between the
severity and amount filled, making it understandable on why certain
characteristics would lead to different insurances rates to help the
companies account for the likelihood of an enormous bill.
