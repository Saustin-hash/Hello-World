# Hello-World
Tarea
https://github.com/Saustin-hash/Hola-Mundo.git
git add .
git commit -m "primer commit
git config --global user.name "Saustin Taberna"
git config --global user.mail "SaustinTDS@gmail.com"
git push -u origin master
git add .
git commit -m "modificaciones para Heroku"
git push
// index.js

// importa la libreria express
const express = require('express');

// ponemos el puerto del server en una variable
const port = process.env.PORT || 3000;

// crea el objeto app
const app = express();

// agregamos esta línea
app.use(express.static('public'));

// la app responde con Hello world
// a todas las peticiones GET a /
app.get('/', (req, res) => {
  res.send('Hello world');
});

// el server escucha en el puerto 3000
app.listen(port);
