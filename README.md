# Udacity Serverless project
A Servess application which gives you a functionality of keeping record of your todos.You can update, delete and upload images to your todos tasks.

## Project Components
- Restful API (Lambda Functions, API Gateway and DynamoDb)
- Client (React)

## How to run the application
### Backend
To deploy an application run the following commands:

```bash
cd backend
npm install
sls deploy -v
````
### Frontend
```bash
cd client
npm install
npm run start
```

## Deplyment details
API Endpoint
```
https://e2mg7iqieb.execute-api.us-east-1.amazonaws.com/dev/todos
```
Postman Collection
```
Udacity C4 Project.postman_collection.json
```
