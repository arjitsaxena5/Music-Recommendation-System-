# Music-Recommendation-System-
Serverless Music Recommendation System Hosted on AWS and developed using Big data technologies like Hadoop and Spark. 
The RecSys Challenge 2018 was organized by Spotify, The University of Massachusetts, Amherst, and Johannes Kepler University, Linz. Spotify is an online music streaming service with over 140 million active users and over 30 million tracks. One of its popular features is the ability to create playlists, and the service currently hosts over 2 billion playlists. The challenge focuses on music recommendation, specifically the challenge of automatic playlist continuation. By suggesting appropriate songs to add to a playlist, a Recommender System can increase user engagement by making playlist creation easier, as well as extending listening beyond the end of existing playlists. It will be like enhanced feature on spotify.

I've created 4 ec2 instances on aws and installed hadoop on these instances making one instance as namenode and 3 instances as datanodes. Written python scripts to analyse the data and get the stats of the data and also preprocessed the data. Inserted the modified data into s3 bucket. Using AWS glue crawler to get the data profiling and decide the data modeling schema. Using star schema for data modeling. Creating role, policy, and lambda functions to automate the data transfer process from s3 to Dynamo DB. Writing lambda function to transfer data from dynamoDB to ec2 instance and later copying data from ec2 instance to hadoop file system. Installing Spark and jupyter notebook on ec2 instance and using yarn as a resource manager. Data ingestion in spark data frame from HDFS and then performing initial steps of data wrangling. Using ALS to develop a recommendation model. Recommendation model output insertion into MongoDB. MongoDB table data insertion in Apache superset. Creation of visualization charts, heat map, and treemap for output data.





 
