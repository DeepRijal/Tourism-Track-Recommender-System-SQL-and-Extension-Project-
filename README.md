# Tourism-Track-Recommender-System-SQL-and-Extension-Project-
The goal is to develop a system that uses information from social media to track potential tourists and suggest nearby tourism walks. To do this, I have used a number of database systems and extensions, including PostgreSQL, PostGIS spatial, Neo4j graph, and MongoDB document databases. These databases will keep track of details about individuals, their social networks, locations, track logs, reviews, and friendship ties.

Four database components make up the project:

Postgres Database: Using tables for users, their connections, and location information, it simulates social networking data. It is necessary to retrieve the coordinates and social relationships of specific persons.

PostGIS Spatial Database: This technique uses PostGIS to manage spatial data, including tracklogs, in the PostgreSQL database. When there is no exact match, spatial searches can locate the closest tracklog or identify tracklogs that are located within a certain range of coordinates.

MongoDB Document Database: Managing reviews of tourist walks as JSON documents. This involves adding reviews and retrieving the one with the best rating.

Neo4j Graph Database: Making a graph database in Neo4j to represent individuals and their friendship connections. This component includes retrieving all related persons for a specific person as well as adding new people and relationships.
![image](https
