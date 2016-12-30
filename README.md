# Soccer-DB-SQL-Queries
1. Software environment & tools
•	MySQl 5.7.13
•	MySQL Workbench
2. Creation of Table for SOCCER database
•	The SOCCER database was created &  DDL queries to create tables COUNTRY, PLAYER, MATCH_RESULTS, PLAYER_ASSISTS_GOALS, PLAYER_CARDS with the constraints were written in TableCreation_1.txt file, the output is spooled in spool_TableCreation_1.out
•	Text file with queries TableCreation_1.txt is attached.
•	 spool_TableCreation_1.out spool file is attached.
2.2 Load the records from files to tables in SOCCER DB
•	Load Infile command was executed from MySQL from Loaddata_2.txt file which contains the scripts below for loading the data from the CSV files in to the respective tables.
•	Loaddata_2.txt script file is attached.
•	Spool file spool_Loaddata_2.out is attached.
LOAD DATA LOCAL INFILE 'D:/DB1/Files/Country.csv' INTO TABLE SOCCER.COUNTRY FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\n';
 LOAD DATA LOCAL INFILE 'D:/DB1/Files/Players.csv' INTO TABLE SOCCER.PLAYERS FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\n';
 LOAD DATA LOCAL INFILE 'D:/DB1/Files/Match_results.csv' INTO TABLE SOCCER.MATCH_RESULTS FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\n';
 LOAD DATA LOCAL INFILE 'D:/DB1/Files/Player_cards.csv' INTO TABLE SOCCER.PLAYER_CARDS FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\n';
 LOAD DATA LOCAL INFILE 'D:/DB1/Files/Player_assists_goals.csv' INTO TABLE SOCCER.PLAYER_ASSISTS_GOALS FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\n';

Run the queries.
Refer Project1_5330_Summer_2016 (world cup 2014).docx for more details
