# Company_collector

### REST API created with Python using Django as the web framework and MySQL as DBMS.

To create the requests you can use platforms like Postman.

With the protocol HTTP we put to use the commands: 
- **GET**,  http:// 127.0.0.1:8000/api/companies //gets all the companies collected
- **GET**,  http:// 127.0.0.1:8000/api/companies/{id} //gets the company by id (integer)
- **POST**, http:// 127.0.0.1:8000/api/companies //and then add the body attributes of the company you want to post in json
- **PUT**,  http:// 127.0.0.1:8000/api/companies/{id} //edit the attributes by the company's id
- **DELETE**, http:// 127.0.0.1:8000/api/companies{id} //deletes the company by id

We collect the information of the companies and manage it as we need.


