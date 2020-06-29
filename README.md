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
{
   "nombre": "express-hello-world",
   "versión": "1.0.0",
   "descripción": "",
   "main": "index.js",
   " guiones " : {
     "start": "nodo index.js",
     "prueba": "echo \" Error: no se especificó ninguna prueba \ "&& salida 1"
  },
  "palabras clave": [],
   "autor": "",
   "licencia": "ISC",
   "dependencias": {
     "express": "^ 4.17.1"
  }
}
echo "# Hola-Mundo" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git remote add origin https://github.com/Saustin-hash/Hola-Mundo.git
 push git -u maestro de origen
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
