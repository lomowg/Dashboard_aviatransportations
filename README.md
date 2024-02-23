# Dashboard Aviatransportations

The project includes a Tableau dashboard on the Russian PostgreSQL air transportation demo database.
The dashboard displays the following information:
* Total number of reservations made for a certain period of time
* Total amount of revenues received from ticket sales for a certain period of time
* Rating of the most popular destinations by number of bookings
* Interactive map

# Database

The database was taken from [postgrespro.ru](https://postgrespro.ru/docs/postgrespro/10/demodb-bookings).
To save space the database **demo-medium.zip** was taken.

The database has the structure:
![Image](https://repo.postgrespro.ru/doc//std/10.23.1/ru/html/demodb-bookings-schema.svg)

# Data conversion

To load the data into Tableau, I using **Python** unloaded the tables from the database into .xlsx files and imported them into Tableau. 
The conversion code is in **Data_downloading.ipynb**
The finished .xlsx files are in the **Excel data** folder

# Dashboard

The interface looks like:
![Image](https://i.imgur.com/fb2Qqsq.png)

To view and interact with the dashboard:
* Download Airport.twbx and open in Tableau
Or
* Follow the link: [Airport Dashboard](https://public.tableau.com/app/profile/nikita.sokolov4040/viz/Airport_17085242855080/Dashboard1?publish=yes)
