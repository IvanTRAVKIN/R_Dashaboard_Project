
# 🌍 Project Title: Life Expectancy Analysis and Dashboard

<a href="https://lifeexpec.shinyapps.io/Vanya/" style="font-size: 24px; font-weight: bold;">Click here to visit the Life Expectancy Visualization</a>

## 🚀 Introduction
Welcome to the Life Expectancy Analysis project, a solo project undertaken as part of the EmLyon Business School curriculum. The project focuses on analyzing global life expectancy data, emphasizing the impact of immunization, mortality, economic, and social factors. The dataset, named `LifeExpectancy_WHO`, encompasses health-related information for 193 countries from the years 2000 to 2015.

## 🌟 Motivation
Previous studies on life expectancy often overlooked the influence of immunization and human development index. This project aims to fill this gap by formulating a regression model using a mixed-effects model and multiple linear regression. The analysis considers critical immunization factors such as Hepatitis B, Polio, and Diphtheria, alongside mortality, economic, social, and other health-related factors. The goal is to help countries identify key areas for improvement to enhance the life expectancy of their populations.

## 📊 Dataset
### 🌐 Context
The data used in this project is sourced from the Global Health Observatory (GHO) data repository under the World Health Organization (WHO). It includes life expectancy and health-related factors for 193 countries. Economic data was collected from the United Nations website. The study focuses on the period from 2000 to 2015.

### 🧹 Data Cleaning
The dataset underwent a meticulous cleaning process to ensure accuracy. Initial visual inspection revealed missing values, primarily in population, Hepatitis B, and GDP. The `Missmap` command in R software was employed to handle missing data. Countries with substantial missing data, such as Vanuatu, Tonga, Togo, Cabo Verde, were excluded from the final model dataset.

### 📊 Final Dataset
The merged dataset consists of 22 columns and 2938 rows, encompassing 20 predicting variables. These variables were categorized into `Immunization`-related factors, `Mortality` factors, `Economical` factors, and `Social` factors.

## 🎯 Project Scope
The analysis delves into identifying factors influencing life expectancy, with a particular focus on immunization. The dataset's global coverage facilitates country-specific recommendations for improving life expectancy.

## 📈 Dashboard
The project culminates in the creation of an interactive dashboard, providing a visually intuitive representation of the analysis. The dashboard aims to empower users to explore and understand the factors contributing to life expectancy variations across different countries.



