# Project Title: Digital Music Store

This project was divided into two portions. The first portion of the project was designed to test my SQL abilities. As an analyst, we are often challenged with time sensitive projects. The second portion of the project demonstrates my aptitude with informal, quick analysis presentations. I used SQL to analyze the data. I used Excel to visualize the data and PowerPoint to present the data. 

[<img src="https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Advanced_Spreadsheet/airbnb_NYC_3.png" alt="airbnb_NYC_3">](https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Advanced_Spreadsheet/airbnb_NYC_3.png)

{{{The Google Sheets workbook can be found <a href='https://docs.google.com/spreadsheets/d/1fC8PR8QrBSSON52mFwTbQOD3YYsWF1wl_P9Ay5MvLUI/edit?gid=1885122433#gid=1885122433'><u>here</u>.</a>}}}}


### NYC_Airbnb_Project File Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [NYC_Airbnb_README](https://github.com/nbrown5071/Data_projects_TripleTen/blob/main/Advanced_Spreadsheet/NYC_Airbnb_README.md) | A file with relevant information about the project, current view. | 
| 2 | []() | description |


| Section Title | Description |
| ----------- |----------- |
| Project Description | Details the projects intended purpose and describes requirements. |
| About the Data | Describes the data used in the project. |
| Process | Briefly describes methodology. |
| Findings | Brief summary of insights learned from the analysis and recommendations provided. |
| Reviewer’s Comments | Project reviewer’s comments on the project. |
| Reflection | Challenges, Improvements, what I learned, etc. | 

### Project Description 
For this project, I was tasked with querying the [Chinook Database](https://github.com/lerocha/chinook-database) which holds information about the music store. Udacity provided a link to the database file. I uploaded the database to my SQLlite server. The first portion of this projection involved several challenge questions provided by Udacity. After answering the questions, I then explored the data and developed questions based on my exploration of the data. We were required to submit the following. 

•	Four Microsoft PowerPoint Slides. Each slide is titled with a question and has a brief description and answer with a visualization. 
•	A .txt file of four SQL query codes formatted with sqlformat.org for readability. Each query must be unique and must use a join, subquery, or other advanced function. 


### Data
Database can be found <a href='https://github.com/lerocha/chinook-database'><u>here</u>.</a>. Media related data was created using real data from an iTunes Library. 
It contains 11 tables with defined relationships:
Artist, Album, Track
                     - AlbumId in the Track table is a foreign key linked to the AlbumId (primary key) in the Album table.
                     - MediaTypeId in the Track table is a foreign key linked to the MediaTypeId (primary key) in the MediaType table.
                     - GenreId in the Track table is a foreign key linked to the GenreId (primary key) in the Genre table. 
MediaType, Playlist, PlaylistTrack
                     - PlaylistId in the PlaylistTrack table is a foreign key linked to the PlaylistId (primary key) in the Playlist table.
                     - TrackId in the PlaylistTrack table is a foreign key linked to the TrackId (primary key) in the Track table.
Genre, Employee, Customer, Invoice, InvoiceLine
                    - InvoiceId in the InvoiceLine table is a foreign key linked to the InvoiceId (primary key) in the Invoice table.
                    - TrackId in the InvoiceLine table is a foreign key linked to the TrackId (primary key) in the Track table.

### Process
First, I reviewed the data dictionary, and I explored the data in order to make myself aware of potential cleaning, formatting, filtering, etc. After exploring the data, I answered the challenge questions provided by Udacity. Next, I developed questions based on my exploration; ensuring not to duplicate any challenge questions. I then wrote SQL code to answer the questions while checking my work to ensure validity and correctness. Finally, I downloaded the data to excel to visualize it. To present my findings and visualizations, I created a PowerPoint presentation and saved it as a PDF for ease of viewing. I also formatted my code and submitted it as a txt file. I completed this project in about three hours. 

### Findings
- The Rock Genre has the most tracks at 1,297. If we sold one of each track we could earn $1,284. No other Genre comes close to this. 
- The artist “Iron Maiden” has the most albums at 21. The rest of our artists are all under 15 albums.
- Our all time best selling rock artist, Iron Maiden, has earned the most and has the most tracks sold. Wealso know that this artist has the most albums. The artist U2 has half as many albums but comes in 2nd to Iron Maiden.

### Reflection
I enjoyed this project and I found it challenging. SQL always tests my ability to deconstruct a question/ problem in order to solve it using SQL language with the data on hand. To improve this project, I should have spent more time developing questions that required the use of a subquery or window function. This project also required each visual to have an axis label. I don't feel this is always necessary. It really depends on your audience. I actually had to resubmit this project because it was missing axis labels.

### Reviewer’s Comments
"Dear Student,

You have submitted a good project and adhered to the required formats. We appreciate this. You have shown your creativity and answered some really interesting questions and the presentation was very appropriate for all the slides. It was very high-quality work from your side. Well done!

I believe you have now gained good confidence after completing this project and can write any query to answer business problems. Also, your creative mindset would surely help you in finding out the hidden insights in the data.

That’s all! Keep up the good work."


[<img src="">]()
