'use strict';
let express = require('express');
let morgen = require('../');

let app = express();
app.use(morgen('combined'));
app.get('/', function(req, res){
  res.send('Hello World');
});

if (!module.parent) {
  app.listen(3000);
  console.log('Express started on port 3000');
}

