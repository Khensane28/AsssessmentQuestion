
HOW TO CREATRE FAKE API :

STEPS :
1. Install Nodejs Software
2 . Get npm (node package manager)
npm install -g json-server
3. Install JSON server
4. Create a jSON file

{
  "employees": [
    {
      "id": 1,
      "name": "Peter",
      "status": true
    },
    {
      "id": 2,
      "name": "David",
      "status": false
    },
    {
      "id": 3,
      "name": "John",
      "status": true
    },
    {
      "id": 4,
      "name": "Jacob",
      "status": true
    }
  ]
}
 cmd to active (json-server json-server)

for port4000 - Ctrl + c then ( json-server -p 40000 json-server  )
5. Run J50n Server with your json file
6. Execute OWN API from postman
 GET: 
POST:
{
         "id":5,
         "name": "Khensane",
         "status": true
 }

PUT: add sername and change true to false 
{
  "id": 4,
  "name": "Jacob Sithole",
  "status": false
}

PATCH :
{
         
 "status": false
 }

DETETE :






