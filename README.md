# Launch-Week-2-Project

Project 2: Databases, Databases, Databases
Overview: 
This project is designed to give you practice designing and pulling data from a wide variety of database architectures. By the end of the week, you and your group will have created a set of data, used it to populate three different database architectures, and collaboratively written python scripts to query each of them.
Structure: 
This project will be completed in predetermined groups of 4 or 5. Your project groups (listed at the bottom of this document) will be your new standup groups, and you will use daily standups to facilitate effective team collaboration, task delegation, and knowledge sharing. In addition, we expect you to use Github as version control.
Topic: 
We’re asking each group to make a synthetic dataset with relationships between observations and interactions. This data is totally fictitious, the goal is learning about databases and getting comfortable with the three main types.

As expanded on later in this document, we are requiring 4 disparate (ie: separate) data sources (ie: tables).
Due date: Friday, May 31st, at 3:00PM.
Deliverables:
Two databases - one MySQL, one MongoDB- that you have spun up locally and populated with your data according to your specified architecture.
A polished, 6-8 minute slide deck presentation detailing the data you created or obtained, the architectural decisions you made for each of the two databases, and which database architecture you feel best suits your topic. Make sure to talk about the performance of queries for each database in the slide deck! This is a technical presentation to be shared with your CTO or technical project manager. Don’t hold back on the jargon, but still explain concepts in-depth and avoid code screenshots. 

Intermediate guidelines:
EOD Monday, May 27th: Determine what data your group will be creating and how you will be creating it. 
EOD Tuesday, May 28th: Have your data created. You can store it in spreadsheets for now, and prepare to insert it into your databases over the next two days. 
EOD Wednesday, May 29th: At least one of your databases should be populated. Ideally, you will do this via a python script, which you will save and upload to GitHub.
EOD Thursday, May 30th: All of your databases should be populated.
3:00pm Friday, May 31st: Your presentation should be finalized, and you should have written some example queries for your databases.

The Scenario:

Music Streaming Service Data Model: You are a data science team working for a music streaming service that offers millions of songs from various artists and genres. You need to design a database schema that can store and analyze the information of the songs, artists, albums, and playlists. You also need to ensure that the schema can generate statistics on the most popular and least popular songs, artists, albums, and playlists.
Songs: This table stores the information of each song, such as its title, artist ID, album ID, genre, duration, rating, etc.
Artists: This table stores the information of each artist, such as their name, biography, country, followers, etc.
Albums: This table stores the information of each album, such as its title, artist ID, release date, cover art, tracks, etc.
Playlists: This table stores the information of each playlist, such as its name, creator ID, description, songs, popularity, etc.
