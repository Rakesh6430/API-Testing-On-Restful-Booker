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

2. ### Verify Booking Details
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Last Name
 	3. > totalprice
	4. > depositpaid
	5. > bookingdates
	6. > additionalneeds

3. ### Create Token
	> Using Form Data with those data
	1. username : admin
	2. password: password123

4. ### Update Booking Info
	> In the test case you need to validate the following field values:
 	1. > Only Message
 
5. ### Verify Updated Booking Info
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Last Name
 	3. > totalprice
	4. > depositpaid
	5. > bookingdates
	6. > additionalneeds

6. ### Verify Updated Booking Info
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Last Name
 	3. > totalprice
	4. > depositpaid
	5. > bookingdates
	6. > additionalneeds

7. ### Cancel Booking
	> In the test case you need to validate the following field values:
	1. > Only Message



## API Documentation:
- https://documenter.getpostman.com/view/26807129/2s93Y2TMiV

## Newman Report Summary:
- Here is the Newman report [link](https://65ad590093d77d8465eafe39--lambent-dolphin-3d0224.netlify.app/)
![image](https://user-images.githubusercontent.com/46712252/233272139-69b52ab1-2c13-4bfb-b4ac-27511d20440c.png)
![image](https://user-images.githubusercontent.com/46712252/233385767-8d8cf79b-499d-49f4-bf54-b89673f773f2.png)

