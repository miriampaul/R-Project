# R-Project
# Load the readr, ggplot2, and dplyr packages
library(readr)
library(ggplot2)
library(dplyr)

# Read datasets/confirmed_cases_worldwide.csv into confirmed_cases_worldwide
confirmed_cases_worldwide <- readr::read_csv('datasets/confirmed_cases_worldwide.csv')

# See the result
str(confirmed_cases_worldwide)
names(confirmed_cases_worldwide)
