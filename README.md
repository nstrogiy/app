
cd into both Project Directories in 2 different terminal windows and then install the dependencies

The "Client" directory contains the React code. The "Server" directory contains the code for the node.js express server. This project requries a PSQL database to run. 

#### 1st window
`cd Client`

#### 2nd window
`cd Server`

#### 1st window
`npm install` 

#### 2nd window
`npm install` 

<br />

### Run both the server and client at the same time

#### 1st window 
`npm start`
(runs react at localhost:3000)

#### 2nd window 
`npm run custom` 


### Set up PSQL

<ol>
  <li>Open the PSQL shell and login to PSQL</li>
  <li>Create a new PSQL database if you have not already done so. </li>   
  <li> In the Server/.env file replace values with the login info for your own PSQL database. </li>   
  <li> In the Client/.env.development set url for backend</li>
</ol>

