parent
Query 

[The query builder](#the-query-builder)
- [Field Mapper](field-mapper)
- [Operator](operator)
- [Negate](negate)
- [OR search term](or-search-term)
- [Sorting and Organising tools](sorting-and-organising-tools)

To start using queries click on Queries in the top bar:

![image](https://user-images.githubusercontent.com/8155743/193250392-dd0c666e-bd0e-4008-86df-abdcb4a6b1e0.png)

This will open a pop up. From here you can open saved queries or create a new one by clicking New:

![image](https://user-images.githubusercontent.com/8155743/193250427-6a6e5460-3170-4d6c-a67f-8ae55bdbbf38.png)

## Understanding the query tool interface

There are two main parts to the query interface, the upper section where you build the query (query builder) and lower section where the results are returned. The software will automatically jump to the results when a query has been completed. 

### The query builder

![image](https://user-images.githubusercontent.com/8155743/193250687-bba2572f-594c-46dd-a6bd-eaad8d212e70.png)

#### Field Mapper

The base field for this is selected when creating the query. This is the table that the results will be opened in e.g. if you want to see a specimen record (e.g. collector, collector number and collected date) you would want to select Collection Object as the base table. 
You can select the fields you want to search on and appear in the results by selecting them from the list. As well as selecting fields from the base table you can also navigate to other tables and select fields from there. Other tables have an icon at the front of the name and an > following it:

![image](https://user-images.githubusercontent.com/8155743/193250749-9b16cbfb-b407-4ddc-acb9-099333f1218c.png)

The output from some tables can be aggregated or formatted to combine information from a particular table.
To add a field you can either double click on it or click on the large + button.

#### Operator

The operator acts on the field to change how the search is carried out. The options in this drop down can vary depending on the type of field that has been selected. The main options are:

Operator | Explanation
-- | --
Any |	Any value from this field is going to result from this query
Like |	You can insert a wildcard character (\*) at the beginning or end of the field to search all items that start or end with an unknown value. Querying \*3 will pull all results that end in a 3.
Equal |	Returns data that are equal to this value
Greater than | Returns data that are greater than this value
Less | than	Returns data that are less than this value
Between |	You can give it two values and it will pull all data in between
In | You can create a non-consecutive list that can be separated with commas or spaces to be searched. Querying 1,3,5,7 will pull the data for your field when it has a value of any of those entered.If you are using the “In” operator on a field that is based on a Pick List, you can hold down “Ctrl” to select multiple items from the presented list rather than typing in a comma-separated list of items.
Contains	| This finds every instance of a specific string associated with that field
Empty	| This will only pull data from items that have said field empty
True/False	| If the value is true or false.

##### Negate

The negate or NOT button can be used to say that you want to return results that do not match the query value e.g. you may only want to see records where a field is not empty.

##### OR search term

You can add an OR search term by clicking on the plus button to the left of a field and add additional search values for this field e.g. below the query would return records where the barcode starts with E005678 or E001234 

![image](https://user-images.githubusercontent.com/8155743/193251360-dde45eee-ca54-405b-afe3-337aba1c6eec.png)

#### Sorting and Organising tools
The four buttons to the right of the mapped field allow you to sort and order your query results:

The tick button allows you to hide a specific field from the query results, whilst still including it in the query itself. By default all fields are unhidden  ![image](https://user-images.githubusercontent.com/8155743/193251485-36b18fda-3783-40b2-9f63-a228e3000be0.png)
, click the button once to make the field hidden  ![image](https://user-images.githubusercontent.com/8155743/193251503-efe2c2b5-b495-4512-9491-499b060fbd7b.png). 

The next button sorts the results, default is no sort  ![image](https://user-images.githubusercontent.com/8155743/193251553-989ebe2d-9a06-4ec7-86c8-91ae6e5c478e.png)
, click once to sort ascending  ![image](https://user-images.githubusercontent.com/8155743/193251565-e9d1f11f-b6af-43a1-932a-9e62bfd33c11.png)
 and again to sort descending ![image](https://user-images.githubusercontent.com/8155743/193251581-d79ae3df-ca17-4b83-b35a-5a15cd019282.png)
.
The last two buttons allow you to reorder the fields in your query, this affects how they appear in the results ![image](https://user-images.githubusercontent.com/8155743/193251610-e16cd083-6513-4649-978d-0be1b9946ac3.png)![image](https://user-images.githubusercontent.com/8155743/193251620-6714fe22-d889-455e-ae76-35db901058ba.png)

#### Modifying the query’s results
Distinct ![image](https://user-images.githubusercontent.com/8155743/193251771-a4c8647b-ad69-44c7-94cb-12a651a445b7.png)
 this will return a list of one off items (e.g. Localities) from a concise query, without duplicates.

Count ![image](https://user-images.githubusercontent.com/8155743/193251792-dbda92f4-16d5-4615-a213-5d99f6dfc479.png) returns the count of result of the query without displaying the results themselves.

#### Running the query

To run the query, click the ![image](https://user-images.githubusercontent.com/8155743/193251825-793413d7-46db-4f1e-9c4c-628566a50b3a.png)
 button. The page will jump down and may take a few minutes to load, depending on the nature of the query.
   
### Query results section

The main body of this section will be the results from your query, they will be displayed based on the sort settings you may have applied in the query builder. 

#### Saving and Editing Queries

At the top of this view are three buttons:

![image](https://user-images.githubusercontent.com/8155743/193251993-ceab6278-19fa-4a19-913f-1600dc078ea5.png)
 returns you to the query builder where you can modify the query
 
 ![image](https://user-images.githubusercontent.com/8155743/193252042-739e346f-9477-4458-873d-715465ae0a77.png)
 Saves the current query
 
 ![image](https://user-images.githubusercontent.com/8155743/193252072-e74b8afe-55ee-4d90-a3ab-68db2217a919.png)
 allows you to save changes to a previously saved query, whilst keeping the original.
 
#### Viewing Query results

There are several ways in which the results of the query can be worked with.

Above the results are four buttons that enable you to work with all or a subset of the results:

![image](https://user-images.githubusercontent.com/8155743/193252268-feb56fa8-461a-4e66-91a5-0954666c2c78.png)
 creates a comma separated file of the selected results
  
![image](https://user-images.githubusercontent.com/8155743/193252286-05d04226-6624-43bc-9155-641f8ea1274e.png)
 creates a Google Earth file from a query that includes geographic data
  
![image](https://user-images.githubusercontent.com/8155743/193252313-927286ed-be13-405a-bce2-53a357a7d63e.png)
 allows you to save the selected results to a record set to be referenced later. A record set can also be used for reports and labels
  
![image](https://user-images.githubusercontent.com/8155743/193252325-c5927136-cd17-40a3-8174-98079abe024c.png)
 opens up an interface, similar to a record set, to browse the query results.

Individual records can be selected for inclusion in the options above by selecting the records using the check box to the left of the individual results

![image](https://user-images.githubusercontent.com/8155743/193252382-ee7028a8-946a-49eb-86ff-9150587a614d.png)

The CSV and KML files can be downloaded from the notifications button in the top right of the interface.

![image](https://user-images.githubusercontent.com/8155743/193252409-c99d6fb8-9174-4ee3-a004-b76100f8be13.png)

Individual results can also be viewed by clicking on the ![image](https://user-images.githubusercontent.com/8155743/193252452-9b8011a2-8937-48b8-b30a-860a800bf589.png)
 symbol to the left of the result, this will open the record in a new tab in the web browser.
