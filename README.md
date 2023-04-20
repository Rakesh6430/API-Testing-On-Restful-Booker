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
## API Documentation:
- https://documenter.getpostman.com/view/26807129/2s93Y2TMiV

## Newman Report Summary:
![image](https://user-images.githubusercontent.com/46712252/233272139-69b52ab1-2c13-4bfb-b4ac-27511d20440c.png)

## Full Report
1. [ AuthorProject Report](https://0oismn759cp9zzj9awmyfg.on.drv.tw/www.mypostman.com/AuthorProject-2023-01-17-16-15-30-787-0.html)
2. [Newman Run Report](https://github.com/Rakesh6430/API-Testing-On-Restful-Booker/blob/main/newman/Newman%20Report.html)
