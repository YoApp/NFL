NFL
===

This repo is to demonstrate what can be very easily done with the Yo API.

To send a Yo to all 49ers subscribers we run this script with a cron job every minute.  
The script checks if a game starts now and if a game starts, sends a Yo using the Yo API.  

Running
===================

    git clone git@github.com:YoApp/NFL.git
    cd NFL
    virtualenv env
    . env/bin/activate
    pip install -r requirements.txt
    ./yo-49ers.py
