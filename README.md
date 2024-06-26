# React
React Internship Assignment
# Run or Open in local browser
cd FormValidation_CT_CSI_RJ_2239
npm i
npm run dev
#------------------------------
# Question->
# Forms and Form Validation
Create a React form with validation for required fields without using third party libraries, Display error messages, disable submission until fields are filled correctly, and show all the filled details on a new route post-successful submission. Fields required: First Name, Last Name, Username, E-mail, password (show/hide), PhoneNo. (country code ____ number), country (dropdown), city (dropdown), Pan No. & Aadhar No.
# Using Regular expressions
Email= /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/
Password = /^(?=.*\d)(?=.*[a-z])(?=.*[A-Z])[0-9a-zA-Z]{8,}$/
Pan = /^[A-Z]{5}[0-9]{4}[A-Z]{1}$/
Aadhaar = /^[2-9]{1}[0-9]{3}[0-9]{4}[0-9]{4}$/
