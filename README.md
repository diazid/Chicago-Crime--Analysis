# Chicago Crime: Analysis
 
* by Israel Diaz
* email: idiazg@udd.cl

---

## Project Description

The main task is to answer a series of questions about trends in crimes in Chicago for a reporter for the local newspaper.

* Stakeholder Questions to Answer:
    1) Comparing Police Districts:
        * Which district has the most crimes? Which has the least?
    2) Crimes Across the Years:
        * Is the total number of crimes increasing or decreasing across the years?
        * Are there any individual crimes that are doing the opposite (e.g decreasing when overall crime is increasing or vice-versa)?
    3) Comparing AM vs. PM Rush Hour:
        * Are crimes more common during AM rush hour or PM rush hour?
        * What are the top 5 most common crimes during AM rush hour? What are the top 5 most common crimes during PM rush hour?
        * Are Motor Vehicle Thefts more common during AM rush hour or PM Rush Hour?

---

## Data Description

**Chicago Crime Data**

* Source: [Chicago Data Portal:](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2) Crimes 2001 to Present
    * Data Description:
        * All Crimes that were reported in the city of Chicago and their details
        * [View Preview](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/data)
    * Includes:
        * type of crime, exact date/time, lat/long, District/ward, was there an arrest, etc.
    * Note: the .csv is very large and needs to be processed into smaller files to fit inside a GitHub repository. We have provided a helper notebook below to process your downloaded file into a repo-friendly format. I used the data processing notebook that is in the project folder.

---

## Project Deliverables

### Sample data points

![png](/img/sample_distrubution_map.png)

### 1. Which district has the most crimes? Which has the least?

![png](/img/Chicago_crimes_by_district.png)

According to this data, the district with the most crimes is the 8TH with 521830 crimes, and the district with the least crimes is 21ST with 4 crimes.

### 2. Is the total number of crimes increasing or decreasing across the years?

![png](/img/total_crimes.png)

The above plot shows the total crimes across the years, and we can see that the total number of crimes is decreasing the years, but in 2022 is increasing the number.

### 3. Are there any individual crimes that are doing the opposite (e.g decreasing when overall crime is increasing or vice-versa)

![png](/img/crimes_per_year.png)

Despite the total number of crimes is decreasing, there are some crimes that are increasing the number of crimes, like: `CONCEALED CARRY LICENSE VIOLATION`, `CRIMINAL SEXUAL ASSAULT`, `DECEPTIVE PRACTICE`, `HOMICIDE`, `INTERFERENCE WITH PUBLIC OFFICER`, `OBSENITY`, `OTHER NARCOTIC VIOLATION`, `PUBLIC INDECENSY`, `WEAPONS VIOLATION`, `HUMAN TRAFFICKING`. Some of those have been maintaining waving behavior, some years going up and some years going down, but the overall trend is increasing. And others have been highly increasing in year 2020 and ahead, like `CRIMINAL SEXUAL ASSAULT`, `HOMICIDE`, `WEAPONS VIOLATION`, `HUMAN TRAFFICKING`.

### 4. Are crimes more common during AM rush hour or PM rush hour?

![png](/img/total_crimes_per_hour.png)

As we can see, the total number of crimes is higher (in average) during PM rush hour, and the total number of crimes is not lower during AM rush hour, but start increasing, in average.

### 5. What are the top 5 most common crimes during AM rush hour? What are the top 5 most common crimes during PM rush hour?

![png](/img/top5_crimes_am_pm.png)

As we can see, the top 5 crimes are mostly same on AM and PM rush hour, but the total number of crimes is higher (in average) on PM rush hour.

### 6. Are Motor Vehicle Thefts more common during AM rush hour or PM Rush Hour?

Also, we can note that `MOTOR VEHICLE THEFT` is not in the top 5 crimes on AM and PM rush hour. Not even in the whole dataset.

---

## Tableau Visualization

![png](/img/Main%20Chicago%20Crimes.png)

You will find the public dashboard at this [Link](https://public.tableau.com/app/profile/israel.diaz/viz/ChicagoCrimeReport_16814516717520/MainChicagoCrimes)



