# Coronavirus in Estonia exploratory analysis
You can find a quick overview of the spread of COVID-19 disease in Estonia here in this simple data analysis I've made recently.
For the research I used an open dataset, provided by the Republic of Estonia Ministry of Health: 
https://www.terviseamet.ee/et/koroonaviirus/koroonaviiruse-andmestik 
<br/>(the set was imported in the morning of 2020-04-13)

### The description of the columns provided by Terviseamet:
<br/>**id** - Unique anonymized test identifier. String 40 characters.
**Gender** - The sex of the patient, if known. String 1 character.
<br/>- M - man
<br/>- N - woman
<br/>**AgeGroup** - Patient's age group at the time of the test.
<br/>- 0-4
<br/>- 5-9
<br/>- 10-14
<br/>- 15-19
<br/>- ...
<br/>- 70-74
<br/>- 75-79
<br/>- 80- 84
<br/>- over 85 (üle 85)
<br/>**Country** - Country of residence according to the patient's population register.
<br/>- Estonia (Eesti)
<br/>- Abroad (Välismaa)
<br/>- Unknown (Tundmatu)
<br/>**County** - County of residence in Estonia according to the patient's population register.
<br/>- E.g. Harju County
<br/>**ResultValue** - SARS-CoV-2 test result response, string 1 character
<br/>- N - negative
<br/>- P - positive
<br/>**StatisticsDate** - Date of inclusion in the statistics in ISO 8601 format
<br/>- 2020-03-31
<br/>**ResultTime** - Time of test result in ISO 8601 format with time zone
<br/>- 2020-03-31T00: 00: 00 + 03: 00
<br/>**AnalysisInsertTime** - Time of receipt of health information system data or test results in ISO 8601 standard format with time zone
<br/>- 2020-03-31T05: 10: 20 + 03: 00
