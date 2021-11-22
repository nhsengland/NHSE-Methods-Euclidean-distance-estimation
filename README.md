## NHSEI Methods: Euclidean distance estimation


### About this method

The Euclidean distance estimation method is an important statistical method which  helps to accurately measure the distance between two points based on various characteristics.
For more information about the method, including how is being used, when and by who, please refer to the Methods toolbox documentation on our [FutureNHS workspace](https://future.nhs.uk/DataMeth/grouphome).


### Requirements

Phyton packages: 'pandas','numpy'


### Summary of the code

This Python code develops the Euclidean distance calculations. Firstly, it reads and standardises the data by calculating the average and standard deviation. Then it applies a standardised value function by name and later the Euclidean distance function. Finally, it sorts the calculated distances and outputs the results.


### Data sources

1. The average Index of Multiple Deprivation (2010) score in the LSOAs where Trusts' patients live (Deprivation) -	NHS Digital, HES
2. Number distinct patients with recorded activity on the previous year	(Patients) -	NHS Digital, HES
3. Total number of finished episodes or attendances	(Attendances) -	NHS Digital, HES
4. Total number of Full time equivalent Staff at the end of the financial year	(FTE staff) -	NHS Digital, Workforce Statistics
5. The proportion of finished admissions where patient's diagnosis is Diseases of the digestive system (K00-K93) or Symptoms, signs and abnormal clinical and laboratory findings, not elsewhere classified (R00-R99)	(diagnosis)	- NHS Digital, HES publication
6. Average percentage of daily number occupied beds overnight (Jan-March)	(Night beds) -	NHS England, Unify2 data collection - KH03
7. Average percentage of daily number occupied beds day only (Jan-March) (Day beds) -	NHS England, Unify2 data collection - KH03
8. The proportion of finished episodes or attendances or appointments where patient's age is ≤15	(Age 0 -15) -	NHS Digital, HES
9. The proportion of finished episodes or attendances or appointments where patient's age is between 60-74	(Age 60 -74) -	NHS Digital, HES
10. The proportion of finished episodes where patient didn't have a procedure or intervention	(No procedure) -	NHS Digital, HES publication
11. Trust's Operating Expendes at the end of the year	(Operating expenses) -	Monitor, Transparency data
12. The proportion of finished episodes or attendances or appointments where the Rural/Urban indicator is recorded as Urban	(Urban) -	NHS Digital, HES databases
13. Number of open sites per Trust	(Sites) -	Organisation Data Service, ODS
14. Distance from the Trust to the sea in miles	(Sea distance) -	ODS to obtain Trust's postcode and doogal.co.uk to calculate distance
15. Market Forces Factor payment values	(MFF payment index) -	NHS England Publications 
16. Proportion of undergraduate medical students placed in any hospital Trust	(StudentStaff) - DH
17. Number of CCGs contracting with Trust	(CCGs) -	NHS Digital, HES
18. Presence of non-emergency department	(Non-type 1 AE department) -	NHS Digital, HES
19. Yearly average Staff sickness absence rate	(Absence Rate) -	NHS Digital, Workforce Statistics
20. Number of Delayed Days during the last quarter of the financial year	(DTOCs) -	NHS England, Unify2 Data Collection - MSitDT
21. Degree of specialisation (Degree of specialisation) -	Calculated using HES databases


### Authors

Felix Asamoah, Senior Analytical Manager - felix.asamoah1@nhs.net 


### License

This project is licensed under the [MIT License](LICENSE.md).

