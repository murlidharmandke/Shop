# Shop

To run ->
clone the entire repo
go to server repo
create .env files 
make environment file with the following keys' values:
MONGO_URI = "path to mongodb url"
userEmail = "your email"
userPass = "your password"
JWT_SECRET = "your secret here"
yarn
yarn server
go to CRM repo
make environment file with the following keys' values:
REACT_APP_API_URL = http://localhost:5000/api
REACT_APP_SERVER_ROUTE = http://localhost:5000
REACT_APP_JWT_SECRET = "your secret here"
yarn
yarn start
