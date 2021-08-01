# MI Schools_api
API for data about schools. 

This is a repository that contains an API that serves school data, which I developed as part of a project. The co-developers of the project are Roberto Briones, Kirstan Komajda
and Amee Yang, but the data cleaning and construction of this api were my primary responsibility. The finished API can be found at the following URL: https://school-data-server.herokuapp.com/ 

Files and Folders: 

app.py  - the python flask app that serves the data in JSON form. 

district_data_full_clean.csv - This is the cleaned data at the district level. The files I used to clean this data were submitted to one of the project repositories: 
https://github.com/robertodiazbriones/Project_2

Procfile and requirements.txt - these exist to help the publication of this data in Heroku, which is where the API is hosted. 

templates/ - HTML and CSS for the front end of the api
