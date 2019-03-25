# crime

Population of US over the years and number of crimes compared to number of police officers

This project was to answer the question 
  "Does the number of violent crimes rises or fall depending on the number of police officers in United States?"

The data that I gathered is the yearly count for the following:
  a. Population
  b. Violent Crimes
  c. Police Officers
    
This project is ran using the following steps:

  a.  download/create the two csv files
    - population and violent crimes is from one location
    - and the number of police officers from another location
    
  b.  create a database if it is not there or connect to the database if it is already created.
  
  c.  import the data from csv file to the table in the sqlite database
      - first delete the tables if it is there so that we can have the correct data
      - then the table is created and the data is imported
  
  d. once the import is completed, I confirm that the tables are there and that the data is in fact in the table
  
  e.  created a query that linked between the two tables via the year column.   
  
  f.  used matplotlib to graph my data
  
  
References:

1. Count of police officers
  https://www.bjs.gov/content/pub/pdf/nsleed.pdf
  The table with title "Number and rate of full-time officers reported to the UCR, by sworn status, 1992–2012"
  Note about the data: There were three different table of data but I only focused on the UCR data
    The FBI collects data on the number and type of law enforcement employees as part of its Uniform Crime Reporting (UCR) Program.

2. Population and Violent Crimes Count - 
  https://ucr.fbi.gov/crime-in-the-u.s/2016/crime-in-the-u.s.-2016/topic-pages/tables/table-1

