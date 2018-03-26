# node.js

- app.get('/update', function(req,res){ fs.appendFile() }
If you go into web API, http://163.239.76.221:3000/update?(data) ,
the data will be written sequentially in the 'update.txt' file.

- app.get('/get', function(req,res){ fs.readFile() }
It reads the data from the 'updata.txt' file and
write down all data on web API http://163.239.76.221:3000/get .


