# nosql-challenge
MongoDB
Overview:
This project involves the 	rating evaluation of the various establishments across the United Kingdom to help the editors of food magazine, Eat Safe, Love. It focus to help the journalists and food critics where to focus in future article.

Scope: 
In this report the establishment data in json format has been imported in database through the terminal i.e. uk food database and collection establishments. In addition, importing the python libraries - PyMongo, Pretty Print and creating instance of the Mongo Client to create a UK food database and collections establishment.    

Methodology:
1.	MongoDB database – uk_food
2.	List of collections in the database - establishments
3.	Displaying the documents in the collections establishments through the find one with pprint.

Tasks Performed:

Updating the Database – as requested by magazines editors. 

1.	Adding new halal restaurant to the UK food database as a part of analysis. 
2.	Finding the Business type ID for Restaurant/Cafe/Canteen and return only the Business Type ID and Business Type fields. 
3.	Updating the Business Type ID for the new Halal Restaurant. 
4.	Since the magazine is not interested in any establishments in Dover and finding the number of establishment and deleting all the establishment from uk food database.
5.	Converting the latitude and longitude to double.

Exploratory Analysis:

Establishments with hygiene score equal to 20:

a.	Query to find the number of establishments with hygiene score of 20.
b.	Total number of establishments with hygiene score of 20.
c.	Results stored in Dataframe. 

Top 5 establishments with a Rating Value of 5 and sorted by the lowest hygiene score, nearest to the new restaurant added “Penang Flavours”.

a.	Query to find the establishments within 0.01 degree of the ‘Pennage Flavour’
b.	Limit the results to establishments with a Rating Value of 5.

Number of establishment in each Local Authority area have a hygiene score of 0 and sorting the results from highest to lowest.

a.	Aggregation pipeline is built to include a match query, group and sort.
b.	Match query – establishment with a a hygiene score of 0.
c.	Grouped on Local Authority Name and total counts of the document.
d.	Sorting based on the counts.
e.	Sending all those query to pipeline and storing it in the variable name data.
f.	Converting the data to Dataframe and storing the information.


