Register API-----------------------
Request Type: POST
Request Body: 
{
  "email": "xyz@email.com"
}
Response:
upon succes
{
  "email": "xyz@email.com",
  "message": "Registered"
}
upon error:
{
  "message": "An error occured while registering employee",
  "error": "Error details"
}

Mark API-----------------------------------------
Request Type:   POST
Request body:
1---------------
{
  "clockIn": "in"
}
2------------------
{
  "clockIn": "out"
}

Response:
Upon success:
{
  "employee Id": "657d5773b56170ba9c452085",
  "message": "Clocked out successfully"
}
Upon failure(When the person is not recognized):
{"message": "You are not recognized"}

There are also other Responses for failures, but will not (most likely) occur. You can check them in the code.
Feel free to ask me in case of any confusion


