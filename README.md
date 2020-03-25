# Computing-Causal-Inference

The goal of this project is to get experience with estimation of causal effects, in particular using the
differences-in-differences (DiD) method. This is a very common task in economics/government/business
analytics. Here I have estimated the impact of progresa subsidies on the school attendance using the
actual data.

Progresa was a a government social assistance program in Mexico. This program, as well as the details
of its impact, are described in the paper "School subsidies for the poor: evaluating the Mexican Progresa
poverty program", by Paul Shultz.

The data are the actual data collected to evaluate the impact of the Progresa program. There are two years of data
(1997 and 1998), and just under 40,000 children who are surveyed in both years. For each child-year
observation, the following variables are collected:

year =  year in which data is collected

sex male = 1

indig indigenous = 1

dist_sec = nearest distance to a secondary school

sc = enrolled in school in year of survey (=1)

grc = grade enrolled

fam_n = family size

min_dist = min distance to an urban center

dist_cap = min distance to the capital

poor poor = "pobre", not poor = "no pobre"

progresa treatment = "basal", control = "0"

hohedu = years of schooling of head of household

hohwag = monthly wages of head of household

welfare_index = welfare index used to classify poor

hohsex = gender of head of household (male=1)

hohage = age of head of household

age = years old

folnum = individual id

village = village id

sc97 = enrolled in school in 1997 (=1)
