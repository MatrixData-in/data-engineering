## Pre Requiste
- Ubuntu Linux

### Update all the Packages
- sudo apt-get install software-properties-common
- sudo apt-add-repository universe
- sudo apt-get update
- sudo apt-get install python-setuptools
- sudo apt install python3-pip
- sudo -H pip3python install --upgrade pip


### Airflow Dependencies
-sudo apt-get install libmysqlclient-dev
-sudo apt-get install libssl-dev
sudo apt-get install libkrb5-dev

### Install Airflow
''' export AIRFLOW_HOME=~/airflowpip3 install apache-airflowpip3 install typing_extensions# initialize the database
airflow initdb

#### start the web server, default port is 8080
airflow webserver -p 8080# start the scheduler. I recommend opening up a separate terminal #window for this step
airflow scheduler

'''

### visit localhost:8080 in the browser and enable the example dag in the home page
