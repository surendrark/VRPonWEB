# VRPonWEB
Installation notes
To setup the server you need the following softwares installed:
1. Python 3 (install Anaconda)
2. Flask for python (conda install -c anaconda flask)
3. Install mysql python link (pip install pymysql)
4. Install XAMPP 

Once you have the above four installed follow the below steps:

1. Setup MySQL in XAMPP
  1.1 Open xampp shell (windows)/ terminal (linux/mac) and type following commands and press enter
  1.2 "mysql -u root -p" press enter twice (no password)
  1.3 CREATE DATABASE gvrp_db;
  1.4 USE gvrp_db;
  1.5 CREATE TABLE input_table (NodeType varchar(20) not null, Latitude float, Longitude float, Demand float);
  1.6 exit
  1.7 exit
2. git clone https://github.com/surendrark/VRPonWEB/
3. Extract the cloned git files
4. Form Anaconda prompt (windows) / terminal (linux/ mac) cd to extracted folder
5. run python GVRP.py

Now the server is up and running

Open a browser and type localhost:5000 or 127.0.0.1:5000 to open the web application
