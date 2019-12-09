# Factors Analysis for Gun Incident and increasing number of people killed in USA

## Introduction:
The increased amount of gun violence and incidences exacts an enormous toll on Americans-taking thousands of lives each year. The toll of gun violences and gun incidents is horrific and it is on the rise each year in America. Over million American have been shot in the past decades and millions more were the witness of firsthand gun violences. Nearly 36,000 of Americans are killed by gun each year, that’s an average of 100 per day. 100,000 Americans are shot and injured each ear. In 2017, gun deaths reached their highest level in the past 4 decades, with 39,773 deaths that year alone. 16% gun deaths was increased between 2014 to 2017[1]. 

The analysis in this study helps to identify room for what are the factors to prescribe fewer related to gun incidents. this situation is the main motivation for this project. What are the factors to prescribe fewer related to gun incidents?

# Follow these steps to run the Project

## 1- R Libraries

The project was created an RStudio and requires the following libraries to run:

library(tidyverse)
library(stringr)
library(tm)
library(quanteda)
library(reshape2)
library(lda)
library(wordcloud)
library(ggthemes)
library(qcc)
library(qicharts2)
library(zoo)
library(mapdata)
library(forecast)
library(scales)
library(e1071)
library(caTools)
library(Metrics)
library(rpart)
library(rpart.plot)
library("RPostgres")
library(DBI)

# Install libraries

Libraries can be installed in RStudio with the following command:

install.package("library")
ex. install.packages("DBI")

## 2- Set up Postgres Database 

Our data is stored in Postgres and can be accessed from RStudio with RPostgres and DBI libraries. 
Table incidents should be created by running the ddl script gunviolence_incidents_table_ddl.sql
Dump file of the database can be found in the repository, extract and restore in Postgres.

Connection string in R expects host, username, password and database.

## 3- Load RStudio rmd file

Load file Gun Violence Final Project.Rmd to access the Project.

