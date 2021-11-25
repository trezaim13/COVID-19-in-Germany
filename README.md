# COVID-19 in Germany

At the end of 2019, the world was faced with a new challenge : the COVID-19 pandemic, which is a still ongoing global pandemic of coronavirus disease 2019. The novel virus was first identified in Wuhan, China in December 2019 but has managed to spread worlwide, which includes Germany of course.

In this personal project, I analyze open source data about the current pandemic situation in Germany. At hand, we have a dataset imported from Kaggle.com, containing informations about the infections, deaths and vaccines in Germany.

Let's analyse this data and see what we can retain from it.

# Data Description 

The data we will be seeing in this project is the following :

- The first dataset, which we named **'`covid`'**, contains 831.604 rows of data with information on covid cases, deaths and recoveries in Germany. The data is separated into the following 8 columns :
    - **`state`** : The state to which the tested individuals belong;
    - **`county`** :  The county which the state belongs to;
    - **`age_group`** : The age group of the tested (xx-xx);
    - **`gender`** : The gender of the tested;
    - **`date`** : The date of the tests (YYYY-MM-DD);
    - **`cases`** : The number of new covid cases;
    - **`deaths`** : The number of deaths;
    - **`recovered`** : The number of recovered cases.
    
- The second dataset, which we named **'`vaccine`'**, contains 313 rows of data with information on the COVID vaccines in Germany. The data is separated into the following 9 columns :
    - **`date`** : The date of the administration of the vaccine (YYYY-MM-DD);
    - **`doses`** :  The number of doses administered;
    - **`doses_first`** : The number of first doses administered;
    - **`doses_second`** : The number of second doses administered;
    - **`pfizer_cumul`** : The cumulated number of the Pfizer vaccine doses administered;
    - **`moderna_cumul`** : The cumulated number of the Moderna vaccine doses administered;
    - **`Astrazeneca_cumul`** : The cumulated number of the AstraZeneca vaccine doses administered;
    - **`persons_first_cumul`** : The cumulated number of patients who have received the first dose of the vaccine;
    - **`persons_second_cumul`** : The cumulated number of patients who are fully vaccinated, meaning they have received the second dose of the vaccine.

- The third dataset, which we named **'`demographics`'**, contains 192 rows of data with information on the demographic distribution in Germany. The data is separated into the following 4 columns :
    - **`state`** : The state to which the demographic belongs;
    - **`gender`** : The gender of the demographic group;
    - **`age_group`** : The age group of the demographic (xx-xx);
    - **`population`** : The number of individuals;
