Next I wanted to get oriented with MySQL. Here are the steps I took to figure it out. 
1. Download and install MySQL Community Server v8.0.25 for macOS (from https://downloads.mysql.com/archives/community/). From here, I could see MySQL.prefPane in my System Preferences and establish a connection to `localhost`. 
 - In order to run MySQL from command line, I also had to append `/usr/local/mysql/bin` to the `$PATH` variable in `~/.bashrc`. But with the GUI of MySQL Workbench (see next step), I won't need the command line much. 
2. Download and install MySQL Workbench v8.0.22 for macOS (I had to downgrade the version twice because of various bugs) from the archives (https://downloads.mysql.com/archives/workbench/). 
3. Next, because I knew that I wouldn't be able to connect to `localhost` from GoogleColab, I had to setup a database on a remote server. 
4. The data that I wanted to put into a database is from Kaggle. I downloaded them as csv files. This is a different dataset than previous: https://www.kaggle.com/kumarajarshi/life-expectancy-who/
5. To convert the csv to database, i used this: https://www.databasestar.com/mysql-workbench-import-csv/
