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
