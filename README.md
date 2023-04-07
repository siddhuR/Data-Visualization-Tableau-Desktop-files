# Data-Visualization-Tableau-Desktop-files

INT 233 – 21 FEB :- 

LIVE DATA – It is the action done and during updation , file gets updated .
EXTRACT DATA – – It is the action done and during updation , file does not gets updated .


LIVE DATA –

1.	OPEN DATA SOURCE
2.	IMPORT DATA
3.	GO TO SHEET 1, SELECT ROWS AND COLUMNS 
4.	IF NEEDED TO CHANGE ANY DATA IN EXCEL, CHANGE IT AND REFRESH IN TABLEAU FROM LIVE VS EXTRACT – REFRESH SECTION .


EXTRACT :-
1.	CHANGE CONNECTION TO  EXTRACT CLICK.
2.	GO TO SHEET 1 , SAVE THE FILE .
3.	IF ANY CHANGES DONE , IT WONT REFLECT INTO TABLEAU .
But if u want to still see the changes , right click on Live Vs extract .. go towards extract select Refresh , it will pop up with , do u want to refresh the data . and change data will be visible .

Symbol for live – extract .
 	-- Extract 

DRILL DOWN  :-
1.	STEP DOWN HIERARCHY

Difference between Dimesnion and measures with example .




Steps to create hierarchry.
1.	Import Data 
2.	Open Sheet 1 
3.	Drag and Drop Subcategory to category to get hierarchical data .


Green and blue pills.

Discrete – multiple pills were there in blue.
In continuous – once green pills will be there 



24 – 02 – 2023


Sorting :--

There are three ways for sorting :

1 . On y axis , there will be an icon for sorting , it will sort in descending order , and for second time it will sort in ascending . on third time ,, it will get to the initial order .

2 .
3 . From pills also , we can sort into ascending and descending order .


SWAPPING ROW  AND COLUMNS :

 


Shortcut to swap from Rows to columns --- Ctrl + W .


Grouping :--
Taking 2 or more attributes and put into the group.
1.	Click on one attribute and click on another attribute with Control button .

Ungroup :-
Right click on group and select Ungroup .

Grouping by another way :--

Right click on attributes – then go to Group and then choose attributes u want to get it in group . Click on group then change the name if u wish to . click on apply and click on Ok  . A new attribute will be generated with name u have given . 




Adding more attributes into group :-
Right click on Blue pill or where u have created group . Click on edit group then select the grp u want to add then click control and select attributes u want to add , Click apply  and ok .

Ungrouping attribute from group -
Right Click on blue pills or where u have created a grp , click on edit grp , then select group then click u wish to remove . Click on ungroup , click apply and ok to get changes .



Longitude and Latitude :-

Insert Columns into Longitude and rows to latitude  then double click on city .Map will be generated.

# Filtering:
General Filters:-
Filters > Edit Filters > General Tab > select the filters which you  want to do

Wildcard filters:-
It will filter the data by matching the data giving by the user.
Filters > Edit Filters > Wildcard tab > select the option to match the data by selecting some data in the box.

Condition filters:-
This will help us to filter by using the condition given.
Filters > Edit Filters > conditions Tab > select By Field to filter the data 

Top Filters :
Filters > Edit Filters > Top Tab > select top 5 or 10 according values to filter in the line wise.

#Applying the segments filter
Drag and drop the segment in marks tab.
It help us to show the filters according to segment 
Right click on segment filter change the visualizing colors accordingly.
 

Parameters used in Filters.
Click on subcategory  filters which is on rows.
Click on top tab > select by option > click create new parameter. New pop up window appears.
Give the name for the parameter and change the data according to you like select current value, choose the maximum range of the parameter. Then click on OK .
Than apply the filters
	Now new parameter option created on the left hand side of the panel. choose the parameter which you want to change. Right click it . select show parameter. You can able to dragger on the right hand side of the screen.

Set of particular items.
Click on ctrl and select the items in the visual chart. Right click on it. > select create set option.
Give the name to the set (Demo set)and click on OK.
On right panel new set will be visible drag and drop it to filters panel.

 

Set whole data by some conditions

 

Select the filter to the set as top 5 items and click on ok to create new set 2.
Drag and drop the demo set 2 in the marks panel.it will show IN/OUT as a name . Right click on it. Show set and show filters. And you change the color as well
 
Now create the parameter in the same method.

Date Filters:
 
Drag Order date to the filters as shown.
There are 5 options of date filters.
1.	Relative dates
2.	Range of dates
3.	Starting date
4.	Ending date
5.	Special
Relative dates
 
You can select the date filter by choosing the year accordingly.
Range of dates
 
Choose the range of the dates as min and max range to filter the dates.
Starting date
 
Choose the starting date to filter the date from that particular starting date.
Ending date
 
Choose the ending date to filter the date till that particular ending date.


Special
 

INTERACTIVE FILTERS
 
Apply normal filters. then right click the filters select show filters.
we can see category filters in the right hand side panel. This is known as interactive filters.

 
You can also apply filters in right side panel also.

CALCULATED FIELDS
 
Click on drop down menu. select Create calculated field.
     	 
Creating the calculated field of Total cost
 

Calculating the field of Number of days to ship the order after ordering
 
Calculating the field of Number of days to ship according to category and sub-category
 
Calculate the field of Number of days to ship for the only continent North America.
 
 







24/03/2023
JOINING DATA
•	Import the 2 or more datasets in the tableau.
•	Drag one dataset to the workspace.
•	And double click on that dataset and drag the another dataset in the new workspace to join the data.
 
•	Select the common column name to perform the join operation.
•	Then select the type of join to perform.
•	Now, we can see the data which we want after this particular join operation.

Now, open new sheet and drag the data columns which you want.
For example in the below picture, we show the total cost for the particular group id.
In this manner we can manage the data analization accordingly.
 

Now, Performing the Left join
 

In the same way we can perform the same process for all type of join operations.

DATA BLENDING:
Data blending always follows left join.
Add the data sets in the workspace
1.	Csv file extension.
2.	Microsoft access file extension.
 
Select Data option > New Data Source.
 
Now choose the type of file to import and add it to the workspace
 
Till here it will add 2 data sets in the workspace to operate.
Blending Relationship
Click on Data > select Edit Blend Relationship
 
Select product as a primary data source. And choose custom > click Add button
 
Select the common columns for primary and secondary data source. click on OK.
 
Finally, Click on OK
. 
Go to sheet and drag product id to the rows. There blue icon indicates primary set.
 
Go to product cost and drag cost to columns. Red icon indicates secondary set.
 
This will give the final visualization after bleding.
Task 2: 
Do the same task as before with primary as product cost and secondary set as product.(In Before task we took primary set as product and secondary set as product cost.)


Charts
Select the dataset
Hold ctrl + click on the columns to select and press on the type of chart you want
 

 

Scatter Plot Charts
 
Drag and drop the category to the marks section(like shape, lable etc…)
 

Drop Line
 




City wise sales
 
State wise sales
 
 
LINE CHART
Tableau automatically detect the data and accordingly it will give the type of  chart
So, 
 
 
If we want to  show labels drag and drop the sales in label section
 
Drag category to colors section
 
Drag category to rows

 
Month wise chart
 
Bubble charts
 

Reference Line
 
 
 
Reference Band
 
Reference distribution
 
Bar chart
 
 
 
 
 

 
 

 




Types of Tree Graphs
Types of Bump Chart
 
 
 

Types of Funnel Chart
 
 




