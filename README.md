# Ricardo's Portafolio - Data Analyst portafolio

Portafolio containing projects in Python, SQL, KDB and Power Bi.

# [Project 1: Analyze data using kdb q+ and embedpy](https://github.com/MrRicardoAcuna7/KDBQ_analyze_videgames_sales_data)
Analyze videogame sales data from csv to kdb q+ language and visualize result

1. Import data from cvs file to kdb as kdb table.
2. Cleaning table removing null values in qsql functional and qsql.
2. Querying table using multiple functions.
3. Using Embedpy get a visualization of sales by region.
4. Create a dynamic function using parse tree of qsql(qsql functional)
![alt text](videgame_sales.PNG)  
[See Notebook here](https://github.com/MrRicardoAcuna7/KDBQ_analyze_videgames_sales_data/blob/main/analyze_vgsales.ipynb)

# [Project 2: ETL (Geting data from public API) + visualization using KDB Q+](https://github.com/MrRicardoAcuna7/ETL_CryptoCoins)
Call get from public API, it becomes into a dictionary easy to parse, all in one line.  

1. Utilize .j.k and to parse json format to kdb dictionary, .q.hg which is get command of the api endpoint.  
2. Use of some element (iterators, flip command,etc) to select element in the dictionary and transform it into a dictionary.  
3. Get list of columns field to graphic using embedpy.  
[See Notebook here](https://github.com/MrRicardoAcuna7/ETL_CryptoCoins/blob/main/CryptoCurrencies_ETL_Analysis.ipynb)

# [Project 3: API conecting to postgres](https://github.com/MrRicardoAcuna7/API_Postgres_Flask)
This is a API done using Flask and Postgres, the example is for communicating your API with an account table.

1. Set up the app through Flask, and creating connection with postgres using app.config['SQLALCHEMY_DATABASE_URI'].
2. Create the meta for the new table that would store the data and using SQLAlchemy create_all() would create it.
3. Create for each method a function to read the input and push to postgres. The endpoint should be localhost:5000/accounts for post.
4. Test it with postman sending one try in json format.
![alt text](https://github.com/MrRicardoAcuna7/API_Postgres_Flask/blob/main/postman_snapshot.PNG)
6. Query that table in postgres.
![alt text](https://github.com/MrRicardoAcuna7/API_Postgres_Flask/blob/main/postgres_snapshot.PNG) 

# [Project 4: API that connect with local json file](https://github.com/MrRicardoAcuna7/local_API_server)
Simple project in python using Flask library, that create all methods for REST API using a product table as json format.  

1. Create a http handler return all messages through a JSON coder.  
2. Call methods(POST,PUT,DELETE) to declare function.  
3. Set up the server connection in some local port.  

# [Project 5: Web Scraping Yahoo Finance using Python](https://github.com/MrRicardoAcuna7/WebScraping_Finance_Apple)
1. Get data from yahoo finance using python Framework scrapy, through xpath expressions.  
2. Extract most import economic metrics of Apple getting date for this extraction.  
3. Export output to csv file.  
![alt text](Yahoo_Apple.jpg)  

# [Project 6: Covid Dashboard](https://github.com/MrRicardoAcuna7/PowerBIProjects)
1. Create a Power BI template with covid data from october 2020.  
2. Analyze trend cases vs total death in Nicaragua and global.  
3. Analyze economic impact in important metrics(HDI and GDP)  
![alt text](Covid.PNG)

# [Project 7: Videogame - Sales Trends](https://github.com/MrRicardoAcuna7/PowerBIProjects)
1. Create a Power BI template with videogames data.  
2. Analyze videogame sales through different ways.  
3. Analyze sales through all years to analyze any trend.  
![alt text](Videogame.PNG)  

# [Project 8: AdventureWorks Data Base SQL - Analysis](https://github.com/MrRicardoAcuna7/AdventureWorks2019DB_SQL_Analysis)
1. Download and restore database in sql server management.  
2. Create a temp table that store a clean dataset.  
3. Get values by different fields.  

# [Project 9: KDB IPC - Read from sql connection and get output tables through an ipc connection](https://github.com/MrRicardoAcuna7/KDB-QIPC)
1. Open KDB ODBC connection usind DSN and call query.  
2. Set up kdb messages and permissions for ipc.  
3. Create the function to be called.
4. In the client side, make async call and get that output into kdb table in a local folder.  

# [Project 10: KAFKA Sending messages from producer to consumer](https://github.com/MrRicardoAcuna7/Kafka_Python_Code)
1. Running kafka and zookeper in a docker container.  
2. Created a pythons script for getting random messages.  
3. Created a producer through kafka producer function to send message.
4. Set up a consumer that would parse and read the message.  

