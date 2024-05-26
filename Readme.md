## Case Study:
### Dataset:
Use 6 csv files in the data_folder and develop your approach to perform below analytics.
 Please use the data dictionary (attached in the mail) to understand the dataset and then develop your approach to perform below analytics.

### Analytics: 
Application should perform below analysis and store the results for each analysis.
1.	Analytics 1: Find the number of crashes (accidents) in which number of males killed are greater than 2?
2.	Analysis 2: How many two wheelers are booked for crashes? 
3.	Analysis 3: Determine the Top 5 Vehicle Makes of the cars present in the crashes in which driver died and Airbags did not deploy.
4.	Analysis 4: Determine number of Vehicles with driver having valid licences involved in hit and run? 
5.	Analysis 5: Which state has highest number of accidents in which females are not involved? 
6.	Analysis 6: Which are the Top 3rd to 5th VEH_MAKE_IDs that contribute to a largest number of injuries including death
7.	Analysis 7: For all the body styles involved in crashes, mention the top ethnic user group of each unique body style  
8.	Analysis 8: Among the crashed cars, what are the Top 5 Zip Codes with highest number crashes with alcohols as the contributing factor to a crash (Use Driver Zip Code)
9.	Analysis 9: Count of Distinct Crash IDs where No Damaged Property was observed and Damage Level (VEH_DMAG_SCL~) is above 4 and car avails Insurance
10.	Analysis 10: Determine the Top 5 Vehicle Makes where drivers are charged with speeding related offences, has licensed Drivers, used top 10 used vehicle colours and has car licensed with the Top 25 states with highest number of offences (to be deduced from the data)

### Expected Output:
1.	Develop an application which is modular & follows software engineering best practices (e.g. Classes, docstrings, functions, config driven, command line executable through spark-submit)
2.	Code should be properly organized in folders as a project.
3.	Input data sources and output should be config driven
4.	Code should be strictly developed using Data Frame APIs (Do not use Spark SQL)
5.	Share the entire project as zip or link to project in GitHub repo.

### Prerequisites

What things you need to run the project?

Download and Install SPARK. Find the latest release from: `https://spark.apache.org/downloads.html`

Configure SPARK_HOME Environment Variable.
```commandline
$SPARK_HOME = {Loaction of spark-3.5.1-bin-hadoop3 Directory}
```
Check Spark is installed properly or not by running.
```commandline
spark-shell
```

### Runbook
Clone the repo and follow these steps:
### Consideration:
1. Tested on Windows

### Steps:
1. Go to the Project Directory: `cd CarCrash-Analysis`
2. Spark Submit
   ```commandline
    spark-submit --master "local[*]" main.py
   ```