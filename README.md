# API Name
JSON POST with Database

## API Description 
API endpoint that will extract and insert data in the database.

 ## API Endpoints
INSERT DATA(postName):
- Endpoint: POST /api/postName
- Description: This endpoint allows you to insert a name into the database.

EXTRACT DATA(printName):
- Endpoint: GET /api/printName
- Description: This endpoint retrieves a list of names from the database.

UPDATE DATA (updateName): 
- Endpoint: PUT	 /api/updateName
- Description: This endpoint allows you to update a name into the database.

DELETE DATA (deleteName):
- Endpoint: DELETE	 /api/deleteName
- Description: This endpoint allows you to insert a name into the database.


## Request
INSERT DATA (postName):
- Request payload:
{
    "lname": "hortizuela",
    "fname": "manny"
}

VIEW DATA (printName):
- Request payload: NONE

UPDATE DATA (updateName):
- Request payload:
{
  "id":1,
  "lname":"wick",
   "fname":"john"
}


DELETE DATA (deletetName):
- Request payload:
{
  "id":1
}

## Response
INSERT DATA (postName):
- Response payload:
{
         "status":"success","data":null
}

VIEW DATA (printName):
- Response payload:
{
         "status":"success","data":["lname":"hortizuela","fname":"manny","lname":"licayan","fname":"arnold"]
}

UPDATE DATA (updateName):
- Response payload:
{
         "status":"success","data":null
}

DELETE DATA (deleteName):
- Response payload:
{
         "status":"success","data":null
}


## License
No license



## Contact
Information
Email: arnelalexandercalub@gmail.com
