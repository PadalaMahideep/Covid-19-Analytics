# Covid-19-Analytics
Covid-19 Analytics DashBoard Using IBM  Cognos

# To create a COVID-19 analytics dashboard using IBM Cognos , you can follow these steps:

1. Import the Dataset: Import the dataset containing the COVID-19 data into IBM Cognos. Ensure that the dataset is properly formatted and organized.

2. Create a Data Source: Create a data source in IBM Cognos using the imported dataset. Connect the data source to the dataset, ensuring that the appropriate fields are mapped correctly.

3. Create a Dashboard: Create a new dashboard in IBM Cognos to display the COVID-19 analytics. Choose a suitable layout and design for your dashboard.

4. Add Visualizations: Add visualizations to the dashboard to represent the COVID-19 data. Based on the given attributes, you can consider the following visualizations:

   a. Line Chart: Use the "Date" attribute on the X-axis and the "Confirmed" attribute on the Y-axis to show the trend of confirmed cases over time. You can also add separate lines for "ConfirmedIndianNational," "ConfirmedForeignNational," "Cured," and "Deaths" to track their respective trends.

   b. Bar Chart: Create a bar chart using the "State/UnionTerritory" attribute on the X-axis and the "Confirmed" attribute on the Y-axis to compare the total confirmed cases across different states or union territories.

   c. Pie Chart: Use a pie chart to represent the distribution of cases by combining the attributes "ConfirmedIndianNational," "ConfirmedForeignNational," "Cured," and "Deaths" into a single calculation, as mentioned in the question.

5. Apply Filters and Interactivity: Implement filters and interactivity options to allow users to drill down into specific data subsets. Users should be able to filter the data by date, state/union territory, or other relevant attributes.

6. Add Additional Metrics: Consider adding additional calculated metrics based on the given attributes. For example, you can calculate the percentage of cured cases or the case fatality rate (deaths divided by confirmed cases).

7. Customize the Dashboard: Customize the appearance of the dashboard by adding titles, legends, and descriptions to make it more informative and user-friendly.

8. Test and Publish: Test the dashboard thoroughly to ensure that the data and visualizations are accurate. Once satisfied, publish the dashboard to make it accessible to users.

Remember to follow the IBM Cognos documentation and user guides for detailed instructions on creating and customizing dashboards using IBM Cognos.

# Screen Shots

==> Map Chat (Covid -19 India Statistics)

Details :
* Over all values of State/UnionTerritory, the sum of Confirmed is nearly 111 thousand.
* Confirmed ranges from 0, when State/UnionTerritory is Nagaland#, to over 22 thousand, when State/UnionTerritory is Maharashtra.

