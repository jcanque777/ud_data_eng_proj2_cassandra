# ud_data_eng_proj2_cassandra
## Data Modeling with Cassandra

Analysis is needed on user data which is located in 28 csv files. After prepocessing which consisted of selecting the correct appropriate columns and saving into new csv file, we connected to Cassandra to create a keyspace. 

### Final CSV Table
![csv table after preprocessing](https://user-images.githubusercontent.com/53429726/94365395-ad76aa00-009e-11eb-871d-89430580a036.png)


A table is created is CQL format to address each queries in the most efficient way possible. Information from the csv file is inserted into the tables and queries are formulated and results are shown using pandas. 

### Find users who listened to "All Hands Against His Own"
!["SELECT firstName, lastName FROM user_history WHERE song = 'All Hands Against His Own'"](https://user-images.githubusercontent.com/53429726/94365612-57a30180-00a0-11eb-872c-86e55796650f.png)