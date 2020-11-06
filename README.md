# **Booking App**
A Booking Application created using REACT framework as front-end and python FLASK as backend.

![](https://github.com/jaspernicholfabella/booking_app/blob/master/Screenshot/1.PNG)

## **Functionality**

*Booking Appointments*
* Date and Time for Appointments (from and to)
* Name of the Person.
* Comments

*Users Can*
* Create new Appointments
* Edit existing Appointments
* Delete an existing Appointments
* List all Existing Appointments by specifying a date range

*Appointment Rules*
* No overbooking of appointments should be allowed
* Appointments are only allowed from 9:00AM - 5:000 PM Mon - Sat



## **Installation**

### **React**
go to the directory where you clone the repo using the terminal, go to react front end and

run `npm i --save` to install all the packages used.

`npm run dev` to run the server on `localhost:1234`


### **Python  Backend (Flask)**

#### **Virtual Environment**
if venv not installed in your device go to this link
https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/

#### **Requirements Installation**
go to the directory where you clone the repo using the terminal, go to the Rest API folder

run `python -m pip install -r requirements.txt` to install all the python requirements

run the program using the command `python app.py`

#### **Misc**

you can create and drop data base using `flask db_create` and `flask db_drop` if you want to clear db data

if you are not running in `localhost:5000` you can change the local server link in the `\React Front End\src\data\rest_connection.js`






