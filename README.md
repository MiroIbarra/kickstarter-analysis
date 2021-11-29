# Kickstarting with Excel

## Overview of Project

### The purpose of the analyasis is to assist the playwright, Louise, that wants to start a crowdfunding campaign to fund her play, Fever. The analysis will include organizing, sorting, and analyzing kickstarter data to provide insights on previous successful crowdfunded plays.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The first step of visualizing campaign outcomes as successful, failed or cancelled based on launch date is creating a pivot table and graphs. Create a pivot table to analyze theater outcomes based on launch date by placing "Category" and "Years" in the "Filters" tab. Place 'Outcomes' in the "Columns" tab,  'data created conversion' in the "Rows" tab, and "Outcomes" in the "Values" tab. 

![Screen Shot 2021-05-13 at 12 35 25 AM](https://user-images.githubusercontent.com/82562823/118094105-294e0a00-b383-11eb-8d2d-44a3bee62cb5.png)

Group the "Row" labels to include months and then click on the drop down arrow next to categories and selected "theater."

![Screen Shot 2021-05-13 at 12 53 15 AM](https://user-images.githubusercontent.com/82562823/118096045-b8f4b800-b385-11eb-97ab-339791482679.png)


Create a line chart by selecting "Insert" and then by clicking on "line chart with markers". Consider using markers with numbers to get a better visualization of data. 

![Screen Shot 2021-05-13 at 12 59 38 AM](https://user-images.githubusercontent.com/82562823/118096676-87302100-b386-11eb-9154-ca83abb5d6e1.png)


### Analysis of Outcomes Based on Goals

The next step of analyzing kickstarter data is to visualize the percentage of successful, failed or cancelled based on goals. Enter the 'Goal' amounts down the A column. The 'Goal' column will be used as the X-Axis for the graph that will be created. The Y-Axis of the graph that will be created, will include the data from the columns that are titled, "Number Successful," "Number Failed," "Number Cancelled," "Total Projects," "Percentage Successful," "Percentage Failed," and "Percentage Canceled." Use the COUNTIFS() function on Cell B1, per image below. 

![Screen Shot 2021-05-12 at 11 13 57 PM](https://user-images.githubusercontent.com/82562823/118086045-35809a00-b378-11eb-8ccc-e8e6cf66c095.png)

The formula was tailored to include the ranges listed under "Goals." Once the "Number Successful" column, repear the same formula except change the condition from 'successful' to 'failed.' The same formula was used for the "Number Cancelled" column. The amounts listed in cells B2, C2, and D2 ("Number Sucessful", "Number Failed," and "Number Cancelled" respectively" were then added in cell E2, which was under the "Total Projects" column using the SUM() function. Finally, find the percentage of successful, failed and cancelled projects by dividing the applicable amount of projects by the total amount of projects per goal amount. Once the table was complete, create a chart. 

Completed table, per image below.

![Screen Shot 2021-05-13 at 12 03 18 AM](https://user-images.githubusercontent.com/82562823/118090663-ac209600-b37e-11eb-81cd-2f93167b8a43.png)

Create a line chart with markers using the information in the "Percentage Succesful", "Percentage Failed," and "Percentage Cancelled." 

![Screen Shot 2021-05-13 at 12 10 55 AM](https://user-images.githubusercontent.com/82562823/118091692-f8b8a100-b37f-11eb-93b1-a707737dc6d9.png)

### Challenges and Difficulties Encountered

The main challenge I faced was writing the COUNTIFS() function since I had to keep track of the quotation marks. A few times I would get the "too few arguments" error message in Excel. 

## Results

- **What are two conclusions you can draw about the Outcomes based on Launch Date?** 
 * The Theater Outcomes Based on Launch Date graph above illustrates the outcomes based on launch dates listed below:
1. The top three months that were the most successful were May, June, and July - listed in ascended order. 
2. December had the lowest amount of successful plays.

- **What can you conclude about the Outcomes based on Goals?**
 * Observing goal ranges 10,000-14,999; 24,999-30,000; 39,000-40,000; and 49,000-50,000; one can see that there is a 50% chance of success and 50% chance of failure of goal outcomes. 
 * ![Screen Shot 2021-05-13 at 1 32 35 AM](https://user-images.githubusercontent.com/82562823/118100456-53a3c580-b38b-11eb-93de-b8d24325e324.png)
 
- **What are some limitations of this dataset?**
 * The limitations of this dataset would be the sample size. Perhaps if there was a different category with a larger sample size then one would have a different outcome. For example, if another category was selected instead of theater, then perhaps a there would be a different peak not in May. 

 - **What are some other possible tables and/or graphs that we could create?**
 * I would recommend using a bar graph since differences are more visible when comparing two bars, per image below. 
 * ![Screen Shot 2021-05-13 at 1 51 35 AM](https://user-images.githubusercontent.com/82562823/118102542-cada5900-b38d-11eb-8e25-ffca19f71b39.png)
 * Also, when the bar graph is horizontal, the months are listed on the X-Axis and the outcomes are on the Y-Axis. One can see the numbers next to the bars which will be next to each month, so it may be easier to read the numbers as your eyes will look just straight across instead of trying to track the numbers on a line graph.
 * ![Screen Shot 2021-05-13 at 1 53 18 AM](https://user-images.githubusercontent.com/82562823/118102843-20166a80-b38e-11eb-8a37-db22bace5379.png)
