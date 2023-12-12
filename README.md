# nosql-challenge
Completed by Daniel Stephens

## About this project
This is a two part project demonstarting the creation of a MongoDB database, loading and querying data, and creating Pandas dataframes from query results. 

### NoSQL_setup.ipynb
The notebook can be accessed in the root folder in this repo

The first app in this project establishes a new database in MongoDB and imports data into this database. A new document is insterted into the database. Finally, some data cleaning is completed by changing datatypes for multiple fields. 

### NoSQL_analysis.ipynb
The notebook can be accessed in the root folder in this repo

The second app in this project is an exploratory analysis of the database, demonstrating sorting and grouping in queries, as well as converting query results to Pandas dataframes. 

#### Running the app

To run the app: 
* MongoBD will need to be installed and started before before the applications can be run. 
* Before running the app, the database will need to be created and data imported. To create the db and import the data, download this repo and run the following command from the Resources folder where the establishments.json file is located: `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`
* NoSQL_setup.ipynb must be run first before running NoSQL_analysis.ipynb
