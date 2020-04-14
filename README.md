# Coronavirus in Estonia exploratory analysis
You can find a quick overview of the spread of COVID-19 disease in Estonia here in this simple data analysis I've made recently.
For the research I used an open dataset, provided by the Republic of Estonia Ministry of Health: 
https://www.terviseamet.ee/et/koroonaviirus/koroonaviiruse-andmestik 
(the set was imported in the morning of 2020-04-13)

The description of the columns provided by Terviseamet:
id - Unique anonymized test identifier. String 40 characters.

Gender - The sex of the patient, if known. String 1 character.

M - man
N - woman
AgeGroup - Patient's age group at the time of the test.

0-4
5-9
10-14
15-19
...
70-74
75-79
80- 84
over 85 (üle 85)
Country - Country of residence according to the patient's population register.

Estonia (Eesti)
Abroad (Välismaa)
Unknown (Tundmatu)
County - County of residence in Estonia according to the patient's population register.

E.g. Harju County
ResultValue - SARS-CoV-2 test result response, string 1 character

N - negative
P - positive
StatisticsDate - Date of inclusion in the statistics in ISO 8601 format

2020-03-31
ResultTime - Time of test result in ISO 8601 format with time zone

2020-03-31T00: 00: 00 + 03: 00
AnalysisInsertTime - Time of receipt of health information system data or test results in ISO 8601 standard format with time zone

2020-03-31T05: 10: 20 + 03: 00
