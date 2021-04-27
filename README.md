# Flight-fare-prediction
In this project we have created a web application that predict the prices of flight based on date, source and destination.


"How to run"


-- change the directory to project directory-----

pip3 install -r requirements.txt 



gunicorn app:app


Due to large size of our model 'flight_rf.pkl' we could not upload it on GitHub, however you can create 'flight_rf.pkl' using 'Flight_price_prediction.ipynb' and then create a folder 'model' and add 'flight_rf.pkl' there.

NOTE- Without 'flight_rf.pkl' flask appllication will not run.
