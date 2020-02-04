


1. http://localhost:8080/projects/rest-api-authentication-example/api/create_users.php

POST , select raw in body
pass input as given below

{
    "firstname" : "Parveen",
    "lastname" : "Shaikh",
    "email" : "shparmeen@gmail.com",
    "password" : "777766666"
}

2. http://localhost:8080/projects/rest-api-authentication-example/api/login.php
	pass input as given below

{
    "email" : "shparmeen@gmail.com",
    "password" : "777766666"
}

3. http://localhost:8080/projects/rest-api-authentication-example/api/validate_token.php

pass input as given below
{
    "jwt": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC9leGFtcGxlLm9yZyIsImF1ZCI6Imh0dHA6XC9cL2V4YW1wbGUuY29tIiwiaWF0IjoxMzU2OTk5NTI0LCJuYmYiOjEzNTcwMDAwMDAsImRhdGEiOnsiaWQiOiI5IiwiZmlyc3RuYW1lIjoiTWlrZSIsImxhc3RuYW1lIjoiRGFsaXNheSIsImVtYWlsIjoibWlrZUBjb2Rlb2ZhbmluamEuY29tIn19.h_Q4gJ3epcpwdwNCNCYxtiKdXsN34W9MEjxZ7sx21Vs"
}

4. http://localhost:8080/projects/rest-api-authentication-example/api/update_user.php

{
    "firstname" : "Parveen",
    "lastname" : "Shaikh",
    "email" : "shparmeen@gmail.com",
    "password" : "777766666",
    "jwt": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOlwvXC9leGFtcGxlLm9yZyIsImF1ZCI6Imh0dHA6XC9cL2V4YW1wbGUuY29tIiwiaWF0IjoxMzU2OTk5NTI0LCJuYmYiOjEzNTcwMDAwMDAsImRhdGEiOnsiaWQiOiI5IiwiZmlyc3RuYW1lIjoiVmluY2UiLCJsYXN0bmFtZSI6IkRhbGlzYXkiLCJlbWFpbCI6Im1pa2VAY29kZW9mYW5pbmphLmNvbSJ9fQ.3Sv65TVYACkNPo4HMr4NvreyZY16wxG-nSorLi_jykI"
}