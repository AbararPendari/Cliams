#Routes
GET      /api/Cliams
POST     /api/Cliams
GET      /api/Cliams/id
PUT      /api/Cliams/id
DELETE   /api/Cliams/id

#server start
npm start

POST Payload
{
    "ID": 1,
    "claimNumber": "CLM001",
    "lineOfBusiness": "Auto",
    "insuredFullName": "Mandy hawk",
    "insuredFName": "Mandy",
    "insuredLName": "hawk",
    "insuredDOB": "1994-01-10",
    "dateOfDeath": "2023-02-28",
    "Status": "Pending",
    "effectiveDate": "2023-01-01",
    "insuredState": "CA"
}
