# Develop NLP pipeline for vaccine uptake sentiment analysis

## Background

Social media has demonstrated its potential to reflect and influence public opinion through the spreading of information, malinformation, misinformation, and disinformation. Several research groups have explored the [use of social media to monitor and evaluate public sentiment towards vaccines](https://www.ecdc.europa.eu/en/publications-data/systematic-scoping-review-social-media-monitoring-methods-and-interventions) but there are challenges to overcome to do this in a standardised and robust manner, and it’s unclear how it could translate through to the design and implementation of interventions to increase vaccine confidence and uptake. Natural language processing (NLP) is a cutting-edge machine learning method that has repeatedly been demonstrated to be a powerful technique for sentiment analysis, knowledge extraction, and other methods related to natural language / free text. We are interested in understanding how NLP can be utilised to analyse social media posts to understand and track the association between vaccine uptake and public sentiment, and to inform interventions that can increase uptake.

## Challenge

Develop an NLP pipeline to analyse public sentiment and messages on social media to understand the association with real-time vaccine uptake. As well as real-time uptake, the algorithm should include predictive methods for alerting stakeholders to decreasing sentiment (or when a critical mass of ‘negativity’ has been reached) in order to predict short-term and long-term ‘shocks to immunisation systems’. You may also want to consider baseline heuristics as well as advanced machine learning solutions, for example triggering warnings for negative sentiment increasing rapidly (for example, increase of X tweets/day). Insights from the system should be useful for real-time modelling to understand current sentiment, as well as for informing the design and monitoring impact of interventions to increasing vaccine uptake and/or preventing shocks to the immunisation system. For example, you may want to consider automated suggestions of interventions and/or causal inference methods for analysing the success of interventions and/or monitoring of sentiment based on interventions (for example, alysing replies to influencer’s tweets). The developed pipeline should include a public-facing platform that includes a clear description of the underlying algorithm, visualisations of findings, and lay explanations of the observed effects and any proposed interventions.

## Questions to answer in your presentation

1. How would you engage with the public to ensure that the platform is minimally invasive and not perceived as a negative tool?
2. How does your proposed pipeline and platform handle predictions in real-time as well as longer time? How would you incorporate uncertainty/ confidence of predictions in triggering alerts?
3. How will you validate any classifier in your platform to distinguish genuine sentiment and deliberate anti-vaccination malinformation (‘trolls’) accurately?
   