![image](https://github.com/PadalaMahideep/Covid-19-Analytics/assets/114172544/d98ce255-69c9-4f8e-b680-ebefeefc26c3)    

==> Bubble chat

Details: 
*   The overall number of results for Deaths is over a thousand.
*   Over all values of State/UnionTerritory, the average of Confirmed is 108.
*   The average values of Confirmed range from 0, occurring when State/UnionTerritory is Nagaland#, to 566.5, when State/UnionTerritory is Maharashtra.
*    Kerala is the most frequently occurring category of State/UnionTerritory with a count of 78 items with Confirmed values (7.6 % of the total).
  
![image](https://github.com/PadalaMahideep/Covid-19-Analytics/assets/114172544/3f1b1148-35aa-49df-b455-ee8f546c7f81)

==> Pie Chat  (Percentage of Confirmed cases of Top 10 Affected States)

Details: 
* The total number of results for percentage Calculation, across all State/UnionTerritory, is 10.

![image](https://github.com/PadalaMahideep/Covid-19-Analytics/assets/114172544/862aef56-e3a3-49a2-9405-b8bf4f637a24)

==> Bar Graph (Top 10 State Wise No Of Confirmed Case)
* The total number of results for Confirmed, across all State/UnionTerritory, is 430.
* The largest value of Confirmed is nearly three thousand, occurring when State/UnionTerritory is Maharashtra.
* Kerala is the most frequently occurring category of State/UnionTerritory with a count of 78 items with Confirmed values (18.1 % of the total).
  
![image](https://github.com/PadalaMahideep/Covid-19-Analytics/assets/114172544/0e1d4a68-e62e-4131-b41f-c2a44f5bb873)

==> Bar chat (Statistics Of Chosen States)

Details:

*    The total number of results for Confirmed, across all State/UnionTerritory, is 82.
*    Over all values of State/UnionTerritory, the average of Confirmed is 221.7.
*    The total number of results for Cured, across all State/UnionTerritory, is 82.
*    Over all values of State/UnionTerritory, the average of Cured is 6.537.
*    The total number of results for Deaths, across all State/UnionTerritory, is 82.
*    Over all values of State/UnionTerritory, the average of Deaths is 3.793.
*    Cured ranges from 115, when State/UnionTerritory is Andhra Pradesh, to 421, when State/UnionTerritory is Delhi.
*    Deaths ranges from 75, when State/UnionTerritory is Andhra Pradesh, to 236, when State/UnionTerritory is Delhi.
*    Confirmed ranges from over five thousand, when State/UnionTerritory is Andhra Pradesh, to over thirteen thousand, when State/UnionTerritory is Delhi.
*    Delhi is the most frequently occurring category of State/UnionTerritory with a count of 46 items with Confirmed values (56.1 % of the total).
*    Delhi is the most frequently occurring category of State/UnionTerritory with a count of 46 items with Cured values (56.1 % of the total).
*    Delhi is the most frequently occurring category of State/UnionTerritory with a count of 46 items with Deaths values (56.1 % of the total).

![image](https://github.com/PadalaMahideep/Covid-19-Analytics/assets/114172544/aba92700-0018-4350-ab05-b70ac6a3fa4b)

Line Chat ()

Details :
*   The total number of results for Deaths, across all dates, is 498.
*   Over all dates, the average of Deaths is 0.4056.
*   The total number of results for Confirmed, across all dates, is 498.
*   Over all dates, the average of Confirmed is 19.45.
*   The  total number of results for Cured, across all dates, is 498.
*   Over all dates, the average of Cured is 1.622.
*   Cured ranges from 0, when Date is 2020- 03-01, to 124, when Date is 2020-03-31.
*   Confirmed ranges from 3, when Date is 2020-03-01, to almost 1500, when Date is 2020-03-31.
*   Deaths ranges from 0, when Date is 2020- 03-01, to 35, when Date is 2020-03-31.
﻿*   Cured is unusually high when Date is 2020- 03-31, 2020-03-30, 2020-03-29 and 2020-03-28.
*   Cured has a moderate upward trend.2020-03-31 (5.6 %), 2020-03-30 (5.6%), 2020-03-29 (5.4%), 2020-03-26 (5.4%), and 2020-03-28 (5.4 %) are the most       
     frequently  occurring categories of Date with a combined count of 137 items with Deaths values (27.5 % of the total).
*   2020-03-31 (5.6 %), 2020-03-30 (5.6%), 2020-03-29 (5.4%), 2020-03-26 (5.4%), and 2020-03-28 (5.4 %) are the most frequently occurring categories of Date    
    with a combined count of 137 items with Confirmed values (27.5 % of the total).
*   2020-03-31 (5.6 %), 2020-03-30 (5.6 %), 2020-03-29 (5.4 %), 2020-03-26 (5.4%), and 2020-03-28 (5.4 %) are the most frequently occurring categories of Date 
    with a combined count of 137 items with Cured values (27.5 % of the total).

![image](https://github.com/PadalaMahideep/Covid-19-Analytics/assets/114172544/6ebb4796-2ce7-4c0f-a05a-a7f14f31c59a)

Forecasting line graph wrt above graph:

![image](https://github.com/PadalaMahideep/Covid-19-Analytics/assets/114172544/2ccc0883-66c4-4b0c-a071-2661caa3eac1)
