# Advanced Modeling: Climate Change Perceptions

This project was created under the course of Advanced Modeling as part of the Master in Computational Science at UC3M. 


## Instructions 

> To look at the results, go directly to `Climate Change Perceptions.html`. If you are interested in running the code, download the script `Climate Change Perceptions.Rmd` and the data it is based on: the zip folder `ESS8e02_3.zip`, in which inside is the `ESS8e02_3.csv` file, as well as `wdi_data.csv`.
> -  Additionally, download `data_mice.rds` and `xgb_tune_broad.rds` to automatically run through the document, as the chunks _{r mice generation excluded, eval=F}_ and _{r RP ML gb train broad, eval=F}_ are set to `eval=F`. This is because of the long computing times for the MICE imputation process and the ML Gradient Boosting training phase. If you want to try them out for yourself, feel free to set those chunks on `TRUE` and have fun waiting... :)


## Description 

Climate change remains one of the most pressing challenges of our time, demanding not only systemic policy reforms and technological solutions, but also widespread public engagement. As European society tries transitions to a low-carbon economy, understanding public perceptions and behaviours regarding climate change is essential. This project uses data from the European Social Survey (ESS) Round 8 (2016), which provides a rich cross-national dataset capturing individuals’ attitudes, beliefs, and behaviours related to climate change and energy use across Europe.

The aim of this project is to apply supervised machine learning techniques of classification and regression to investigate key public attitudes.

- The classification task focuses on predicting whether an individual believes climate change is primarily caused by human activity.
- The regression task explores what predicts an individual’s willingness to reduce their personal energy consumption to help mitigate climate change, measured on a 1–10 scale. These predictive models aim to uncover the most influential individual and attitudinal factors behind climate-related perceptions and behaviours. Such insights are essential for policymakers and stakeholders seeking to promote public support for environmental initiatives and behavioural change across different European contexts.

I use a subset of the ESS Round 8 dataset (DOI: 10.21338/ess8e02_3), which includes over 30,000 respondents and covers a wide range of demographic, political, and environmental variables.
