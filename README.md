# new2-demo
This is demo for Git &amp; GitHub Class for new2-demo repository.
git clone https://github.com/username/repository.git
nikhil
const apiKey = 'your_api_key';
const city = 'London';
const url = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}`;

const express = require('express');
const app = express();
const port = 3000;

app.use(express.json());

let users = [
  { id: 1, name: 'John Doe' },
  { id: 2, name: 'Jane Doe' }
];

app.get('/users', (req, res) => {
  res.json(users);
});

