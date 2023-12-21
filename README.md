Routes

URL
https://cc-alphalearn-soczugczfa-uc.a.run.app/
Endpoint
Register
URL
/api/users/register
Method
POST
Request Body
{
    "name": "newname",
    "email": "123@gmail.com",
    "password": "password"
}
Response
	{
    "user": {
        "name": "newname",
        "email": "123@gmail.com",
        "password": "$2a$10$6Z0Un0h9IHPl6Qn72QGb4Ockm/Lp9ADq40/dAk7b5WWYsstSEgEE2",
        "_id": "657ec50beb630b93766cb26a",
        "date": "1702806795414",
        "__v": 0
    }
}




Login
URL
/api/users/login
Method
POST
Request Body
{
    "email": "123@gmail.com",
    "password": "password"
}
Response
	{
    "userId": "657e23aaaf866c21bfa2f0a9",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI2NTdlMjNhYWFmODY2YzIxYmZhMmYwYTkiLCJpYXQiOjE3MDI4MTQ2NzB9.9EEulQhcK3-ZXz6SdFwqTst7xeotIAHais13bwigAnI"
}














Akses konten
URL
/api/posts
Method
GET
Request Body

Request Headers
Auth token
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI2NTdlYzUwYmViNjMwYjkzNzY2Y2IyNmEiLCJpYXQiOjE3MDI4MDY4ODZ9.ck2JW8oZd_nHf61lWe7FpOtzfIIis_ysWDB67r4ORUA (auth-token)

Response
{
    "post": {
        "title": "project 1",
        "description": "isi deskripsi"
    }
}




	




