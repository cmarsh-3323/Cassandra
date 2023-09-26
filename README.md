# Data Modeling with Apache Cassandra
Project submission for Udacity Data Engineering Nano Degree

Author: Chris Marshall

# Summary
The company Sparkify is looking to hire a data engineer to take there CSV logged data and create an Apache Cassandra database for a straightforward way to answer queries relating to there song play data.

We will be performing an ETL(Extract, Transform, Load) pipeline to process the data and provide Sparkify with a functional data model. We will be creating are tables, inserting the data into the tables and making our requested queries on each table. Lastly, we will drop each individual table and close our connection.

# Getting Started and Usage
* Make sure to have Python installed on your system. You can download python from the official website: [Python Downloads](https://www.python.org/downloads/)

* Open the notebook file:

     `Project_1B_Project_Template.ipynb`

* Run the cells in order from top to bottom

  `(make sure to close the session when finished)`

## Directory Structure
This section provides an overview of the major files in the repository and their respective purposes and functionalities.

| File Name     | Purpose                                              |
|---------------|------------------------------------------------------|
| event_data    | Contains songs and information in CSV format to create Apache Cassandra tables  |
| images   | Representation of the denormalized data           |
| Project_1B_Project_Template.ipynb    | Python notebook for ETL Pipeline and to model the database tables on our queries    |
| event_datafile_new.csv      | Dataset to create a denormalized dataset        | 
| README.md     | Documentation for data modeling with Apache  Cassandra                    |


# References

[Cassandra Data Modeling](https://cassandra.apache.org/doc/latest/cassandra/data_modeling/index.html)

[Python Standard Library](https://docs.python.org/3/library/index.html)

[Stack Overflow](https://stackoverflow.com/)

* dealt with a ValueError on scalar values

[Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)

* created a Panda DataFrame to add the columns for all 3 queries