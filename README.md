extract zipFolder mongodb-macos-x86_64-4.2.17.taz to the same folder, week6<br>
- cd to new extracted folder the copy all files in bin directory to an empty folder bin above<br>
$cd mongodb-macos-x86_64-4.2.17<br>
$ cp bin/* ../bin/<br><br>

- Run mongod and mongo from root folder, week6, as follow:
$ bin/mongod --config mongod.conf
$ bin/mongo 

MongoDB is in _data/db 
This is a mongoDB version 4.2 that is in bin directory
