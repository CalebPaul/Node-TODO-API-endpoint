## _Node API Endpoint (TODO List)_

#### _6-26-2017_

### Description
_This is a Node server/MongoDB backend for a todo list app._
_Using [PostMan](https://www.getpostman.com/) is recommended for interacting with the backend._

### Setup/Installation Requirements
* _Clone this repository (https://github.com/CalebPaul/Node-TODO-API-endpoint.git) to your desktop._
* _Navigate to project folder using terminal._
* _Install Node and MongoDB.  Refer to installation documentation for Node and MongoDB if needed._
* _Install NodeMon by typing `npm install --save-dev nodemon`.  Refer to the documentation if needed._
* _Install bodyParser by typing `npm install body-parser`.  Refer to the documentation if needed._
* _Install all dependencies listed in the package.json file._

* _Type `mongod` in terminal, this will start the MongoDB server._
* _Type `npm run start` in terminal, this will start the Node server._

* _Open PostMan._
* _Enter `http://localhost:3000/tasks` into PostMan as a GET request to see all tasks._
* _Enter `http://localhost:3000/tasks` into PostMan as a POST request with `name` as a key and `testPOST` as a value to add a task._
* _Enter `http://localhost:3000/tasks` into PostMan as a PUT request with `name` as a key and `updateTestPUT` as a value to update a task._

* _See todoListController functions for other CRUD functionality._


### Known Bugs
_None known_

### Support and contact details

_Caleb Paul: @calebpaulmusic_

### Technologies Used
* _Node_
* _Express_
* _MongoDB_

### License
*This is licensed under the GPL license.*

Copyright (c) 2017 **_Caleb Paul_**
