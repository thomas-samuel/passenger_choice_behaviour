# Modelling Passenger Choice Behaviour of Purchasing Railway Tickets in India

## Project Overview

This project investigates how **Indian railway passengers make ticket purchasing decisions**, focusing on whether individuals choose faster but costlier trains or cheaper slower alternatives. The study combines survey-based data collection with econometric modeling to analyze the role of **income, age, gender, seating preference, and departure time** in shaping consumer choices.

## Objectives

* Collect stated-preference data on passenger ticket choices.
* Model how socioeconomic and ticket attributes affect decision-making.
* Apply discrete choice models (conditional logit) to estimate ticket choice probabilities.
* Generate insights into how pricing and service design could influence passenger preferences and railway revenues.

## Methods

* **Survey Design**: Online stated-preference survey (167 responses, 94 valid after filtering).
* **Variables Collected**: Passenger demographics (age, gender, income), train attributes (speed, cost, seating, departure time).
* **Model**: Conditional Logit Model based on random utility theory.
* **Evaluation**: Likelihood ratio, Wald, and Score tests to assess significance of model estimates.
* **Tools Used**: R (econometrics, conditional logit modeling).

## Key Findings

* **Income**: Higher-income passengers were significantly more likely to choose faster, costlier trains (probability ~0.89 vs. ~0.37 for low-income groups).
* **Age**: Older passengers (50–65) showed stronger preference for quicker trains when booking in advance.
* **Gender**: Female passengers showed higher likelihood of choosing sleeper trains compared to males.
* **Departure Time**: Night departures were strongly preferred for long journeys (>6 hours).

## Limitations

* **Sample Size**: Only 94 valid responses → not representative of the broader Indian passenger population.
* **Sampling Bias**: Survey distribution via WhatsApp groups likely biased toward educated, urban respondents.
* **Model Strength**: Small dataset resulted in weak statistical power and borderline significance levels.
* **Scope**: Did not distinguish between **business vs. leisure travel**, which is a critical determinant of willingness to pay.
* **Generalisability**: Findings provide exploratory insights, but results should not be treated as definitive for policy or railway pricing decisions.

## Repository Contents

* `Term_paper.pdf` → Full research paper including introduction, literature review, methodology, results, and discussion.
* **Note**: No raw survey data is included due to privacy of respondents.

## Impact

While limited in scale, this project provided hands-on experience in **survey design, econometric modeling, and interpretation of consumer behavior**. It demonstrates the application of econometrics to real-world transport economics and highlights challenges in data collection and statistical inference.
