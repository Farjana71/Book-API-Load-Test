# Book-API-Load-Test
#Book-API-Load-Test by Jmeter
#### **Question**

- Find out the actual TPS for if 10000 user can give load within 1 hour **Expected load:** 10000 user, per hour.
- **Actual load:** what TPS? Breakdown the expected TPS in excel sheet and find out the actual TPS.
- For 60s, 300s and 600s load, add Jmeter UI screenshot and for 900s generate html report and take screenshot.

##### **Solved**

- #### [**Excel and Word Report**](https://github.com/Farjana71/Book-API-Load-Test/tree/main/resources)

#### **Load Test Strategy**

- [Server](https://demoqa.com/BookStore/v1/Books)

| ![TPS Report](./Images/TPS_report.png) |
| :------------------------------------: |
|              _Actual TPS_              |

#### **JMeter Summary Report**

- 167 users for 60 seconds

| ![Test Case 1](./Images/Test_01.png) |
| :----------------------------------: |
|         _60 sec, 167 users_          |

- 833 users for 300 seconds

| ![Test Case 2](./Images/Test_02.png) |
| :----------------------------------: |
|         _300 sec, 833 users_         |

- 1667 users for 600 seconds

| ![Test Case 3](./Images/Test_03.png) |
| :----------------------------------: |
|        _600 sec, 1666 users_         |

- 2500 users for 900 seconds

| ![Test Case 4](./Images/Test_04.png) |
| :-------------------------------------: |
|          _900 sec, 2500 users_          |

- 2500 users for 900 seconds

| ![Test Case 4.1](./Images/Test_04_1.png) |
| :-------------------------------------: |
|          _900 sec, 2500 users_          |

- Test Summary Report - 2500 users for 950 seconds

| ![Test Summary Report](./Images/reports.png) |
| :------------------------------------------: |
|               _Summary Report_               |
