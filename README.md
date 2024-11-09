Delpoyment Of Project
https://flex-with-yoga-imfh.onrender.com
The project is divided into three section
Registration form
Payment page
Confirmation Page.
Registration Page
Basic info as EmailID, username, age and phone number needed on register page.
ONLY Any user age between 18 - 65 years can register on the portal.
After successful registration of new user have to payment.
Payment Page
After successful registration, user need to pay a fixed amount of INR 500/-.
User need to fill the payment mode details.
After filling correct information, payment will be successful or unsuccessfull and confirmation message is shown.
Confirmation Page
After successful payment, a comfirmation will be shown. success page

IF complete payment function unsuccessfull we will gre failure page failure image

Database
After successful payment, user data is stored in the mongodb database. Here we have gone with 2 tables users and paymentmodes. Users

Payment

ER Diagram for both tables
TABLES with ER DIAGRAMS

Important Assumptions made
Here you have to register on application form to book a slot and make payment.
Every user have a unique ID which will be used to access the service within slot.
Both payment details and user details are stored there at system.
By clicking on Payment button, payment will be successful or unsuccessfull according to completepayment() function responce here we have only shown for successfull payment in frontend.
Validity of one time payment is till last day of the month.
User need to register and make payment again for booking a new slot.
User cannot book more than one time in a month.
The validation is done for the registration page only.
We can integrate a login page to check current date is greaterr than expdate or not and produce output in frontend accordingly/
Instructions to use
Use git clone for cloning the repo
Run command npm i for installations of dependecies.
Run nodemon app.js for implementation.
