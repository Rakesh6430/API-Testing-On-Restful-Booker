# API-Testing-On-Restful-Booker

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run API_Assignment.postman_collection.json -e Batch17.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run API_Assignment.postman_collection.json -e Batch17.postman_environment.json -r cli,htmlextra
```
## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```
## Test case list:

1. ### Create Booking
	> Create Data Sets Using the Dynamic Random Variables.

2. ### Verify Crated Booking Details
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Last Name
 	3. > totalprice
	4. > depositpaid
	5. > bookingdates
	6. > additionalneeds

3. ### Create Auth Token
	> Using Form Data with those data
	1. username : admin
	2. password: password123

4. ### Update Booking
	> In the test case you need to validate the following field values:
 	1. > Only Message
 
5. ### Verify Verify Updated Booking Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Last Name
 	3. > totalprice
	4. > depositpaid
	5. > bookingdates
	6. > additionalneeds

6. ### Get the Booking's Full Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Last Name
 	3. > totalprice
	4. > depositpaid
	5. > bookingdates
	6. > additionalneeds

7. ### Delete Specific Booking
	> In the test case you need to validate the following field values:
	1. > Only Message



## API Documentation:
- https://documenter.getpostman.com/view/26807129/2s93Y2TMiV

## Newman Report Summary:
![image](https://user-images.githubusercontent.com/46712252/233272139-69b52ab1-2c13-4bfb-b4ac-27511d20440c.png)

## Full Report
1. [Newman Run Report](file:///G:/Department/SQA%20Course/Assignment/API%20Project%203/newman/Newman%20Report.html)
